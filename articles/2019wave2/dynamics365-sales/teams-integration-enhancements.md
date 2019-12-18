---
title: Microsoft Teams 統合の機能拡張
description: Microsoft Teams の統合によるコラボレーションのメリットに関するフィードバックを顧客やパートナーから取得し、機能の導入をサポートするため、Dynamics 365 Sales での統合エクスペリエンスが強化されています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 11/18/2019
ms.assetid: de61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: cindyliu
dynamics365pdf: true
ms.openlocfilehash: f2f78f97b7f3eec207766ccc433b37b32f5dcce5
ms.sourcegitcommit: b42a148c376fc4d3297326179cf301404448f570
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2888728"
---
# <a name="microsoft-teams-integration-enhancements"></a><span data-ttu-id="8e09b-103">Microsoft Teams 統合の機能拡張</span><span class="sxs-lookup"><span data-stu-id="8e09b-103">Microsoft Teams integration enhancements</span></span>


| <span data-ttu-id="8e09b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8e09b-104">Enabled for</span></span>    |  <span data-ttu-id="8e09b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8e09b-105">Public preview</span></span> | <span data-ttu-id="8e09b-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="8e09b-106">Early access</span></span> | <span data-ttu-id="8e09b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8e09b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="8e09b-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8e09b-108">End users, automatically</span></span>|-|<span data-ttu-id="8e09b-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8e09b-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8e09b-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="8e09b-110">Aug 2, 2019</span></span>| <span data-ttu-id="8e09b-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8e09b-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8e09b-112">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="8e09b-112">Oct 31, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="8e09b-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8e09b-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8e09b-114">Dynamics 365 Sales と Teams の統合は、2019 年 4 月に導入されました。</span><span class="sxs-lookup"><span data-stu-id="8e09b-114">Dynamics 365 Sales integration with Teams was introduced in April 2019.</span></span> <span data-ttu-id="8e09b-115">この拡張機能では、Dynamics 365 Sales アプリを終了することなく、Dynamics 365 Sales レコードを Microsoft Teams チャネルに接続できます。</span><span class="sxs-lookup"><span data-stu-id="8e09b-115">Enhancements help to connect Dynamics 365 Sales records to Microsoft Teams channels without leaving the Dynamics 365 Sales app.</span></span> <span data-ttu-id="8e09b-116">販売担当者は、Dynamics 365 Sales のアクセス権限に基づいて、接続フローの間に、チーム メンバーのレコメンデーションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="8e09b-116">Sellers will receive team member recommendations, during the connection flow, based on Dynamics 365 Sales access privileges.</span></span> <span data-ttu-id="8e09b-117">拡張性をさらに向上させるため、Dynamics 365 Sales と Teams の接続で、既製のエンティティとカスタム エンティティに対してファイル共有を有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="8e09b-117">To further improve the extensibility, file sharing can now be enabled for any out-of-the-box and custom entities, across Dynamics 365 Sales and Teams connections.</span></span> <span data-ttu-id="8e09b-118">接続とは、Dynamics 365 のタブを Teams のチャネルに追加する機能のことです。</span><span class="sxs-lookup"><span data-stu-id="8e09b-118">Connections refer to the ability to add a Dynamics 365 tab to a Teams channel.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8e09b-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8e09b-119">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="8e09b-120">Dynamics 365 Sales のレコードを Microsoft Teams のチャネルに接続すると、Dynamics 365 Sales レコードに関連付けられているユーザーに基づいて、関連するメンバーが提案されます。</span><span class="sxs-lookup"><span data-stu-id="8e09b-120">When connecting a Dynamics 365 Sales record to a Microsoft Teams channel, relevant members are suggested based on users associated with the Dynamics 365 Sales record.</span></span> <span data-ttu-id="8e09b-121">チャネルの所有者として指定されている場合、ユーザーはメンバーの提案を使用できます。</span><span class="sxs-lookup"><span data-stu-id="8e09b-121">Member suggestions will be available to a user if designated as a channel owner.</span></span> 
- <span data-ttu-id="8e09b-122">カスタム エンティティ タイプを含むすべてのエンティティ タイプについて、Microsoft Teams の統合機能で SDK サポートを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8e09b-122">SDK support is now available for the Microsoft Teams integration feature for any entity type, including custom entity types.</span></span> 
- <span data-ttu-id="8e09b-123">Dynamics 365 Sales レコード ページから Teams チャネルを作成するとき、ユーザーは Dynamics 365 Sales レコードを選択したチャネルに自動的に接続できます。</span><span class="sxs-lookup"><span data-stu-id="8e09b-123">When creating a Teams channel from the Dynamics 365 Sales record page, users can automatically connect the Dynamics 365 Sales record to the selected channel.</span></span>
<!--feature detail end -->


> [!NOTE]
> - <span data-ttu-id="8e09b-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="8e09b-124">This feature is available in the Unified Interface only.</span></span> 
> - <span data-ttu-id="8e09b-125">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="8e09b-125">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="8e09b-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="8e09b-126">See also</span></span>
<span data-ttu-id="8e09b-127">[機能の探索](https://aka.ms/ROGS19RW2ROV3) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="8e09b-127">[Feature exploration](https://aka.ms/ROGS19RW2ROV3) (video)</span></span>

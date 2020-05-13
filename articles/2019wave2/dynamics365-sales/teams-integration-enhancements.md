---
title: Microsoft Teams 統合の機能拡張
description: Microsoft Teams の統合によるコラボレーションのメリットに関するフィードバックを顧客やパートナーから取得し、機能の導入をサポートするため、Dynamics 365 Sales での統合エクスペリエンスが強化されています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 03/20/2020
ms.assetid: de61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: cindyliu
dynamics365pdf: true
ms.openlocfilehash: 5ac485439911ba4ea60ce54f1437f5db944d6cba
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178827"
---
# <a name="microsoft-teams-integration-enhancements"></a><span data-ttu-id="44485-103">Microsoft Teams 統合の機能拡張</span><span class="sxs-lookup"><span data-stu-id="44485-103">Microsoft Teams integration enhancements</span></span>


| <span data-ttu-id="44485-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="44485-104">Enabled for</span></span>    |  <span data-ttu-id="44485-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="44485-105">Public preview</span></span> | <span data-ttu-id="44485-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="44485-106">Early access</span></span> | <span data-ttu-id="44485-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="44485-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="44485-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="44485-108">End users, automatically</span></span>|-|<span data-ttu-id="44485-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="44485-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="44485-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="44485-110">Aug 2, 2019</span></span>| <span data-ttu-id="44485-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="44485-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="44485-112">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="44485-112">Oct 31, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="44485-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="44485-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="44485-114">Dynamics 365 Sales と Teams の統合は、2019 年 4 月に導入されました。</span><span class="sxs-lookup"><span data-stu-id="44485-114">Dynamics 365 Sales integration with Teams was introduced in April 2019.</span></span> <span data-ttu-id="44485-115">この拡張機能では、Dynamics 365 Sales アプリを終了することなく、Dynamics 365 Sales レコードを Microsoft Teams チャネルに接続できます。</span><span class="sxs-lookup"><span data-stu-id="44485-115">Enhancements help to connect Dynamics 365 Sales records to Microsoft Teams channels without leaving the Dynamics 365 Sales app.</span></span> <span data-ttu-id="44485-116">販売担当者は、Dynamics 365 Sales のアクセス権限に基づいて、接続フローの間に、チーム メンバーのレコメンデーションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="44485-116">Sellers will receive team member recommendations, during the connection flow, based on Dynamics 365 Sales access privileges.</span></span> <span data-ttu-id="44485-117">拡張性をさらに向上させるため、Dynamics 365 Sales と Teams の接続で、既製のエンティティとカスタム エンティティに対してファイル共有を有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="44485-117">To further improve the extensibility, file sharing can now be enabled for any out-of-the-box and custom entities, across Dynamics 365 Sales and Teams connections.</span></span> <span data-ttu-id="44485-118">接続とは、Dynamics 365 のタブを Teams のチャネルに追加する機能のことです。</span><span class="sxs-lookup"><span data-stu-id="44485-118">Connections refer to the ability to add a Dynamics 365 tab to a Teams channel.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="44485-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="44485-119">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="44485-120">Dynamics 365 Sales のレコードを Microsoft Teams のチャネルに接続すると、Dynamics 365 Sales レコードに関連付けられているユーザーに基づいて、関連するメンバーが提案されます。</span><span class="sxs-lookup"><span data-stu-id="44485-120">When connecting a Dynamics 365 Sales record to a Microsoft Teams channel, relevant members are suggested based on users associated with the Dynamics 365 Sales record.</span></span> <span data-ttu-id="44485-121">チャネルの所有者として指定されている場合、ユーザーはメンバーの提案を使用できます。</span><span class="sxs-lookup"><span data-stu-id="44485-121">Member suggestions will be available to a user if designated as a channel owner.</span></span> 
- <span data-ttu-id="44485-122">カスタム エンティティ タイプを含むすべてのエンティティ タイプについて、Microsoft Teams の統合機能で SDK サポートを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="44485-122">SDK support is now available for the Microsoft Teams integration feature for any entity type, including custom entity types.</span></span> 
- <span data-ttu-id="44485-123">Dynamics 365 Sales レコード ページから Teams チャネルを作成するとき、ユーザーは Dynamics 365 Sales レコードを選択したチャネルに自動的に接続できます。</span><span class="sxs-lookup"><span data-stu-id="44485-123">When creating a Teams channel from the Dynamics 365 Sales record page, users can automatically connect the Dynamics 365 Sales record to the selected channel.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="44485-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="44485-124">This feature is available in the Unified Interface only.</span></span> 
>
> <span data-ttu-id="44485-125">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="44485-125">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="44485-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="44485-126">See also</span></span>
<span data-ttu-id="44485-127">[機能の探索](https://aka.ms/ROGS19RW2ROV3) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="44485-127">[Feature exploration](https://aka.ms/ROGS19RW2ROV3) (video)</span></span>

<span data-ttu-id="44485-128">[Microsoft Teams によって強化される共同作業エクスペリエンス](https://docs.microsoft.com/dynamics365/teams-integration/teams-collaboration-enhanced-experience) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="44485-128">[Enhanced Collaboration Experience with Microsoft Teams](https://docs.microsoft.com/dynamics365/teams-integration/teams-collaboration-enhanced-experience) (docs)</span></span>

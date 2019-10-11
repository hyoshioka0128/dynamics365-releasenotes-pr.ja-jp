---
title: Microsoft Teams 統合の機能拡張
description: Microsoft Teams の統合によるコラボレーションのメリットに関するフィードバックを顧客やパートナーから取得し、機能の導入をサポートするため、Dynamics 365 では統合エクスペリエンスが強化されています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 09/05/2019
ms.assetid: de61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: 6deb894d17d1d5d16aea23d0855c77c7a9bc3e67
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143397"
---
# <a name="microsoft-teams-integration-enhancements"></a><span data-ttu-id="8d666-103">Microsoft Teams 統合の機能拡張</span><span class="sxs-lookup"><span data-stu-id="8d666-103">Microsoft Teams integration enhancements</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="8d666-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8d666-104">Enabled for</span></span>    |  <span data-ttu-id="8d666-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8d666-105">Public preview</span></span> | <span data-ttu-id="8d666-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="8d666-106">Early access</span></span> | <span data-ttu-id="8d666-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8d666-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="8d666-108">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8d666-108">Users, automatically</span></span>|-|<span data-ttu-id="8d666-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8d666-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8d666-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="8d666-110">Aug 2, 2019</span></span>| <span data-ttu-id="8d666-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8d666-111">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="8d666-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8d666-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8d666-113">Dynamics 365 と Teams の統合は、2019 年 4 月に導入されました。</span><span class="sxs-lookup"><span data-stu-id="8d666-113">Dynamics 365 integration with Teams was introduced in April 2019.</span></span> <span data-ttu-id="8d666-114">この拡張機能では、Dynamics 365 アプリを終了することなく、Dynamics 365 レコードを Teams チャネルに接続できます。</span><span class="sxs-lookup"><span data-stu-id="8d666-114">Enhancements help to connect Dynamics 365 records to Teams channels without leaving the Dynamics 365 app.</span></span> <span data-ttu-id="8d666-115">販売担当者は、Dynamics 365 のアクセス権限に基づいて、接続フローの間に、チーム メンバーのレコメンデーションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="8d666-115">Sellers will receive team member recommendations, during the connection flow, based on Dynamics 365 access privileges.</span></span> <span data-ttu-id="8d666-116">拡張性をさらに向上させるため、Dynamics 365 と Teams の接続で、既製のエンティティとカスタム エンティティに対してファイル共有を有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="8d666-116">To further improve the extensibility, file sharing can now be enabled for any out-of-the-box and custom entities, across Dynamics 365 and Teams connections.</span></span> <span data-ttu-id="8d666-117">接続とは、Dynamics 365 のタブを Teams のチャネルに追加する機能のことです。</span><span class="sxs-lookup"><span data-stu-id="8d666-117">Connections refer to the ability to add a Dynamics 365 tab to a Teams channel.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8d666-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8d666-118">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="8d666-119">Dynamics 365 のレコードを Teams のチャネルに接続すると、Dynamics 365 レコードに関連付けられているユーザーに基づいて、関連するメンバーが提案されます。</span><span class="sxs-lookup"><span data-stu-id="8d666-119">When connecting a Dynamics 365 record to a Teams channel, relevant members are suggested based on users associated with the Dynamics 365 record.</span></span> <span data-ttu-id="8d666-120">チャネルの所有者として指定されている場合、ユーザーはメンバーの提案を使用できます。</span><span class="sxs-lookup"><span data-stu-id="8d666-120">Member suggestions will be available to a user if designated as a channel owner.</span></span> 
- <span data-ttu-id="8d666-121">カスタム エンティティ タイプを含むすべてのエンティティ タイプについて、Microsoft Teams の統合機能で SDK サポートを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8d666-121">SDK support is now available for the Microsoft Teams integration feature for any entity type, including custom entity types.</span></span> 
- <span data-ttu-id="8d666-122">Dynamics 365 レコード ページから Teams チャネルを作成するとき、ユーザーは Dynamics 365 レコードを選択したチャネルに自動的に接続できます。</span><span class="sxs-lookup"><span data-stu-id="8d666-122">When creating a Teams channel from the Dynamics 365 record page, users can automatically connect the Dynamics 365 record to the selected channel.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="8d666-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="8d666-123">This feature is available in the Unified Interface only.</span></span>









## <a name="see-also"></a><span data-ttu-id="8d666-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="8d666-124">See also</span></span>
<span data-ttu-id="8d666-125">[機能の探索](https://aka.ms/ROGS19RW2ROV3) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="8d666-125">[Feature exploration](https://aka.ms/ROGS19RW2ROV3) (video)</span></span>

<span data-ttu-id="8d666-126">[Microsoft Teams 統合](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-sales/teams-integration-enhancements) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="8d666-126">[Microsoft Teams integration](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-sales/teams-integration-enhancements) (blog)</span></span>

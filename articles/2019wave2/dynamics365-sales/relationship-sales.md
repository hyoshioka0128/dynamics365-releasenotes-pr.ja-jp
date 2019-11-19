---
title: LinkedIn Sales Navigator 統合の機能拡張
description: LinkedIn Sales Navigator 統合は、引き続き 2 つの製品 Dynamics 365 Sales と LinkedIn Sales Navigator の価値を合わせて提供します。 最新の改良の目的は、LinkedIn InMail を営業ユーザーからもっとアクセスしやすくすることです。
author: relnotes
ms.reviewer: shujoshi
ms.date: 10/23/2019
ms.assetid: d461278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: goravi
dynamics365pdf: true
ms.openlocfilehash: ad8af53b26fbe5a9ed7e57fc298296e85bb361fa
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2661341"
---
# <a name="linkedin-sales-navigator-integration-enhancements"></a><span data-ttu-id="7e866-104">LinkedIn Sales Navigator 統合の機能拡張</span><span class="sxs-lookup"><span data-stu-id="7e866-104">LinkedIn Sales Navigator integration enhancements</span></span>


| <span data-ttu-id="7e866-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="7e866-105">Enabled for</span></span>    |  <span data-ttu-id="7e866-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7e866-106">Public preview</span></span> | <span data-ttu-id="7e866-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="7e866-107">Early access</span></span> | <span data-ttu-id="7e866-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="7e866-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="7e866-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7e866-109">End users, automatically</span></span>|-|<span data-ttu-id="7e866-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7e866-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7e866-111">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="7e866-111">Aug 2, 2019</span></span>| <span data-ttu-id="7e866-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7e866-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7e866-113">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7e866-113">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="7e866-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7e866-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7e866-115">Microsoft Relationship Sales は LinkedIn Sales Navigator と Dynamics 365 Sales を連携して、販売担当者がよりパーソナライズされた有意義な関係を購入者と築けるようにします。</span><span class="sxs-lookup"><span data-stu-id="7e866-115">Microsoft Relationship Sales solution brings together LinkedIn Sales Navigator and Dynamics 365 Sales to empower sellers to drive more personalized and meaningful engagements with buyers.</span></span> <span data-ttu-id="7e866-116">LinkedIn の InMails は、営業担当者が顧客と連絡をとるためによく使用される通信チャネルです。</span><span class="sxs-lookup"><span data-stu-id="7e866-116">InMails by LinkedIn are a commonly used communication channel for sales representatives to connect with their customers.</span></span> <span data-ttu-id="7e866-117">Dynamics 365 Sales は、営業担当者が Dynamics 365 Sales エンティティ内から InMail を作成して送信できるようにすることで、効率的な顧客エンゲージメントを促進します。</span><span class="sxs-lookup"><span data-stu-id="7e866-117">Dynamics 365 Sales will foster efficient customer engagement by allowing sales reps to compose and send InMail from within Dynamics 365 Sales entities.</span></span>

<span data-ttu-id="7e866-118">販売担当者が取引先担当者をより簡単に識別できるように、LinkedIn からのプロフィール写真を Dynamics 365 Sales 内で使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7e866-118">To help sellers more easily identify contacts, profile pictures from LinkedIn will now be available within Dynamics 365 Sales.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7e866-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7e866-119">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="7e866-120">LinkedIn InMail コンポーネントをホストするための新しい LinkedIn ウィジェットが、Dynamics 365 Sales レコード内に導入されます。</span><span class="sxs-lookup"><span data-stu-id="7e866-120">A new LinkedIn widget will be introduced inside a Dynamics 365 Sales record to host the LinkedIn InMail component.</span></span> <span data-ttu-id="7e866-121">この LinkedIn ウィジェットを使用すると、営業担当者は、LinkedIn のプロフィール情報を並べて表示しながら、取引先担当者、営業案件、リード、および取引先企業エンティティの連絡先に InMail を送信できます。</span><span class="sxs-lookup"><span data-stu-id="7e866-121">This LinkedIn widget will allow sales representatives to send InMails to their contact, opportunity, lead, and account entity contacts while viewing the LinkedIn profile information alongside.</span></span>

- <span data-ttu-id="7e866-122">セールス ユーザーは、Dynamics 365 Sales の組織図機能で作業しながら、InMail コンポーネントにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="7e866-122">Sales users will be able to access the InMail component while working on the Org chart feature in Dynamics 365 Sales.</span></span> <span data-ttu-id="7e866-123">組織図ノードをダブルクリックして、InMail アイコンを選択するだけで、Dynamics 365 Sales から直接 LinkedIn InMail を送信できます。</span><span class="sxs-lookup"><span data-stu-id="7e866-123">They can just double-click the Org chart node and select the InMail icon to send LinkedIn InMails directly from Dynamics 365 Sales.</span></span>

- <span data-ttu-id="7e866-124">組織で同期が有効になっている場合、送信された InMail は、InMail が送信された場所から、取引先担当者、営業案件、リード、および取引先企業エンティティのアクティビティ タイムラインにもアクティビティとして追加されます。</span><span class="sxs-lookup"><span data-stu-id="7e866-124">If organizations have enabled the sync, the sent InMail is also added as an activity in the activity timeline of the contact, opportunity, lead, and account entity from where the InMail was sent.</span></span>

- <span data-ttu-id="7e866-125">組織で同期が有効になっている場合、LinkedIn のプロフィール写真が Dynamics 365 Sales 内で取引先担当者の写真として表示されます。</span><span class="sxs-lookup"><span data-stu-id="7e866-125">If organizations have enabled the sync, profile photos from LinkedIn will show as the contact picture within Dynamics 365 Sales.</span></span> <span data-ttu-id="7e866-126">これにより、取引先担当者の写真としてアップロードされた既存の写真が置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="7e866-126">This will replace any existing picture that has been uploaded as the contact picture.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="7e866-127">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="7e866-127">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="7e866-128">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="7e866-128">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="7e866-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="7e866-129">See also</span></span>

<span data-ttu-id="7e866-130">[既定の LinkedIn Sales Navigator コントロールの有効化](https://docs.microsoft.com/en-us/dynamics365/linkedin/install-sales-navigator) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7e866-130">[Enable default LinkedIn Sales Navigator controls](https://docs.microsoft.com/en-us/dynamics365/linkedin/install-sales-navigator) (docs)</span></span>

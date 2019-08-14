---
title: LinkedIn Sales Navigator 統合の機能拡張
description: LinkedIn Sales Navigator 統合は、引き続き 2 つの製品 Dynamics 365 for Sales と LinkedIn Sales Navigator の価値を合わせて提供します。 最新の改良の目的は、LinkedIn InMail を営業ユーザーからもっとアクセスしやすくすることです。
author: relnotes
ms.reviewer: shujoshi
ms.date: 07/22/2019
ms.assetid: d461278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: e3f3547e3f0b55d9a74e844594476608570ac8bb
ms.sourcegitcommit: 0b8be9c5138c1e2b7f46527bd303cae5207cced7
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/29/2019
ms.locfileid: "1791358"
---
# <a name="linkedin-sales-navigator-integration-enhancements"></a><span data-ttu-id="8b0ff-104">LinkedIn Sales Navigator 統合の機能拡張</span><span class="sxs-lookup"><span data-stu-id="8b0ff-104">LinkedIn Sales Navigator integration enhancements</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="8b0ff-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="8b0ff-105">Enabled for</span></span>    |  <span data-ttu-id="8b0ff-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8b0ff-106">Public preview</span></span> | <span data-ttu-id="8b0ff-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8b0ff-107">General availability</span></span> | <span data-ttu-id="8b0ff-108">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="8b0ff-108">Early Access</span></span> |
| ---------- | ---------- |---------- |---------- |
|<span data-ttu-id="8b0ff-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8b0ff-109">End users, automatically</span></span>|| <span data-ttu-id="8b0ff-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8b0ff-110">October 2019</span></span>|<span data-ttu-id="8b0ff-111">はい</span><span class="sxs-lookup"><span data-stu-id="8b0ff-111">Yes</span></span> |


## <a name="business-value"></a><span data-ttu-id="8b0ff-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8b0ff-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8b0ff-113">Microsoft Relationship Sales ソリューションは LinkedIn Sales Navigator と Dynamics 365 for Sales を連携させて、社内の販売担当者がよりパーソナライズされた有意義な関係を購入者と築けるようにします。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-113">Microsoft Relationship Sales solution brings together LinkedIn Sales Navigator and Dynamics 365 for Sales to empower sellers to drive more personalized and meaningful engagements with buyers.</span></span> <span data-ttu-id="8b0ff-114">LinkedIn の InMails は、営業担当者が顧客と連絡をとるためによく使用される通信チャネルです。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-114">InMails by LinkedIn are a commonly used communication channel for sales representatives to connect with their customers.</span></span> <span data-ttu-id="8b0ff-115">Dynamics 365 for Sales は、営業担当者が Dynamics 365 for Sales エンティティ内から InMail を作成して送信できるようにすることで、効率的な顧客エンゲージメントを促進します。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-115">Dynamics 365 for Sales will foster efficient customer engagement by allowing sales reps to compose and send InMail from within Dynamics 365 for Sales entities.</span></span>

<span data-ttu-id="8b0ff-116">販売担当者が取引先担当者をより簡単に識別できるように、LinkedIn からのプロフィール写真を Dynamics 365 for Sales 内で使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-116">To help sellers more easily identify contacts, profile pictures from LinkedIn will now be available within Dynamics 365 for Sales.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8b0ff-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8b0ff-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="8b0ff-118">LinkedIn InMail コンポーネントをホストするための新しい LinkedIn ウィジェットが、Dynamics 365 レコード内に導入されます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-118">A new LinkedIn widget will be introduced inside a Dynamics 365 record to host the LinkedIn InMail component.</span></span> <span data-ttu-id="8b0ff-119">この LinkedIn ウィジェットを使用すると、営業担当者は、LinkedIn のプロフィール情報を並べて表示しながら、取引先担当者、営業案件、リード、およびエンティティ連絡先に InMails を送信できます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-119">This LinkedIn widget will allow sales representatives to send InMails to their contact, opportunity, lead, and entity contacts while viewing the LinkedIn profile information alongside.</span></span>

- <span data-ttu-id="8b0ff-120">セールス ユーザーは、Dynamics 365 for Sales の組織図機能で作業しながら、InMail コンポーネントにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-120">Sales users will be able to access the InMail component while working on the Org chart feature in Dynamics 365 for Sales.</span></span> <span data-ttu-id="8b0ff-121">組織図ノードをダブルクリックして、InMail アイコンを選択するだけで、Dynamics 365 for Sales から直接 LinkedIn InMail を送信できます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-121">They can just double-click the Org chart node and select the InMail icon to be able to send LinkedIn InMails directly from Dynamics 365 for Sales.</span></span>

- <span data-ttu-id="8b0ff-122">組織で同期が有効になっている場合、送信された InMail は、InMail が送信された場所から、取引先担当者、営業案件、リード、および取引先企業エンティティのアクティビティ タイムラインにもアクティビティとして追加されます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-122">If organizations have enabled the sync, the sent InMail is also added as an activity in the activity timeline of the contact, opportunity, lead, and account entity from where the InMail was sent.</span></span>

- <span data-ttu-id="8b0ff-123">組織で同期が有効になっている場合、LinkedIn のプロフィール写真が Dynamics 365 内で取引先担当者の写真として表示されます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-123">If organizations have enabled the sync, profile photos from LinkedIn will show as the contact picture within Dynamics 365.</span></span> <span data-ttu-id="8b0ff-124">これにより、取引先担当者の写真としてアップロードされた既存の写真が置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-124">This will replace any existing picture that has been uploaded as the contact picture.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="8b0ff-125">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="8b0ff-125">This feature is available in the Unified Interface only.</span></span>









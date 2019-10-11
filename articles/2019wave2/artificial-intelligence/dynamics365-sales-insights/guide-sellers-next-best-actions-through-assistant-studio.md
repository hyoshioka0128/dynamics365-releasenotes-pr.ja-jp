---
title: Assistant Studio での次善のアクションによる販売担当者のガイド
description: 販売担当者は、リレーションシップ アシスタントを使用して次善のアクションを見つけることができます。 Assistant Studio を使用することで、組織はビジネス ニーズに合わせてこれらのアクションを調整できます。 この機能は、2019 年リリース ウェーブ 2 で一般提供されます。
author: relnotes
ms.reviewer: udag
ms.date: 09/13/2019
ms.assetid: c463278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: ab58c0a32b315d676d23b5296d3b77c6acfd75ea
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140141"
---
# <a name="guide-sellers-with-next-best-actions-through-the-assistant-studio"></a><span data-ttu-id="a11d7-105">Assistant Studio での次善のアクションによる販売担当者のガイド</span><span class="sxs-lookup"><span data-stu-id="a11d7-105">Guide sellers with next best actions through the Assistant Studio</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="a11d7-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="a11d7-106">Enabled for</span></span>    |  <span data-ttu-id="a11d7-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a11d7-107">Public preview</span></span> | <span data-ttu-id="a11d7-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="a11d7-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a11d7-109">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a11d7-109">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="a11d7-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a11d7-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a11d7-111">2019 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a11d7-111">Apr 1, 2019</span></span>| <span data-ttu-id="a11d7-112">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="a11d7-112">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="a11d7-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a11d7-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a11d7-114">販売担当者は多忙です。</span><span class="sxs-lookup"><span data-stu-id="a11d7-114">Sellers are busy.</span></span> <span data-ttu-id="a11d7-115">情報の収集、同僚への連絡、顧客エンゲージメントの準備に多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="a11d7-115">They spend significant time collecting information, reaching out to peers, and preparing for customer engagements.</span></span> <span data-ttu-id="a11d7-116">その間ずっと、適切な顧客を、適切なタイミングと適切な方法でフォローアップできるように努めます。</span><span class="sxs-lookup"><span data-stu-id="a11d7-116">All the while, they ensure that they follow up with the right customer, at the right time, and in the right way.</span></span> <span data-ttu-id="a11d7-117">推奨アクションは、販売担当者が最適な次善のアクションを実行できるように支援し、時間の節約、効果の最大化、営業全体の生産性向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a11d7-117">Suggested actions can help sellers optimize their next best action and can help save time and maximize effectiveness, improving overall sales productivity.</span></span>

<span data-ttu-id="a11d7-118">2019 年 4 月から、組織が販売担当者に対するカスタム推奨アクションを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a11d7-118">In April 2019, we started offering organizations the ability to create custom suggested actions for sellers.</span></span> <span data-ttu-id="a11d7-119">これらの推奨アクションは、組織がよりターゲットを絞った推奨によって販売担当者をガイドすることで販売プロセスを変革できるように支援します。</span><span class="sxs-lookup"><span data-stu-id="a11d7-119">These suggested actions empower organizations to transform the sales process by helping guide sellers with more targeted suggestions.</span></span> <span data-ttu-id="a11d7-120">組織は、多数のシステムからのイベントを使用し、条件を定義して、推奨が表示される状況を記述できます。</span><span class="sxs-lookup"><span data-stu-id="a11d7-120">Organizations can use events from many systems and define conditions to describe circumstances under which each suggestion will be surfaced.</span></span> <span data-ttu-id="a11d7-121">これにより、販売担当者をビジネス プロセス内で柔軟にガイドできます。</span><span class="sxs-lookup"><span data-stu-id="a11d7-121">This provides flexibility when guiding sellers in their business processes.</span></span> <span data-ttu-id="a11d7-122">ガイドラインによって、適切な情報が適切なタイミングで販売担当者のワークフローにプロアクティブにプッシュされます。</span><span class="sxs-lookup"><span data-stu-id="a11d7-122">The guidelines proactively push the right information into the seller’s workflow at the right moment.</span></span> <span data-ttu-id="a11d7-123">Studio は、ビジネス手法を合理化し、営業活動における予測可能性を高めることにより、組織がベスト プラクティスを実施して生産性を大幅に改善し、より迅速な商談成立と収益増加のための道筋を販売担当者にガイドできるように支援します。</span><span class="sxs-lookup"><span data-stu-id="a11d7-123">By streamlining business practices and introducing more predictability into sales motions, the studio helps organizations enforce best practices and transform productivity, guiding sellers on a path to close deals faster and increase revenue.</span></span>

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a11d7-124">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a11d7-124">Feature details</span></span>
<!--feature detail start --><span data-ttu-id="a11d7-125">
-\*\*カスタマイズされた推奨アクションで販売担当者をガイド\*\*: Microsoft Flow と Studio を使用して、特定の販売プロセスを順守した、Relationship Assistant やその他のサーフェスを通じて適切なタイミングで販売担当者に提供される新しい分析情報カードを作成します。</span><span class="sxs-lookup"><span data-stu-id="a11d7-125">
-\*\*Guide sellers with customized suggested actions\*\*: Use Microsoft Flow and the studio to create new insight cards that adhere to particular sales processes and are delivered to sellers at the right moment via the Relationship Assistant and other surfaces.</span></span> <span data-ttu-id="a11d7-126">推奨アクションは、受信メールや Dynamics 365 Sales の更新など、Microsoft Flow に登録された 200 以上のサービスによってトリガーされるイベントに基づいて作成でき、あらゆる組織のベスト プラクティスを順守する独自の柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="a11d7-126">Suggested actions can be based on events triggered by over 200 services registered with Microsoft Flow, such as emails received or updates in Dynamics 365 Sales, offering unique flexibility to adhere to every organizational best practices.</span></span><span data-ttu-id="a11d7-127">
-\*\*パーソナライズされたガイダンスのためのロールのターゲット設定\*\*: アクションごとに対応可能な対象者を選択することで、適切な販売担当者ロールで推奨アクションのターゲットを設定し、適切なコンテンツが適切なタイミングで適切な個人に表示されるようにします。</span><span class="sxs-lookup"><span data-stu-id="a11d7-127">
-\*\*Target roles for personalized guidance\*\*: Select the addressable audience for each action, to target suggested actions at the right seller roles, ensuring the right content is surfaced to the right individual at the right time.</span></span> <span data-ttu-id="a11d7-128">コンテキストが適切な場合に、販売担当者が販売資料を活用する可能性が高くなります。</span><span class="sxs-lookup"><span data-stu-id="a11d7-128">When the context is right, sellers are more likely to leverage sales materials.</span></span><span data-ttu-id="a11d7-129">
-\*\*強化されたエクスペリエンスの利用\*\*: Microsoft はお客様へのコミットメントの一環としてフィードバックに積極的に耳を傾け、それに従ってエクスペリエンスを改善しています。</span><span class="sxs-lookup"><span data-stu-id="a11d7-129">
-\*\*Benefit from enhanced experiences\*\*: As part of our commitment to customers, we are actively listening to feedback and improving experiences accordingly.</span></span> <span data-ttu-id="a11d7-130">ユーザーは、自分で作成したカードを検索し、より多くのフィルターを利用し、より合理化されたエクスペリエンスを利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a11d7-130">Users can now search for cards they have created, benefit from more filters, and enjoy a more streamlined experience.</span></span> <span data-ttu-id="a11d7-131">特に、フロー作成エクスペリエンスが Studio に組み込まれ、不要なコンテキストの切り替えを行わずに済むようになりました。</span><span class="sxs-lookup"><span data-stu-id="a11d7-131">Notably, the flow creation experience is embedded into the studio to save unnecessary context switching.</span></span>

<!--feature detail end -->



## <a name="see-also"></a><span data-ttu-id="a11d7-132">関連項目</span><span class="sxs-lookup"><span data-stu-id="a11d7-132">See also</span></span>
<span data-ttu-id="a11d7-133">[機能の探索](https://aka.ms/ROGSI19RW2ROV2) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="a11d7-133">[Feature exploration](https://aka.ms/ROGSI19RW2ROV2) (video)</span></span>

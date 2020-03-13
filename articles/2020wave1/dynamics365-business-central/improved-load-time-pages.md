---
title: ページの読み込み時間の向上
description: ページの読み込み時間の向上
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 02/03/2020
ms.assetid: c9b05388-851a-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 6eb528832a20e1e1b7dd709067262a0c388a2780
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031838"
---
# <a name="improved-load-time-for-pages"></a><span data-ttu-id="5ba30-103">ページの読み込み時間の向上</span><span class="sxs-lookup"><span data-stu-id="5ba30-103">Improved load time for pages</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="5ba30-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5ba30-104">Enabled for</span></span>    |  <span data-ttu-id="5ba30-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5ba30-105">Public preview</span></span> | <span data-ttu-id="5ba30-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5ba30-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5ba30-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="5ba30-107">End users, automatically</span></span>|<span data-ttu-id="5ba30-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5ba30-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5ba30-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5ba30-109">Feb 1, 2020</span></span>| <span data-ttu-id="5ba30-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="5ba30-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5ba30-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5ba30-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5ba30-112">ビジネス ユーザーは、タスクを完了するためにページ間を移動するとき、ページとダイアログ ボックスがすばやく読み込まれることを期待します。</span><span class="sxs-lookup"><span data-stu-id="5ba30-112">When navigating across pages to complete their tasks, business users expect snappy loading of pages and dialog boxes.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5ba30-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5ba30-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5ba30-114">ユーザーは、頻繁に使用するページが前より速く開くようになったことがわかります。</span><span class="sxs-lookup"><span data-stu-id="5ba30-114">Users will find that pages they use often now open faster.</span></span> <span data-ttu-id="5ba30-115">技術的には、レンダリングされたページは、最初に開かれたときにキャッシュされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5ba30-115">Technically, the rendered page is now cached the first time it is opened.</span></span> <span data-ttu-id="5ba30-116">これを行うために、ビジネス データや機密情報がユーザーのデバイスに永続化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="5ba30-116">This is done without persisting any business data or sensitive information to the user's device.</span></span> <span data-ttu-id="5ba30-117">ページへの後続のアクセスでは、データがサービスからフェッチされている間は、すぐにページがレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="5ba30-117">Subsequent accesses to the page will immediately render the page while data is fetched from the service.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="5ba30-118">フィードバック</span><span class="sxs-lookup"><span data-stu-id="5ba30-118">Tell us what you think</span></span>
<span data-ttu-id="5ba30-119">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="5ba30-119">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="5ba30-120">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="5ba30-120">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="5ba30-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="5ba30-121">See also</span></span>

<span data-ttu-id="5ba30-122">[開発者向けのパフォーマンス トピック](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5ba30-122">[Performance Topics for Developers](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (docs)</span></span>

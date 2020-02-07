---
title: AI を搭載した自動取り込みが一般提供される - 自動取り込み
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 09/13/2019
ms.assetid: d36b871b-34cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: goravi
dynamics365pdf: true
ms.openlocfilehash: e8ab0e9c3c11f333a61a9c001e763287438a3021
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986844"
---
# <a name="ai-infused-auto-capture-is-generally-available"></a><span data-ttu-id="1b325-102">AI を搭載した自動取り込みが一般提供されます</span><span class="sxs-lookup"><span data-stu-id="1b325-102">AI-infused Auto capture is generally available</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="1b325-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="1b325-103">Enabled for</span></span>    |  <span data-ttu-id="1b325-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1b325-104">Public preview</span></span> | <span data-ttu-id="1b325-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="1b325-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1b325-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1b325-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="1b325-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="1b325-107">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1b325-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1b325-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1b325-109">2019 年リリース ウェーブ 2 の一環として、新しいバージョンの自動取り込みをパブリック プレビューとしてリリースしました。</span><span class="sxs-lookup"><span data-stu-id="1b325-109">As part of 2019 release wave 2, we released for public preview a new version of Auto capture.</span></span> <span data-ttu-id="1b325-110">AI 機能を組み込むことにより、取り込まれた活動の適切なレコードへのマッピングが向上し、取り込まれた活動で示されている新しい連絡先が自動的に検出されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1b325-110">By incorporating AI capabilities, mapping of captured activities to the appropriate records was improved, and new contacts mentioned in captured activities were automatically detected.</span></span> <span data-ttu-id="1b325-111">さらに、オンボーディングを改善し、UI を合理化して、管理者が機能を簡単に有効にでき、販売担当者が活動と連絡先を簡単に追跡できるようにしました。</span><span class="sxs-lookup"><span data-stu-id="1b325-111">Furthermore, we improved onboarding and streamlined the UI, making it easier for admins to enable the feature and easier for sellers to track activities and contacts.</span></span>  

<span data-ttu-id="1b325-112">2020 年リリース ウェーブ 1 の一環として、これらの機能が一般提供されます。</span><span class="sxs-lookup"><span data-stu-id="1b325-112">As part of 2020 release wave 1, these capabilities become generally available.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1b325-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1b325-113">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="1b325-114">**エンティティへの活動の自動マッピングの利点**: エンティティに対する活動の AI 主導のマッピング。</span><span class="sxs-lookup"><span data-stu-id="1b325-114">**Benefit from the automated mapping of activities to entities**: AI-driven mapping of activities to entities.</span></span> <span data-ttu-id="1b325-115">自然言語処理 (NLP) モデルを組み込んで、活動と適切なレコード間の関連付けを改善し、Dynamics 365 のデータの品質を向上させました。</span><span class="sxs-lookup"><span data-stu-id="1b325-115">We incorporated Natural Language Processing (NLP) models to improve the association between activities to the appropriate records and increase the quality of the data in Dynamics 365.</span></span>
- <span data-ttu-id="1b325-116">**何も見過ごされないように UI の向上を活用**: 自動取り込みでは、タイムライン ウォールの上部に推奨される活動が集約され、取り込まれた活動の見つけやすさが向上するので、販売担当者は取り込まれた活動をより合理的な方法で追跡、編集、または却下できます。</span><span class="sxs-lookup"><span data-stu-id="1b325-116">**Take advantage of UI improvements so nothing falls between the cracks**: Auto capture aggregates activity suggestions at the top of the timeline wall to increase discoverability of captured activities, so sellers can track, edit, or dismiss captured activities in a more streamlined manner.</span></span> <span data-ttu-id="1b325-117">取り込まれた活動が追跡されると、タイムライン ウォールにシームレスに追加されます。</span><span class="sxs-lookup"><span data-stu-id="1b325-117">Once the captured activity is tracked, it will be added to the timeline wall seamlessly.</span></span>
- <span data-ttu-id="1b325-118">**推奨される活動と連絡先の専用リスト ビューの利点**: データ入力をより生産的かつ予防的にするために、自動取り込みは取り込まれた活動と連絡先の新しいリスト ビューを導入するため、販売担当者はワンストップ ショップで複数の活動を追跡し、新しい連絡先を作成できます。</span><span class="sxs-lookup"><span data-stu-id="1b325-118">**Benefit from dedicated list views for activity and contact suggestions**: To make data entry more productive and proactive, Auto capture introduces new list views for captured activities and contacts so sellers can have a one-stop-shop from which they can track multiple activities and create new contacts.</span></span> <span data-ttu-id="1b325-119">これにより、顧客関連の活動のより完全で正確な全体像が得られます。</span><span class="sxs-lookup"><span data-stu-id="1b325-119">This offers a more complete and accurate picture of customer-related activities.</span></span>
- <span data-ttu-id="1b325-120">**事前のセットアップや前提条件なしで簡単にオンボード**: 自動取り込みのオンボーディング エクスペリエンスが簡素化され、構成の障壁が除去されました。</span><span class="sxs-lookup"><span data-stu-id="1b325-120">**Onboard easily with no preliminary setup or prerequisites**: Auto capture onboarding experience is now simplified, and configuration barriers removed.</span></span> <span data-ttu-id="1b325-121">自動取り込みはサーバー側の同期に依存しなくなり、管理者は取り込む通信チャネルの種類を選択しながら、特定のセキュリティ ロールまたは組織全体で有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="1b325-121">Auto capture is no longer dependent on server-side sync and admins can enable it for specific security roles or for the entire organization while selecting the types of communication channels to capture.</span></span>
<!--feature detail end -->










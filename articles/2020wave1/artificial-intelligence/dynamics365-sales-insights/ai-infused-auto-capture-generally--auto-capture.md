---
title: 自動アクティビティと推奨される連絡先の改善
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 03/17/2020
ms.assetid: d36b871b-34cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: cindyliu
dynamics365pdf: true
ms.openlocfilehash: 0d74a3d9621200b152cea93d384348f7d88b6db7
ms.sourcegitcommit: f7b958b02d7cb7543a3f81414e7b3e62a5b8539d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2020
ms.locfileid: "3158360"
---
# <a name="improvements-to-automatic-activity-and-contact-suggestions"></a><span data-ttu-id="04f18-102">自動アクティビティと推奨される連絡先の改善</span><span class="sxs-lookup"><span data-stu-id="04f18-102">Improvements to automatic activity and contact suggestions</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="04f18-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="04f18-103">Enabled for</span></span>    |  <span data-ttu-id="04f18-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="04f18-104">Public preview</span></span> | <span data-ttu-id="04f18-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="04f18-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="04f18-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="04f18-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="04f18-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="04f18-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="04f18-108">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="04f18-108">Feb 1, 2020</span></span>| <span data-ttu-id="04f18-109">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="04f18-109">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="04f18-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="04f18-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="04f18-111">2019 年リリース ウェーブ 2 の一環として、新しいバージョンの自動取り込みをパブリック プレビューとしてリリースしました。</span><span class="sxs-lookup"><span data-stu-id="04f18-111">As part of 2019 release wave 2, we released for public preview a new version of Auto capture.</span></span> <span data-ttu-id="04f18-112">AI 機能を組み込むことにより、取り込まれた活動の適切なレコードへのマッピングが向上し、取り込まれた活動で示されている新しい連絡先が自動的に検出されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="04f18-112">By incorporating AI capabilities, mapping of captured activities to the appropriate records was improved, and new contacts mentioned in captured activities were automatically detected.</span></span> <span data-ttu-id="04f18-113">さらに、オンボーディングを改善し、UI を合理化して、管理者が機能を簡単に有効にでき、販売担当者が活動と連絡先を簡単に追跡できるようにしました。</span><span class="sxs-lookup"><span data-stu-id="04f18-113">Furthermore, we improved onboarding and streamlined the UI, making it easier for admins to enable the feature and easier for sellers to track activities and contacts.</span></span>  

<span data-ttu-id="04f18-114">2020 年リリース ウェーブ 1 の一環として、これらの機能が一般提供されます。</span><span class="sxs-lookup"><span data-stu-id="04f18-114">As part of 2020 release wave 1, these capabilities become generally available.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="04f18-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="04f18-115">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="04f18-116">**エンティティへの活動の自動マッピングの利点**: エンティティに対する活動の AI 主導のマッピング。</span><span class="sxs-lookup"><span data-stu-id="04f18-116">**Benefit from the automated mapping of activities to entities**: AI-driven mapping of activities to entities.</span></span> <span data-ttu-id="04f18-117">自然言語処理 (NLP) モデルを組み込んで、活動と適切なレコード間の関連付けを改善し、Dynamics 365 のデータの品質を向上させました。</span><span class="sxs-lookup"><span data-stu-id="04f18-117">We incorporated Natural Language Processing (NLP) models to improve the association between activities to the appropriate records and increase the quality of the data in Dynamics 365.</span></span>
- <span data-ttu-id="04f18-118">**何も見過ごされないように UI の向上を活用**: 自動取り込みでは、タイムライン ウォールの上部に推奨される活動が集約され、取り込まれた活動の見つけやすさが向上するので、販売担当者は取り込まれた活動をより合理的な方法で追跡、編集、または却下できます。</span><span class="sxs-lookup"><span data-stu-id="04f18-118">**Take advantage of UI improvements so nothing falls between the cracks**: Auto capture aggregates activity suggestions at the top of the timeline wall to increase discoverability of captured activities, so sellers can track, edit, or dismiss captured activities in a more streamlined manner.</span></span> <span data-ttu-id="04f18-119">取り込まれた活動が追跡されると、タイムライン ウォールにシームレスに追加されます。</span><span class="sxs-lookup"><span data-stu-id="04f18-119">Once the captured activity is tracked, it will be added to the timeline wall seamlessly.</span></span>
- <span data-ttu-id="04f18-120">**推奨される活動と連絡先の専用リスト ビューの利点**: データ入力をより生産的かつ予防的にするために、自動取り込みは取り込まれた活動と連絡先の新しいリスト ビューを導入するため、販売担当者はワンストップ ショップで複数の活動を追跡し、新しい連絡先を作成できます。</span><span class="sxs-lookup"><span data-stu-id="04f18-120">**Benefit from dedicated list views for activity and contact suggestions**: To make data entry more productive and proactive, Auto capture introduces new list views for captured activities and contacts so sellers can have a one-stop-shop from which they can track multiple activities and create new contacts.</span></span> <span data-ttu-id="04f18-121">これにより、顧客関連の活動のより完全で正確な全体像が得られます。</span><span class="sxs-lookup"><span data-stu-id="04f18-121">This offers a more complete and accurate picture of customer-related activities.</span></span>
- <span data-ttu-id="04f18-122">**事前のセットアップや前提条件なしで簡単にオンボード**: 自動取り込みのオンボーディング エクスペリエンスが簡素化され、構成の障壁が除去されました。</span><span class="sxs-lookup"><span data-stu-id="04f18-122">**Onboard easily with no preliminary setup or prerequisites**: Auto capture onboarding experience is now simplified, and configuration barriers removed.</span></span> <span data-ttu-id="04f18-123">自動取り込みはサーバー側の同期に依存しなくなり、管理者は取り込む通信チャネルの種類を選択しながら、特定のセキュリティ ロールまたは組織全体で有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="04f18-123">Auto capture is no longer dependent on server-side sync and admins can enable it for specific security roles or for the entire organization while selecting the types of communication channels to capture.</span></span>
<!--feature detail end -->










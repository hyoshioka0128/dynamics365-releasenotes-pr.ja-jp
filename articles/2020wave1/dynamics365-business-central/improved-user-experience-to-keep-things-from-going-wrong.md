---
title: 間違った方向に進まないようにするためのユーザー エクスペリエンスの向上
description: 潜在的な問題を発生前に指摘するビジュアル インジケーターがある Business Central を使用できるようになりました。
author: relnotes
ms.reviewer: edupont
ms.date: 06/23/2020
ms.assetid: bde2e299-ae99-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 2d365cc71744334692544c8f9cd917631c75fc47
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522799"
---
# <a name="improved-user-experience-to-keep-things-from-going-wrong"></a><span data-ttu-id="3fed0-103">間違った方向に進まないようにするためのユーザー エクスペリエンスの向上</span><span class="sxs-lookup"><span data-stu-id="3fed0-103">Improved user experience to keep things from going wrong</span></span>


| <span data-ttu-id="3fed0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3fed0-104">Enabled for</span></span>    |  <span data-ttu-id="3fed0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3fed0-105">Public preview</span></span> | <span data-ttu-id="3fed0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3fed0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3fed0-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3fed0-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="3fed0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3fed0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3fed0-109">2020 年 6 月 19 日</span><span class="sxs-lookup"><span data-stu-id="3fed0-109">Jun 19, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3fed0-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3fed0-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3fed0-111">ドキュメントまたは仕訳帳の処理中に発生する可能性のある問題を示す初期の視覚的手掛かりと控えめなインジケーターにより、生産性を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="3fed0-111">Early visual cues and unobtrusive indications of issues that you might experience while processing documents or journals can improve your productivity.</span></span> <span data-ttu-id="3fed0-112">問題が最も頻繁に発生する場所を示す製品テレメトリに基づいて、問題を発生前に回避するのに役立ついくつかのことを行いました。</span><span class="sxs-lookup"><span data-stu-id="3fed0-112">Based on product telemetry that shows where people experience issues most frequently, we've done a few things that can help you avoid issues before they occur.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3fed0-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3fed0-113">Feature details</span></span>
<!--feature detail start -->
### <a name="document-status"></a><span data-ttu-id="3fed0-114">ドキュメント状態</span><span class="sxs-lookup"><span data-stu-id="3fed0-114">Document status</span></span>

<span data-ttu-id="3fed0-115">ドキュメントの状態を簡単に認識できるようにして編集可能かどうかがわかるようにするために、販売注文や発注書などのドキュメントの**状態**フィールドをレベル上げおよび色分けしました。</span><span class="sxs-lookup"><span data-stu-id="3fed0-115">To make it easier to notice the status of a document so that you know if it can be edited, we've promoted and color-coded **Status** fields on documents such as sales and purchase orders.</span></span>  

<span data-ttu-id="3fed0-116">![レベル上げされて条件付きで書式設定された販売注文の状態フィールドのビュー](media/document-status.png "レベル上げされて条件付きで書式設定された販売注文の状態フィールドのビュー")</span><span class="sxs-lookup"><span data-stu-id="3fed0-116">![A view of promoted and conditionally formatted Sales Order Status field](media/document-status.png "A view of promoted and conditionally formatted Sales Order Status field")</span></span>

### <a name="reverse-register"></a><span data-ttu-id="3fed0-117">登録の取り消し</span><span class="sxs-lookup"><span data-stu-id="3fed0-117">Reverse Register</span></span>

<span data-ttu-id="3fed0-118">**G/L 登録**ページの**登録の取り消し**アクションはコンテキスト対応になったため、選択した G/L 登録を取り消せる場合にのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="3fed0-118">The **Reverse Register** action on the **G/L Register** page is now context-aware, so that it is available only when you can reverse the selected G/L register.</span></span> <span data-ttu-id="3fed0-119">反対に、[登録の取り消し] アクションを使用して指定された G/L 登録を取り消せない場合は使用できません。</span><span class="sxs-lookup"><span data-stu-id="3fed0-119">Conversely, it is not available when you cannot use the Reverse Register action to reverse the specified G/L register.</span></span> 

<span data-ttu-id="3fed0-120">![G/L 登録ページで無効になっている登録の取り消しアクションのビュー](media/reverse-register.png "G/L 登録ページで無効になっている登録の取り消しアクションのビュー")</span><span class="sxs-lookup"><span data-stu-id="3fed0-120">![A view of disabled Reverse Register action on G/L Registers page](media/reverse-register.png "A view of disabled Reverse Register action on G/L Registers page")</span></span>

### <a name="document-line-actions"></a><span data-ttu-id="3fed0-121">ドキュメント明細行アクション</span><span class="sxs-lookup"><span data-stu-id="3fed0-121">Document line actions</span></span>

<span data-ttu-id="3fed0-122">販売注文や発注書などのドキュメントに対する品目の在庫状態、品目の追跡などの明細行アクションは、コンテキスト対応になりました。</span><span class="sxs-lookup"><span data-stu-id="3fed0-122">Line actions such as Item Availability, Item Tracking, and so on, on documents such as sales and purchase orders, are now context-aware.</span></span> <span data-ttu-id="3fed0-123">たとえば、選択した発注書明細行のタイプが**リソース**、**品目料金の割り当て**、または**繰り延べスケジュール**の場合、アクションは、**品目**、**G/L 勘定**、および**発注書**明細タイプにのみ適用されるため使用できません。</span><span class="sxs-lookup"><span data-stu-id="3fed0-123">For example, if a selected purchase order line is of type **Resource**, **Item Charge Assignment**, or **Deferral Schedule**, actions are not available because they only apply to the **Item**, **G/L Account**, and **Purchase Order** line types.</span></span> 

<span data-ttu-id="3fed0-124">![コンテキストにより無効になっている発注書明細行アクションのビュー](media/document-line-actions.png "コンテキストにより無効になっている発注書明細行アクションのビュー")</span><span class="sxs-lookup"><span data-stu-id="3fed0-124">![A view of contextually disabled purchase order line actions](media/document-line-actions.png "A view of contextually disabled purchase order line actions")</span></span>

### <a name="mandatory-fields-on-journals"></a><span data-ttu-id="3fed0-125">仕訳帳の必須フィールド</span><span class="sxs-lookup"><span data-stu-id="3fed0-125">Mandatory fields on journals</span></span>

<span data-ttu-id="3fed0-126">一般仕訳帳などの仕訳帳の**ドキュメント番号**および**転記日付**フィールドには、仕訳帳を転記する前に特定のフィールドに入力する必要があることを示す赤いアスタリスク (\*) が表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3fed0-126">The **Document Number** and **Posting Date** fields in journals, such as the general journal, now show a red asterisk (\*) to indicate that you must fill in certain fields before you can post the journal.</span></span> <span data-ttu-id="3fed0-127">仕訳帳により多くの、またはより少ない列が表示されている場合にも同じことが適用されます。</span><span class="sxs-lookup"><span data-stu-id="3fed0-127">The same applies when journals are shown with more, or fewer, columns.</span></span> 

<span data-ttu-id="3fed0-128">![必須のアスタリスクが表示されている一般仕訳帳明細行のドキュメント番号の表示](media/mandatory-field-journal.png "必須のアスタリスクが表示されている一般仕訳帳明細行のドキュメント番号の表示")</span><span class="sxs-lookup"><span data-stu-id="3fed0-128">![Shows Document Number on general journal line with mandatory asterisk](media/mandatory-field-journal.png "Shows Document Number on general journal line with mandatory asterisk")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="3fed0-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="3fed0-129">See also</span></span>

<!--docs start-->
<span data-ttu-id="3fed0-130">[データを入力する](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3fed0-130">[Entering Data](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (docs)</span></span>
<!--docs end-->

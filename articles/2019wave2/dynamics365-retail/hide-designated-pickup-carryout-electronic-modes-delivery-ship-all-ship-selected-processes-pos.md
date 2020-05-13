---
title: 指定された集荷、実行、電子的配送モードが POS のすべて出荷プロセスと選択された出荷プロセスに表示されないようにする
description: Retail のパラメーター ページに新しいパラメーターが追加され、小売業者はそれを使用して、構成された集荷、実行、電子的配送モードがチャネル、品目、配送先住所の組み合わせに対して有効な場合でも [すべて出荷] および [選択された出荷] ダイアログ内のオプションとして表示されないように設定できます。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/09/2020
ms.assetid: 4f19b331-24d4-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 1d2d6fc13d9fe8a7c62ba203ae1f971458b59e5f
ms.sourcegitcommit: 8756c08fc492e62cc366fa85ee3e510af3d16f70
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/18/2020
ms.locfileid: "3139559"
---
# <a name="hide-designated-pickup-carryout-and-electronic-modes-of-delivery-from-ship-all-and-ship-selected-processes-in-pos"></a><span data-ttu-id="6c337-103">指定された集荷、実行、電子的配送モードが POS のすべて出荷プロセスと選択された出荷プロセスに表示されないようにする</span><span class="sxs-lookup"><span data-stu-id="6c337-103">Hide designated pickup, carryout, and electronic modes of delivery from ship all and ship selected processes in POS</span></span>


| <span data-ttu-id="6c337-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6c337-104">Enabled for</span></span>    |  <span data-ttu-id="6c337-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6c337-105">Public preview</span></span> | <span data-ttu-id="6c337-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6c337-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6c337-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="6c337-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6c337-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6c337-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6c337-109">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="6c337-109">Oct 21, 2019</span></span>| <span data-ttu-id="6c337-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6c337-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6c337-111">2020 年 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="6c337-111">Jan 3, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="6c337-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6c337-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6c337-113">この機能は、販売時点管理 (POS) の出荷設定画面に "非配送業者" 配送モードを表示したくない小売業者向けに柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="6c337-113">This feature will give flexibility to retailers who might not want to see "non-carrier" delivery modes appearing in the shipment configuration screens in the point of sale (POS).</span></span> <span data-ttu-id="6c337-114">現在は、指定された "集荷"、"実行"、または "電子的" 配送モードが品目、チャネル、配送先住所の組み合わせに対して有効な場合、それらの配送モードが "すべて出荷" または "選択された出荷" オペレーションで選択オプションとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="6c337-114">Currently, if a designated "pickup," "carryout," or "electronic" mode of delivery is acceptable for the item, channel, and delivery address combination, those delivery modes will appear as a selection option during the "ship all" or "ship selected" operation.</span></span> <span data-ttu-id="6c337-115">これらのタイプをこの出荷作成フローに表示させたくない小売業者の場合、**小売パラメーター**で**出荷については配送オプションのみを表示**と呼ばれる新しいパラメーターが使用できます。</span><span class="sxs-lookup"><span data-stu-id="6c337-115">For retailers who prefer not to have these types displayed in this shipment creation flow, a new parameter will be available in **Retail parameters** called **Show only carrier options for ship orders**.</span></span> <span data-ttu-id="6c337-116">このパラメーターを有効にすると、配送業者以外のモードが選択画面で非表示になります。</span><span class="sxs-lookup"><span data-stu-id="6c337-116">Enabling this parameter will hide these non-carrier modes of delivery from the selection display.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6c337-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="6c337-117">See also</span></span>

<span data-ttu-id="6c337-118">[配送業者以外のモードを非表示にする](https://docs.microsoft.com/dynamics365/retail/hide-non-carrier-modes) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6c337-118">[Hide Non-Carrier Modes](https://docs.microsoft.com/dynamics365/retail/hide-non-carrier-modes) (docs)</span></span>

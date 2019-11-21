---
title: 指定された集荷、実行、電子的配送モードが POS のすべて出荷プロセスと選択された出荷プロセスに表示されないようにする
description: Retail のパラメーター ページに新しいパラメーターが追加され、小売業者はそれを使用して、構成された集荷、実行、電子的配送モードがチャネル、品目、配送先住所の組み合わせに対して有効な場合でも [すべて出荷] および [選択された出荷] ダイアログ内のオプションとして表示されないように設定できます。
author: hhainesms
ms.reviewer: josaw
ms.date: 10/10/2019
ms.assetid: 4f19b331-24d4-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 60eed17a8cd9489457877bac24fae30df8629f6d
ms.sourcegitcommit: c843aacec8dddcb0d6693c79fbace7f19bf09565
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/11/2019
ms.locfileid: "2574504"
---
# <a name="hide-designated-pickup-carryout-and-electronic-modes-of-delivery-from-ship-all-and-ship-selected-processes-in-pos"></a>指定された集荷、実行、電子的配送モードが POS のすべて出荷プロセスと選択された出荷プロセスに表示されないようにする
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 10 月| 2020 年 1 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は、販売時点管理 (POS) の出荷設定画面に "非配送業者" 配送モードを表示したくない小売業者向けに柔軟性を提供します。 現在は、指定された "集荷"、"実行"、または "電子的" 配送モードが品目、チャネル、配送先住所の組み合わせに対して有効な場合、それらの配送モードが "すべて出荷" または "選択された出荷" オペレーションで選択オプションとして表示されます。 これらのタイプをこの出荷作成フローに表示させたくない小売業者の場合、**小売パラメーター**で**出荷については配送オプションのみを表示**と呼ばれる新しいパラメーターが使用できます。 このパラメーターを有効にすると、配送以外のモードが選択画面で非表示になります。
<!--feature detail end -->










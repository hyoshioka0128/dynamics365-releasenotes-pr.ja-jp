---
title: 以前は日付仮想テーブルに基づいていた ListPlus ページの拡張
description: 以前は**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間** などの ListPlus ページを拡張できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/06/2020
ms.assetid: de25edaf-9e4d-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 981e683a8ad65420c4819525e2daaeb95a8e1bc5
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255081"
---
# <a name="extend-listplus-pages-previously-based-on-the-date-virtual-table"></a>以前は日付仮想テーブルに基づいていた ListPlus ページの拡張


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
**日付**仮想テーブルに基づくサブページを含む ListPlus ページの拡張は、顧客が**品目**や**リソースの空き時間**などのページに関して特定の要件がある場合や、追加の測定値を分析する必要がある場合に関係します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
基になっているバッファー テーブルを拡張し、OnAfterCalcLine イベントにサブスクライブすることで、**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間**などの ListPlus ページを拡張できます。 このようなベース アプリケーションのすべてのページで、この拡張性モデルがサポートされます。
<!--feature detail end -->










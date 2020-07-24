---
title: 以前は日付仮想テーブルに基づいていた ListPlus ページの拡張
description: 以前は**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間** などの ListPlus ページを拡張できるようになりました。
author: relnotes
ms.reviewer: solsen
ms.date: 05/11/2020
ms.assetid: de25edaf-9e4d-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 396cacff1c165070c9defa46ef6bf87d2ccc5bbe
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381422"
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










## <a name="see-also"></a>関連項目

<!--docs start-->
[以前は日付仮想テーブルに基づいていたページの拡張](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-extend-pages-based-on-date-virtual-table) (ドキュメント)
<!--docs end-->

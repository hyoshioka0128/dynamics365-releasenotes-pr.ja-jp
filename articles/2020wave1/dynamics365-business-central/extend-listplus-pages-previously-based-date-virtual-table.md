---
title: 以前は日付仮想テーブルに基づいていた ListPlus ページの拡張
description: 以前は**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間** などの ListPlus ページを拡張できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 02/14/2020
ms.assetid: de25edaf-9e4d-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 53d9b0514fd8c5fd1e70e865cccc324a7e41d418
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080686"
---
# <a name="extend-listplus-pages-previously-based-on-the-date-virtual-table"></a>以前は日付仮想テーブルに基づいていた ListPlus ページの拡張
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
**日付**仮想テーブルに基づくサブページを含む ListPlus ページの拡張は、顧客が**品目**や**リソースの空き時間**などのページに関して特定の要件がある場合や、追加の測定値を分析する必要がある場合に関係します。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
基になっているバッファー テーブルを拡張し、OnAfterCalcLine イベントにサブスクライブすることで、**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間**などの ListPlus ページを拡張できます。 このようなベース アプリケーションのすべてのページで、この拡張性モデルがサポートされます。
<!--feature detail end -->










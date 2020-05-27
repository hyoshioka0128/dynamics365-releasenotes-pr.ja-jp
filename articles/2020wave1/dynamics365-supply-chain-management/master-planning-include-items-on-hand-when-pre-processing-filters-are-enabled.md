---
title: 前処理フィルターが有効になっている場合に、手持在庫のある品目がマスター プランに含まれる
description: 前処理フィルターが有効になっている場合に、手持在庫のある品目がマスター プランに含まれる
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/14/2020
ms.assetid: 39eb3f7d-9563-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: a7d8e6bc38e6494a435f7cb8227001cc909383da
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273887"
---
# <a name="master-planning-includes-items-with-on-hand-inventory-when-pre-processing-filters-are-enabled"></a>前処理フィルターが有効になっている場合に、手持在庫のある品目がマスター プランに含まれる


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 3 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を使用すると、**マスター プランのパラメーター** ページで**前処理: 直納品目で自動的にフィルター処理する**設定が有効になっている場合に、実行されたマスター プランに手持在庫のある品目が常に含まれるようになります。 

この機能を使用するには、[機能管理](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json)で_前処理フィルターが有効になっている場合に手持在庫のある品目を含める_機能を有効にする必要があります。

> [!IMPORTANT]
> 製造計画プロセスで*展開*または*正味変更の更新*機能を使用している場合は、この機能を有効にする必要があります。 そうしないと、**正味必要量**フォームに直納以外の品目の誤った手持在庫のデータが表示され、展開時に誤った計画オーダーが生成される可能性があります。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[直納品目で自動的にフィルター処理する](https://docs.microsoft.com/dynamics365/supply-chain/master-planning/master-planning-performance#automatically-filter-by-items-with-direct-demand) (ドキュメント)
<!--docs end-->

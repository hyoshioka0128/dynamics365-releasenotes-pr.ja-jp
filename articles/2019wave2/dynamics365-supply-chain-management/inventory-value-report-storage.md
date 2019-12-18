---
title: 在庫金額レポート ストレージ
description: 在庫金額レポート ストレージを使用すると、在庫金額レポートを実行して、Dynamics 365 Supply Chain Management のフォーム内で出力にアクセスできるようにしたり、外部アプリケーションで使用するためにデータ エンティティを通じて出力をエクスポートしたりできます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: eda2b127-79ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 14961e65cd9dfc0c2cd4628429ac4669d4f535cf
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889851"
---
# <a name="inventory-value-report-storage"></a>在庫金額レポート ストレージ


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 6 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 8 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この新しい在庫金額レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。 たとえば、50.000 の品目と 300 の店舗があるシナリオで品目、サイト、倉庫別の在庫期末残高を要求すると、データの確認が困難な非常に長いレポートが生成されます。 結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりできると、在庫金額レポートの結果をすばやく簡単に確認できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しい在庫金額レポート ストレージ機能が導入されました。 新しい在庫金額レポートの実行を開始するときは、特定の実行に対して一意の名前を指定する必要があり、レポート生成の結果はその名前で保存されます。 これにより、同じ期間に対して複数の在庫金額レポートを実行する必要がなくなります。 

レポート実行の出力には、在庫金額レポート ストレージの詳細フォーム内でアクセスできます。 このフォームでは、構成された在庫金額レポートのレイアウトに応じて列が動的に調整され、残高が集計されます。 現在の在庫金額レポートの構成をすべて使用できます。 

新しい在庫金額レポート データ エンティティも導入されました。 これにより、実行された特定の名前付き在庫金額レポートの出力を、データ管理でサポートされている任意の形式でエクスポートできます。
<!--feature detail end -->









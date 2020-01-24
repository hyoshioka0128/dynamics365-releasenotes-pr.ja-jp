---
title: 在庫エイジング レポート ストレージ
description: 在庫エイジング レポート ストレージを使用すると、在庫エイジング レポートを実行し、出力を Dynamics 365 Supply Chain Management のフォームのシンプルなリストとしてアクセスできるようにするか、結果をグラフで視覚化できます。 また、外部アプリケーションで使用するために、データ エンティティを介して在庫エイジング レポートからの出力をエクスポートすることもできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/07/2020
ms.assetid: a816499f-67e0-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 84c3de92cb3d5e7cacf764f11f4c0ffb5273777d
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2948343"
---
# <a name="inventory-aging-report-storage"></a>在庫エイジング レポート ストレージ


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 21 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 3 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この新しい在庫エイジング レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。 たとえば、50,000 の品目と 300 の店舗があるシナリオで品目グループ、品目、サイト、倉庫別の在庫エイジングを要求すると、データの確認が困難な非常に長いレポートが生成されます。 

新しいグラフの視覚化により、拡張された在庫エイジングの概要がより短時間で提供されます。 結果を並べ替えてフィルター処理し、結果を外部システムにエクスポートする機能により、在庫エイジング レポートの結果を短時間で簡単に確認できるようになります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しい在庫エイジング レポート ストレージ機能が導入されました。 新しい在庫エイジング レポートの実行を開始するときは、特定の実行に対して一意の名前を指定する必要があり、レポート生成の結果はその名前で保存されます。 実行した日時も記録されます。 この新しい機能により、同じ期間の在庫エイジング レポートを複数回再生成する必要がなくなります。

レポート実行の出力は、**在庫エイジング レポート ストレージの詳細**ページの単純なリストとして、またはフィルター処理とドリルスルーの両方をサポートする新しい在庫エイジング グラフ内の集計ページからアクセスできます。 このページでは、在庫エイジング レポートの構成に応じて列が動的に調整され、残高が集計されます。 現在の在庫エイジング レポートの構成をすべて使用できます。

新しい在庫エイジング レポート データ エンティティも導入されました。 これにより、保存した在庫エイジング レポートの出力を、データ管理でサポートされている任意の形式でエクスポートできます。
<!--feature detail end -->

![在庫エイジング グラフ](media/chart-final.png "在庫エイジング グラフ")
<!-- Picture 1 -->









## <a name="see-also"></a>関連項目

[Dynamics 365 Supply Chain Management 10.0.6 (2019 年 11 月) の新機能および変更された機能](https://docs.microsoft.com/dynamics365/supply-chain/get-started/whats-new-scm-10-0-6) (ドキュメント)

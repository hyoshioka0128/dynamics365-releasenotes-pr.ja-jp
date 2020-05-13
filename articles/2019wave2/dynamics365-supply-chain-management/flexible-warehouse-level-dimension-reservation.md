---
title: 柔軟な倉庫レベルの分析コード引当
description: この機能強化により、在庫引当ポリシーが柔軟になり、バッチ管理される製品を販売し WMS 対応オペレーションとしてロジスティクスを実行する企業は、製品に関連付けられた在庫引当階層で禁じられている ("batch-below" と呼ばれるタイプになっている) 場合でも、顧客からの特定のバッチの要求を販売注文に登録できます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: a3cd03d8-93cd-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: c92beee735b8a875e5e613edaf1861628ab1ce48
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320151"
---
# <a name="flexible-warehouse-level-dimension-reservation"></a>柔軟な倉庫レベルの分析コード引当


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 27 日| 近日発表|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
顧客の要件に基づいてオーバーライドを設定できるようにしつつ、定型業務でのバッチ管理製品のピッキングに対する最適化に焦点を当てたアプローチを維持します。 製品の既定の引当ポリシーで、倉庫のピッキング工程が開始されるまでピッキングするバッチとその場所の決定を延期すると規定されている場合 (たとえば、在庫ストック戦略に対する最適化に焦点を当てたアプローチ) でも、その製品のバッチ番号を顧客の注文に対して事前に引き当てることができます。 この機能により、バッチ番号の選択の大部分が倉庫で行われる製品に関して、在庫と倉庫の効率を妥協する必要がなくなります。

販売注文を受ける作業者は、顧客の要望に応えて特定のバッチ番号を再指定できます。 販売注文担当者は受注時にバッチ番号の記録と引当を行うことができます。そのバッチ番号が倉庫オペレーションで変更されたり別の需要に充てられたりすることはありません。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
柔軟な倉庫レベルの分析コード引当には、次の機能が含まれます。

- 注文の製品数量に対して、それらの分析コードが製品の引当階層内で倉庫の場所の下にある場合に、特定の追跡用分析コードまたは倉庫保管分析コード値を引き当てることができます。(2019 年リリース ウェーブ 2 では、販売注文に対するバッチ番号の引当のみがサポートされます)。

- 販売注文に対して引き当てられたバッチ番号は既存の WMS プロセスによって処理され、指定されたバッチがピッキングされて顧客に出荷されます。

- 手持数量に対する販売注文からのバッチ引当のサポート。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[柔軟な倉庫レベル分析コードの引当ポリシー](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/flexible-warehouse-level-dimension-reservation) (ドキュメント)
<!--docs end-->

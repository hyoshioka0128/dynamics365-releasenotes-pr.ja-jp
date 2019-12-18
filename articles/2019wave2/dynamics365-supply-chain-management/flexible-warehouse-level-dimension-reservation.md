---
title: 柔軟な倉庫レベルの分析コード引当
description: この機能強化により、在庫引当ポリシーが柔軟になり、バッチ管理される製品を販売し WMS 対応オペレーションとしてロジスティクスを実行する企業は、製品に関連付けられた在庫引当階層で禁じられている ("batch-below" と呼ばれるタイプになっている) 場合でも、顧客からの特定のバッチの要求を販売注文に登録できます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/28/2019
ms.assetid: a3cd03d8-93cd-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: omulvad
dynamics365pdf: true
ms.openlocfilehash: a4ff4d56bbbc23a73cb3e0c420f4e6b2fbe8c5fd
ms.sourcegitcommit: cefe454c62a0cd90d468ae3b12f5b74678345401
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/08/2019
ms.locfileid: "2778567"
---
# <a name="flexible-warehouse-level-dimension-reservation"></a>柔軟な倉庫レベルの分析コード引当
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2020 年 1 月| 近日発表|


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










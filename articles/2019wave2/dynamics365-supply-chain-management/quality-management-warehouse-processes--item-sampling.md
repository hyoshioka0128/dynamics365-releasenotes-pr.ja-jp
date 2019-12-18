---
title: 倉庫プロセスの品質管理 - 品目サンプリング
description: この機能は、モバイル デバイスを使って品質チェックの場所の間で在庫を移動する作業指示書を作成する機能を導入することによって、既存の品質指示機能を拡張します。
author: relnotes
ms.reviewer: josaw
ms.date: 12/02/2019
ms.assetid: df491424-14cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 82d592cc7626dc6665c5ecc70a75d48cf4bf42d7
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889632"
---
# <a name="quality-management-for-warehouse-processes--item-sampling"></a>倉庫プロセスの品質管理 - 品目サンプリング
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2020 年 1 月| 近日発表|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
入庫在庫を受け取ったら、品質の関連付けを使用して品質指示を作成できます。 注文は、既存の品質管理プロセスを使用して処理されます。 

この機能は、倉庫への入庫在庫のセット サンプルを品質目的で調べる必要があるときに使用されます。 ビジネス標準に従う必要のある新しい仕入先や、または過去に問題が発生して、より詳細な調査を必要とする仕入先のような場合です。 

注文の作成方法は、品質関連と品目サンプリングの設定方法の基準によって異なります。 それらは、積荷ごと、出荷ごと、注文ごとのいずれかです。 ここでは、検査するライセンス プレートの数に加えて、完全なライセンス プレートとその一部のどちらを検査するのかと、各品目 ID を個別に検査するかどうかも決定されます。

在庫を受け取ったら、品質の関連付けを使用して品質指示を作成できます。 この方法で品質指示が作成された場合、品質サンプリング作業トランザクション タイプの品質を使用して、オーダーの在庫を移動する作業が作成されます。 必要な在庫を入庫ドック (または開始場所) から品質場所に移動する作業が作成されます。 在庫は、品質管理によって品質指示が処理されて完了するまでその場所に残ります。 品質指示が完了すると、新しい作業指示書を作成して在庫を保管場所に移動できます。
<!--feature detail end -->










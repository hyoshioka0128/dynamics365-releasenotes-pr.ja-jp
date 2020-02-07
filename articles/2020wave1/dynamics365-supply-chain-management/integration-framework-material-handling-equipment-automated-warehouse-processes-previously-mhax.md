---
title: 自動倉庫プロセス用の材料取り扱い機器の統合フレームワーク (以前の MHAX)
description: 自動倉庫用の材料取り扱い機器の統合フレームワークにより、完全または部分的に自動化された倉庫を持つ顧客企業は、Dynamics 365 と統合して倉庫モジュールで生成された作業を処理できます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/13/2019
ms.assetid: 277b7ab1-d1e3-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 43063851936029c4074b8951b3f31e6530400b83
ms.sourcegitcommit: 9ede92eba84a02579fc8fc63e6a9673b034ce30c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2020
ms.locfileid: "2976542"
---
# <a name="integration-framework-for-material-handling-equipment-for-automated-warehouse-processes-previously-mhax"></a>自動倉庫プロセス用の材料取り扱い機器の統合フレームワーク (以前の MHAX)
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
材料取り扱い機器 (MHE) の統合フレームワークは、WMS によって作成された倉庫作業と、基本的な倉庫処理操作を実行できる材料取り扱い機器との間のインターフェイスとして機能します。 この機能は柔軟で、機器が Web サービスを介して統合できる限り、すべてのタイプの機器と統合できます。

コンベア、縦型カルーセル、ハイベイ - ASRS (自動化ストレージおよび取り出しシステム)、梱包装置など、さまざまな MHE に対して行われた資本投資に統合できる WMS システムを顧客が持つことが不可欠です。 多くの顧客は、単純な材料取り扱い機器との統合を整理する追加のプロバイダーに投資することを避けたいと考えます。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ユーザーは、作業の作成、完了、キャンセルなどの倉庫イベントで、アウトバウンド サブスクリプションを設定できます。 これらのイベントは、関連付けられたデータとともに、キューで追跡され、外部の機器から Web サービス経由でアクセスできます。 各トランザクションに関連付けられたデータは、完全にユーザー構成可能です。 各キュー レコードを追加するために、最大 10 個のフィールドを指定できます。 各レコードのステータスは、ブロック済みから送信済みまで追跡されます。

同様に、インバウンド キューが存在し、外部機器は Web サービス経由でこれを設定できます。 インバウンド キュー レコードが消費されると、作業の完了やライセンス プレートの受取などの倉庫アクションがトリガーされます。  作業は一度に 1 つずつ実行するか、またはピック/プットのペアを単一のトランザクションで実行することができます。 未処理ピッキングと場所の上書きもサポートされています。

この新しい機能は、既存顧客の一部向けにプライベート プレビューでリリースされたライセンス ソリューションである MHAX と比較して、パフォーマンスとスケール、新しいデータ モデル、その他の必要な設計強化に対応するリファクタリングにも対応します。

<!--feature detail end -->










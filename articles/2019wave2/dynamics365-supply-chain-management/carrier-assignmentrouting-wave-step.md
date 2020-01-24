---
title: 配送業者割り当て/ルート指定ウェーブ ステップ
description: AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレートショップを自動的に行い、最も安いレートを適用します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/13/2019
ms.assetid: b862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: aba11f4b49145cd72d74c49575f12fe25ebb1b09
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2909909"
---
# <a name="carrier-assignmentrouting-wave-step"></a>配送業者割り当て/ルート指定ウェーブ ステップ
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2020 年 2 月| 近日発表|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
一部の流通業者は、注文が倉庫で処理されるときに輸送業者を割り当てる必要がありますが、このプロセスを手動で行うことを望んでいません。 ウェーブ プロセス中に注文を自動的に評価できるようにする新しいウェーブ ステップが導入されました。 AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレート ショップを自動的に行い、最も安いレートを適用します。 注文が評価されると、残りの倉庫処理では割り当てられた配送業者/サービスを考慮して、注文を正しいドック ドアに送ったり、ラベルを印刷したりすることができます。
<!--feature detail end -->










---
title: 配送業者割り当て/ルート指定ウェーブ ステップ
description: AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレートショップを自動的に行い、最も安いレートを適用します。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: b862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 76af34d36a32fcfd37e2dad2356f38b3efd68d2d
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660561"
---
# <a name="carrier-assignmentrouting-wave-step"></a>配送業者割り当て/ルート指定ウェーブ ステップ
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2020 年 1 月| 2020 年 3 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
一部の流通業者は、注文が倉庫で処理されるときに輸送業者を割り当てる必要がありますが、このプロセスを手動で行うことを望んでいません。 ウェーブ プロセス中に注文を自動的に評価できるようにする新しいウェーブ ステップが導入されました。 AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレート ショップを自動的に行い、最も安いレートを適用します。 注文が評価されると、残りの倉庫処理では割り当てられた配送業者/サービスを考慮して、注文を正しいドック ドアに送ったり、ラベルを印刷したりすることができます。
<!--feature detail end -->










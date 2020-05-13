---
title: バッチ ジョブの優先順位ベースのスケジューリング
description: バッチ ジョブの優先順位ベースのスケジューリング
author: relnotes
ms.reviewer: kfend
ms.date: 02/03/2020
ms.assetid: f462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: peakerbl
dynamics365pdf: true
ms.openlocfilehash: 44afe0212e5c9e700956e4dd8e8302a53a66e352
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058554"
---
# <a name="priority-based-scheduling-for-batch-jobs"></a>バッチ ジョブの優先順位ベースのスケジューリング


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 31 日| -|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
優先順位ベースのスケジューリングは、バッチ グループをインフラストラクチャから切り離します。 サーバーにバッチ ジョブを割り当てる必要がなくなりました。 代わりに、ビジネス要件に基づく相対的なスケジューリング優先順位を使用して、使用可能なバッチ サーバー間でタスクが実行される順序が決定されます。 この機能によって、バッチ サーバーを使用した自動的な最適化が有効になります。 スケジューリングの優先順位の分類は、相対的な優先順位を宣言し、ジョブおよびビジネス プロセスの処理順序を決定するために使用されます。

この機能は環境で徐々に有効化されています。  関心をお持ちのお客様で、**機能管理**にこれが表示されない場合は、バッチ ジョブの優先順位ベースのスケジューリングへのアクセスを要請するために、Microsoft にご連絡いただくことができます。
<!--feature detail end -->


> [!NOTE]
> この機能は、Platform update 31 から限定プレビューで利用できます。







## <a name="see-also"></a>関連項目

[優先順位に基づくバッチ スケジューリング](https://aka.ms/prioritybasedbatchscheduling) (ドキュメント)

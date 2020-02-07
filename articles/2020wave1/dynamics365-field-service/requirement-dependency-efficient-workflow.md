---
title: 効率的なワークフローのための要件の依存関係
description: 要件やタスク間に依存関係を作成して、一貫した効率的なワークフローを推進するために必要な順序で実行されるようにします。
author: relnotes
ms.reviewer: krbjoran
ms.date: 01/15/2020
ms.assetid: f9f164ca-0c1e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: ragguru
dynamics365pdf: true
ms.openlocfilehash: 044ed7bd84102682034049b1d58d9879d3423195
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986616"
---
# <a name="requirement-dependency-for-efficient-workflow"></a>効率的なワークフローのための要件の依存関係
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|エンド ユーザー、自動的|-|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
正しい順序で作業が実施されるように、作業を順序付けることが必要になる場合があります。 たとえば、電気的な配線を行う前に物理的な設置を行う必要があります。 企業は、依存タスクが順番に実行されるようにすることで、運用ワークフローを最適化できます。 この機能により、組織は特定の順序で作業を完了することができます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を使用すると、技術者が最適なワークフローに従い、最も効率的なサービス運用を実現するように、要件の依存関係を構成できます。 要件の依存関係により、顧客は、先行する要件と後続する要件の依存関係に基づいて、特定の順序で要件をスケジュールできます。 たとえば、技術者は倉庫から特殊な部品をピックアップし、顧客のサイトで作業を行うことが必要になる場合があります。 相互に依存する一連のタスクが必要な重要なジョブを、先行するタスクと後続するタスクとしてリンクし、リソース スケジューリング オプティマイザーを介して予約できるようになりました。 
 
2020 年リリース ウェーブ 1 では、この機能は、スケジュール ボードでこうした予約を表示できるリソース スケジュール最適化 (RSO) によってのみサポートされます。 また、これらの依存関係は、単一リソースかつ単一日のシナリオでのみ機能します。
<!--feature detail end -->


> [!NOTE]
> この機能は、統一インターフェイスでのみ使用できます。







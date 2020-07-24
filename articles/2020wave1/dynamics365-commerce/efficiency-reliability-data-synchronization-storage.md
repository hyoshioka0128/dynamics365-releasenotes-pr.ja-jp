---
title: データの同期および保存の効率と信頼性
description: この機能は、CDX バックグラウンド最適化を提供し、パフォーマンスと信頼性を向上させるための機能を複数の方法で強化します。
author: relnotes
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: 9b3daeb0-73fb-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 735da0fc9b1b98e1d7bf7a2cdc65beea538862d4
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3416361"
---
# <a name="efficiency-and-reliability-of-data-synchronization-and-storage"></a>データの同期および保存の効率と信頼性
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 18 日| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Channel Data Exchange (CDX) コンポーネントは、Commerce チャネル データベース (同じ場所に配置されたクラウド チャネル、Commerce Cloud Scale Unit、Commerce Store Scale Unit、およびオフライン サポート付きの最新の販売時点管理 (MPOS)) 間でデータを同期します。

データの利用不可、他のコンポーネントの速度低下、またはデータベース データとログ サイズへの影響に関する問題を解決するいくつかのパフォーマンスと信頼性の更新プログラムが実装されました。 データ同期フレームワーク (CDX) の可用性、信頼性、効率の最大化には常に重点が置かれています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能には、次の領域でのいくつかの独立した改善が含まれます。

- コマース本部でのデータ パッケージ生成の改善。
- チャネル データベースに適用する際のデータ パッケージの改善。
- 必要な完全同期の数の削減と、避けられない場合はパフォーマンスへの影響の最小化。
- チャネル レベルでのマスター データ削除、DB 統計の更新、同期中のインデックス作成など、複数のデータ最適化。
<!--feature detail end -->










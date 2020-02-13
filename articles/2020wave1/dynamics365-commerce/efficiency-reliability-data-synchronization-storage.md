---
title: データの同期および保存の効率と信頼性
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/11/2020
ms.assetid: 9b3daeb0-73fb-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: b4ed0b81d824697a0ea19c58ec8fb98fd93ce5c4
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986643"
---
# <a name="efficiency-and-reliability-of-data-synchronization-and-storage"></a>データの同期および保存の効率と信頼性
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|2020 年 5 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Channel Data Exchange (CDX) コンポーネントは、Commerce チャネル データベース (同じ場所に配置されたクラウド チャネル、Commerce Cloud Scale Unit、Commerce Store Scale Unit、およびオフライン サポート付きの最新の販売時点管理 (POS)) 間でデータを同期します。

データの利用不可、他のコンポーネントの速度低下、またはデータベース データとログ サイズへの影響に関する問題を解決するいくつかのパフォーマンスと信頼性の更新プログラムが実装されました。 データ同期フレームワーク (CDX) の可用性、信頼性、効率の最大化には常に重点が置かれています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能には、次の領域でのいくつかの独立した改善が含まれます。

- 本社でのデータ パッケージ生成の改善。
- チャネル データベースに適用する際のデータ パッケージの改善。
- 必要な完全同期の数の削減と、避けられない場合はパフォーマンスへの影響の最小化。
- チャネル レベルでのマスター データ削除、DB 統計の更新、同期中のインデックス作成など、複数のデータ最適化。
<!--feature detail end -->









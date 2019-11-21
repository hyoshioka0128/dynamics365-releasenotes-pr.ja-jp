---
title: プラットフォーム
description: ''
author: relnotes
ms.reviewer: ''
ms.date: 10/23/2019
ms.assetid: bc096b69-725d-e911-a973-000d3a1c79c5
ms.topic: structure
ms.service: business-applications
ms.author: robadawy
dynamics365pdf: true
ms.openlocfilehash: 876b5249ecf02b5e4c37445580d9ade3df65bff6
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668062"
---
# <a name="platform"></a>プラットフォーム

[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

<!--structure start-->
## <a name="user-productivity-and-experiences"></a>ユーザーの生産性とエクスペリエンス
改善されたユーザー エクスペリエンスと既存機能の拡張への取り組みは、2019 年リリース ウェーブ 2 の焦点となる分野です。 保存されたビューは一般提供になり、ワークスペースおよびダイアログに対する保存されたビューのサポートおよび変更されたビューの改善された管理など、この機能に対するいくつかの改良が毎月の更新の一部として行われます。 新しいグリッド コントロール (2019 年 7 月現在のプレビュー) は、表形式のグリッドでの数値列の合計表示機能、1 つ以上の列の値に基づくデータ グループ化機能、ビュー外にスクロールしないようにする固定機能などの新しい機能により、向上したユーザー エクスペリエンスで一般提供されます。

**列挙**フィールドと**日時**フィールドをフィルター処理するためのより簡単で便利な方法など、フィルター処理の改善が提供され、ほとんどのユーザーおよびビジネス シナリオのエクスペリエンスが向上します。 ユーザーが最適化されたエクスペリエンスを構築できるようにする個人用設定機能が作成され、モバイル エクスペリエンスの向上への取り組みにより、モバイル デバイスでのアプリケーションの使い勝手が大幅に向上します。

2019 年リリース ウェーブ 2 では、バッチ ジョブとバッチ キューの管理が大幅に改善され、管理者はビジネス プロセスによってバッチ ジョブに優先順位を付けることができます。 さらに、ドキュメントのレポート作成、ルーティング、および印刷は、より柔軟に構成できるようになり、エンタープライズ シナリオまで拡張できます。

## <a name="developer-tools"></a>開発者ツール
実装を評価するための必須の新しいフェーズが、パートナーとシステム インテグレーターのライフサイクルに導入されます。 パートナーは、サンドボックスおよび運用環境における静的分析と実行時分析の両方に基づいたメトリックを、Lifecycle Services 内から使用できるようになります。 これらの品質ゲートにより、運用環境に悪影響を及ぼす可能性があるカスタム パッケージの展開をブロックできます。 これらのメトリックは、パートナーの実装間で集約され、パートナー ポータルで利用可能になります。

多くの大規模な顧客は Lifecycle Services 内に複数のプロジェクトを持っており、プロジェクト間で環境を管理、更新、および監視したいと考えています。 パートナーと ISV にも、顧客全体にわたる集約されたビューが必要です。 Lifecycle Services に新しいクロス プロジェクト ワークスペースが導入され、これらのプロジェクト全体で更新と機能を管理し、正常性を監視します。 これは、集中型 Microsoft Azure ISV ポータルとも統合されます。 開発者ツールは、スタンドアロンのインストール可能コンポーネントとして提供される予定です。

## <a name="microsoft-power-platform-integration"></a>Microsoft Power Platform 統合
Common Data Service には、すぐに使用可能な追加エンティティ マッピングが含まれるようになります。 このリリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。 これらのエンティティにより、Microsoft Power Platform を通じてより深い拡張性シナリオが可能になります。 Finance and Operations アプリは、いくつかのビジネス プロセス分野 (製造、倉庫および輸送、銀行および現金管理など) のビジネス イベントと Microsoft Power Automate をトリガーおよび監視する機能が追加され、Finance and Operations アプリでのワークフローの主な推進力になっています。


お客様が Dynamics 365 の Finance and Operations モデル駆動型アプリ (Dynamics 365 Sales、Dynamics 365 Customer Service、Dynamics 365 Field Service、Dynamics 365 Marketing、Dynamics 365 Project Service Automation) と Common Data Service の間で統合シナリオを拡張およびトラブルシューティングする必要がある Common Data Service 統合シナリオに対しては、Microsoft Power Platform 管理センターで単一の管理者エクスペリエンスを利用できます。 サポート案件を一元的にログに記録することができ、これにより迅速な解決が可能になります。 トラブルシューティングを支援するために、環境と診断機能も Microsoft Power Platform 管理センターで利用できるようになります。

## <a name="geo-expansion-and-availability-zones-in-azure"></a>Azure での地域拡張および Availability Zones
Finance and Operations アプリは、実行可能なビジネス チャンスがある特定の場所で、Microsoft Azure が利用可能になってから 6 か月以内に、利用できるように拡張されます。 Finance and Operations アプリ用のデータ常駐型クラウドにより、すべての顧客データ、コード、メタデータ、および診断が指定された地域内に確実に残るようになります。 

Availability Zones (独立した電力、冷却、およびネットワークを備えた 1 つ以上のデータセンターで構成される Azure リージョン内の物理的に独立した場所) は、Finance and Operations アプリ全体でサポートされ、部分的なリージョンまたはゾーンの停止が発生した場合でもサービスを継続的に提供できます。
<!--structure end-->




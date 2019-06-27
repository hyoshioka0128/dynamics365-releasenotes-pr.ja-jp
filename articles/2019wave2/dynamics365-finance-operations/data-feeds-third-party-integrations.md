---
title: サード パーティ統合のためのデータ フィード
description: サード パーティ統合のためのデータ フィード
author: relnotes
ms.reviewer: sericks
ms.date: 05/29/2019
ms.assetid: fe62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: sunilg
dynamics365pdf: true
---
# サード パーティ統合のためのデータ フィード
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 10 月| 2020 年 3 月|






## 機能の詳細
<!--feature detail start -->
データ フィードにより、Dynamics 365 for Finance and Operations データのほぼリアルタイムの増分エクスポートが可能になります。 Finance and Operations のデータが変更され、Azure Data Lake や Azure メッセージング サービスなどの汎用コンシューマーに送信されると、増分エクスポートが発生します。 外部のビジネス アプリケーションとシステムは、Azure メッセージング サービスを使用して、顧客データ フィードや販売注文データ フィードなどの特定のデータ フィードをサブスクライブして、Finance and Operations からほぼリアルタイムでデータの更新を受け取ることができます。 データ フィードは、フル プッシュのユース ケースもサポートし、イベント駆動型アーキテクチャに基づいてメッセージベースのデータ統合を有効にします。 これにより、アプリケーション間の高スループットと待ち時間の短縮が実現されます。
<!--feature detail end -->











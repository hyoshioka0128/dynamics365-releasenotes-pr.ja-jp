---
title: サード パーティ統合のためのデータ フィード
description: サード パーティ統合のためのデータ フィード
author: ''
ms.reviewer: sericks
ms.date: 06/18/2019
ms.assetid: fe62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: sunilg
dynamics365pdf: true
ms.openlocfilehash: 19d7cf5aa3e01d6b9345e0f94a0778ecbe71aa57
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701822"
---
# <a name="data-feeds-for-third-party-integrations"></a>サード パーティ統合のためのデータ フィード
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 10 月| 2020 年 3 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
データ フィードにより、Dynamics 365 for Finance and Operations データのほぼリアルタイムの増分エクスポートが可能になります。 Finance and Operations のデータが変更され、Azure Data Lake や Azure メッセージング サービスなどの汎用コンシューマーに送信されると、増分エクスポートが発生します。 外部のビジネス アプリケーションとシステムは、Azure メッセージング サービスを使用して、顧客データ フィードや販売注文データ フィードなどの特定のデータ フィードをサブスクライブして、Finance and Operations からほぼリアルタイムでデータの更新を受け取ることができます。 データ フィードは、フル プッシュのユース ケースもサポートし、イベント駆動型アーキテクチャに基づいてメッセージベースのデータ統合を有効にします。 これにより、アプリケーション間の高スループットと待ち時間の短縮が実現されます。
<!--feature detail end -->











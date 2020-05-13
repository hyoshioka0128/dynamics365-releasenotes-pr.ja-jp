---
title: Commerce API - 非同期パターンのフレームワークとランタイムのサポート
description: Commerce API フレームワークは、Commerce が要求する拡張機能の非同期実行をサポートするように強化されました。 このフレームワークの機能強化の前は、要求は同期的にのみ実行できました。 長時間の操作 (I/O 操作、データベース クエリ、ネットワーク要求など) は、実行スレッドをブロックします。 Commerce Runtime に非同期モデルのサポートを追加すると、このような操作の非同期バージョンを使用できるようになるため、実行スレッドのブロックが解除されます。 Commerce API フレームワークでは、拡張要求が非同期で実行されるように非同期/待機モデルがサポートされるため、一部の作業を並列に実行する必要がある場合のビジネス ロジックを簡素化できます。
author: mugunthanm
ms.reviewer: rhaertle
ms.date: 04/14/2020
ms.assetid: 98bace36-044d-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 1d7da74c4db4af2b42d31462607dcb17c0a8b894
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320470"
---
# <a name="commerce-apis--framework-and-run-time-support-for-async-patterns"></a>Commerce API - 非同期パターンのフレームワークとランタイムのサポート
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 31 日| 近日発表|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、Commerce Runtime フレームワーク、Retail サーバー コントローラー、およびデータベース アクセスの非同期/待機プログラミング モデルがサポートされます。 これにより、開発者は、高負荷時のパフォーマンス結果の向上を実現し、ビジネス ロジックの一部を並列に実行できる場合に実行時間を短縮できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Commerce API フレームワークは、拡張機能の非同期実行をサポートするように強化されました。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[ビジネス ロジックでの非同期 Commerce CRT API の作成](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/async-commerce-extension) (ドキュメント)
<!--docs end-->

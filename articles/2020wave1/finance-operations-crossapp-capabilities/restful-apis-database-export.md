---
title: データベース エクスポート用の RESTful API
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 04/02/2020
ms.assetid: 487df01a-8e74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: c5d4768323803a12aa5d9be888aa1e1bf74fccac
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256795"
---
# <a name="restful-apis-for-database-export"></a>データベース エクスポート用の RESTful API
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
当社のデータによると、データベースの更新を実行するお客様の 90% 以上が、そのデータベースをユーザー受け入れテスト (UAT) 環境から資産ライブラリにエクスポートしています。 現在、お客様はセルフサービス アクションを使用してエクスポートをトリガーする必要があります。これには営業時間中の作業を必要とします。 RESTful API を使用すると、営業時間外または繰り返しのアクティビティを実装できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
データベースのエクスポートをトリガーする新しい API がドキュメントと共に提供されます。 これにより、運用環境からサンドボックスへの、さらにサンドボックスから資産ライブラリへの、エンドツーエンドの完全な自動化が可能になります。 そこから、既存の API を使用して BACPAC ファイルを開発者マシンにダウンロードすることもできます。
<!--feature detail end -->










---
title: データベース エクスポート用の RESTful API
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 03/16/2020
ms.assetid: 85c8ade0-7548-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: e155ac34ef9f2fc1ede99ee94db5a7fdbcbf1732
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178441"
---
# <a name="restful-apis-for-database-export"></a>データベース エクスポート用の RESTful API
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 16 日| 近日発表|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
当社のデータによると、データベースの更新を実行するお客様の 90% 以上が、そのデータベースをユーザー受け入れテスト (UAT) 環境から資産ライブラリにエクスポートしています。 現在、お客様はセルフサービス アクションを使用してエクスポートをトリガーする必要があります。これには営業時間中の作業を必要とします。 RESTful API を使用すると、営業時間外または繰り返しのアクティビティを実装できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
データベースのエクスポートをトリガーする新しい API がドキュメントと共に提供されます。 これにより、運用環境からサンドボックスへの、さらにサンドボックスから資産ライブラリへの、エンドツーエンドの完全な自動化が可能になります。 そこから、既存の API を使用して BACPAC ファイルを開発者マシンにダウンロードすることもできます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[データベース エクスポートの作成 v1](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/api/v1/reference-create-export) (ドキュメント)

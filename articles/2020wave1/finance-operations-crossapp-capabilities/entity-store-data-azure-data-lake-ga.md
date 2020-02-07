---
title: Azure Data Lake でエンティティ格納が利用可能に
description: 顧客は、Finance and Operations アプリの分析データとトランザクション データ (エンティティ格納で集計の測定として定義される) を独自の Azure Data Lake で使用して、ほぼリアルタイムの AI と分析を実現できます。
author: relnotes
ms.reviewer: kfend
ms.date: 12/16/2019
ms.assetid: c3876dfc-31cc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 6621d5b116024c64e457989e61ec1504591e629e
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986722"
---
# <a name="entity-store-data-is-available-in-azure-data-lake"></a>Azure Data Lake でエンティティ格納が利用可能に
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 6 月 1 日| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Finance and Operations アプリと顧客独自の Azure Data Lake に含まれるその他のデータ全体で、高度な分析と AI (データに基づく推論など) が可能になります。 Finance and Operations アプリでは、非正規化トランザクション データにほぼリアルタイムで簡単にアクセスできます。

分析ワークスペースに供給される同じデータセットが、独自のレポートとデータ マッシュアップ シナリオで利用できるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
集計の測定は、Dynamics 365 Finance and Operations アプリ内で定義されている非正規化スター スキーマです。 集計の測定を使用すると、ユーザーは複雑なデータ スキーマを理解する必要なく運用データをナビゲートできます。 集計の測定はエンティティ格納にステージングされ、運用データ ウェアハウスが含まれます。

Azure Data Lake でのエンティティ格納スキーマの一般提供に伴い、顧客はレポート作成と分析のために非正規化データに直接アクセスできるようになります。 集計の測定は Data Lake Storage Common Data Model フォルダーとして格納されるため、リッチなデータ マッシュアップ シナリオや分析シナリオが可能になります。 たとえば、集計の測定データを Power BI 参照データ フローとして Power BI に添付し、レポート作成に使用できます。 パワー ユーザーは、Power BI Desktop で新しいデータ マッシュアップとレポートを簡単に作成できます。 

開発者と BI のプロフェッショナルは Azure Synapse や Azure Data Factory などのツールを使用してデータを操作し、エンタープライズ データ ウェアハウスを作成できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Data Lake でエンティティ格納を構成する方法](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/data-entities/entity-store-data-lake) (ドキュメント)

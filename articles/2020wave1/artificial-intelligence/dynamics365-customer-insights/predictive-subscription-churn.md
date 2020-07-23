---
title: サブスクリプション解約予測
description: サブスクリプション解約予測
author: relnotes
ms.reviewer: mhart
ms.date: 05/29/2020
ms.assetid: 53c8e911-6395-ea11-a811-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: midevane
dynamics365pdf: true
ms.openlocfilehash: 5874be53e4a60b47f9a6a5d3bc41c210e17bc0da
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440569"
---
# <a name="subscription-churn-prediction"></a>サブスクリプション解約予測
[!include[artificial-intelligence/dynamics365-customer-insights banner](../includes/artificial-intelligence/dynamics365-customer-insights.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 6 月| -|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
シンプルなガイド付きエクスペリエンスに従って、クラウド サービス、顧客メンバーシップ、その他のセクターなどのサブスクリプション分野における解約予測を作成します。 

サブスクリプション解約予測機能を使用すると、データ サイエンティストを採用せずに、顧客がサブスクリプション ベースの製品またはサービスの利用を停止する可能性を予測できます。 予測スコアを使用すると、顧客に関する他の情報を組み合わせて、解約のリスクが高いセグメントを作成できます。  このセグメントの利用により、Customer Insights との統合を使用して、マーケティング、顧客サポート、およびその他のシナリオで顧客を直接ターゲット設定できます。また、特定の顧客の解約リスクを減らし、収益を改善して、コストを削減できます。

![サブスクリプション解約モデルのステップ 1 のビジュアル](media/june2020_subchurn_1.png "サブスクリプション解約モデルのステップ 1 のビジュアル")

エクスペリエンス内では、解約の定義をビジネスに固有の時間ベースのウィンドウとして構成できます。  たとえば、月単位のサブスクリプション プロセスがあるビデオ ストリーミング ビジネスでは、サブスクリプションの期限が切れてから 15 日後に顧客が解約したと見なすことができます。 

予測の際には、必要なデータをガイドし、顧客の解約を予測するために必要なフィールドにビジネスに関するデータをマップできるようにします。 

![ステップ 2 のビジュアル – 必要なデータを追加する – 解約モデル](media/june2020_subchurn_2.png "ステップ 2 のビジュアル – 必要なデータを追加する – 解約モデル")

ビジネス情報の変化に応じて、システムの新しい情報での再トレーニングを実施するスケジュールを設定し、変化するビジネス状況に適応することもできます。

![サブスクリプション解約モデルのトレーニング スケジュールのビジュアル](media/june2020_subchurn_4.png "サブスクリプション解約モデルのトレーニング スケジュールのビジュアル")


<!--feature detail end -->










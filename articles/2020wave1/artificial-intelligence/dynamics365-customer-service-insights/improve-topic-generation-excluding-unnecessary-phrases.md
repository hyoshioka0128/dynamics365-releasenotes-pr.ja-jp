---
title: 不要な語句を除外してトピックの生成を改善する
description: トピック タイトルの一般的で無関係な単語を無視することにより、トピックの生成とクラスタリングを改善する
author: relnotes
ms.reviewer: iawilt
ms.date: 01/14/2020
ms.assetid: 7e58833f-5c1d-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
dynamics365pdf: true
ms.openlocfilehash: 3ce3c5d47557d928a5d6a66b84424d07b9da32ac
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986846"
---
# <a name="improve-topic-generation-by-excluding-unnecessary-phrases"></a>不要な語句を除外してトピックの生成を改善する
[!include[artificial-intelligence/dynamics365-customer-service-insights banner](../includes/artificial-intelligence/dynamics365-customer-service-insights.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 6 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
サポート トピック クラスターの分析は、企業がサポートの提供を最適化し、カスタマー エクスペリエンスを改善するのに役立ちますが、時間がかかる場合があります。 この機能は、企業名など、クラスタリングを歪める可能性があるため除外する必要のあるフレーズを特定することにより、組織が AI 駆動型クラスタリングの品質を向上させるのに役立ちます。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 Customer Service Insights により、自然言語の理解を使用して、サポート案件データが自動的に解析され、意味的に類似したサポート案件が自動生成されたトピックにグループ化されます。 トレンド上位のトピックを知ることで、マネージャーはサポートを最適化し、コア製品チームにフィードバックを提供できます。 ただし、会社名や製品名などの一般的なフレーズは、トピック クラスタリング アルゴリズムの強度を弱め、サポート トピック クラスターの有用性を低下させる可能性があります。 現在、ユーザーはこの問題を軽減するために、無視できるサポート案件タイトル内のタグとして (特に) 使用される区切り文字を指定できますが、区切りのないテキストを無視する方法はありません。 

このリリースでは、ユーザーはテキストを解析するときに無視する必要がある追加のキーワードまたはフレーズ (会社名またはその他の一般的で無関係な用語) を指定できるため、より正確で意味のあるトピックが生成されます。 
<!--feature detail end -->










---
title: 会計統合フレームワークに基づくスウェーデン向けの制御ユニット統合サンプル
description: スウェーデンでは、キャッシュ レジスターに関する現地の規制に従い、すべての小売販売を、統合型の会計デバイス (制御ユニット) を備えたキャッシュ レジスターに登録する必要があります。 スウェーデン向けの制御ユニット統合サンプルでは、スウェーデンの市場で利用できる一般的な会計デバイス モデルの 1 つがサポートされています。 このサンプルは Retail SDK の一部であり、会計統合フレームワークを拡張するものです。
author: relnotes
ms.reviewer: josaw
ms.date: 12/11/2019
ms.assetid: 6e903f43-01e6-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 38857cfb75e8d7a5f98dfc965a79132fd2ccdb08
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2909975"
---
# <a name="control-unit-integration-sample-for-sweden-based-on-the-fiscal-integration-framework"></a>会計統合フレームワークに基づくスウェーデン向けの制御ユニット統合サンプル 
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|-| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
スウェーデン向けの制御ユニット統合サンプルは、お客様が現地のキャッシュ レジスター規制に準拠した販売時点管理 (POS) ソリューションを構築するために使用できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
スウェーデン向けの制御ユニット統合サンプルでは、[会計統合フレームワーク](https://docs.microsoft.com/dynamics365/retail/localizations/fiscal-integration-for-retail-channel)が使用されています。つまり、このサンプルは組み込みの会計統合機能をすべてサポートしており、ビルド後、そのままの構成で使用できます。 また、お客様固有のビジネス プロセスや、制御ユニットのさまざまなモデルをサポートするために、カスタマイズや拡張を行うこともできます。 このサンプルでは、さまざまな現金持ち帰り販売シナリオでの販売について会計統合を行うことができ、基本的なシナリオ (再試行が可能な場合など) や、より高度なシナリオ (それまでに制御ユニットに登録されていない完了取引の登録など) でのエラー処理オプションも用意されています。

Retail 会計統合フレームワークを使用することで、多国籍の小売業者は、事業を展開する国や地域のさまざまな会計規制に準拠した、共通の POS ソリューションを構築することができます。
<!--feature detail end -->



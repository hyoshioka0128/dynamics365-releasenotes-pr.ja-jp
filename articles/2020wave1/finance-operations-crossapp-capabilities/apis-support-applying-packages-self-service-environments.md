---
title: セルフサービス環境へのパッケージの適用をサポートする API
description: 現在、以前のインフラストラクチャ アーキテクチャに展開された Tier 1-5 DevTest およびサンドボックスタイプの環境にパッケージを適用するための API が存在しますが、これらの API はセルフサービス インフラストラクチャ環境をサポートしていません。 この機能では、すべてのタイプの Tier 1-5 環境を有効にするサポートを追加します。
author: relnotes
ms.reviewer: sericks
ms.date: 04/02/2020
ms.assetid: 3c6f224b-8e74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: adbae459eebfab370391d6241f206c0f2559309b
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219705"
---
# <a name="apis-to-support-applying-packages-for-self-service-environments"></a>セルフサービス環境へのパッケージの適用をサポートする API
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
顧客は現在 Azure DevOps タスクを夜間のビルド プロセスと CI/CD パイプラインに使用しています。 より多くの顧客をセルフサービス環境に移行すると、それらの顧客は DevOps タスクを使用できなくなります。 この機能により、セルフサービス環境のサポートが有効になり、CI/CD の観点からすべての種類の環境に均衡がもたらされます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しい Lifecycle Services (LCS) RESTful API を導入して、以前のインフラストラクチャ アーキテクチャ上にあるか、セルフサービス インフラストラクチャ上にあるかに関係なく、Tier 1-5 DevTest またはサンドボックスタイプの環境に Azure DevOps から直接アプリケーションをパッケージ化できるようにします。
<!--feature detail end -->










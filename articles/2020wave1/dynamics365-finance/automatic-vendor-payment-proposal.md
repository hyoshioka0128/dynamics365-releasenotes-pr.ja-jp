---
title: 自動仕入先支払提案
description: この機能は、支払提案を自動的に生成し、承認のためのワークフロー プロセスにルーティングすることにより、仕入先支払のタイミングの最適化を支援します。
author: relnotes
ms.reviewer: roschlom
ms.date: 02/04/2020
ms.assetid: 6a2a6bad-4dcb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 381cd6cb2192514b4041c519792bfa6554573bd9
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032611"
---
# <a name="automatic-vendor-payment-proposal"></a>自動仕入先支払提案
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 7 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
組織は通常、特定の状況に適用される一連のルールに従って仕入先への支払を行います。 たとえば、仕入先を重要度の順にランク付けして、最も重要な仕入先から先に支払う場合があります。 他の組織では、仕入先を分類する 1 つ以上の異なる方法を使用して、特定の日に特定のカテゴリーの仕入先に支払う場合もあります。 このプロセスを自動化すると、組織は独自のルールを適用して、手動プロセスを使用するよりも一貫性のある効率的な方法で仕入先支払提案を作成できます。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
会計登録者と買掛金勘定マネージャーは、“ルール エンジン” を使用して製品内でルールを定義します。このルールにより、システムは支払う必要がある仕入先を学習し、それらの仕入先に対する支払時期を決定できます。 システムはこの情報を使用して支払提案を自動的に生成し、承認のためのワークフロー プロセスに送信します。  
<!--feature detail end -->










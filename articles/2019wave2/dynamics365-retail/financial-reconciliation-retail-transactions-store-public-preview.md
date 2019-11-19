---
title: 店舗での小売トランザクションの財務調整 (パブリック プレビュー)
description: 店舗での小売トランザクションの財務調整 (パブリック プレビュー)
author: anpurush
ms.reviewer: josaw
ms.date: 09/04/2019
ms.assetid: 66751c33-f6c9-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: anpurush
dynamics365pdf: true
ms.openlocfilehash: a28942a009ac9f69c87e0d5c71018152a577700d
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659850"
---
# <a name="financial-reconciliation-of-retail-transactions-in-the-store-public-preview"></a>店舗での小売トランザクションの財務調整 (パブリック プレビュー)
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 11 月| 2020 年 2 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
小売店舗では、店舗マネージャーが店内での現金の処理と調整のすべての側面に関する説明義務と責任を負います。 店舗マネージャーはシフトの終わりに、そのシフトの現金エントリの調整と転記を行う必要があります。 この作業を POS クライアントで実行できるようにすることは、店舗マネージャーが責任を果たすために必要な重要な機能です。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は[トリクル フィード命令の作成](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-retail/enhancements-retail-statement-posting#trickle-feed-order-creation)プロセスでのみ使用でき、小売業者が財務諸表を MPOS/CPOS クライアントで作成するかまたは Retail Headquarters で作成するかを決定するパラメーターによって駆動されます。 この機能を使用すると、店舗マネージャーは次のことができます。

1. シフトの財務小売明細書を MPOS/CPOS で作成する。
2. 現在利用可能な現金管理トランザクション タイプを使用して、必要に応じて現金エントリの調整を行う。
3. MPOS/CPOS で財務小売明細書を転記する。
4. MPOS/CPOS に転記された財務諸表を使用して、同じものを Retail Headquarters に転記する。

このプロセスにより、Retail Headquarters で財務諸表の作成と転記を行う必要がなくなります。
<!--feature detail end -->










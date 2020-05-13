---
title: Service Fabric 配置での Commerce 支払パッケージのサポート
description: この機能により、ISV、顧客、およびパートナーは、オンプレミス環境および Service Fabric 環境で Service Fabric インフラストラクチャを使用して配置できる Dynamics 365 Commerce の支払パッケージを作成できます。
author: mugunthanm
ms.reviewer: rhaertle
ms.date: 04/14/2020
ms.assetid: 8bde666f-094d-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 19321d10137660d4ac878359a9d3c82c7a12de6b
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320415"
---
# <a name="commerce-payment-packaging-support-in-service-fabric-deployments"></a>Service Fabric 配置での Commerce 支払パッケージのサポート
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 31 日| 近日発表|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、支払パッケージをオンプレミス環境に配置できます。 以前は、支払拡張機能パッケージはクラウド環境でのみサポートされていたため、顧客はオンプレミス環境の Dynamics 365 Commerce で支払拡張機能を使用できませんでした。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
拡張機能を使用して、Dynamics 365 Commerce で新しい支払パッケージを作成し、拡張モデルへの参照として支払ライブラリを追加し、カスタマイズを行うことができます。 すべての支払拡張機能モジュールは、名前が RetailPaymentConnectors で始まる (これが接頭辞として付加されている) 必要があります。 モデルで別の接頭辞が使用される場合、それは支払モジュールとは見なされません。 カスタマイズ後、配置可能なパッケージを作成し、Dynamics Lifecycle Services (LCS) を使用して配置できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[Service Fabric 配置でのアプリケーション エクスプローラー用支払パッケージの作成](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/payment-connector-package) (ドキュメント)
<!--docs end-->

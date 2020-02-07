---
title: Azure AD での POS サインインのサポート
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: e6241ff2-f00c-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 0e981f6180271559238728582f429101a9e6324d
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986650"
---
# <a name="azure-ad-support-for-pos-sign-in"></a>Azure AD での POS サインインのサポート
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 2 月| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
現在、Commerce POS (販売時点管理) アプリケーションは、独自の ID プロバイダーに基づくスタッフ認証のみをサポートしています。 Azure Active Directory (Azure AD) での POS サインインのサポートは、さまざまな小売業者からリクエストされたもので、一般にセキュリティと保守性の 2 つの要件があります。 企業のセキュリティ要件が厳しいお客様は通常、POS に対する認証をより安全に処理する方法として Azure AD を検討します。 多くのお客様は通常、複数の Microsoft クラウド サービス (Azure、Office 365、Dynamics 365) を使用しており、Azure AD で既にワーカーをセットアップしています。 Commerce ソリューションを使用するために、Dynamics 365 Commerce バック オフィスでそれら (およびそのパスワード) をもう一度管理したくはありません。 これにより、簡単に回避できる重複作業が作成されます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能では、以下のものが導入されます。

- POS サインインに必要な認証方法を指定するための Commerce Headquarters (HQ) の新しい構成パラメーター。
- ユーザー認証に Azure AD を活用するように変更された POS サインイン ページ。
<!--feature detail end -->










---
title: チャネルごとの Azure Active Directory 企業と顧客間テナント
description: チャネルごとの Azure Active Directory 企業と顧客間テナント
author: relnotes
ms.reviewer: josaw
ms.date: 02/14/2020
ms.assetid: a4013e72-aff6-e911-a813-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: fb948e6d81ade63d5cc2c0da0bb0b56713fdc159
ms.sourcegitcommit: bfe05af05f11f2c318a77bb3138c3df0796c7187
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/27/2020
ms.locfileid: "3088858"
---
# <a name="azure-active-directory-business-to-customer-tenant-per-channel"></a>チャネルごとの Azure Active Directory 企業と顧客間テナント


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、サイトとチャネルを個別のブランドとして扱う企業にとって価値があります。 エンド ユーザーは、同じ法人の下で維持されるサイトおよびチャネルごとに別々のログイン資格情報を持ちます。 この機能は、企業が自社のブランドのルック アンド フィールを別のビジネスのように見せたいが、ブランドを横断する可能性のある在庫や製品は複製したくない場合に使用されます。 この機能により、顧客は各ブランドの複製を別々の法人で実行する必要がなくなります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
顧客は、エンド ユーザーからは別々のビジネスのように見え、感じられるサイトやチャネルを単一の法人の下で使用することを選択できます。 マイクロソフトは、個別の Azure AD B2C テナントをチャネルにマップする機能をサポートするようになったため、エンド ユーザーはチャネルおよびサイトごとに完全に異なるログイン資格情報を持ちます。 エンド ユーザーは、チャネル固有のサイトに明確に移動し、参照し、そこでトランザクションを実行します。 コマースの顧客は、自身の環境でこの機能を有効にする必要があります。システム管理者は、Web Storefront Administration ツールでチャネルベースの B2C テナントを構成できます。 顧客は環境あたり 1 つの Azure AD B2C テナントに制限されなくなり、サイトレベルのログインおよび ID エクスペリエンスをより細かく制御できるようになります。
<!--feature detail end -->











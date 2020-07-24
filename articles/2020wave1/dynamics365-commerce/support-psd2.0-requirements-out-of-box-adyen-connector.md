---
title: すぐに使用できる Adyen コネクタで PSD2.0 要件をサポート
description: 'Adyen 用のすぐに使用できる支払いコネクタは、Adyen が提供する更新された SDK のサポートを取得します。 このバージョンの支払いコネクタでは、PSD2.0 に含まれる強力な顧客認証 (Strong Customer Authentication: SCA) 規定で定められている支払いリダイレクトを含む、PSD2.0 支払い要件のサポートが追加されます。'
author: relnotes
ms.reviewer: josaw
ms.date: 06/24/2020
ms.assetid: ed913be9-6e8e-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: fab14068cc5133f47902db94523e49648540a776
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522859"
---
# <a name="support-psd20-requirements-in-the-out-of-the-box-adyen-connector"></a>すぐに使用できる Adyen コネクタで PSD2.0 要件をサポート
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 18 日| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
欧州の PSD2.0 要件では、チェックアウト時にカード所有者を銀行で直接認証できるようにする必要があります。 この機能により、銀行が顧客を認証するために必要なリダイレクトのサポートが追加されます。 この機能では、この強力な顧客認証のサポートだけでなく、Adyen が提供する新しい SDK のサポートが追加されます。これにより、利用可能な支払い方法に関してチェックアウト時の柔軟性が向上します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、バージョン "V002" を指定するためのオプションが Adyen 支払いコネクタ セットアップに追加されます。 オンライン ストアの支払いアカウントのセットアップでその設定が変更されると、チェックアウト プロセスでは Adyen Web Drop-in SDK を使用して支払いを作成します。 このバージョンの支払いコネクタを使用すると、ストアフロントの業者は PSD2.0 準拠の支払いを処理できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[Adyen コネクタを使用した強力な顧客認証 (SCA)](https://docs.microsoft.com/dynamics365/commerce/adyen_redirect) (ドキュメント)
<!--docs end-->

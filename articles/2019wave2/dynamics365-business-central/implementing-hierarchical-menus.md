---
title: 階層メニューの実装
description: 新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールで利用できる機能を探索できます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/08/2020
ms.assetid: 9e23ce60-4abb-e911-a966-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 8b306f0d4f03f00977a8e229e9335391c6ea2cee
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320536"
---
# <a name="implementing-hierarchical-menus"></a>階層メニューの実装


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
アプリ開発者は、ソリューションでできることをユーザーや見込顧客が理解できるように、ソリューションで提供されるビジネス機能の全体的なカタログを示すように求められることがよくあります。 同様に、再販業者は多くの場合、顧客の部署またはユーザー ロールの固有のニーズに一致する論理的なグループ化によってビジネス機能を実装したいと考えます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL では、開発者はセクション領域コントロールをさらにサブグループに分割して、より複雑なリンクの階層をナビゲーション メニュー内に作成することができます。 リンクから、ページ、レポート、XmlPort、Codeunit などのさまざまな AL オブジェクトを実行できます。

以前のバージョンの Dynamics NAV では、メニュー スイートと部署を通じてこれを実現していました。 Business Central では、これらの新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールが利用できる関心のある機能を探索できます。

![一般的なナビゲーション メニューのサブグループ化](media/subgroups-3000x2000.png "一般的なナビゲーション メニューのサブグループ化")
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目

<!--docs start-->
[ページへのアクションの追加](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-adding-actions-to-a-page) (ドキュメント)
<!--docs end-->

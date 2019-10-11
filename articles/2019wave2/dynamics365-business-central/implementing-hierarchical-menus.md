---
title: 階層メニューの実装
description: ''
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 09/02/2019
ms.assetid: 9e23ce60-4abb-e911-a966-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 09cc813793a5ebd3af94bbe983ca4cc4bc1e8014
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140559"
---
# <a name="implementing-hierarchical-menus"></a>階層メニューの実装
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
アプリ開発者はしばしば、ソリューションで何ができるかをユーザーや見込顧客が理解できるようにするために、ソリューションで提供されるビジネス機能の全体的なカタログを示すように求められます。 同様に、再販業者は多くの場合、顧客の部署またはユーザー ロールの固有のニーズに一致する論理的なグループ化によってビジネス機能を実装したいと考えます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL では、開発者はセクション領域コントロールをさらにサブグループに分割して、より複雑なリンクの階層をナビゲーション メニュー内に作成することができます。 リンクから、ページ、レポート、XmlPort、Codeunit などのさまざまな AL オブジェクトを実行できます。

以前のバージョンの Dynamics NAV では、メニュー スイートと部署を通じてこれを実現していました。 Business Central では、これらの新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールが利用できる関心のある機能を探索できます。
<!--feature detail end -->

![一般的なナビゲーション メニューのサブグループを示したスクリーンショット](media/subgroups-3000x2000.png "一般的なナビゲーション メニューのサブグループを示したスクリーンショット")
<!-- Picture 1 -->







## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




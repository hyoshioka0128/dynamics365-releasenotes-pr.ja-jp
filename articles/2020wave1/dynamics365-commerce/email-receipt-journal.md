---
title: 仕訳帳から領収書をメールで送信する
description: レジ担当者は領収書の印刷に加えて、仕訳帳から過去のトランザクションの領収書をメールで送信できるようになります。
author: relnotes
ms.reviewer: josaw
ms.date: 05/11/2020
ms.assetid: 9d6e0bf6-0b1d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: stuharg
dynamics365pdf: true
ms.openlocfilehash: b74e788aef85f30874f2c8b92c092387bdbac31a
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381816"
---
# <a name="email-a-receipt-from-the-journal"></a>仕訳帳から領収書をメールで送信する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 24 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
デジタル領収書には、紙のドキュメントを使用せずに購買を追跡できたり、他のユーザーにメールで領収書を転送できるなど、顧客にとって多くの利点があります。 Dynamics 365 Commerce で、印刷された領収書に対するのと同じ機能が、メールで送信される領収書に対しても提供されます。 具体的には、顧客は以前の取引の領収書をメールで送信 (または再送信) するよう要求できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
レジ担当者は、仕訳帳にアクセスしてトランザクションを選択し、**領収書の表示**を選択することにより、Modern POS (販売時点管理) またはクラウド POS から顧客に以前のトランザクションの領収書をメールで送信できます。 レジ担当者が新しい**メール** アイコンを選択すると、ダイアログ ボックスが開き、Commerce Headquarters 内の顧客のレコードに領収書メール プロパティの値が表示されます。 レジ担当者は次のことができます。

- テキスト フィールドのメール アドレスに領収書を送信する。
- 領収書を送信する宛先メール アドレスを変更する。

> [!NOTE]
> 既定では、この機能は無効になっています。 Commerce Headquarters でこれを有効にするには、**機能管理**ワークスペースに移動し、**仕訳帳から領収書をメールで送信する**機能を有効にします。
<!--feature detail end -->










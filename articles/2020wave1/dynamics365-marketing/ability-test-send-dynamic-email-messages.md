---
title: 動的なメール メッセージをテスト送信する機能
description: 本番環境に移行する前にメッセージをプレビューしてテストし、メッセージの一貫性を確保します。
author: relnotes
ms.reviewer: alfergus
ms.date: 05/08/2020
ms.assetid: 014e97e2-18ce-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: prrana
dynamics365pdf: true
ms.openlocfilehash: eec9abc0e3a501b0200ea276566993aa7e9e8bd7
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3380938"
---
# <a name="ability-to-test-send-dynamic-email-messages"></a>動的なメール メッセージをテスト送信する機能


| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 Marketing で、パーソナライズされた動的コンテンツを含む視覚的に充実した電子メール メッセージを設計できます。 しかし、電子メール クライアントのレンダリングのばらつきを考慮し、動的コンテンツが正確であることを確認するには、これらのメッセージを慎重にテストする必要があります。 改善されたテスト送信機能により、実稼働前にメッセージをプレビューしてテストできるため、メッセージの一貫性を確保できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
- **アップグレードされたエラー検出**: 送信テスト メッセージ用の改善されたエラー チェック。
- **動的コンテンツのテスト送信**: 選択したサンプル連絡先レコードに基づいて、完全にレンダリングされた動的コンテンツ (動的フィールド値、エンティティ関係、ループ、条件など) を含むテスト送信メッセージ。


<!--feature detail end -->

![テスト メッセージ内のパーソナライズされた動的データ](media/personalizedtestsend.png "テスト メッセージ内のパーソナライズされた動的データ")
<!-- Picture 1 -->









## <a name="see-also"></a>関連項目

<!--docs start-->
[テスト メッセージを送信する](https://docs.microsoft.com/dynamics365/marketing/email-preview#send-a-test-message) (ドキュメント)
<!--docs end-->

---
title: 新しい URL パラメーターによって Web クライアントのヘッダーを非表示にする
description: URL の新しいパラメーターによってクライアントのヘッダーを非表示にする
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 06/10/2020
ms.assetid: 2f7a3732-0b6d-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: d612304fb857553c71152f4a75ffe72d11b11f98
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3487678"
---
# <a name="new-url-parameter-hides-web-client-header"></a>新しい URL パラメーターによって Web クライアントのヘッダーを非表示にする


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 17 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 6 月 10 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Business Central Web クライアントは、さまざまな UI 統合のニーズを満たすのに十分な柔軟性を備えています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
開発者と管理者が Web クライアントで Microsoft 365 ヘッダーを非表示にできるように、Business Central にアクセスするための URL で新しい **showHeader** パラメーターがサポートされます。

このパラメーターは、次のようなさまざまな制御された統合シナリオでユーザー エクスペリエンスを向上させるために使用できます。

- 他の Web アプリケーションに Business Central Web クライアントを埋め込む。
- 画面の大部分を占めるよう意図されたクライアント コントロール アドイン用に、より多くの画面スペースを解放する。

このパラメーターは、より焦点を絞ったスペースを作成するために UI 内の要素を取り除く他の URL パラメーターと同様に動作します。 ヘッダーを非表示にすると、ユーザーは、アプリ起動ツールを使用してサインアウトや別のアプリへの切り替えを行う機能など、ヘッダーを通じて公開される機能にアクセスできなくなります。

![ShowHeader パラメーターが URL に適用されるときにレンダリングされる Web クライアント](media/web-client-with-showheader-parameter.png "ShowHeader パラメーターが URL に適用されるときにレンダリングされる Web クライアント")
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcIdeas) をご利用ください。




## <a name="see-also"></a>関連項目

<!--docs start-->
[Web クライアントの URL](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-web-client-urls) (ドキュメント)
<!--docs end-->

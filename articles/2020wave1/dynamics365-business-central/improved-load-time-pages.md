---
title: ページをよりすばやく開く
description: ページをよりすばやく開きます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: c9b05388-851a-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: e16698993c0f1d5fd75686e478c3dfddef495628
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232222"
---
# <a name="pages-open-faster"></a>ページをよりすばやく開く


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ビジネス ユーザーは、タスクを完了するためにページ間を移動するとき、ページとダイアログ ボックスがすばやく読み込まれることを期待します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ユーザーは、頻繁に使用するページが前より速く開くようになったことがわかります。 最初にページの構造が表示され、データが読み込まれるまでのコンテキストが示されます。

技術的には、レンダリングされたページは、最初に開かれたときにキャッシュされるようになりました。 これを行うために、ビジネス データや機密情報がユーザーのデバイスに永続化されることはありません。 次にページが開いたときに、サービスから最新のデータがフェッチされている間、キャッシュからすぐにレンダリングされます。

- Update 16.0 では、ユーザーのセッションの間、ページがキャッシュされます。 ユーザーは、ログインしたままの状態でのみ、パフォーマンス向上のメリットを得られます。
- Update 16.1 では、セッション間でページをキャッシュすることで機能を改善します。 ユーザーは、ブラウザーを閉じたりログアウトした後に再度ログインした場合にも、読み込み時間が改善されるというメリットがあります。

サービスからのデータの取得でビジーな間、Business Central には、データがまだ読み込まれていないことを示す独特な脈動 UI 要素が表示されます。

![UI には、独特の脈動視覚化要素が表示されます](media/ghosted-ui.png "UI には、独特の脈動視覚化要素が表示されます")

### <a name="try-it-now"></a>試してみましょう
[こちらで](https://businesscentral.dynamics.com/?page=9301)オンライン環境にログインすることで、さまざまな売上請求書を開くときなど、ページを開く時間の向上を体験してください。  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目


<!--docs start-->
[開発者向けのパフォーマンス記事](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (ドキュメント)
<!--docs end-->


---
title: ページをよりすばやく開く
description: ページをよりすばやく開きます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/21/2020
ms.assetid: c9b05388-851a-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 30bd1557bc1af08f11458ad4f9d2cd21819e1c92
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293766"
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

- Update 16.0 では、ユーザーのセッションの間、ページがキャッシュされます。 ユーザーは、サインインしたままの状態でのみ、パフォーマンス向上のメリットを得られます。
- Update 16.2 では、セッション間でページをキャッシュすることで機能を改善します。 ユーザーは、別のブラウザー タブで Business Central を開いた場合や、ブラウザーを閉じたりサインアウトした後に再度サインインした場合にも、読み込み時間が改善されるというメリットがあります。

サービスからのデータの取得でビジーな間、Business Central には、データがまだ読み込まれていないことを示す独特な脈動 UI 要素が表示されます。

![UI には、独特の脈動視覚化要素が表示されます](media/ghosted-ui.png "UI には、独特の脈動視覚化要素が表示されます")

### <a name="try-it-now"></a>試してみましょう
[オンライン環境にサインイン](https://businesscentral.dynamics.com/?page=9301)して、さまざまな売上請求書を開くときなど、ページを開く時間の改善を体験してください。
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目

<!--docs start-->
[開発者向けのパフォーマンス記事](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (ドキュメント)
<!--docs end-->

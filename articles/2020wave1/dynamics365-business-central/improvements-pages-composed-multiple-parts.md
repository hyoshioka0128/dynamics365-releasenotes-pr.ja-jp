---
title: ページ上のスペースの最適化された使用
description: ページ上のスペースの最適化された使用
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: f4392522-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 8cf205007d94d1003d23dc0db7ff1a5def24be65
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232167"
---
# <a name="optimized-use-of-space-on-a-page"></a>ページ上のスペースの最適化された使用


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
一部のビジネス タスクには、タスクの性質とタスクに関連したデータの量を反映した高度な画面レイアウトが必要です。 高度に最適化されたレイアウトを使用することで、ユーザーはデータの最適な概要を取得して迅速な意思決定と行動が可能になり、タスクを完了するためのスクロールやナビゲートの必要性が減少します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
**複数の部分で構成されるページの改善**

デスクトップ クライアントには、ListParts や CardParts などの複数のパーツで構成されるページ オブジェクトの完全なサポートが追加されます。 この機能は、Role Center または FactBox ペインでは既に可能でした。 しかし、他のページ タイプのキャンバスは、他のコンテンツと一緒にパーツを表示するのに最適ではなかったため、UI 要素が重複したり、データに到達できなかったりしました。

開発者は、予測可能な結果を提供する事前定義された AL パターンから選択することで、ページを実装できるようになりました。 たとえば、ListPlus ページに 2 つのリストを並べて表示できます。 または、ドキュメント ページで複数の依存リストを重ねて表示します。 これらの制御パターンを既に使用しているページは、追加の開発作業を必要とせずに、自動的にこの変更の恩恵を受けます。

- **2020 年 4 月に利用可能**: リスト ページ、ドキュメント ページ、カード ページ、および ListPlus ページで使用される ListPart の最適化。
- **2020 年 4 月以降に利用可能**: ワークシート ページで使用される ListPart と、さまざまなページ タイプで使用される CardPart の最適化。

![複数の ListPart を表示する ListPlus ページの例](media/listplus-example-demonstrating-multiple-lists.png "複数の ListPart を表示する ListPlus ページの例")

**画面上のコンテンツの増加**

- ユーザーが画面全体にページを表示すると、ページ キャプションがコンパクトになり、サイドのグレースペースが減少するというメリットがあります。 例として、基本的なリスト ページを取り上げます。 Business Central Web クライアントの過去のバージョンと比較して、コンテンツ用に約 15% の左右の間隔と 5% の上下の間隔が確保されます。 これらの確保により、さらに 2 列と 1 行が表示されます。
- キャプションが指定されていない FastTab は、ページの構造を定義するグループとして扱われます。 その結果、"キャプションのない" FastTab は空白が減らされ、ユーザーが折りたたむことができなくなります。
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目


<!--docs start-->
[パーツの概要](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-parts) (ドキュメント)
<!--docs end-->


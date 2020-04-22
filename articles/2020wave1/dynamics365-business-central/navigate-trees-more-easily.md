---
title: ツリーでより簡単に移動する
description: ツリーの移動が改善されました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 78855116-36e1-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 14504bae4eaf4016446280fe98e86cf7975d825b
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232772"
---
# <a name="navigate-trees-more-easily"></a>ツリーでより簡単に移動する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ユーザーは、データをカテゴリにグループ化することで、概要を掴みやすくなります。 一部のデータは、深い階層リストとして最適に表示されます。 Business Central は、これらの両方のシナリオのページを開発者が設計することを可能にし、ユーザーが最善の概要を取得して関連するレコードに移動できるようにします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
リピーター コントロールの **ShowAsTree** プロパティが True に設定されているページ オブジェクトでは、ユーザーはデータ ツリーの操作で最新レベルの効率を体験できます。 ユーザーは、キーボードやマウスを使用して、簡単にドリルダウンしたり再度元に戻したりできます。 個別のグループの展開と折りたたみを実行するか、**すべて展開**アクションと**すべて折りたたむ**アクションを使用できます。 

![展開ボタンと折りたたみボタンを使用した勘定科目表の探索](media/coa-tree.png "展開ボタンと折りたたみボタンを使用した勘定科目表の探索")

また開発者は、リピーター コントロールにある新しいプロパティ **TreeInitialState** を使用して、ツリーを完全に展開された状態と完全に折りたたまれた状態のどちらで開くかを指定できます。

### <a name="try-it-now"></a>試してみましょう
[https://businesscentral.dynamics.com/?page=1801](https://businesscentral.dynamics.com/?page=1801) でオンライン環境にサインインして、支援セットアップ ページなどの階層リストのすばやく簡単な探索をお試しください。  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目


<!--docs start-->
[インデントされた階層リストの設計](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-indented-hierarchy-lists) (ドキュメント)
<!--docs end-->


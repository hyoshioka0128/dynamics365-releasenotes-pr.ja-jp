---
title: データへのメモとリンクの追加
description: Business Central のデータに関連するメモとリンク
author: kotelko
ms.reviewer: sgroespe
ms.date: 09/12/2019
ms.assetid: a22f5f6d-957c-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 3756e0eda483b89e600bf7d5608678c6fe30d35b
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140768"
---
# <a name="add-notes-and-links-to-data"></a>データへのメモとリンクの追加
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
最近のビジネス アプリケーションでは、従来よりもさらに構造化されていないデータを表すメモを追加する機能が不可欠です。 メモとリンクは Business Central のオンプレミス展開で既に使用できるようになっていますが、これらの機能をオンライン環境にもデプロイし、データをクラウドに格納できるように強化しています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central オンラインとオンプレミスでキャプチャおよび処理されたビジネス データに内部メモを追加できます。 メモは、[情報ボックス] ペイン内のスタイルが刷新されたパネルのデータの横に表示されます。

そこにあるすべての情報ボックスは現在、**詳細** (すべてのビジネス関連の情報ボックスを含む) と**添付ファイル**(メモ、リンク、ドキュメントの添付ファイルを含む) の 2 つのグループに分けられています。 グループは必要な場合にのみ表示されるため、画面が乱雑になりません。

![メモを使用する](media/notes.png "メモを使用する")

次の特別な機能に注目してください。

- Alt + O キーのキーボード ショートカットを使用すると、**メモ**情報ボックスにフォーカスが合っていないときでも、画面上のどこからでもメモを追加できます。
- Alt + Shift + F2 キーボード ショートカットを使用すると、情報ボックス ペインのグループ間のフォーカスを切り替えることができます。
- 画面には、メモやリンクを含むすべての添付ファイルを示すカウンターがあります。
- 新しく追加されたノートは常に最初に配置され、フォーカスがそこに保持されます。
- メモはより長く、複数の行を入力できるようになり、十分なスペースがある場合は画面上にそのように表示されます。

**リンク**部分では、ユーザーはカードやドキュメント ページからオンライン コンテンツへのハイパーリンクを追加できるようになり、各種高度なシナリオにも対応します。
<!--feature detail end -->












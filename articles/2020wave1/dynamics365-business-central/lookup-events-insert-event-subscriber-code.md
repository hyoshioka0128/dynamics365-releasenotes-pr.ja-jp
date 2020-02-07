---
title: イベントを検索して、コードにイベント サブスクライバーを挿入する
description: Visual Studio Code での AL コードの作成中にイベントをすばやく検索し、選択したイベントに対するイベント サブスクライバーをコードに挿入します。
author: relnotes
ms.reviewer: solsen
ms.date: 12/12/2019
ms.assetid: 96befc08-db1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 1c2422560d0d131928aa283d0efe89b429e29af0
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986663"
---
# <a name="look-up-events-and-insert-event-subscriber-in-code"></a>イベントを検索して、コードにイベント サブスクライバーを挿入する
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
拡張ベースの "カスタマイズ" の中核は、イベントとイベント サブスクライバーの使用です。 

イベントを識別してイベント サブスクライバーのコード テンプレートを生成するために、すでにクライアントにイベント レコーダが追加されており、スローされたイベントを記録して検査することが可能です。 ただし多くの場合、開発者は、サブスクライブするイベントを認識しているか、先行入力/補完機能でイベントを検索し、コード コンテキストにイベント サブスクライバーを挿入する高速な方法を必要としています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL コード エディタの新しい Shift + Alt + E ショートカットを使用して、すべてのイベントのリストを呼び出します。 先行入力を使用してイベント リストを動的に検索/フィルタリングできます。リターン キーを押してイベント エントリを選択すると、イベントのイベント サブスクライバーがアクティブな AL コード エディタ ウィンドウのカーソル位置に挿入されます。 
<!--feature detail end -->










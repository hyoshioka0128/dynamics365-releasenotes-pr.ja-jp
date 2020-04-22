---
title: イベントを検索して、コードにイベント サブスクライバーを挿入する
description: Visual Studio Code での AL コードの作成中にイベントをすばやく検索し、選択したイベントに対するイベント サブスクライバーをコードに挿入します。
author: relnotes
ms.reviewer: solsen
ms.date: 04/02/2020
ms.assetid: 96befc08-db1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 9b33182532c150f0210ba7103164754cf0575a96
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232838"
---
# <a name="look-up-events-and-insert-event-subscriber-in-code"></a>イベントを検索して、コードにイベント サブスクライバーを挿入する
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
拡張ベースの "カスタマイズ" の中核は、イベントとイベント サブスクライバーの使用です。 

イベントを識別してイベント サブスクライバーのコード テンプレートを生成するために、既にクライアントにイベント レコーダーが追加されており、スローされたイベントを記録して検査することが可能です。ただし多くの場合、開発者は、サブスクライブするイベントを認識しているか、先行入力/補完機能でイベントを検索し、コード コンテキストにイベント サブスクライバーを挿入する高速な方法を必要としています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL コード エディターの新しい Shift + Alt + E ショートカットを使用して、すべてのイベントのリストを呼び出します。 
![Shift+Alt+E でイベントを検索する](media/event-lookup.png "Shift+Alt+E でイベントを検索する")

先行入力を使用してイベント リストを動的に検索およびフィルタリングできます ![イベント リストに入力してコンテンツをフィルタリングする](media/event-lookup-type-ahead.png "イベントリストに入力してコンテンツをフィルタリングする")

リターン キーを押してイベント エントリを選択すると、イベントのイベント サブスクライバーがアクティブな AL コード エディター ウィンドウのカーソル位置に挿入されます。
![リスト内のイベントを選択して、カーソル位置にイベントのサブスクライバーを挿入する](media/event-subscriber-insert.png "リスト内のイベントを選択して、カーソル位置にイベントのサブスクライバーを挿入する")
<!--feature detail end -->










## <a name="see-also"></a>関連項目


<!--docs start-->
[Al Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)
<!--docs end-->


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
# <a name="look-up-events-and-insert-event-subscriber-in-code"></a><span data-ttu-id="1835c-103">イベントを検索して、コードにイベント サブスクライバーを挿入する</span><span class="sxs-lookup"><span data-stu-id="1835c-103">Look up events and insert event subscriber in code</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="1835c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1835c-104">Enabled for</span></span>    |  <span data-ttu-id="1835c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1835c-105">Public preview</span></span> | <span data-ttu-id="1835c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1835c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1835c-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="1835c-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="1835c-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="1835c-108">Feb 2020</span></span>| <span data-ttu-id="1835c-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="1835c-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1835c-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1835c-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1835c-111">拡張ベースの "カスタマイズ" の中核は、イベントとイベント サブスクライバーの使用です。</span><span class="sxs-lookup"><span data-stu-id="1835c-111">A core part of extension-based "customization" is the use of events and event subscribers.</span></span> 

<span data-ttu-id="1835c-112">イベントを識別してイベント サブスクライバーのコード テンプレートを生成するために、すでにクライアントにイベント レコーダが追加されており、スローされたイベントを記録して検査することが可能です。</span><span class="sxs-lookup"><span data-stu-id="1835c-112">To identify an event and generate an event subscriber code template, we added the Event Recorder in the client some time ago, allowing recording and inspecting of thrown events.</span></span> <span data-ttu-id="1835c-113">ただし多くの場合、開発者は、サブスクライブするイベントを認識しているか、先行入力/補完機能でイベントを検索し、コード コンテキストにイベント サブスクライバーを挿入する高速な方法を必要としています。</span><span class="sxs-lookup"><span data-stu-id="1835c-113">However, in many cases, developers are either aware of the event they want to subscribe to or want to have a fast way to search for the event (with type ahead/completion) and then insert event subscriber in code context.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1835c-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1835c-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1835c-115">AL コード エディタの新しい Shift + Alt + E ショートカットを使用して、すべてのイベントのリストを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="1835c-115">Use the new Shift+Alt+E shortcut in the AL code editor to invoke a list of all events.</span></span> <span data-ttu-id="1835c-116">先行入力を使用してイベント リストを動的に検索/フィルタリングできます。リターン キーを押してイベント エントリを選択すると、イベントのイベント サブスクライバーがアクティブな AL コード エディタ ウィンドウのカーソル位置に挿入されます。</span><span class="sxs-lookup"><span data-stu-id="1835c-116">You can use type ahead to dynamically search and filter the event list, and when pressing return to select an event entry, an event subscriber for the event will be inserted at the cursor position in the active AL code editor window.</span></span> 
<!--feature detail end -->










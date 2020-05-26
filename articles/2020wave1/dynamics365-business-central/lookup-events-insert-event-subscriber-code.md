---
title: イベントを検索して、コードにイベント サブスクライバーを挿入する
description: Visual Studio Code での AL コードの作成中にイベントをすばやく検索し、選択したイベントに対するイベント サブスクライバーをコードに挿入します。
author: relnotes
ms.reviewer: solsen
ms.date: 04/16/2020
ms.assetid: 96befc08-db1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 5e0fdfaff523b89c258f0cde751d5ed9820080b6
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293722"
---
# <a name="look-up-events-and-insert-event-subscriber-in-code"></a><span data-ttu-id="6a8c7-103">イベントを検索して、コードにイベント サブスクライバーを挿入する</span><span class="sxs-lookup"><span data-stu-id="6a8c7-103">Look up events and insert event subscriber in code</span></span>


| <span data-ttu-id="6a8c7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6a8c7-104">Enabled for</span></span>    |  <span data-ttu-id="6a8c7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6a8c7-105">Public preview</span></span> | <span data-ttu-id="6a8c7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6a8c7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6a8c7-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="6a8c7-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="6a8c7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6a8c7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6a8c7-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6a8c7-109">Feb 1, 2020</span></span>| <span data-ttu-id="6a8c7-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6a8c7-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6a8c7-111">2020 年 4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="6a8c7-111">Apr 2, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="6a8c7-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6a8c7-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6a8c7-113">拡張ベースの "カスタマイズ" の中核は、イベントとイベント サブスクライバーの使用です。</span><span class="sxs-lookup"><span data-stu-id="6a8c7-113">A core part of extension-based "customization" is the use of events and event subscribers.</span></span> 

<span data-ttu-id="6a8c7-114">イベントを識別してイベント サブスクライバーのコード テンプレートを生成するために、既にクライアントにイベント レコーダーが追加されており、スローされたイベントを記録して検査することが可能です。ただし多くの場合、開発者は、サブスクライブするイベントを認識しているか、先行入力/補完機能でイベントを検索し、コード コンテキストにイベント サブスクライバーを挿入する高速な方法を必要としています。</span><span class="sxs-lookup"><span data-stu-id="6a8c7-114">To identify an event and generate an event subscriber code template, we added the Event Recorder in the client some time ago, allowing recording and inspecting of thrown events; however, in many cases, developers are either aware of the event they want to subscribe to or want to have a fast way to search for the event (with type ahead/completion) and then insert event subscriber in code context.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6a8c7-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6a8c7-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6a8c7-116">AL コード エディターの新しい Shift + Alt + E ショートカットを使用して、すべてのイベントのリストを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="6a8c7-116">Use the new Shift+Alt+E shortcut in the AL code editor to invoke a list of all events.</span></span> 

<span data-ttu-id="6a8c7-117">![Shift+Alt+E でイベントを検索する](media/event-lookup.png "Shift+Alt+E でイベントを検索する")</span><span class="sxs-lookup"><span data-stu-id="6a8c7-117">![Look up events with Shift+Alt+E](media/event-lookup.png "Look up events with Shift+Alt+E")</span></span>

<span data-ttu-id="6a8c7-118">先行入力を使用してイベント リストを動的に検索およびフィルタリングできます。</span><span class="sxs-lookup"><span data-stu-id="6a8c7-118">You can use type ahead to dynamically search and filter the event list.</span></span>

<span data-ttu-id="6a8c7-119">![イベント リストに入力してコンテンツをフィルタリングする](media/event-lookup-type-ahead.png "イベント リストに入力してコンテンツをフィルタリングする")</span><span class="sxs-lookup"><span data-stu-id="6a8c7-119">![Type in event list to filter content](media/event-lookup-type-ahead.png "Type in event list to filter content")</span></span>

<span data-ttu-id="6a8c7-120">Enter キーを押してイベント エントリを選択すると、イベントのイベント サブスクライバーがアクティブな AL コード エディター ウィンドウのカーソル位置に挿入されます。</span><span class="sxs-lookup"><span data-stu-id="6a8c7-120">When pressing Enter to select an event entry, an event subscriber for the event will be inserted at the cursor position in the active AL code editor window.</span></span>

<span data-ttu-id="6a8c7-121">![リスト内のイベントを選択して、カーソル位置にイベントのサブスクライバーを挿入する](media/event-subscriber-insert.png "リスト内のイベントを選択して、カーソル位置にイベントのサブスクライバーを挿入する")</span><span class="sxs-lookup"><span data-stu-id="6a8c7-121">![Choose event in list to insert subscriber for event at cursor position](media/event-subscriber-insert.png "Choose event in list to insert subscriber for event at cursor position")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6a8c7-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="6a8c7-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="6a8c7-123">[イベント サブスクライバー メソッドの作成](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-subscribing-to-events#creating-an-event-subscriber-method) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6a8c7-123">[Creating an event subscriber method](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-subscribing-to-events#creating-an-event-subscriber-method) (docs)</span></span>
<!--docs end-->

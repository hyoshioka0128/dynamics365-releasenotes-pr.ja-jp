---
title: アタッチして次にデバッグ
description: サーバーにアタッチし、次にブレークポイントに達したセッションをデバッグできます。
author: relnotes
ms.reviewer: edupont
ms.date: 08/13/2019
ms.assetid: a43333b1-706d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: bb7d1c20ad319e311461366b28e4da54ad0076ad
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140724"
---
# <a name="attach-and-debug-next"></a><span data-ttu-id="9a43c-103">アタッチして次にデバッグ</span><span class="sxs-lookup"><span data-stu-id="9a43c-103">Attach and debug next</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="9a43c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9a43c-104">Enabled for</span></span>    |  <span data-ttu-id="9a43c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9a43c-105">Public preview</span></span> | <span data-ttu-id="9a43c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9a43c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9a43c-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="9a43c-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="9a43c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9a43c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9a43c-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9a43c-109">Aug 1, 2019</span></span>| <span data-ttu-id="9a43c-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="9a43c-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="9a43c-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9a43c-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9a43c-112">場合によっては、デバッグするために機能を公開して呼び出すことができない (または望ましくない) ために、代わりにセッションをサーバーにアタッチし、プロセスによってブレークポイントがトリガーされるのを待つことがあります。</span><span class="sxs-lookup"><span data-stu-id="9a43c-112">Sometimes you cannot or do not want to publish and invoke functionality to debug it, but instead attach a session to the server and await a process to trigger the breakpoint.</span></span> <span data-ttu-id="9a43c-113">アタッチして次にデバッグなら、それができます。</span><span class="sxs-lookup"><span data-stu-id="9a43c-113">With attach and debug next, you can do that.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9a43c-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9a43c-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9a43c-115">コード内にブレークポイントを設定し、オンラインまたはオンプレミスで実行中のサーバーにアタッチすると、サーバーにアタッチされている間にブレークポイントがヒットした場合、デバッガーは停止します。</span><span class="sxs-lookup"><span data-stu-id="9a43c-115">Set a breakpoint in code and attach to a running server, online or on-premises, and the debugger will break if the breakpoint is hit while it is attached to the server.</span></span>
<!--feature detail end -->












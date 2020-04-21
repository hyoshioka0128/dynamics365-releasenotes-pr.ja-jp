---
title: メッセージ バーにアクションを埋め込む
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 03/02/2020
ms.assetid: 42fd36c8-3d5c-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: 7149c9957d531dfea6512ad7bbd87af180f05e2e
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3099210"
---
# <a name="embed-actions-in-the-message-bar"></a><span data-ttu-id="860fc-102">メッセージ バーにアクションを埋め込む</span><span class="sxs-lookup"><span data-stu-id="860fc-102">Embed actions in the message bar</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="860fc-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="860fc-103">Enabled for</span></span>    |  <span data-ttu-id="860fc-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="860fc-104">Public preview</span></span> | <span data-ttu-id="860fc-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="860fc-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="860fc-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="860fc-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="860fc-107">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="860fc-107">May 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="860fc-108">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="860fc-108">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="860fc-109">バージョン 10.0.10/Platform update 34 以降、Message::AddAction() メソッドを使用して、メッセージ バーに送信されるメッセージ内にアクションを埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="860fc-109">Starting in version 10.0.10/Platform update 34, the Message::AddAction() method can be used to embed an action within a message sent to the message bar.</span></span> <span data-ttu-id="860fc-110">このメソッドは、リンク ボタンとして視覚化される、表示またはアクション メニュー項目に関連付けられた単一のアクションの追加をサポートします。</span><span class="sxs-lookup"><span data-stu-id="860fc-110">This method supports adding a single action that is associated with a display or action menu item, which is then visualized as a link button.</span></span> <span data-ttu-id="860fc-111">この API は、Dynamics AX 2012 の SysInfoAction クラスの代替として機能することを目的としています。</span><span class="sxs-lookup"><span data-stu-id="860fc-111">This API is meant to serve as a replacement for the SysInfoAction class from Dynamics AX 2012.</span></span>  
<!--feature detail end -->










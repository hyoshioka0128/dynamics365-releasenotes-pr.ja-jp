---
title: メッセージ バーにアクションを埋め込む
description: メッセージ バーのメッセージに 1 つのアクションを含めることができます。
author: relnotes
ms.reviewer: sericks
ms.date: 05/11/2020
ms.assetid: 42fd36c8-3d5c-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: 98d8a8c9473964d0a0628dda9be4f53602796768
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381794"
---
# <a name="embed-actions-in-the-message-bar"></a><span data-ttu-id="89503-103">メッセージ バーにアクションを埋め込む</span><span class="sxs-lookup"><span data-stu-id="89503-103">Embed actions in the message bar</span></span>


| <span data-ttu-id="89503-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="89503-104">Enabled for</span></span>    |  <span data-ttu-id="89503-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="89503-105">Public preview</span></span> | <span data-ttu-id="89503-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="89503-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="89503-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="89503-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="89503-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="89503-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="89503-109">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="89503-109">May 1, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="89503-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="89503-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="89503-111">バージョン 10.0.10/Platform update 34 以降、Message::AddAction() メソッドを使用して、メッセージ バーに送信されるメッセージ内にアクションを埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="89503-111">Starting in version 10.0.10/Platform update 34, the Message::AddAction() method can be used to embed an action within a message sent to the message bar.</span></span> <span data-ttu-id="89503-112">このメソッドは、リンク ボタンとして視覚化される、表示またはアクション メニュー項目に関連付けられた単一のアクションの追加をサポートします。</span><span class="sxs-lookup"><span data-stu-id="89503-112">This method supports adding a single action that is associated with a display or action menu item, which is then visualized as a link button.</span></span> <span data-ttu-id="89503-113">この API は、Dynamics AX 2012 の SysInfoAction クラスの代替として機能することを目的としています。</span><span class="sxs-lookup"><span data-stu-id="89503-113">This API is meant to serve as a replacement for the SysInfoAction class from Dynamics AX 2012.</span></span>  
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="89503-114">関連項目</span><span class="sxs-lookup"><span data-stu-id="89503-114">See also</span></span>

<!--docs start-->
<span data-ttu-id="89503-115">[メッセージング API - アクション センター、メッセージ バー、メッセージ詳細](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/user-interface/messaging-api-center-bar-details) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="89503-115">[Messaging APIs - Action center, message bar, and message details](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/user-interface/messaging-api-center-bar-details) (docs)</span></span>
<!--docs end-->

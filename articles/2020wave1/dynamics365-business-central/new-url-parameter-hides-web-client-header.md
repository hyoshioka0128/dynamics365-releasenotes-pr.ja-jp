---
title: 新しい URL パラメーターによって Web クライアントのヘッダーを非表示にする
description: URL の新しいパラメーターによってクライアントのヘッダーを非表示にする
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 06/10/2020
ms.assetid: 2f7a3732-0b6d-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: d612304fb857553c71152f4a75ffe72d11b11f98
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3487678"
---
# <a name="new-url-parameter-hides-web-client-header"></a><span data-ttu-id="3c68d-103">新しい URL パラメーターによって Web クライアントのヘッダーを非表示にする</span><span class="sxs-lookup"><span data-stu-id="3c68d-103">New URL parameter hides web client header</span></span>


| <span data-ttu-id="3c68d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3c68d-104">Enabled for</span></span>    |  <span data-ttu-id="3c68d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3c68d-105">Public preview</span></span> | <span data-ttu-id="3c68d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3c68d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3c68d-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3c68d-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3c68d-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3c68d-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3c68d-109">2020 年 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="3c68d-109">Apr 17, 2020</span></span>| <span data-ttu-id="3c68d-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3c68d-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3c68d-111">2020 年 6 月 10 日</span><span class="sxs-lookup"><span data-stu-id="3c68d-111">Jun 10, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3c68d-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3c68d-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3c68d-113">Business Central Web クライアントは、さまざまな UI 統合のニーズを満たすのに十分な柔軟性を備えています。</span><span class="sxs-lookup"><span data-stu-id="3c68d-113">The Business Central web client is flexible enough to meet a variety of UI integration needs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3c68d-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3c68d-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3c68d-115">開発者と管理者が Web クライアントで Microsoft 365 ヘッダーを非表示にできるように、Business Central にアクセスするための URL で新しい **showHeader** パラメーターがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="3c68d-115">A new **showHeader** parameter is now supported in the URL to access Business Central so that developers and administrators can hide the Microsoft 365 header from the web client.</span></span>

<span data-ttu-id="3c68d-116">このパラメーターは、次のようなさまざまな制御された統合シナリオでユーザー エクスペリエンスを向上させるために使用できます。</span><span class="sxs-lookup"><span data-stu-id="3c68d-116">This parameter can be used to improve the user experience in various controlled integration scenarios, such as:</span></span>

- <span data-ttu-id="3c68d-117">他の Web アプリケーションに Business Central Web クライアントを埋め込む。</span><span class="sxs-lookup"><span data-stu-id="3c68d-117">Embedding the Business Central web client in other web applications.</span></span>
- <span data-ttu-id="3c68d-118">画面の大部分を占めるよう意図されたクライアント コントロール アドイン用に、より多くの画面スペースを解放する。</span><span class="sxs-lookup"><span data-stu-id="3c68d-118">Freeing up more screen space for client control add-ins that are intended to occupy most of the screen.</span></span>

<span data-ttu-id="3c68d-119">このパラメーターは、より焦点を絞ったスペースを作成するために UI 内の要素を取り除く他の URL パラメーターと同様に動作します。</span><span class="sxs-lookup"><span data-stu-id="3c68d-119">This parameter behaves similarly to other URL parameters that strip away elements in the UI to create more focused space.</span></span> <span data-ttu-id="3c68d-120">ヘッダーを非表示にすると、ユーザーは、アプリ起動ツールを使用してサインアウトや別のアプリへの切り替えを行う機能など、ヘッダーを通じて公開される機能にアクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="3c68d-120">By hiding the header, users will not be able to reach any functionality that is exposed through the header, such as the ability to sign out or switch to different apps using the App Launcher.</span></span>

<span data-ttu-id="3c68d-121">![ShowHeader パラメーターが URL に適用されるときにレンダリングされる Web クライアント](media/web-client-with-showheader-parameter.png "ShowHeader パラメーターが URL に適用されるときにレンダリングされる Web クライアント")</span><span class="sxs-lookup"><span data-stu-id="3c68d-121">![The web client as rendered when the ShowHeader parameter is applied to the URL](media/web-client-with-showheader-parameter.png "The web client as rendered when the ShowHeader parameter is applied to the URL")</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="3c68d-122">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3c68d-122">Tell us what you think</span></span>
<span data-ttu-id="3c68d-123">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="3c68d-123">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3c68d-124">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3c68d-124">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="3c68d-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="3c68d-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="3c68d-126">[Web クライアントの URL](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-web-client-urls) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3c68d-126">[Web Client URL](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-web-client-urls) (docs)</span></span>
<!--docs end-->

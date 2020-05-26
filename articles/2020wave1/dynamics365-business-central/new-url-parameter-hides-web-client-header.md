---
title: 新しい URL パラメーターによって Web クライアントのヘッダーを非表示にする
description: URL の新しいパラメーターによってクライアントのヘッダーを非表示にする
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/20/2020
ms.assetid: 2f7a3732-0b6d-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: a4d15f98009da1967d4009e7fc2e67e39cbece74
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294261"
---
# <a name="new-url-parameter-hides-web-client-header"></a><span data-ttu-id="1d0f6-103">新しい URL パラメーターによって Web クライアントのヘッダーを非表示にする</span><span class="sxs-lookup"><span data-stu-id="1d0f6-103">New URL parameter hides web client header</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="1d0f6-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1d0f6-104">Enabled for</span></span>    |  <span data-ttu-id="1d0f6-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1d0f6-105">Public preview</span></span> | <span data-ttu-id="1d0f6-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1d0f6-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1d0f6-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1d0f6-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1d0f6-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1d0f6-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1d0f6-109">2020 年 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="1d0f6-109">Apr 17, 2020</span></span>| <span data-ttu-id="1d0f6-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="1d0f6-110">Jun 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1d0f6-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1d0f6-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1d0f6-112">Business Central Web クライアントは、さまざまな UI 統合のニーズを満たすのに十分な柔軟性を備えています。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-112">The Business Central web client is flexible enough to meet a variety of UI integration needs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1d0f6-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1d0f6-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1d0f6-114">開発者と管理者が Web クライアントで Office 365 ヘッダーを非表示にできるように、Business Central にアクセスするための URL で新しい **showHeader** パラメーターがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-114">A new **showHeader** parameter is now supported in the URL to access Business Central so that developers and administrators can hide the Office 365 Header from the web client.</span></span>

<span data-ttu-id="1d0f6-115">これは、次のようなさまざまな制御された統合シナリオでユーザー エクスペリエンスを向上させるために使用できます。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-115">This can be used to improve the user experience in various controlled integration scenarios, such as:</span></span>

- <span data-ttu-id="1d0f6-116">他の Web アプリケーションに Business Central Web クライアントを埋め込む。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-116">Embedding the Business Central web client in other web applications.</span></span>
- <span data-ttu-id="1d0f6-117">画面の大部分を占めるよう意図されたクライアント コントロール アドイン用に、より多くの画面スペースを解放する。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-117">Freeing up more screen space for client Control AddIns that are intended to occupy most of the screen.</span></span>

<span data-ttu-id="1d0f6-118">これは、より焦点を絞ったスペースを作成するためにUI 内の要素を取り除く他の URL パラメーターと同様に動作します。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-118">This behaves similarly to other URL parameters that strip away elements in the UI to create more focused space.</span></span> <span data-ttu-id="1d0f6-119">ヘッダーを非表示にすると、ユーザーは、アプリ起動ツールを使用してサインアウトや別のアプリへの切り替えを行う機能など、ヘッダーを通じて公開される機能にアクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-119">By hiding the header, users will not be able to reach any functionality that is exposed through the header, such as the ability to sign out or switch to different apps using the App Launcher.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="1d0f6-120">フィードバック</span><span class="sxs-lookup"><span data-stu-id="1d0f6-120">Tell us what you think</span></span>
<span data-ttu-id="1d0f6-121">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-121">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="1d0f6-122">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="1d0f6-122">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="1d0f6-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="1d0f6-123">See also</span></span>

<!--docs start-->
<span data-ttu-id="1d0f6-124">[Web クライアントの URL](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-web-client-urls) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1d0f6-124">[Web Client URL](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-web-client-urls) (docs)</span></span>
<!--docs end-->

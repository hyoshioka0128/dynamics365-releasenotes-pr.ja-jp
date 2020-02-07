---
title: ページの読み込み時間の向上
description: ページの読み込み時間の向上
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 01/15/2020
ms.assetid: c9b05388-851a-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: d55a5120bf1d49c772f9ef9672c883bc07d7a3dd
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986666"
---
# <a name="improved-load-time-for-pages"></a><span data-ttu-id="cd4b1-103">ページの読み込み時間の向上</span><span class="sxs-lookup"><span data-stu-id="cd4b1-103">Improved load time for pages</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="cd4b1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cd4b1-104">Enabled for</span></span>    |  <span data-ttu-id="cd4b1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cd4b1-105">Public preview</span></span> | <span data-ttu-id="cd4b1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cd4b1-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cd4b1-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="cd4b1-107">End users, automatically</span></span>|<span data-ttu-id="cd4b1-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="cd4b1-108">Feb 2020</span></span>| <span data-ttu-id="cd4b1-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="cd4b1-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="cd4b1-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cd4b1-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cd4b1-111">ビジネス ユーザーは、タスクを完了するためにページ間を移動するとき、ページとダイアログ ボックスがすばやく読み込まれることを期待します。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-111">When navigating across pages to complete their tasks, business users expect snappy loading of pages and dialog boxes.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cd4b1-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cd4b1-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cd4b1-113">ユーザーは、頻繁に使用するページが前より速く開くようになったことがわかります。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-113">Users will find that pages they use often now open faster.</span></span> <span data-ttu-id="cd4b1-114">技術的には、レンダリングされたページは、最初に開かれたときにキャッシュされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-114">Technically, the rendered page is now cached the first time it is opened.</span></span> <span data-ttu-id="cd4b1-115">これを行うために、ビジネス データや機密情報がユーザーのデバイスに永続化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-115">This is done without persisting any business data or sensitive information to the user's device.</span></span> <span data-ttu-id="cd4b1-116">ページへの後続のアクセスでは、データがサービスからフェッチされている間は、すぐにページがレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-116">Subsequent accesses to the page will immediately render the page while data is fetched from the service.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="cd4b1-117">フィードバック</span><span class="sxs-lookup"><span data-stu-id="cd4b1-117">Tell us what you think</span></span>
<span data-ttu-id="cd4b1-118">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-118">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="cd4b1-119">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="cd4b1-119">Use the forum at https://aka.ms/bcideas.</span></span>




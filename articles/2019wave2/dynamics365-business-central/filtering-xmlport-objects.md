---
title: XMLport オブジェクトのフィルター処理
description: XmlPort オブジェクトの要求ページをブラウザー クライアントに表示できます
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 09/02/2019
ms.assetid: 629ae289-8897-e911-a968-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: f82360dc6e4e8aa82c536f3167d67e5132c7b541
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140614"
---
# <a name="filtering-xmlport-objects"></a><span data-ttu-id="3dedf-103">XMLport オブジェクトのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="3dedf-103">Filtering XmlPort Objects</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="3dedf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3dedf-104">Enabled for</span></span>    |  <span data-ttu-id="3dedf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3dedf-105">Public preview</span></span> | <span data-ttu-id="3dedf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3dedf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3dedf-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3dedf-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="3dedf-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3dedf-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3dedf-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3dedf-109">Aug 1, 2019</span></span>| <span data-ttu-id="3dedf-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="3dedf-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="3dedf-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3dedf-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3dedf-112">多くの場合、ビジネス データベースが大きくなると、Business Central からエクスポートまたは Business Central にインポートするデータをより高度に制御する必要性が出てきます。</span><span class="sxs-lookup"><span data-stu-id="3dedf-112">As your business database grows, you often need a higher degree of control over the data that you export out of or into Business Central.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3dedf-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3dedf-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3dedf-114">開発者は、XmlPort オブジェクトの UseRequestPage プロパティを True に設定して、ユーザーがブラウザー クライアントに要求ページを表示できるようにします。</span><span class="sxs-lookup"><span data-stu-id="3dedf-114">Developers can set the UseRequestPage property to True on an XmlPort object so that users will see a request page in the browser client.</span></span> <span data-ttu-id="3dedf-115">その後、日付範囲、式、フィルター トークンなどの強力なフィルター機能を利用して、ソース テーブルの任意のフィールドをフィルター処理することで、潜在的にエクスポートされたデータを必要なレコードにまで正確に削減できます。</span><span class="sxs-lookup"><span data-stu-id="3dedf-115">Users can then filter on any fields from the source table and potentially reduce the exported data to precisely the records they want, taking advantage of powerful filtering capabilities such as date ranges, expressions, and filter tokens.</span></span>
<!--feature detail end -->








## <a name="tell-us-what-you-think"></a><span data-ttu-id="3dedf-116">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3dedf-116">Tell us what you think</span></span>
<span data-ttu-id="3dedf-117">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="3dedf-117">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3dedf-118">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3dedf-118">Use the forum at https://aka.ms/bcideas.</span></span>




---
title: XmlPort オブジェクトのフィルター処理
description: XmlPort オブジェクトの要求ページをブラウザー クライアントに表示できます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 03/26/2020
ms.assetid: 629ae289-8897-e911-a968-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 74505d4ce968d7d26e9778697f114580d33a6dc5
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320547"
---
# <a name="filtering-xmlport-objects"></a><span data-ttu-id="bed04-103">XmlPort オブジェクトのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="bed04-103">Filtering XmlPort objects</span></span>


| <span data-ttu-id="bed04-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bed04-104">Enabled for</span></span>    |  <span data-ttu-id="bed04-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bed04-105">Public preview</span></span> | <span data-ttu-id="bed04-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bed04-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bed04-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="bed04-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="bed04-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bed04-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bed04-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bed04-109">Aug 1, 2019</span></span>| <span data-ttu-id="bed04-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bed04-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bed04-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bed04-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="bed04-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bed04-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bed04-113">多くの場合、ビジネス データベースが大きくなると、Business Central からエクスポートまたは Business Central にインポートするデータをより高度に制御する必要性が出てきます。</span><span class="sxs-lookup"><span data-stu-id="bed04-113">As your business database grows, you often need a higher degree of control over the data that you export out of or into Business Central.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bed04-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bed04-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bed04-115">開発者は、XmlPort オブジェクトの UseRequestPage プロパティを True に設定して、ユーザーがブラウザー クライアントに要求ページを表示できるようにします。</span><span class="sxs-lookup"><span data-stu-id="bed04-115">Developers can set the UseRequestPage property to True on an XmlPort object so that users will see a request page in the browser client.</span></span> <span data-ttu-id="bed04-116">その後、日付範囲、式、フィルター トークンなどの強力なフィルター機能を利用して、ソース テーブルの任意のフィールドをフィルター処理することで、潜在的にエクスポートされたデータを必要なレコードにまで正確に削減できます。</span><span class="sxs-lookup"><span data-stu-id="bed04-116">Users can then filter on any fields from the source table and potentially reduce the exported data to precisely the records they want, taking advantage of powerful filtering capabilities such as date ranges, expressions, and filter tokens.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="bed04-117">フィードバック</span><span class="sxs-lookup"><span data-stu-id="bed04-117">Tell us what you think</span></span>
<span data-ttu-id="bed04-118">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="bed04-118">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="bed04-119">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="bed04-119">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="bed04-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="bed04-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="bed04-121">[レポート、バッチ ジョブ、XMLport の操作](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="bed04-121">[Working with Reports, Batch Jobs, and XMLports](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (docs)</span></span>
<!--docs end-->

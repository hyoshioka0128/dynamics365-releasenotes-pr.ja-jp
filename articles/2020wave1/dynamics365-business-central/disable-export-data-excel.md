---
title: Excel へのデータのエクスポートを無効にする
description: Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 33e8c1aa-d1f5-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 685dcc04afefdb7dcdc25839267726e85399a762
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232926"
---
# <a name="disable-export-of-data-to-excel"></a><span data-ttu-id="809ce-103">Excel へのデータのエクスポートを無効にする</span><span class="sxs-lookup"><span data-stu-id="809ce-103">Disable export of data to Excel</span></span>


| <span data-ttu-id="809ce-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="809ce-104">Enabled for</span></span>    |  <span data-ttu-id="809ce-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="809ce-105">Public preview</span></span> | <span data-ttu-id="809ce-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="809ce-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="809ce-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="809ce-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="809ce-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="809ce-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="809ce-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="809ce-109">Feb 1, 2020</span></span>| <span data-ttu-id="809ce-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="809ce-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="809ce-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="809ce-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="809ce-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="809ce-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="809ce-113">**Excel で編集**および **Excel で開く**アクションを使用すると、ユーザーは Business Central データを含む Excel スプレッドシートをすばやく取得して、Excel でさらに処理することができます。ただし、一部の組織には、制御と監査が難しくなる Excel へのデータ セットの配置を制限するデータ管理ルールがあります。</span><span class="sxs-lookup"><span data-stu-id="809ce-113">With the **Edit in Excel** and **Open in Excel** actions, users can quickly get an Excel spreadsheet with Business Central data for further processing in Excel; however, some organizations have data control rules with restrictions on having data sets in Excel where it is more difficult to control and audit.</span></span> <span data-ttu-id="809ce-114">新機能では、Excel にデータをエクスポートできるユーザーを管理者が指定できるようになりました。これにより、組織においてデータをより厳密に制御できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="809ce-114">Administrators can now specify which users are allowed to export data to Excel, which gives the organization stricter control over data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="809ce-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="809ce-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="809ce-116">Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="809ce-116">Business Central administrators have the option to disable features that allow users to export data to Excel.</span></span> <span data-ttu-id="809ce-117">Business Central からデータをエクスポートする機能は、**D365 Excel Export Action** という新しいアクセス許可セットによって制御されます。</span><span class="sxs-lookup"><span data-stu-id="809ce-117">The ability to export data from Business Central is controlled by a new **D365 Excel Export Action** permission set.</span></span> <span data-ttu-id="809ce-118">特定のユーザーのアクセス許可が削除された場合、そのユーザーは、アプリケーションのどのページでも、**Excel で編集**および **Excel で開く**アクションを使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="809ce-118">If the permission is removed for a specific user, then the **Edit in Excel** and **Open in Excel** actions are no longer available to the user on any pages in the application.</span></span>

### <a name="try-it-now"></a><span data-ttu-id="809ce-119">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="809ce-119">Try it now</span></span>
<span data-ttu-id="809ce-120">[https://businesscentral.dynamics.com/?page=9802](https://businesscentral.dynamics.com/?page=9802) でオンライン環境にログインして、アクセス許可セットの一覧で探してください。</span><span class="sxs-lookup"><span data-stu-id="809ce-120">Find it in the list of permission sets by signing into your online environment at [https://businesscentral.dynamics.com/?page=9802](https://businesscentral.dynamics.com/?page=9802).</span></span>  
<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="809ce-121">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="809ce-121">Thank you for your idea</span></span>
<span data-ttu-id="809ce-122">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="809ce-122">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c).</span></span> <span data-ttu-id="809ce-123">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="809ce-123">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="809ce-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="809ce-124">See also</span></span>


<!--docs start-->
<span data-ttu-id="809ce-125">[Excel での表示と編集](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="809ce-125">[Viewing and Editing in Excel](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (docs)</span></span>
<!--docs end-->


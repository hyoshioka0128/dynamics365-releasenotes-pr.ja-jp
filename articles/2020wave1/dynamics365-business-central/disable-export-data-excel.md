---
title: Excel へのデータのエクスポートを無効にする
description: Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 05/05/2020
ms.assetid: 33e8c1aa-d1f5-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: d22dce96d62b8abe78786d4ff6b85bf992205dba
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349844"
---
# <a name="disable-export-of-data-to-excel"></a><span data-ttu-id="95d40-103">Excel へのデータのエクスポートを無効にする</span><span class="sxs-lookup"><span data-stu-id="95d40-103">Disable export of data to Excel</span></span>


| <span data-ttu-id="95d40-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="95d40-104">Enabled for</span></span>    |  <span data-ttu-id="95d40-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="95d40-105">Public preview</span></span> | <span data-ttu-id="95d40-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="95d40-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="95d40-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="95d40-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="95d40-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="95d40-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="95d40-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="95d40-109">Feb 1, 2020</span></span>| <span data-ttu-id="95d40-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="95d40-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="95d40-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="95d40-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="95d40-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="95d40-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="95d40-113">Excel で編集および Excel で開くアクションを使用すると、ユーザーは Business Central データを含んだ Excel スプレッドシートをすばやく取得し、Excel でさらなる処理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="95d40-113">With the Edit in Excel and Open in Excel actions, users can quickly get an Excel spreadsheet with Business Central data for further processing in Excel.</span></span> <span data-ttu-id="95d40-114">ただし、組織によっては、Excel でのデータ セットの保持に制限を設けたデータ制御規則があります。その場合は、制御や監査が通常よりも困難になります。</span><span class="sxs-lookup"><span data-stu-id="95d40-114">However, some organizations have data control rules with restrictions on having data sets in Excel, where it is more difficult to control and audit.</span></span> <span data-ttu-id="95d40-115">新機能では、Excel にデータをエクスポートできるユーザーを管理者が指定できるようになりました。これにより、組織においてデータをより厳密に制御できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="95d40-115">Administrators can now specify which users are allowed to export data to Excel, which gives the organization stricter control over data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="95d40-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="95d40-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="95d40-117">Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="95d40-117">Business Central administrators have the option to disable features that allow users to export data to Excel.</span></span> <span data-ttu-id="95d40-118">Business Central からデータをエクスポートする機能は、**D365 Excel Export Action** という新しいアクセス許可セットと ID 6110 のシステム アクセス許可によって制御されます。</span><span class="sxs-lookup"><span data-stu-id="95d40-118">The ability to export data from Business Central is controlled by a new **D365 Excel Export Action** permission set and system permission with ID 6110.</span></span> <span data-ttu-id="95d40-119">特定のユーザーのアクセス許可が削除された場合、そのユーザーは、アプリケーションのどのページでも、**Excel で編集**および **Excel で開く**アクションを使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="95d40-119">If the permission is removed for a specific user, then the **Edit in Excel** and **Open in Excel** actions are no longer available to the user on any pages in the application.</span></span>

### <a name="upgrading-to-business-central-2020-release-wave-1"></a><span data-ttu-id="95d40-120">Business Central 2020 リリース ウェーブ 1 へのアップグレード</span><span class="sxs-lookup"><span data-stu-id="95d40-120">Upgrading to Business Central 2020 release wave 1</span></span>

<span data-ttu-id="95d40-121">以前のバージョンの Business Central からアップグレードするお客様は、データを Excel にエクスポートできなくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="95d40-121">In some cases, customers upgrading from an earlier version of Business Central might lose the ability to export data to Excel.</span></span> <span data-ttu-id="95d40-122">2020 年リリース ウェーブ 1 にアップグレードした後、管理者は、関連するユーザー グループとアクセス許可セットに **D365 Excel Export Action** アクセス許可セットまたはシステム アクセス許可 6110 が含まれていることを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="95d40-122">After upgrading to 2020 release wave 1, administrators should ensure that the relevant user groups and permission sets include either the **D365 Excel Export Action** permission set or the system permission 6110.</span></span>  

### <a name="try-it-now"></a><span data-ttu-id="95d40-123">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="95d40-123">Try it now</span></span>
<span data-ttu-id="95d40-124">[https://businesscentral.dynamics.com/?page=9802](https://businesscentral.dynamics.com/?page=9802) でオンライン環境にログインして、アクセス許可セットの一覧で探してください。</span><span class="sxs-lookup"><span data-stu-id="95d40-124">Find it in the list of permission sets by signing in to your online environment at [https://businesscentral.dynamics.com/?page=9802](https://businesscentral.dynamics.com/?page=9802).</span></span>  

<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="95d40-125">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="95d40-125">Thank you for your idea</span></span>
<span data-ttu-id="95d40-126">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="95d40-126">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c).</span></span> <span data-ttu-id="95d40-127">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="95d40-127">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="95d40-128">関連項目</span><span class="sxs-lookup"><span data-stu-id="95d40-128">See also</span></span>

<!--docs start-->
<span data-ttu-id="95d40-129">[Excel での表示や編集を Business Central から実行する](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="95d40-129">[Viewing and Editing in Excel from Business Central](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (docs)</span></span>
<!--docs end-->

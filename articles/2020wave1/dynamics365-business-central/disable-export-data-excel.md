---
title: Excel へのデータのエクスポートを無効にする
description: Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 12/10/2019
ms.assetid: 33e8c1aa-d1f5-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 7298051244f5f8a519dff236b18fbdc7e5436a0e
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986829"
---
# <a name="disable-export-of-data-to-excel"></a><span data-ttu-id="0d884-103">Excel へのデータのエクスポートを無効にする</span><span class="sxs-lookup"><span data-stu-id="0d884-103">Disable export of data to Excel</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="0d884-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0d884-104">Enabled for</span></span>    |  <span data-ttu-id="0d884-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0d884-105">Public preview</span></span> | <span data-ttu-id="0d884-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0d884-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0d884-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="0d884-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="0d884-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="0d884-108">Feb 2020</span></span>| <span data-ttu-id="0d884-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="0d884-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0d884-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0d884-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0d884-111">**Excel で編集** および **Excel で開く** アクションを使用すると、ユーザーは Business Central データを含んだ Excel スプレッドシートをすばやく取得し、Excel でさらなる処理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="0d884-111">With the **Edit in Excel** and **Open in Excel** actions, users can quickly get an Excel spreadsheet with Business Central data for further processing in Excel.</span></span> <span data-ttu-id="0d884-112">ただし、組織によっては、Excel でのデータ セットの保持に制限を設けたデータ制御規則があります。その場合は、制御や監査が通常よりも困難になります。</span><span class="sxs-lookup"><span data-stu-id="0d884-112">However, some organizations have data control rules with restrictions on having data sets in Excel, where it is more difficult to control and audit.</span></span> <span data-ttu-id="0d884-113">新機能では、Excel にデータをエクスポートできるユーザーを管理者が指定できるようになりました。これにより、組織においてデータをより厳密に制御できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d884-113">Administrators can now specify which users are allowed to export data to Excel, which gives the organization stricter control over data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0d884-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0d884-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0d884-115">Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d884-115">Business Central administrators have the option to disable features that allow users to export data to Excel.</span></span> <span data-ttu-id="0d884-116">Business Central からデータをエクスポートする機能は、**D365 EXCEL EXPORT** という新しいアクセス許可セットによって制御されます。</span><span class="sxs-lookup"><span data-stu-id="0d884-116">The ability to export data from Business Central is controlled by a new **D365 EXCEL EXPORT** permission set.</span></span> <span data-ttu-id="0d884-117">特定のユーザーのアクセス許可が削除された場合、そのユーザーは、アプリケーションのどのページでも、**Excel で編集** および **Excel で開く** アクションを使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="0d884-117">If the permission is removed for a specific user, then the **Edit in Excel** and **Open in Excel** actions are no longer available to the user on any pages in the application.</span></span>
<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="0d884-118">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="0d884-118">Thank you for your idea</span></span>
<span data-ttu-id="0d884-119">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="0d884-119">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c).</span></span> <span data-ttu-id="0d884-120">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="0d884-120">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

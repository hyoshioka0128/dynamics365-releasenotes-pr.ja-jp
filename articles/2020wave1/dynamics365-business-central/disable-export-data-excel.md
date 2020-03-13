---
title: Excel へのデータのエクスポートを無効にする
description: Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 02/03/2020
ms.assetid: 33e8c1aa-d1f5-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ceea8c1b46c88b4f2124666bd0b851b2ed4928cd
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031893"
---
# <a name="disable-export-of-data-to-excel"></a><span data-ttu-id="dbfcf-103">Excel へのデータのエクスポートを無効にする</span><span class="sxs-lookup"><span data-stu-id="dbfcf-103">Disable export of data to Excel</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="dbfcf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="dbfcf-104">Enabled for</span></span>    |  <span data-ttu-id="dbfcf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="dbfcf-105">Public preview</span></span> | <span data-ttu-id="dbfcf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="dbfcf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="dbfcf-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="dbfcf-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="dbfcf-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="dbfcf-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="dbfcf-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="dbfcf-109">Feb 1, 2020</span></span>| <span data-ttu-id="dbfcf-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="dbfcf-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="dbfcf-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="dbfcf-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="dbfcf-112">**Excel で編集** および **Excel で開く** アクションを使用すると、ユーザーは Business Central データを含んだ Excel スプレッドシートをすばやく取得し、Excel でさらなる処理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-112">With the **Edit in Excel** and **Open in Excel** actions, users can quickly get an Excel spreadsheet with Business Central data for further processing in Excel.</span></span> <span data-ttu-id="dbfcf-113">ただし、組織によっては、Excel でのデータ セットの保持に制限を設けたデータ制御規則があります。その場合は、制御や監査が通常よりも困難になります。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-113">However, some organizations have data control rules with restrictions on having data sets in Excel, where it is more difficult to control and audit.</span></span> <span data-ttu-id="dbfcf-114">新機能では、Excel にデータをエクスポートできるユーザーを管理者が指定できるようになりました。これにより、組織においてデータをより厳密に制御できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-114">Administrators can now specify which users are allowed to export data to Excel, which gives the organization stricter control over data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="dbfcf-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="dbfcf-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="dbfcf-116">Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-116">Business Central administrators have the option to disable features that allow users to export data to Excel.</span></span> <span data-ttu-id="dbfcf-117">Business Central からデータをエクスポートする機能は、**D365 EXCEL EXPORT** という新しいアクセス許可セットによって制御されます。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-117">The ability to export data from Business Central is controlled by a new **D365 EXCEL EXPORT** permission set.</span></span> <span data-ttu-id="dbfcf-118">特定のユーザーのアクセス許可が削除された場合、そのユーザーは、アプリケーションのどのページでも、**Excel で編集** および **Excel で開く** アクションを使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-118">If the permission is removed for a specific user, then the **Edit in Excel** and **Open in Excel** actions are no longer available to the user on any pages in the application.</span></span>
<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="dbfcf-119">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="dbfcf-119">Thank you for your idea</span></span>
<span data-ttu-id="dbfcf-120">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-120">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c).</span></span> <span data-ttu-id="dbfcf-121">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="dbfcf-121">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="dbfcf-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="dbfcf-122">See also</span></span>

<span data-ttu-id="dbfcf-123">[Excel での表示と編集](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="dbfcf-123">[Viewing and Editing in Excel](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (docs)</span></span>

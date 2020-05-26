---
title: サンドボックス環境ピッカー
description: サンドボックス環境ピッカーで、サンドボックス環境を簡単に切り替えることができます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/27/2020
ms.assetid: 1399b215-4086-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: b6117283b23d73bd378dc7967cad02e2db5149c6
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350930"
---
# <a name="sandbox-environment-picker"></a><span data-ttu-id="4d2a1-103">サンドボックス環境ピッカー</span><span class="sxs-lookup"><span data-stu-id="4d2a1-103">Sandbox environment picker</span></span>


| <span data-ttu-id="4d2a1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4d2a1-104">Enabled for</span></span>    |  <span data-ttu-id="4d2a1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4d2a1-105">Public preview</span></span> | <span data-ttu-id="4d2a1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4d2a1-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4d2a1-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="4d2a1-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="4d2a1-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4d2a1-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4d2a1-109">2020 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="4d2a1-109">Apr 23, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="4d2a1-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4d2a1-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4d2a1-111">管理者、開発者、コンサルタント、パワー ユーザーなど、サンドボックス環境を使用する組織のロールは、しばしば、異なるデータやカスタマイズを含んでいたり新しいビジネス プロセスの展開の異なる段階にあるさまざまなテスト環境を切り替える必要があります。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-111">Any organizational role that uses sandbox environments, such as administrators, developers, consultants, or power users, often has to switch between different test environments that contain different data, customizations, or are at different stages of rolling out a new business process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4d2a1-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4d2a1-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4d2a1-113">サンドボックス環境ピッカーを使用すると、組織で利用可能なすべてのサンドボックス環境から選択することができます。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-113">With the sandbox environment picker, you can choose from all sandbox environments that are available in your organization.</span></span> <span data-ttu-id="4d2a1-114">このピッカーは複数のサンドボックスがプロビジョニングされている場合にのみ表示され、Dynamics 365 ホーム ポータルまたはアプリ起動ツールの Business Central サンドボックス タイルから移動したときに表示されます。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-114">The picker will only be displayed if multiple sandboxes have been provisioned and displays when you navigate from the Business Central Sandbox tile in the Dynamics 365 Home portal or in the App Launcher.</span></span>

<span data-ttu-id="4d2a1-115">![ユーザーはサンドボックス ピッカーを使用して利用可能なサンドボックスから選択できます](media/sandbox-picker-3000x1878.png "ユーザーはサンドボックス ピッカーを使用して利用可能なサンドボックスから選択できます")</span><span class="sxs-lookup"><span data-stu-id="4d2a1-115">![The sandbox picker allows users to choose between their available sandboxes](media/sandbox-picker-3000x1878.png "The sandbox picker allows users to choose between their available sandboxes")</span></span>

<span data-ttu-id="4d2a1-116">別のサンドボックス環境に切り替えるには、アプリ起動ツールを開いて Dynamics 365 タイルを選択してから、Business Central サンドボックス タイルを選択します。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-116">To switch from one sandbox environment to another, open the App Launcher, choose the Dynamics 365 tile, and then choose the Business Central Sandbox tile.</span></span> <span data-ttu-id="4d2a1-117">利用可能なサンドボックスがピッカーに表示されます。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-117">The picker will display the available sandboxes.</span></span>

### <a name="try-it-out"></a><span data-ttu-id="4d2a1-118">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="4d2a1-118">Try it out</span></span>
<span data-ttu-id="4d2a1-119">組織に既に複数のサンドボックス環境がある場合は、[Business Central アカウント](https://businesscentral.dynamics.com?sandbox=true)にサインインしてピッカーをお試しください。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-119">If your organization already has multiple sandbox environments, try the picker by signing in to [your Business Central account](https://businesscentral.dynamics.com?sandbox=true).</span></span>  

<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="4d2a1-120">フィードバック</span><span class="sxs-lookup"><span data-stu-id="4d2a1-120">Tell us what you think</span></span>
<span data-ttu-id="4d2a1-121">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-121">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="4d2a1-122">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="4d2a1-122">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="4d2a1-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="4d2a1-123">See also</span></span>

<!--docs start-->
<span data-ttu-id="4d2a1-124">[サンドボックス環境](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/environment-types#sandbox-environments) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="4d2a1-124">[Sandbox environments](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/environment-types#sandbox-environments) (docs)</span></span>
<!--docs end-->

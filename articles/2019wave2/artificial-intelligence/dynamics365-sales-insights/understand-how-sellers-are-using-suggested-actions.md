---
title: 販売担当者が推奨アクションをどのように使用しているかを理解する
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 09/16/2019
ms.assetid: c0c7ba08-f3d4-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: 3bef1f8fda2b6bb782256e9f2f361bc4621762d6
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143890"
---
# <a name="understand-how-sellers-are-using-suggested-actions"></a><span data-ttu-id="63a47-102">販売担当者が推奨アクションをどのように使用しているかを理解する</span><span class="sxs-lookup"><span data-stu-id="63a47-102">Understand how sellers are using suggested actions</span></span>
<span data-ttu-id="63a47-103">[!include[artificial-intelligence/dynamics365-sales-insights バナー](../includes/artificial-intelligence/dynamics365-sales-insights.md)</span><span class="sxs-lookup"><span data-stu-id="63a47-103">[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)</span></span>

| <span data-ttu-id="63a47-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="63a47-104">Enabled for</span></span>    |  <span data-ttu-id="63a47-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="63a47-105">Public preview</span></span> | <span data-ttu-id="63a47-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="63a47-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="63a47-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="63a47-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="63a47-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="63a47-108">Oct 2019</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="63a47-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="63a47-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="63a47-110">販売担当者は忙しく、多数の顧客と幅広い販売資料を追跡する必要があります。</span><span class="sxs-lookup"><span data-stu-id="63a47-110">Sellers are busy and need to keep track of numerous customers and a wide range of sales materials.</span></span> <span data-ttu-id="63a47-111">また、組織は、収益を最大化するための資料とガイダンスを作成するために多大な時間とリソースを投資しています。</span><span class="sxs-lookup"><span data-stu-id="63a47-111">Organizations also invest significant time and resources producing materials and guidance to maximizes revenue.</span></span> <span data-ttu-id="63a47-112">販売担当者に適切なコンテキストで適切な情報を提供すると、販売資料を確実に活用できるようになり、ROI の最大化と販売プロセスの改善に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="63a47-112">Giving sellers the right information in the right context can help ensure they leverage their sales materials, which helps to maximize ROI and improves the selling process.</span></span> 

<span data-ttu-id="63a47-113">マイクロソフトでは販売組織に権限を与えているため、Dynamics 365 Assistant を介して販売担当者に配信される推奨アクションをフロー内に作成でき、販売担当者がどこにいても会うことができます。</span><span class="sxs-lookup"><span data-stu-id="63a47-113">We're empowering sales organizations so you can create suggested actions in the flow, delivered to sellers via the Dynamics 365 Assistant, meeting sellers wherever they are.</span></span> <span data-ttu-id="63a47-114">これにより、最も適切な情報が確実にプロモートされ、不必要な注意散漫を避けることができます。</span><span class="sxs-lookup"><span data-stu-id="63a47-114">This will help to ensure the most pertient information is promoted and to avoid unnecessary distractions.</span></span> <span data-ttu-id="63a47-115">マイクロソフトでは、推奨アクションの使用と正常性を最大化し、販売ガイダンスの影響を把握するのに役立つ基準を提供しています。</span><span class="sxs-lookup"><span data-stu-id="63a47-115">We're offering measures to help maximize the usage and health of suggested actions and to help you understand the impact of sales guidance.</span></span> <span data-ttu-id="63a47-116">これらの基準は、どの販売資料が使用されているかと、それらが販売担当者にとって有用であるかどうかを強調し、推奨アクションが、よりターゲットを絞って適切に優先順位付けされた、影響力を持ったものになるようにします。</span><span class="sxs-lookup"><span data-stu-id="63a47-116">These measures highlight which sales materials are used and whether they are useful for sellers, ensuring suggested actions are more targeted, better prioritized, and drive impact.</span></span>

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="63a47-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="63a47-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="63a47-118">**推奨アクションの有用性を理解する**: インサイト カードの有用性を理解するには、各推奨の使用方法を理解する必要があります。</span><span class="sxs-lookup"><span data-stu-id="63a47-118">**Understand the usefulness of a suggested action**: To understand the usefulness of an insight card, organizations need to understand how each suggestion is used.</span></span> <span data-ttu-id="63a47-119">各推奨アクションの基準には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="63a47-119">Measures for each suggested action includes:</span></span>
   - <span data-ttu-id="63a47-120">推奨アクションが表示された頻度と販売担当者数</span><span class="sxs-lookup"><span data-stu-id="63a47-120">How often was a suggested action shown, and to how many sellers?</span></span>
   - <span data-ttu-id="63a47-121">販売担当者が推奨アクションと対話した頻度と対話の内容</span><span class="sxs-lookup"><span data-stu-id="63a47-121">How often did sellers interact with a suggested action and what was the interaction?</span></span>
   - <span data-ttu-id="63a47-122">専用ボタンを介して肯定的または否定的なフィードバックを行った販売担当者数</span><span class="sxs-lookup"><span data-stu-id="63a47-122">How many sellers gave positive or negative feedback via dedicated buttons?</span></span>
   
- <span data-ttu-id="63a47-123">**基礎となるロジックの正常性を理解する**: 推奨アクションが適切に機能しているかどうかを理解するには、組織がコンテキストとフローを理解する必要があります。</span><span class="sxs-lookup"><span data-stu-id="63a47-123">**Understand the health of the underlying logic**: To understand whether a suggested action is working properly, organizations need to understand the context and flow.</span></span> <span data-ttu-id="63a47-124">推奨の正常性の基準には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="63a47-124">Measures for suggestion health include:</span></span>
   - <span data-ttu-id="63a47-125">基礎となるフローの名前。</span><span class="sxs-lookup"><span data-stu-id="63a47-125">Name of the underlying flow</span></span>
   - <span data-ttu-id="63a47-126">フローが最後に実行された時刻と実行が成功したかどうか</span><span class="sxs-lookup"><span data-stu-id="63a47-126">Last time the flow was executed and if the execution was successful</span></span> 
   - <span data-ttu-id="63a47-127">フローが推奨アクションの作成につながったかどうかの表示。この情報に簡単にアクセスできるようにするために、正常性情報はスタジオ内のインサイトカードの管理タブの一部としても表示されます。</span><span class="sxs-lookup"><span data-stu-id="63a47-127">Indication whether the flow resulted in the creation of a suggested action To ensure this information is easy to access, health information is also shown as part of the manage insight-cards tab within the studio.</span></span>
<!--feature detail end -->


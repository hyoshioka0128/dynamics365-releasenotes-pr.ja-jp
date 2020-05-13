---
title: 販売担当者が推奨アクションをどのように使用しているかを理解する
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 03/26/2020
ms.assetid: c0c7ba08-f3d4-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: nataln
dynamics365pdf: true
ms.openlocfilehash: 7b40bb4dc0702fa69a09d90b18bf36c0a9e84e2d
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3319645"
---
# <a name="understand-how-sellers-are-using-suggested-actions"></a><span data-ttu-id="ee12b-102">販売担当者が推奨アクションをどのように使用しているかを理解する</span><span class="sxs-lookup"><span data-stu-id="ee12b-102">Understand how sellers are using suggested actions</span></span>


| <span data-ttu-id="ee12b-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="ee12b-103">Enabled for</span></span>    |  <span data-ttu-id="ee12b-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ee12b-104">Public preview</span></span> | <span data-ttu-id="ee12b-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="ee12b-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ee12b-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ee12b-106">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="ee12b-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ee12b-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ee12b-108">2020 年 1 月 18 日</span><span class="sxs-lookup"><span data-stu-id="ee12b-108">Jan 18, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ee12b-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ee12b-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ee12b-110">販売担当者は忙しく、多数の顧客と幅広い販売資料を追跡する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ee12b-110">Sellers are busy and need to keep track of numerous customers and a wide range of sales materials.</span></span> <span data-ttu-id="ee12b-111">また、組織は、収益を最大化するための資料とガイダンスを作成するために多大な時間とリソースを投資しています。</span><span class="sxs-lookup"><span data-stu-id="ee12b-111">Organizations also invest significant time and resources producing materials and guidance to maximize revenue.</span></span> <span data-ttu-id="ee12b-112">販売担当者に適切なコンテキストで適切な情報を提供すると、販売資料を確実に活用できるようになり、ROI の最大化と販売プロセスの改善に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="ee12b-112">Giving sellers the right information in the right context can help ensure they leverage their sales materials, which helps to maximize ROI and improves the selling process.</span></span> 

<span data-ttu-id="ee12b-113">マイクロソフトでは販売組織に権限を与えているため、Assistant を介して販売担当者に配信される推奨アクションをフロー内に作成でき、販売担当者がどこにいても会うことができます。</span><span class="sxs-lookup"><span data-stu-id="ee12b-113">We're empowering sales organizations so you can create suggested actions in the flow, delivered to sellers via Assistant, meeting sellers wherever they are.</span></span> <span data-ttu-id="ee12b-114">これにより、最も適切な情報が確実にプロモートされ、不必要な注意散漫を避けることができます。</span><span class="sxs-lookup"><span data-stu-id="ee12b-114">This will help to ensure the most pertinent information is promoted and to avoid unnecessary distractions.</span></span> <span data-ttu-id="ee12b-115">マイクロソフトでは、推奨アクションの使用と正常性を最大化し、販売ガイダンスの影響を把握するのに役立つ基準を提供しています。</span><span class="sxs-lookup"><span data-stu-id="ee12b-115">We're offering measures to help maximize the usage and health of suggested actions and to help you understand the impact of sales guidance.</span></span> <span data-ttu-id="ee12b-116">これらの基準は、どの販売資料が使用されているかと、それらが販売担当者にとって有用であるかどうかを強調し、推奨アクションが、よりターゲットを絞って適切に優先順位付けされた、影響力を持ったものになるようにします。</span><span class="sxs-lookup"><span data-stu-id="ee12b-116">These measures highlight which sales materials are used and whether they are useful for sellers, ensuring suggested actions are more targeted, better prioritized, and drive impact.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ee12b-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ee12b-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ee12b-118">**推奨アクションの有用性を理解する**: 分析情報カードの有用性を理解するには、各推奨の使用方法を理解する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ee12b-118">**Understand the usefulness of a suggested action**: To understand the usefulness of an insight card, organizations need to understand how each suggestion is used.</span></span> <span data-ttu-id="ee12b-119">各推奨アクションの基準には以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="ee12b-119">Measures for each suggested action include:</span></span>

- <span data-ttu-id="ee12b-120">推奨アクションが表示された頻度と販売担当者数</span><span class="sxs-lookup"><span data-stu-id="ee12b-120">How often was a suggested action shown, and to how many sellers?</span></span>
- <span data-ttu-id="ee12b-121">販売担当者が推奨アクションと対話した頻度と対話の内容</span><span class="sxs-lookup"><span data-stu-id="ee12b-121">How often did sellers interact with a suggested action and what was the interaction?</span></span>
- <span data-ttu-id="ee12b-122">専用ボタンを介して肯定的または否定的なフィードバックを行った販売担当者数</span><span class="sxs-lookup"><span data-stu-id="ee12b-122">How many sellers gave positive or negative feedback via dedicated buttons?</span></span>
   
<span data-ttu-id="ee12b-123">この情報に簡単にアクセスできるようにするために、正常性情報はスタジオ内の分析情報カードの管理タブの一部としても表示されます。</span><span class="sxs-lookup"><span data-stu-id="ee12b-123">To ensure this information is easy to access, health information is also shown as part of the manage insight-cards tab within the studio.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ee12b-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="ee12b-124">See also</span></span>

<!--docs start-->
<span data-ttu-id="ee12b-125">[カードの使用状況の指標を表示する](https://docs.microsoft.com/dynamics365/ai/sales/edit-insight-cards#view-card-usage-metrics) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ee12b-125">[View card usage metrics](https://docs.microsoft.com/dynamics365/ai/sales/edit-insight-cards#view-card-usage-metrics) (docs)</span></span>
<!--docs end-->

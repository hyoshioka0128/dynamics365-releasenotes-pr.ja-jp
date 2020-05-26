---
title: Field Service の検査
description: フィールド サービス技術者がサービス ワークフローの一部として検査を実行およびキャプチャする機能。
author: relnotes
ms.reviewer: krbjoran
ms.date: 05/04/2020
ms.assetid: c088db1a-ea0b-ea11-a811-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: nehasg
dynamics365pdf: true
ms.openlocfilehash: 61228757994c0d8cac71d5c11e09a63a66df87b0
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350339"
---
# <a name="field-service-inspections"></a><span data-ttu-id="ad864-103">Field Service の検査</span><span class="sxs-lookup"><span data-stu-id="ad864-103">Field Service inspections</span></span>


| <span data-ttu-id="ad864-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ad864-104">Enabled for</span></span>    |  <span data-ttu-id="ad864-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ad864-105">Public preview</span></span> | <span data-ttu-id="ad864-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="ad864-106">Early access</span></span> | <span data-ttu-id="ad864-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ad864-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="ad864-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ad864-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ad864-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ad864-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ad864-110">2020 年 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="ad864-110">Apr 29, 2020</span></span>|-| -|


## <a name="business-value"></a><span data-ttu-id="ad864-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ad864-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ad864-112">多くの場合、フィールド サービス技術者は、サービス提供の一環として、質問に対する一連の回答を取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ad864-112">In many cases, field service technicians need to capture a set of answers to questions as part of offering service.</span></span> <span data-ttu-id="ad864-113">たとえば、技術者は、機器を整備する前に安全性チェックを行ったり、圧力レベルや機械内の残留液を検査したりすることが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="ad864-113">For instance, a technician might need to conduct safety checks before servicing a piece of equipment, or perhaps need to inspect pressure levels or remaining liquid in a machine.</span></span> <span data-ttu-id="ad864-114">その他のケースでは、技術者は作業の完了後に検査を実行する必要がある場合があるほか、検査自体が作業指示書全体を構成する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ad864-114">In other cases, technicians might need to perform an inspection after the work is complete, or the inspection itself might constitute the entire work order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ad864-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ad864-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ad864-116">Field Service に、検査を定義およびキャプチャする機能が含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ad864-116">Field Service now includes the capability to define and capture inspections.</span></span> <span data-ttu-id="ad864-117">お客様は次のことができます。</span><span class="sxs-lookup"><span data-stu-id="ad864-117">It enables customers to:</span></span>

- <span data-ttu-id="ad864-118">デザイナー エクスペリエンスを使用して検査を作成します。</span><span class="sxs-lookup"><span data-stu-id="ad864-118">Create an inspection through a designer experience.</span></span>
- <span data-ttu-id="ad864-119">検査を作業指示書に関連付けます。</span><span class="sxs-lookup"><span data-stu-id="ad864-119">Associate an inspection with a work order.</span></span>
- <span data-ttu-id="ad864-120">モバイル エクスペリエンスを使用して検査を完了します。</span><span class="sxs-lookup"><span data-stu-id="ad864-120">Complete an inspection via a mobile experience.</span></span>
- <span data-ttu-id="ad864-121">分析またはさらなるアクションのために検査結果をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="ad864-121">Capture the inspection results for analysis or further action.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="ad864-122">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="ad864-122">This feature is available in the Unified Interface only.</span></span>







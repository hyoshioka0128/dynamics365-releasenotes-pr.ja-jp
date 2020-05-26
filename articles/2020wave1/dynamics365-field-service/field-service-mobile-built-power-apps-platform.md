---
title: Microsoft Power Apps プラットフォームに構築された Field Service Mobile
description: Microsoft Power Apps プラットフォームに構築された Field Service Mobile
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/28/2020
ms.assetid: c568f5f7-8289-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: drfuller
dynamics365pdf: true
ms.openlocfilehash: a7c01721cabda598793272ebadc3fb4387750a39
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350928"
---
# <a name="field-service-mobile-built-on-microsoft-power-apps-platform"></a><span data-ttu-id="0f26c-103">Microsoft Power Apps プラットフォームに構築された Field Service Mobile</span><span class="sxs-lookup"><span data-stu-id="0f26c-103">Field Service mobile built on Microsoft Power Apps platform</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="0f26c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0f26c-104">Enabled for</span></span>    |  <span data-ttu-id="0f26c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0f26c-105">Public preview</span></span> | <span data-ttu-id="0f26c-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="0f26c-106">Early access</span></span> | <span data-ttu-id="0f26c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0f26c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="0f26c-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0f26c-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="0f26c-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="0f26c-109">May 2020</span></span>|



## <a name="business-value"></a><span data-ttu-id="0f26c-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0f26c-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0f26c-111">Microsoft の次世代 Field Service Mobile アプリは、問題を解決するために顧客の場所に出張する技術者向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="0f26c-111">Our next generation Field Service mobile app is optimized for technicians who travel to customer locations to resolve issues.</span></span> <span data-ttu-id="0f26c-112">使いやすいモバイル エクスペリエンスで、技術者は割り当てられたジョブをカレンダーに表示し、写真やビデオ、バーコード スキャン、デジタル署名を使用して作業を記録できます。</span><span class="sxs-lookup"><span data-stu-id="0f26c-112">It empowers technicians with an easy-to-use mobile experience to view assigned jobs on a calendar, and record work with pictures and videos, barcode scanning, and digital signatures.</span></span> <span data-ttu-id="0f26c-113">さらに、インターネットに接続していないリモートの目的地を訪問しているときに、重要情報をオフラインで利用できます。</span><span class="sxs-lookup"><span data-stu-id="0f26c-113">Furthermore, important information is available offline when visiting remote destinations without internet connectivity.</span></span> <span data-ttu-id="0f26c-114">モデル駆動型アプリとして Microsoft Power Platform に構築されており、他のすべての Dynamics 365 ビジネス アプリケーションと同じツールを使用して、Field Service Mobile をビジネス ニーズに合わせてカスタマイズし、Azure IoT、Remote Assist、Power Virtual Agents などの Microsoft Stack と簡単に統合できます。</span><span class="sxs-lookup"><span data-stu-id="0f26c-114">Built as a model-driven app on Microsoft Power Platform, you can customize Field Service mobile to your business needs with the same tools as all your other Dynamics 365 business applications, and easily integrate with the Microsoft stack like Azure IoT, Remote Assist, Power Virtual Agents, and more.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0f26c-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0f26c-115">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="0f26c-116">重要データおよびタスクに中断なくアクセスするためのオフライン サポート。</span><span class="sxs-lookup"><span data-stu-id="0f26c-116">Offline support for uninterrupted access to important data and tasks.</span></span>
- <span data-ttu-id="0f26c-117">1 日を計画するためのすべての予約のカレンダー ビュー。</span><span class="sxs-lookup"><span data-stu-id="0f26c-117">Calendar view of all your bookings to plan your day.</span></span>
- <span data-ttu-id="0f26c-118">予約の状態、サービス タスク、製品など、すべての予約関連情報。</span><span class="sxs-lookup"><span data-stu-id="0f26c-118">All booking-related information, such as booking status, service tasks, and products.</span></span>
- <span data-ttu-id="0f26c-119">サービスの場所へのワンクリック ナビゲーション。</span><span class="sxs-lookup"><span data-stu-id="0f26c-119">One-click navigation to the service location.</span></span>
- <span data-ttu-id="0f26c-120">完了したタスクのメモを追加し、画像を添付します。</span><span class="sxs-lookup"><span data-stu-id="0f26c-120">Add notes and attach images for the completed tasks.</span></span>
- <span data-ttu-id="0f26c-121">UPC やバーコードなどのフィールドをスキャンしてすばやく入力します。</span><span class="sxs-lookup"><span data-stu-id="0f26c-121">Scan to quickly populate fields, such as UPC and barcode.</span></span>
- <span data-ttu-id="0f26c-122">顧客のサインオフのためのデジタル署名。</span><span class="sxs-lookup"><span data-stu-id="0f26c-122">Digital signatures for customer sign-off.</span></span> 
- <span data-ttu-id="0f26c-123">アプリから直接休暇を申請します。</span><span class="sxs-lookup"><span data-stu-id="0f26c-123">Request time off directly from the app.</span></span> 
- <span data-ttu-id="0f26c-124">iOS および Android の電話で利用できます。</span><span class="sxs-lookup"><span data-stu-id="0f26c-124">Available on iOS and Android phones.</span></span>
- <span data-ttu-id="0f26c-125">Microsoft Power Apps プラットフォーム上に構築されたモバイル アプリケーションを完全にカスタマイズして、フィールド サービス ワーカーがアクセスできるデータの種類などを定義できます。</span><span class="sxs-lookup"><span data-stu-id="0f26c-125">Built on the Microsoft Power Apps platform, the mobile application is entirely customizable to define what types of data field service workers can access and much more.</span></span>

<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="0f26c-126">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="0f26c-126">This feature is available in the Unified Interface only.</span></span>


## <a name="see-also"></a><span data-ttu-id="0f26c-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="0f26c-127">See also</span></span>

[<span data-ttu-id="0f26c-128">Field Service Mobile</span><span class="sxs-lookup"><span data-stu-id="0f26c-128">Field Service Mobile</span></span>](https://aka.ms/FSMPowerApp)



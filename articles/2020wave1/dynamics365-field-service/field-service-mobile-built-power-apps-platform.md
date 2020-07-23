---
title: Microsoft Power Apps プラットフォームに構築された Field Service Mobile
description: Microsoft Power Apps プラットフォームに構築された Field Service Mobile
author: relnotes
ms.reviewer: krbjoran
ms.date: 05/15/2020
ms.assetid: c568f5f7-8289-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: drfuller
dynamics365pdf: true
ms.openlocfilehash: 07f8b167f2206dcb8a23d780d2cee79398e13bc0
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3547730"
---
# <a name="field-service-mobile-built-on-microsoft-power-apps-platform"></a><span data-ttu-id="a249a-103">Microsoft Power Apps プラットフォームに構築された Field Service Mobile</span><span class="sxs-lookup"><span data-stu-id="a249a-103">Field Service mobile built on Microsoft Power Apps platform</span></span>


| <span data-ttu-id="a249a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a249a-104">Enabled for</span></span>    |  <span data-ttu-id="a249a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a249a-105">Public preview</span></span> | <span data-ttu-id="a249a-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="a249a-106">Early access</span></span> | <span data-ttu-id="a249a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="a249a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="a249a-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a249a-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="a249a-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a249a-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a249a-110">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a249a-110">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a249a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a249a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a249a-112">Microsoft の次世代 Field Service Mobile アプリは、問題を解決するために顧客の場所に出張する技術者向けに最適化されています。</span><span class="sxs-lookup"><span data-stu-id="a249a-112">Our next generation Field Service mobile app is optimized for technicians who travel to customer locations to resolve issues.</span></span> <span data-ttu-id="a249a-113">使いやすいモバイル エクスペリエンスで、技術者は割り当てられたジョブをカレンダーに表示し、写真やビデオ、バーコード スキャン、デジタル署名を使用して作業を記録できます。</span><span class="sxs-lookup"><span data-stu-id="a249a-113">It empowers technicians with an easy-to-use mobile experience to view assigned jobs on a calendar, and record work with pictures and videos, barcode scanning, and digital signatures.</span></span> <span data-ttu-id="a249a-114">さらに、インターネットに接続していないリモートの目的地を訪問しているときに、重要情報をオフラインで利用できます。</span><span class="sxs-lookup"><span data-stu-id="a249a-114">Furthermore, important information is available offline when visiting remote destinations without internet connectivity.</span></span> <span data-ttu-id="a249a-115">モデル駆動型アプリとして Microsoft Power Platform に構築されており、他のすべての Dynamics 365 ビジネス アプリケーションと同じツールを使用して、Field Service Mobile をビジネス ニーズに合わせてカスタマイズし、Azure IoT、Remote Assist、Power Virtual Agents などの Microsoft Stack と簡単に統合できます。</span><span class="sxs-lookup"><span data-stu-id="a249a-115">Built as a model-driven app on Microsoft Power Platform, you can customize Field Service mobile to your business needs with the same tools as all your other Dynamics 365 business applications, and easily integrate with the Microsoft stack like Azure IoT, Remote Assist, Power Virtual Agents, and more.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a249a-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a249a-116">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="a249a-117">重要データおよびタスクに中断なくアクセスするためのオフライン サポート。</span><span class="sxs-lookup"><span data-stu-id="a249a-117">Offline support for uninterrupted access to important data and tasks.</span></span>
- <span data-ttu-id="a249a-118">1 日を計画するためのすべての予約のカレンダー ビュー。</span><span class="sxs-lookup"><span data-stu-id="a249a-118">Calendar view of all your bookings to plan your day.</span></span>
- <span data-ttu-id="a249a-119">予約の状態、サービス タスク、製品など、すべての予約関連情報。</span><span class="sxs-lookup"><span data-stu-id="a249a-119">All booking-related information, such as booking status, service tasks, and products.</span></span>
- <span data-ttu-id="a249a-120">サービスの場所へのワンクリック ナビゲーション。</span><span class="sxs-lookup"><span data-stu-id="a249a-120">One-click navigation to the service location.</span></span>
- <span data-ttu-id="a249a-121">完了したタスクのメモを追加し、画像を添付します。</span><span class="sxs-lookup"><span data-stu-id="a249a-121">Add notes and attach images for the completed tasks.</span></span>
- <span data-ttu-id="a249a-122">UPC やバーコードなどのフィールドをスキャンしてすばやく入力します。</span><span class="sxs-lookup"><span data-stu-id="a249a-122">Scan to quickly populate fields, such as UPC and barcode.</span></span>
- <span data-ttu-id="a249a-123">顧客のサインオフのためのデジタル署名。</span><span class="sxs-lookup"><span data-stu-id="a249a-123">Digital signatures for customer sign-off.</span></span> 
- <span data-ttu-id="a249a-124">アプリから直接休暇を申請します。</span><span class="sxs-lookup"><span data-stu-id="a249a-124">Request time off directly from the app.</span></span> 
- <span data-ttu-id="a249a-125">iOS および Android の電話で利用できます。</span><span class="sxs-lookup"><span data-stu-id="a249a-125">Available on iOS and Android phones.</span></span>
- <span data-ttu-id="a249a-126">Microsoft Power Apps プラットフォーム上に構築されたモバイル アプリケーションを完全にカスタマイズして、フィールド サービス ワーカーがアクセスできるデータの種類などを定義できます。</span><span class="sxs-lookup"><span data-stu-id="a249a-126">Built on the Microsoft Power Apps platform, the mobile application is entirely customizable to define what types of data field service workers can access and much more.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="a249a-127">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="a249a-127">This feature is available in Unified Interface only.</span></span>







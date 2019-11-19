---
title: 場所ステータス
description: この機能では、より柔軟に場所ステータスを処理して維持できるように、およびクエリのフィルター処理で使用できるように、場所テーブルにいくつかの新しいフィールドが導入されます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 7062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 2c5e7f5b1ad10fdbd026ab6e8caa0094f8e70e4c
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660601"
---
# <a name="location-status"></a><span data-ttu-id="b99bf-103">場所ステータス</span><span class="sxs-lookup"><span data-stu-id="b99bf-103">Location status</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="b99bf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b99bf-104">Enabled for</span></span>    |  <span data-ttu-id="b99bf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b99bf-105">Public preview</span></span> | <span data-ttu-id="b99bf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b99bf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b99bf-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b99bf-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b99bf-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b99bf-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b99bf-109">2019 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="b99bf-109">Mar 5, 2019</span></span>| <span data-ttu-id="b99bf-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="b99bf-110">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b99bf-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b99bf-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b99bf-112">この機能では、より柔軟に場所を処理して維持できるよう、場所テーブルにいくつかの新しいフィールドが導入されます。</span><span class="sxs-lookup"><span data-stu-id="b99bf-112">This functionality introduces several new fields on the locations table for more flexibility in working with and maintaining locations.</span></span> <span data-ttu-id="b99bf-113">倉庫フロー管理を改善するため、場所ステータス (空、保管、ピッキング、凍結) を場所指示クエリに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="b99bf-113">Location statuses (empty, storage, picking, or frozen) can be included in the location directives query for better warehouse flow control.</span></span> <span data-ttu-id="b99bf-114">ブロックの原因を設定し、後で任意の場所に割り当てて、そのような場所に対する入庫または出庫のトランザクションをブロックすることができます。</span><span class="sxs-lookup"><span data-stu-id="b99bf-114">Blocking causes can be set up and can later be assigned to any location to either block inbound or outbound transactions against such a location.</span></span> <span data-ttu-id="b99bf-115">場所ブロックでは予約の場所は除外されません。</span><span class="sxs-lookup"><span data-stu-id="b99bf-115">Location blocking does not exclude locations for reservations.</span></span> <span data-ttu-id="b99bf-116">一時的な運用上のブロックのみを意味します。</span><span class="sxs-lookup"><span data-stu-id="b99bf-116">It is meant only as a temporary operational blocking.</span></span>
<!--feature detail end -->










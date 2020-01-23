---
title: 場所ステータス
description: この機能では、より柔軟に場所ステータスを処理して維持できるように、およびクエリのフィルター処理で使用できるように、場所テーブルにいくつかの新しいフィールドが導入されます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/06/2020
ms.assetid: 7062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 794abe1bb2eb61f4305e9be20f196ee22b8832f3
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947969"
---
# <a name="location-status"></a><span data-ttu-id="8c059-103">場所ステータス</span><span class="sxs-lookup"><span data-stu-id="8c059-103">Location status</span></span>


| <span data-ttu-id="8c059-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8c059-104">Enabled for</span></span>    |  <span data-ttu-id="8c059-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8c059-105">Public preview</span></span> | <span data-ttu-id="8c059-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8c059-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8c059-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="8c059-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8c059-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8c059-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8c059-109">2019 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="8c059-109">Mar 5, 2019</span></span>| <span data-ttu-id="8c059-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8c059-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8c059-111">2019 年 12 月 19 日</span><span class="sxs-lookup"><span data-stu-id="8c059-111">Dec 19, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8c059-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8c059-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8c059-113">この機能では、より柔軟に場所を処理して維持できるよう、場所テーブルにいくつかの新しいフィールドが導入されます。</span><span class="sxs-lookup"><span data-stu-id="8c059-113">This functionality introduces several new fields on the locations table for more flexibility in working with and maintaining locations.</span></span> <span data-ttu-id="8c059-114">倉庫フロー管理を改善するため、場所ステータス (空、保管、ピッキング、凍結) を場所指示クエリに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8c059-114">Location statuses (empty, storage, picking, or frozen) can be included in the location directives query for better warehouse flow control.</span></span> <span data-ttu-id="8c059-115">ブロックの原因を設定し、後で任意の場所に割り当てて、そのような場所に対する入庫または出庫のトランザクションをブロックすることができます。</span><span class="sxs-lookup"><span data-stu-id="8c059-115">Blocking causes can be set up and can later be assigned to any location to either block inbound or outbound transactions against such a location.</span></span> <span data-ttu-id="8c059-116">場所ブロックでは予約の場所は除外されません。</span><span class="sxs-lookup"><span data-stu-id="8c059-116">Location blocking does not exclude locations for reservations.</span></span> <span data-ttu-id="8c059-117">一時的な運用上のブロックのみを意味します。</span><span class="sxs-lookup"><span data-stu-id="8c059-117">It is meant only as a temporary operational blocking.</span></span>
<!--feature detail end -->








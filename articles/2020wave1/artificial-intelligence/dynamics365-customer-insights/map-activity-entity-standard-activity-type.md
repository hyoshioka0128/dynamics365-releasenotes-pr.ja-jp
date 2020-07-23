---
title: 活動エンティティを標準の活動の種類にマップする
description: 活動エンティティを標準の活動の種類にマップして、セマンティックの理解を深め、動的なタイムラインにおける利用を強化します。
author: relnotes
ms.reviewer: mhart
ms.date: 06/03/2020
ms.assetid: 64386f91-bb88-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: midevane
dynamics365pdf: true
ms.openlocfilehash: 25d461047a91674302c9b3d70155287199011ada
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441152"
---
# <a name="map-activity-entity-to-standard-activity-type"></a><span data-ttu-id="1c4b7-103">活動エンティティを標準の活動の種類にマップする</span><span class="sxs-lookup"><span data-stu-id="1c4b7-103">Map activity entity to standard activity type</span></span>


| <span data-ttu-id="1c4b7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1c4b7-104">Enabled for</span></span>    |  <span data-ttu-id="1c4b7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1c4b7-105">Public preview</span></span> | <span data-ttu-id="1c4b7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1c4b7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1c4b7-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1c4b7-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1c4b7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1c4b7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1c4b7-109">2020 年 4 月 30 日</span><span class="sxs-lookup"><span data-stu-id="1c4b7-109">Apr 30, 2020</span></span>| <span data-ttu-id="1c4b7-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1c4b7-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1c4b7-111">2020 年 5 月 19 日</span><span class="sxs-lookup"><span data-stu-id="1c4b7-111">May 19, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="1c4b7-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1c4b7-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1c4b7-113">現在、活動の構成とストレージはそれらをタイムラインに表示するための静的な設計に基づいています。</span><span class="sxs-lookup"><span data-stu-id="1c4b7-113">Activity configuration and storage is currently based on a static design to view them in a timeline.</span></span> <span data-ttu-id="1c4b7-114">現時点では、AI モデルで複数のユース ケースが発生する可能性のある活動のセマンティックな意味が十分に活用されていません。</span><span class="sxs-lookup"><span data-stu-id="1c4b7-114">The semantic meaning of activities, which has potential for multiple use-cases in AI models, isn't fully used at the moment.</span></span> <span data-ttu-id="1c4b7-115">活動の種類および活動のセマンティックのより詳しい理解に基づいて、活動タイムラインをより動的にする予定です。</span><span class="sxs-lookup"><span data-stu-id="1c4b7-115">We plan to make the activity timeline more dynamic, based on the activity type and better semantic understanding of the activities.</span></span> <span data-ttu-id="1c4b7-116">この機能は、取り込んだ活動向けの Common Data Model で定義されている活動の種類を識別するためのものです。</span><span class="sxs-lookup"><span data-stu-id="1c4b7-116">This feature aims to identify the activity type as defined in Common Data Model for any ingested activity.</span></span>
<!--feature detail end -->










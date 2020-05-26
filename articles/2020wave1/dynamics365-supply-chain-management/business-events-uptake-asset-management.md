---
title: 資産管理のビジネス イベントの取り込み
description: この機能では、ビジネス イベント フレームワークに対するメンテナンス要求と作業指示書の状態の変更に対するトリガーが提供されます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 05/04/2020
ms.assetid: aef593c4-89cb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: dabourq
dynamics365pdf: true
ms.openlocfilehash: dcde48d23965ed49984ba6025bbee5a30e24dd81
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350933"
---
# <a name="business-events-uptake-for-asset-management"></a><span data-ttu-id="8b074-103">資産管理のビジネス イベントの取り込み</span><span class="sxs-lookup"><span data-stu-id="8b074-103">Business events uptake for asset management</span></span>


| <span data-ttu-id="8b074-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8b074-104">Enabled for</span></span>    |  <span data-ttu-id="8b074-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8b074-105">Public preview</span></span> | <span data-ttu-id="8b074-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8b074-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8b074-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8b074-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8b074-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8b074-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8b074-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8b074-109">Feb 3, 2020</span></span>| <span data-ttu-id="8b074-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8b074-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8b074-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8b074-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8b074-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8b074-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8b074-113">この機能により、ユーザーは、Microsoft Power Automate とロジック アプリを利用して、外部から資産管理ビジネス ドキュメントと対話できます。</span><span class="sxs-lookup"><span data-stu-id="8b074-113">This functionality enables users to interact with asset management business documents externally by leveraging Microsoft Power Automate and logic apps.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8b074-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8b074-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8b074-115">この機能では、ビジネス イベント フレームワークに対するメンテナンス要求と作業指示書の状態の変更に対するトリガーが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8b074-115">This functionality provides triggers for maintenance requests and work order state changes to the business events framework.</span></span> <span data-ttu-id="8b074-116">これにより、ユーザーは、Microsoft Power Automate とロジック アプリを利用して、外部から資産管理ビジネス ドキュメントと対話できます。</span><span class="sxs-lookup"><span data-stu-id="8b074-116">It lets users interact with asset management business documents externally by leveraging Microsoft Power Automate and logic apps.</span></span> <span data-ttu-id="8b074-117">次のビジネス イベントのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="8b074-117">We have now added support for the following business events:</span></span>

- <span data-ttu-id="8b074-118">メンテナンス要求が作成されます</span><span class="sxs-lookup"><span data-stu-id="8b074-118">Maintenance request is created</span></span>
- <span data-ttu-id="8b074-119">資産プロパティが変更されました</span><span class="sxs-lookup"><span data-stu-id="8b074-119">Asset property is changed</span></span>
- <span data-ttu-id="8b074-120">メンテナンス要求にメンテナンス作業指示書が作成されます</span><span class="sxs-lookup"><span data-stu-id="8b074-120">Maintenance work order created for maintenance request</span></span>
- <span data-ttu-id="8b074-121">メンテナンス作業指示書が完了したことが報告されます</span><span class="sxs-lookup"><span data-stu-id="8b074-121">Maintenance work order reported completed</span></span>
- <span data-ttu-id="8b074-122">メンテナンス作業指示書がスケジュールされます</span><span class="sxs-lookup"><span data-stu-id="8b074-122">Maintenance work order is scheduled</span></span>
<!--feature detail end -->









## <a name="see-also"></a><span data-ttu-id="8b074-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="8b074-123">See also</span></span>

<!--docs start-->
<span data-ttu-id="8b074-124">[ビジネス イベントの概要](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/business-events/home-page) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8b074-124">[Business events overview](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/business-events/home-page) (docs)</span></span>
<!--docs end-->

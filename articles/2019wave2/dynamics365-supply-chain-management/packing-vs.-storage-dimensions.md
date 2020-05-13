---
title: 梱包と保管の分析コード
description: 指定した分析コードを梱包、保管、または入れ子の梱包に使用するプロセスをユーザーが指定できるよう、新しいフィールドが現物分析コード ページに追加されています。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 408d9bc461dd436987f9088b7a057ad4e415891f
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3319975"
---
# <a name="packing-vs-storage-dimensions"></a><span data-ttu-id="5be5b-103">梱包と保管の分析コード</span><span class="sxs-lookup"><span data-stu-id="5be5b-103">Packing vs. storage dimensions</span></span>


| <span data-ttu-id="5be5b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5be5b-104">Enabled for</span></span>    |  <span data-ttu-id="5be5b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5be5b-105">Public preview</span></span> | <span data-ttu-id="5be5b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5be5b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5be5b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5be5b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5be5b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5be5b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5be5b-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="5be5b-109">Feb 3, 2020</span></span>| <span data-ttu-id="5be5b-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="5be5b-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="5be5b-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5be5b-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5be5b-112">一部の品目は、異なるプロセスに対する現物分析コードを追跡する必要があるような方法で、梱包または保管されます。</span><span class="sxs-lookup"><span data-stu-id="5be5b-112">Some items are packed or stored in such a way that there is a need to track physical dimensions for the different processes.</span></span> <span data-ttu-id="5be5b-113">指定した分析コードを梱包、保管、または入れ子の梱包に使用するプロセスをユーザーが指定できるよう、新しいフィールドが**現物分析コード** ページに追加されています。</span><span class="sxs-lookup"><span data-stu-id="5be5b-113">A new field is being added to the **Physical dimensions** page to allow users to specify what process the specified dimensions are used for: packing, storage, or nested packing.</span></span> <span data-ttu-id="5be5b-114">保管分析コードと場所の容積測定を併せて使用し、倉庫内の場所に保管できる品目の量を決定します。</span><span class="sxs-lookup"><span data-stu-id="5be5b-114">The storage dimensions will be used along with location volumetrics to determine how much of the item can be stored in locations in the warehouse.</span></span> <span data-ttu-id="5be5b-115">梱包分析コードは、コンテナー詰めおよび手動梱包プロセスの間に、異なるコンテナーの種類に収まる品目の数を決定するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="5be5b-115">The packing dimensions will be used during containerization and the manual packing process to determine how many of the items will fit in different container types.</span></span> <span data-ttu-id="5be5b-116">入れ子になった梱包の分析コードは、梱包プロセスに複数のレベルが含まれる場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="5be5b-116">The nested packing dimensions will be used when the packing process contains multiple levels.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="5be5b-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="5be5b-117">See also</span></span>

<!--docs start-->
<span data-ttu-id="5be5b-118">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5be5b-118">[Warehouse management overview](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
<!--docs end-->

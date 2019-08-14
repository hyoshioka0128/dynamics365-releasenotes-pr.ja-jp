---
title: 梱包と保管の分析コード
description: 指定した分析コードを梱包、保管、または入れ子の梱包に使用するプロセスをユーザーが指定できるよう、新しいフィールドが現物分析コード ページに追加されています。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 9c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: de4650a2223db70008b00586bcfc75a85ad6ae45
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855133"
---
# <a name="packing-vs-storage-dimensions"></a><span data-ttu-id="1a42c-103">梱包と保管の分析コード</span><span class="sxs-lookup"><span data-stu-id="1a42c-103">Packing vs. storage dimensions</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="1a42c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1a42c-104">Enabled for</span></span>    |  <span data-ttu-id="1a42c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1a42c-105">Public preview</span></span> | <span data-ttu-id="1a42c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1a42c-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="1a42c-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="1a42c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1a42c-108">2019 年 7 月</span><span class="sxs-lookup"><span data-stu-id="1a42c-108">July 2019</span></span>| <span data-ttu-id="1a42c-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="1a42c-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="1a42c-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1a42c-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1a42c-111">一部の品目は、異なるプロセスに対する現物分析コードを追跡する必要があるような方法で、梱包または保管されます。</span><span class="sxs-lookup"><span data-stu-id="1a42c-111">Some items are packed or stored in such a way that there is a need to track physical dimensions for the different processes.</span></span> <span data-ttu-id="1a42c-112">指定した分析コードを梱包、保管、または入れ子の梱包に使用するプロセスをユーザーが指定できるよう、新しいフィールドが**現物分析コード** ページに追加されています。</span><span class="sxs-lookup"><span data-stu-id="1a42c-112">A new field is being added to the **Physical dimensions** page to allow users to specify what process the specified dimensions are used for: packing, storage, or nested packing.</span></span> <span data-ttu-id="1a42c-113">保管分析コードと場所の容積測定を併せて使用し、倉庫内の場所に保管できる品目の量を決定します。</span><span class="sxs-lookup"><span data-stu-id="1a42c-113">The storage dimensions will be used along with location volumetrics to determine how much of the item can be stored in locations in the warehouse.</span></span> <span data-ttu-id="1a42c-114">梱包分析コードは、コンテナー詰めおよび手動梱包プロセスの間に、異なるコンテナーの種類に収まる品目の数を決定するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="1a42c-114">The packing dimensions will be used during containerization and the manual packing process to determine how many of the items will fit in different container types.</span></span> <span data-ttu-id="1a42c-115">入れ子になった梱包の分析コードは、梱包プロセスに複数のレベルが含まれる場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="1a42c-115">The nested packing dimensions will be used when the packing process contains multiple levels.</span></span>
<!--feature detail end -->












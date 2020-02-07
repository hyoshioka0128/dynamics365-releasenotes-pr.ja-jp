---
title: 外部カタログの機能強化
description: 外部カタログの機能強化により、調達組織はログ機能を有効にして、外部カタログのパラメーターの変更が必要になる可能性がある一般的な問題をキャプチャできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/16/2019
ms.assetid: 61b663a5-f41d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: lcash
dynamics365pdf: true
ms.openlocfilehash: fa08e595a88faf030ccfc81cea87e438826db0b5
ms.sourcegitcommit: 9ede92eba84a02579fc8fc63e6a9673b034ce30c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2020
ms.locfileid: "2976546"
---
# <a name="external-catalog-enhancements"></a><span data-ttu-id="666d3-103">外部カタログの機能強化</span><span class="sxs-lookup"><span data-stu-id="666d3-103">External catalog enhancements</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="666d3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="666d3-104">Enabled for</span></span>    |  <span data-ttu-id="666d3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="666d3-105">Public preview</span></span> | <span data-ttu-id="666d3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="666d3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="666d3-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="666d3-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="666d3-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="666d3-108">Feb 2020</span></span>| <span data-ttu-id="666d3-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="666d3-109">Apr 2020</span></span>|





## <a name="feature-details"></a><span data-ttu-id="666d3-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="666d3-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="666d3-111">調達組織は、Microsoft Dynamics 365 for Finance and Operations バージョン 7.2 で外部カタログの cXML プロトコルを利用することができました。</span><span class="sxs-lookup"><span data-stu-id="666d3-111">Procurement organizations were able to leverage the external catalogs cXML protocol in Microsoft Dynamics 365 for Finance and Operations version 7.2.</span></span> <span data-ttu-id="666d3-112">仕入先システムが異なるため、外部カタログの設定とテストではトラブルシューティングが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="666d3-112">Due to different vendor systems, setting up and testing external catalogs can involve some troubleshooting.</span></span> <span data-ttu-id="666d3-113">新しいカタログの機能強化により、調達組織はログ機能を有効にして、外部カタログのパラメーターの変更が必要になる可能性がある一般的な問題をキャプチャできます。</span><span class="sxs-lookup"><span data-stu-id="666d3-113">With the new catalog enhancements, the procurement organization can enable the logging feature that captures common issues that might require changes to external catalog parameters.</span></span> 

<!--![External catalog enhancements](media/external-catalog-enhancements-1.png "External catalog enhancements")-->

<span data-ttu-id="666d3-114">出荷バスケットから **SupplierPartIAuxiliary** ID を返して購買要求および関連する発注書でそれをキャプチャできるようにする、新しいサポートが追加されています。</span><span class="sxs-lookup"><span data-stu-id="666d3-114">We're adding additional support to allow the return of the **SupplierPartIAuxiliary** ID from the shipping basket and to capture it on the purchase requisition and the related purchase order.</span></span> <span data-ttu-id="666d3-115">この ID は、品目の固有の構成を表すために一部のサプライヤーによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="666d3-115">This identification is used by some suppliers to represent a unique configuration for an item.</span></span>
<!--feature detail end -->










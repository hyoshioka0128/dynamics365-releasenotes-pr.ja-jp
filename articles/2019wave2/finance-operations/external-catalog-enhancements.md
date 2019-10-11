---
title: 外部カタログの機能強化
description: 外部カタログの機能強化
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 3c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: lcash
dynamics365pdf: true
ms.openlocfilehash: ba2b22445534d95baa8bfc12732859b5b5d1cb1c
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143201"
---
# <a name="external-catalog-enhancements"></a><span data-ttu-id="cc00b-103">外部カタログの機能強化</span><span class="sxs-lookup"><span data-stu-id="cc00b-103">External catalog enhancements</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="cc00b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cc00b-104">Enabled for</span></span>    |  <span data-ttu-id="cc00b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cc00b-105">Public preview</span></span> | <span data-ttu-id="cc00b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cc00b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cc00b-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="cc00b-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="cc00b-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="cc00b-108">Sep 2019</span></span>| <span data-ttu-id="cc00b-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="cc00b-109">Nov 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="cc00b-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cc00b-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cc00b-111">調達組織は、Microsoft Dynamics 365 for Finance and Operations バージョン 7.2 で外部カタログの cXML プロトコルを利用することができました。</span><span class="sxs-lookup"><span data-stu-id="cc00b-111">Procurement organizations were able to leverage the external catalogs cXML protocol in Microsoft Dynamics 365 for Finance and Operations version 7.2.</span></span> <span data-ttu-id="cc00b-112">仕入先システムが異なるため、外部カタログの設定とテストではトラブルシューティングが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="cc00b-112">Due to different vendor systems, setting up and testing external catalogs can involve some troubleshooting.</span></span> <span data-ttu-id="cc00b-113">新しいカタログの機能強化により、調達組織はログ機能を有効にして、外部カタログのパラメーターの変更が必要になる可能性がある一般的な問題をキャプチャできます。</span><span class="sxs-lookup"><span data-stu-id="cc00b-113">With the new catalog enhancements, the procurement organization can enable the logging feature that captures common issues that might require changes to external catalog parameters.</span></span> 

![外部カタログの機能強化](media/external-catalog-enhancements-1.png "") 

<span data-ttu-id="cc00b-115">出荷バスケットから **SupplierPartIAuxiliary** ID を返して購買要求および関連する発注書でそれをキャプチャできるようにする、新しいサポートが追加されています。</span><span class="sxs-lookup"><span data-stu-id="cc00b-115">Additional support is being added to allow the return of the **SupplierPartIAuxiliary** ID from the shipping basket and to capture it on the purchase requisition and the related purchase order.</span></span> <span data-ttu-id="cc00b-116">この ID は、品目の固有の構成を表すために一部のサプライヤーによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="cc00b-116">This identification is used by some suppliers to represent a unique configuration for an item.</span></span>
<!--feature detail end -->












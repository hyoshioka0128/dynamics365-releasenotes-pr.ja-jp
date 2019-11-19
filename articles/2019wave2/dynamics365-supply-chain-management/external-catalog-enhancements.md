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
ms.openlocfilehash: 675c389bf46b7fd68da227ebf79e45236190cd7a
ms.sourcegitcommit: 5d6e90743e29603bfc5d06566a6966de05931982
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2019
ms.locfileid: "2669149"
---
# <a name="external-catalog-enhancements"></a><span data-ttu-id="f9866-103">外部カタログの機能強化</span><span class="sxs-lookup"><span data-stu-id="f9866-103">External catalog enhancements</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="f9866-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f9866-104">Enabled for</span></span>    |  <span data-ttu-id="f9866-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f9866-105">Public preview</span></span> | <span data-ttu-id="f9866-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f9866-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f9866-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f9866-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f9866-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="f9866-108">Sep 2019</span></span>| <span data-ttu-id="f9866-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="f9866-109">Nov 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="f9866-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f9866-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f9866-111">調達組織は、Microsoft Dynamics 365 for Finance and Operations バージョン 7.2 で外部カタログの cXML プロトコルを利用することができました。</span><span class="sxs-lookup"><span data-stu-id="f9866-111">Procurement organizations were able to leverage the external catalogs cXML protocol in Microsoft Dynamics 365 for Finance and Operations version 7.2.</span></span> <span data-ttu-id="f9866-112">仕入先システムが異なるため、外部カタログの設定とテストではトラブルシューティングが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f9866-112">Due to different vendor systems, setting up and testing external catalogs can involve some troubleshooting.</span></span> <span data-ttu-id="f9866-113">新しいカタログの機能強化により、調達組織はログ機能を有効にして、外部カタログのパラメーターの変更が必要になる可能性がある一般的な問題をキャプチャできます。</span><span class="sxs-lookup"><span data-stu-id="f9866-113">With the new catalog enhancements, the procurement organization can enable the logging feature that captures common issues that might require changes to external catalog parameters.</span></span> 

<span data-ttu-id="f9866-114">![外部カタログの機能強化](media/external-catalog-enhancements-1.png "外部カタログの機能強化")</span><span class="sxs-lookup"><span data-stu-id="f9866-114">![External catalog enhancements](media/external-catalog-enhancements-1.png "External catalog enhancements")</span></span> 

<span data-ttu-id="f9866-115">出荷バスケットから **SupplierPartIAuxiliary** ID を返して購買要求および関連する発注書でそれをキャプチャできるようにする、新しいサポートが追加されています。</span><span class="sxs-lookup"><span data-stu-id="f9866-115">Additional support is being added to allow the return of the **SupplierPartIAuxiliary** ID from the shipping basket and to capture it on the purchase requisition and the related purchase order.</span></span> <span data-ttu-id="f9866-116">この ID は、品目の固有の構成を表すために一部のサプライヤーによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="f9866-116">This identification is used by some suppliers to represent a unique configuration for an item.</span></span>
<!--feature detail end -->










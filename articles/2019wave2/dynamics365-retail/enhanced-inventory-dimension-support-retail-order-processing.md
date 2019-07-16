---
title: Retail 注文処理における在庫分析コード サポートの強化
description: Retail 注文処理における在庫分析コード サポートの強化
author: hhainesms
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 2f4f1ee60e3b44754c8d055c2d2df1cf3c6df932
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1694268"
---
# <a name="enhanced-inventory-dimension-support-in-retail-order-processing"></a><span data-ttu-id="00270-103">Retail 注文処理における在庫分析コード サポートの強化</span><span class="sxs-lookup"><span data-stu-id="00270-103">Enhanced inventory dimension support in Retail order processing</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="00270-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="00270-104">Enabled for</span></span>    |  <span data-ttu-id="00270-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="00270-105">Public preview</span></span> | <span data-ttu-id="00270-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="00270-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="00270-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="00270-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="00270-108">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="00270-108">March 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="00270-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="00270-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="00270-110">小売ユーザーのサポートを向上させるには、在庫が場所、バッチ、シリアル番号、または所有者分析コードによって制御されている場合に、販売時点管理 (POS) アプリケーションを改善して注文の作成と販売および返品トランザクションの処理をより適切に扱う必要があります。</span><span class="sxs-lookup"><span data-stu-id="00270-110">To better support Retail users, the point of sale (POS) application needs to be improved to better handle the order creation and processing of sales and return transactions when inventory is controlled by location, batch, serial number, or owner dimension.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="00270-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="00270-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="00270-112">POS 機能は、これらの追跡用分析コードに関連付けられている製品の販売時に、ユーザーが販売場所、バッチ ID、またはシリアル番号分析コードをオプションで入力する機能をサポートするように改善されます。</span><span class="sxs-lookup"><span data-stu-id="00270-112">POS functionality will be improved to support the ability for users to optionally enter a selling location, batch ID, or serial number dimension at the time of sale of products that are tied to these tracking dimensions.</span></span> <span data-ttu-id="00270-113">小売業者が特定の販売場所の入力を要求したくない場合は、既定の販売場所を使用するための既存の機能が引き続き使用されます。</span><span class="sxs-lookup"><span data-stu-id="00270-113">In cases where the retailer does not want to prompt for a specific selling location, existing functions for using a default selling location will still be used.</span></span> <span data-ttu-id="00270-114">小売業者が販売時に特定のバッチ ID の入力を要求したくない場合は、ビジネス ルールに基づいてバッチ ID を処理済みの販売注文にリンクするためのビジネス ロジックを追加してアプリケーションが拡張されます。</span><span class="sxs-lookup"><span data-stu-id="00270-114">In cases where the retailer does not want to prompt for a specific batch ID at the time of selling, the application will be enhanced with added business logic to link a batch ID to the processed sales order based on business rules.</span></span> <span data-ttu-id="00270-115">必要に応じて所有者分析コードが処理中に販売明細行に正しく適用されるように、所有者分析コードのサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="00270-115">Owner dimension support will be added to ensure that the owner dimension, if required, is properly applied to the sales line during processing.</span></span>
<!--feature detail end -->











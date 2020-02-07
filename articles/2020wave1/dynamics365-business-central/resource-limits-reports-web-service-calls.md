---
title: レポートおよび Web サービス呼び出しに対するリソースの制限
description: Business Central インストールのリソースを保護するために、レポートおよび SOAP Web サービス呼び出しの最大実行時間に制限を構成できるようになりました
author: relnotes
ms.reviewer: jswymer
ms.date: 12/16/2019
ms.assetid: 075dbe76-ea1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 2ab4cdfd5c47e935f680426f99d8a27ebe58fa27
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986655"
---
# <a name="resource-limits-for-reports-and-web-service-calls"></a><span data-ttu-id="73179-103">レポートおよび Web サービス呼び出しに対するリソースの制限</span><span class="sxs-lookup"><span data-stu-id="73179-103">Resource limits for reports and web service calls</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="73179-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="73179-104">Enabled for</span></span>    |  <span data-ttu-id="73179-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="73179-105">Public preview</span></span> | <span data-ttu-id="73179-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="73179-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="73179-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="73179-107">End users, automatically</span></span>|<span data-ttu-id="73179-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="73179-108">Feb 2020</span></span>| <span data-ttu-id="73179-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="73179-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="73179-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="73179-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="73179-111">誤って設定された Web サービス メソッドが実行されている場合や、ユーザーが誤ってフィルターなしでレポートを開始した場合でも、他のユーザーが作業できるようにします。</span><span class="sxs-lookup"><span data-stu-id="73179-111">To make sure that other users can work even if a misconfigured web service method is running or a user started a report with no filters by mistake.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="73179-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="73179-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="73179-113">Business Central Server には、管理者がレポートおよび SOAP Web サービスの呼び出し実行時間を制限できる新しい設定が用意されています。</span><span class="sxs-lookup"><span data-stu-id="73179-113">The Business Central server will have new settings where an administrator can set limits on the execution time for reports and SOAP web service calls.</span></span> <span data-ttu-id="73179-114">この制限に達すると、サーバーの操作がキャンセルされます。</span><span class="sxs-lookup"><span data-stu-id="73179-114">When the limit is reached, the server cancels the operation.</span></span>

<span data-ttu-id="73179-115">Business Central online (サービスとしてのソフトウェア) では、既定値は Business Central 運用チームによって設定され、顧客やパートナーがそれを上書きすることはできません。</span><span class="sxs-lookup"><span data-stu-id="73179-115">In Business Central online (software as a service), the default values are set by the Business Central operations team and cannot be overridden by customers or partners.</span></span> <span data-ttu-id="73179-116">2020 年リリース ウェーブ 1 では、既定値は数時間に設定されます (実際の値は未定です)。</span><span class="sxs-lookup"><span data-stu-id="73179-116">In the 2020 release wave 1, the default values will be set to hours (actual values are to be determined).</span></span>

<span data-ttu-id="73179-117">Business Central (オンプレミス) の場合、管理者がサーバーの設定を制御できます。</span><span class="sxs-lookup"><span data-stu-id="73179-117">For Business Central (on-premises), an administrator can control the settings in the server.</span></span>
<!--feature detail end -->










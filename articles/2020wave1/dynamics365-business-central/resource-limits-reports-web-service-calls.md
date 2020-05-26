---
title: レポートおよび Web サービス呼び出しに対するリソースの制限
description: Business Central インストールのリソースを保護するために、レポートおよび SOAP Web サービス呼び出しの最大実行時間に制限を構成できるようになりました
author: relnotes
ms.reviewer: jswymer
ms.date: 04/15/2020
ms.assetid: 075dbe76-ea1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 5e9709ea04b6bdff36f3c5cf9ffa085a313226db
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273700"
---
# <a name="resource-limits-for-reports-and-web-service-calls"></a><span data-ttu-id="0234e-103">レポートおよび Web サービス呼び出しに対するリソースの制限</span><span class="sxs-lookup"><span data-stu-id="0234e-103">Resource limits for reports and web service calls</span></span>


| <span data-ttu-id="0234e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0234e-104">Enabled for</span></span>    |  <span data-ttu-id="0234e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0234e-105">Public preview</span></span> | <span data-ttu-id="0234e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0234e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0234e-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="0234e-107">End users, automatically</span></span>|<span data-ttu-id="0234e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0234e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0234e-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0234e-109">Apr 1, 2020</span></span>| <span data-ttu-id="0234e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0234e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0234e-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0234e-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0234e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0234e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0234e-113">誤って設定された Web サービス メソッドが実行されている場合や、ユーザーが誤ってフィルターなしでレポートを開始した場合でも、他のユーザーが作業できるようにします。</span><span class="sxs-lookup"><span data-stu-id="0234e-113">To make sure that other users can work even if a misconfigured web service method is running or a user started a report with no filters by mistake.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0234e-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0234e-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0234e-115">Business Central Server には、管理者がレポートおよび SOAP Web サービスの呼び出し実行時間を制限できる新しい設定が用意されています。</span><span class="sxs-lookup"><span data-stu-id="0234e-115">The Business Central server will have new settings where an administrator can set limits on the execution time for reports and SOAP web service calls.</span></span> <span data-ttu-id="0234e-116">この制限に達すると、サーバーの操作がキャンセルされます。</span><span class="sxs-lookup"><span data-stu-id="0234e-116">When the limit is reached, the server cancels the operation.</span></span>

<span data-ttu-id="0234e-117">Business Central online (サービスとしてのソフトウェア) では、既定値は Business Central 運用チームによって設定され、顧客やパートナーがそれを上書きすることはできません。</span><span class="sxs-lookup"><span data-stu-id="0234e-117">In Business Central online (software as a service), the default values are set by the Business Central operations team and cannot be overridden by customers or partners.</span></span> <span data-ttu-id="0234e-118">2020 年リリース ウェーブ 1 では、既定値は数時間に設定されます (実際の値は未定です)。</span><span class="sxs-lookup"><span data-stu-id="0234e-118">In 2020 release wave 1, the default values will be set to hours (actual values are to be determined).</span></span>

<span data-ttu-id="0234e-119">Business Central (オンプレミス) の場合、管理者がサーバーの設定を制御できます。</span><span class="sxs-lookup"><span data-stu-id="0234e-119">For Business Central (on-premises), an administrator can control the settings in the server.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="0234e-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="0234e-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="0234e-121">[Business Central Server の構成](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/configure-server-instance?) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0234e-121">[Configuring Business Central Server](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/configure-server-instance?) (docs)</span></span>
<!--docs end-->

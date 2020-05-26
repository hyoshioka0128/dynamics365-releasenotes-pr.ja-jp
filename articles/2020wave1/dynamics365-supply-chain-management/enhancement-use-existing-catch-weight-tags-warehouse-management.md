---
title: 倉庫管理で既存の CW タグを使用するための機能強化
description: 農業、食品、鉱業、金属などの一部の産業では、ビジネス プロセス フローで複数の測定単位を使用して製品を追跡する必要があります。
author: relnotes
ms.reviewer: josaw
ms.date: 04/14/2020
ms.assetid: 48e7a756-9363-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 117e5ea41cee0419cbebdd0bdd78b8581510f263
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273062"
---
# <a name="enhancement-to-use-existing-catch-weight-tags-with-warehouse-management"></a><span data-ttu-id="cb688-103">倉庫管理で既存の CW タグを使用するための機能強化</span><span class="sxs-lookup"><span data-stu-id="cb688-103">Enhancement to use existing catch weight tags with warehouse management</span></span>


| <span data-ttu-id="cb688-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cb688-104">Enabled for</span></span>    |  <span data-ttu-id="cb688-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cb688-105">Public preview</span></span> | <span data-ttu-id="cb688-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cb688-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cb688-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="cb688-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="cb688-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cb688-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cb688-109">2020 年 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="cb688-109">Mar 6, 2020</span></span>| <span data-ttu-id="cb688-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cb688-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cb688-111">2020 年 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="cb688-111">Apr 10, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="cb688-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cb688-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cb688-113">この機能は、適切な注文の CW タグが事前に登録されている場合に、モバイル デバイスを使用して製造オーダーが完了したことを報告するためのサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="cb688-113">This feature adds support for using a mobile device to report a production order as finished when catch weight tags have been registered in advance for the appropriate order.</span></span>

<span data-ttu-id="cb688-114">**モバイル デバイスのメニュー品目**ページを使用して、_完了レポートとプット アウェイ_作業の作成プロセスを使用するすべてのモバイル デバイスのメニュー品目に追加します。</span><span class="sxs-lookup"><span data-stu-id="cb688-114">Use the **Mobile device menu items** page to add this feature to any mobile-device menu item that uses the _Report as finished and put away_ work creation process.</span></span> <span data-ttu-id="cb688-115">この機能では、使用されるメニュー項目に対して **CW タグの生成**設定を無効にする必要があり、**製品、追跡、およびすべての保管分析コード**の CW タグ追跡を **CW 品目の取り扱いに関するポリシー**設定の一部として使用する必要もあります。</span><span class="sxs-lookup"><span data-stu-id="cb688-115">The feature requires that the **Generate catch weight tag** setting be disabled for the used menu item, and also that you are using catch weight tag tracking for **Product, tracking, and all storage dimensions** as part of the **Catch weight item handling policy** setup.</span></span>

<span data-ttu-id="cb688-116">この機能を使用するには、[機能管理](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json)で、_製造オーダーの完了をレポートするときに既存の CW タグを使用する_機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb688-116">To use this capability, you must enable the _Use existing catch weight tags when reporting production orders as finished_ feature in [Feature management](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="cb688-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="cb688-117">See also</span></span>

<!--docs start-->
<span data-ttu-id="cb688-118">[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="cb688-118">[Catch weight product processing with warehouse management](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (docs)</span></span>
<!--docs end-->

---
title: 倉庫管理で既存の CW タグを使用するための機能強化
description: 農業、食品、鉱業、金属などの一部の産業では、ビジネス プロセス フローで複数の測定単位を使用して製品を追跡する必要があります。
author: relnotes
ms.reviewer: josaw
ms.date: 03/13/2020
ms.assetid: 48e7a756-9363-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: fd9a6a19bac6135621543af306c8d270f567b2ce
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232321"
---
# <a name="enhancement-to-use-existing-catch-weight-tags-with-warehouse-management"></a><span data-ttu-id="64bd2-103">倉庫管理で既存の CW タグを使用するための機能強化</span><span class="sxs-lookup"><span data-stu-id="64bd2-103">Enhancement to use existing catch weight tags with warehouse management</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="64bd2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="64bd2-104">Enabled for</span></span>    |  <span data-ttu-id="64bd2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="64bd2-105">Public preview</span></span> | <span data-ttu-id="64bd2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="64bd2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="64bd2-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="64bd2-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="64bd2-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="64bd2-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="64bd2-109">2020 年 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="64bd2-109">Mar 6, 2020</span></span>| <span data-ttu-id="64bd2-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="64bd2-110">Apr 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="64bd2-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="64bd2-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="64bd2-112">この機能は、適切な注文の CW タグが事前に登録されている場合に、モバイル デバイスを使用して製造オーダーが完了したことを報告するためのサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="64bd2-112">This feature adds support for using a mobile device to report a production order as finished when catch weight tags have been registered in advance for the appropriate order.</span></span>

<span data-ttu-id="64bd2-113">**モバイル デバイスのメニュー品目**ページを使用して、_完了レポートとプット アウェイ_作業の作成プロセスを使用するすべてのモバイル デバイスのメニュー品目に追加します。</span><span class="sxs-lookup"><span data-stu-id="64bd2-113">Use the **Mobile device menu items** page to add this feature to any mobile-device menu item that uses the _Report as finished and put away_ work creation process.</span></span> <span data-ttu-id="64bd2-114">この機能では、使用されるメニュー項目に対して **CW タグの生成**設定を無効にする必要があり、**製品、追跡、およびすべての保管分析コード**の CW タグ追跡を **CW 品目の取り扱いに関するポリシー**設定の一部として使用する必要もあります。</span><span class="sxs-lookup"><span data-stu-id="64bd2-114">The feature requires that the **Generate catch weight tag** setting be disabled for the used menu item, and also that you are using catch weight tag tracking for **Product, tracking, and all storage dimensions** as part of the **Catch weight item handling policy** setup.</span></span>

<span data-ttu-id="64bd2-115">この機能を使用するには、[機能管理](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json)で、_製造オーダーの完了をレポートするときに既存の CW タグを使用する_機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="64bd2-115">To use this capability, you must enable the _Use existing catch weight tags when reporting production orders as finished_ feature in [Feature management](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json).</span></span> 

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="64bd2-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="64bd2-116">See also</span></span>


<!--docs start-->
<span data-ttu-id="64bd2-117">[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="64bd2-117">[Catch weight product processing with warehouse management](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (docs)</span></span>
<!--docs end-->


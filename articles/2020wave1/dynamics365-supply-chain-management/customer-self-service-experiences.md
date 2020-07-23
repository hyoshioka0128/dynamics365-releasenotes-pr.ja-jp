---
title: Dynamics 365 Supply Chain Management のカスタマー ポータル
description: 基本的な管理機能と照会機能を提供するための顧客セルフサービスの機能強化。
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/02/2020
ms.assetid: 19ca3ae8-64cb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: damadipa
dynamics365pdf: true
ms.openlocfilehash: 2c32d03fd38f49d61a8985b6e9776d4bb2ad393c
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441724"
---
# <a name="customer-portal-for-dynamics-365-supply-chain-management"></a><span data-ttu-id="cd2d3-103">Dynamics 365 Supply Chain Management のカスタマー ポータル</span><span class="sxs-lookup"><span data-stu-id="cd2d3-103">Customer portal for Dynamics 365 Supply Chain Management</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="cd2d3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cd2d3-104">Enabled for</span></span>    |  <span data-ttu-id="cd2d3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cd2d3-105">Public preview</span></span> | <span data-ttu-id="cd2d3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cd2d3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cd2d3-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="cd2d3-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="cd2d3-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cd2d3-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cd2d3-109">2020 年 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="cd2d3-109">May 29, 2020</span></span>| <span data-ttu-id="cd2d3-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="cd2d3-110">Jun 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="cd2d3-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cd2d3-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cd2d3-112">カスタマー ポータル テンプレートは Power Apps テンプレート ギャラリーで利用できる Power Apps ポータル テンプレートです。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-112">The customer portal template is a Power Apps portals template that will be available in the Power Apps template gallery.</span></span> <span data-ttu-id="cd2d3-113">これにより、企業は Dynamics 365 Supply Chain Management 環境に接続された外部向け Web サイトを作成できます。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-113">It allows companies to create an externally facing website that is connected to a Dynamics 365 Supply Chain Management environment.</span></span>

<span data-ttu-id="cd2d3-114">このテンプレートは、エンドツーエンドのソリューション全体を提供するのではなく、企業間 (B2B) の受注処理および関連シナリオ用のカスタム Web サイトを作成するためのガイダンスと開始点を提供します。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-114">The template doesn't provide an entire end-to-end solution, but instead provides guidance and a starting point for creating custom websites for business-to-business (B2B) sales-order processing and related scenarios.</span></span> <span data-ttu-id="cd2d3-115">企業が二重書き込み、Power Apps ポータル、および Dynamics 365 Supply Chain Management を寄せ集めて企業顧客向けのセルフサービス エクスペリエンスを作成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-115">It helps companies bring dual-write, Power Apps portals, and Dynamics 365 Supply Chain Management together to create a self-service experience for their enterprise customers.</span></span>

<span data-ttu-id="cd2d3-116">すぐに使えるテンプレートには、次の機能が用意されています。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-116">Out of the box, the template provides the following functionality:</span></span>

- <span data-ttu-id="cd2d3-117">注文履歴の表示。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-117">View order history.</span></span>
- <span data-ttu-id="cd2d3-118">勘定情報の表示。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-118">View account information.</span></span>
- <span data-ttu-id="cd2d3-119">注文の作成。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-119">Create orders.</span></span>
- <span data-ttu-id="cd2d3-120">Power Apps ポータル ユーザーの事前構成済み Web ロールとエンティティのアクセス許可。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-120">Preconfigured web roles and entity permissions for Power Apps portals users.</span></span>

<span data-ttu-id="cd2d3-121">これは Power Apps ポータル テンプレートであるため、システム カスタマイザーは Power Apps ポータルが提供するすべての機能とカスタマイズ機能を使用できます。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-121">Because this is a Power Apps portals template, system customizers can use all features and customization capabilities that Power Apps portals offers.</span></span> <span data-ttu-id="cd2d3-122">二重書き込みでサポートされる範囲まで機能を拡張することもできます。</span><span class="sxs-lookup"><span data-stu-id="cd2d3-122">They will also be able to extend the functionality to the extent supported by dual-write.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="cd2d3-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="cd2d3-123">See also</span></span>

<!--docs start-->
<span data-ttu-id="cd2d3-124">[Dynamics 365 Supply Chain Management の顧客ポータルの概要](https://docs.microsoft.com/dynamics365/supply-chain/sales-marketing/customer-portal-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="cd2d3-124">[Customer portal for Dynamics 365 Supply Chain Management overview](https://docs.microsoft.com/dynamics365/supply-chain/sales-marketing/customer-portal-overview) (docs)</span></span>
<!--docs end-->

---
title: シークレットへの安全なアクセス
description: シークレットへの安全なアクセス
author: relnotes
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: 5c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: aamiral
dynamics365pdf: true
ms.openlocfilehash: 49f553682beb32ecf657dd748518af05d62cf481
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143489"
---
# <a name="secure-access-to-secrets"></a><span data-ttu-id="60ca9-103">シークレットへの安全なアクセス</span><span class="sxs-lookup"><span data-stu-id="60ca9-103">Secure access to secrets</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="60ca9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="60ca9-104">Enabled for</span></span>    |  <span data-ttu-id="60ca9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="60ca9-105">Public preview</span></span> | <span data-ttu-id="60ca9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="60ca9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="60ca9-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="60ca9-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="60ca9-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="60ca9-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="60ca9-109">2019 年 9 月 3 日</span><span class="sxs-lookup"><span data-stu-id="60ca9-109">Sep 3, 2019</span></span>| <span data-ttu-id="60ca9-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="60ca9-110">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="60ca9-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="60ca9-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="60ca9-112">この機能では、Azure Key Vault を使用して顧客が所有するシークレットにアクセスするためのカスタマイズに対して、標準化された安全なメカニズムを可能にします。</span><span class="sxs-lookup"><span data-stu-id="60ca9-112">This feature will enable a standardized and secure mechanism for customizations to access customer-owned secrets using Azure Key Vault.</span></span> <span data-ttu-id="60ca9-113">Retail Cloud Scale Unit (RCSU) でホストされているカスタマイズは、顧客所有のキー コンテナーにアクセスして、シークレットを安全に取得して (たとえば外部システムに接続するために) 使用できます。</span><span class="sxs-lookup"><span data-stu-id="60ca9-113">Customizations hosted in Retail Cloud Scale Unit (RCSU) will be able to access a customer-owned key vault to securely retrieve secrets and use them—for example, to connect to external systems.</span></span> <span data-ttu-id="60ca9-114">これにより、カスタマイズでシークレットと認証情報を使用する安全で管理しやすい手段が提供されます。</span><span class="sxs-lookup"><span data-stu-id="60ca9-114">This will provide a secure and manageable means of using secrets and credentials within customizations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="60ca9-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="60ca9-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="60ca9-116">この機能を使用すると、IT 技術者は、Azure Key Vault を使用して構成とシークレットを安全に使用し、Dynamics 365 内のサード パーティ システムと統合できます。</span><span class="sxs-lookup"><span data-stu-id="60ca9-116">This feature will enable an IT pro to securely use configurations and secrets using Azure Key Vault for integrating with third-party systems within Dynamics 365.</span></span>
<!--feature detail end -->






## <a name="see-also"></a><span data-ttu-id="60ca9-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="60ca9-117">See also</span></span>

<span data-ttu-id="60ca9-118">[小売チャネルのシークレットを管理する](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/manage-secrets) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="60ca9-118">[Manage secrets for Retail channels](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/manage-secrets) (docs)</span></span>

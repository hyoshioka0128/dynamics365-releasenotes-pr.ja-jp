---
title: シークレットへの安全なアクセス
description: シークレットへの安全なアクセス
author: relnotes
ms.reviewer: josaw
ms.date: 07/22/2019
ms.assetid: 5c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: aamiral
dynamics365pdf: true
ms.openlocfilehash: 8a7ac2e8486f6ce37b64a0e8a4d62bee1d5f1ea9
ms.sourcegitcommit: 4101748c25acf79b22e31a01b73969500926ff91
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1794016"
---
# <a name="secure-access-to-secrets"></a><span data-ttu-id="bbeea-103">シークレットへの安全なアクセス</span><span class="sxs-lookup"><span data-stu-id="bbeea-103">Secure access to secrets</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="bbeea-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bbeea-104">Enabled for</span></span>    |  <span data-ttu-id="bbeea-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bbeea-105">Public preview</span></span> | <span data-ttu-id="bbeea-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bbeea-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="bbeea-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="bbeea-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="bbeea-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="bbeea-108">September 2019</span></span>| <span data-ttu-id="bbeea-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="bbeea-109">November 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="bbeea-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bbeea-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bbeea-111">この機能では、Azure Key Vault を使用して顧客が所有するシークレットにアクセスするためのカスタマイズに対して、標準化された安全なメカニズムを可能にします。</span><span class="sxs-lookup"><span data-stu-id="bbeea-111">This feature will enable a standardized and secure mechanism for customizations to access customer-owned secrets using Azure Key Vault.</span></span> <span data-ttu-id="bbeea-112">Retail Cloud Scale Unit (RCSU) でホストされているカスタマイズは、顧客所有のキー コンテナーにアクセスして、シークレットを安全に取得して (たとえば外部システムに接続するために) 使用できます。</span><span class="sxs-lookup"><span data-stu-id="bbeea-112">Customizations hosted in Retail Cloud Scale Unit (RCSU) will be able to access a customer-owned key vault to securely retrieve secrets and use them—for example, to connect to external systems.</span></span> <span data-ttu-id="bbeea-113">これにより、カスタマイズでシークレットと認証情報を使用する安全で管理しやすい手段が提供されます。</span><span class="sxs-lookup"><span data-stu-id="bbeea-113">This will provide a secure and manageable means of using secrets and credentials within customizations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bbeea-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bbeea-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bbeea-115">この機能を使用すると、IT 技術者は、Azure Key Vault を使用して構成とシークレットを安全に使用し、Dynamics 365 内のサード パーティ システムと統合できます。</span><span class="sxs-lookup"><span data-stu-id="bbeea-115">This feature will enable an IT pro to securely use configurations and secrets using Azure Key Vault for integrating with third-party systems within Dynamics 365.</span></span>
<!--feature detail end -->












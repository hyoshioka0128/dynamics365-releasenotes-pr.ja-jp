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
ms.openlocfilehash: 1f38926229b6166601979e56570f507542f47105
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659775"
---
# <a name="secure-access-to-secrets"></a><span data-ttu-id="b3c5b-103">シークレットへの安全なアクセス</span><span class="sxs-lookup"><span data-stu-id="b3c5b-103">Secure access to secrets</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="b3c5b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b3c5b-104">Enabled for</span></span>    |  <span data-ttu-id="b3c5b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b3c5b-105">Public preview</span></span> | <span data-ttu-id="b3c5b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b3c5b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b3c5b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="b3c5b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="b3c5b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b3c5b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b3c5b-109">2019 年 9 月 3 日</span><span class="sxs-lookup"><span data-stu-id="b3c5b-109">Sep 3, 2019</span></span>| <span data-ttu-id="b3c5b-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="b3c5b-110">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b3c5b-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b3c5b-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b3c5b-112">この機能では、Azure Key Vault を使用して顧客が所有するシークレットにアクセスするためのカスタマイズに対して、標準化された安全なメカニズムを可能にします。</span><span class="sxs-lookup"><span data-stu-id="b3c5b-112">This feature will enable a standardized and secure mechanism for customizations to access customer-owned secrets using Azure Key Vault.</span></span> <span data-ttu-id="b3c5b-113">Retail Cloud Scale Unit (RCSU) でホストされているカスタマイズは、顧客所有のキー コンテナーにアクセスして、シークレットを安全に取得して (たとえば外部システムに接続するために) 使用できます。</span><span class="sxs-lookup"><span data-stu-id="b3c5b-113">Customizations hosted in Retail Cloud Scale Unit (RCSU) will be able to access a customer-owned key vault to securely retrieve secrets and use them—for example, to connect to external systems.</span></span> <span data-ttu-id="b3c5b-114">これにより、カスタマイズでシークレットと認証情報を使用する安全で管理しやすい手段が提供されます。</span><span class="sxs-lookup"><span data-stu-id="b3c5b-114">This will provide a secure and manageable means of using secrets and credentials within customizations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b3c5b-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b3c5b-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b3c5b-116">この機能を使用すると、IT 技術者は、Azure Key Vault を使用して構成とシークレットを安全に使用し、Dynamics 365 内のサード パーティ システムと統合できます。</span><span class="sxs-lookup"><span data-stu-id="b3c5b-116">This feature will enable an IT pro to securely use configurations and secrets using Azure Key Vault for integrating with third-party systems within Dynamics 365.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b3c5b-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="b3c5b-117">See also</span></span>

<span data-ttu-id="b3c5b-118">[小売チャネルのシークレットを管理する](https://docs.microsoft.com/dynamics365/unified-operations/retail/manage-secrets) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b3c5b-118">[Manage secrets for Retail channels](https://docs.microsoft.com/dynamics365/unified-operations/retail/manage-secrets) (docs)</span></span>

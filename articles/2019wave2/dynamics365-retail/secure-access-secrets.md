---
title: シークレットへの安全なアクセス
description: シークレットへの安全なアクセス
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 5c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: aamiral
dynamics365pdf: true
ms.openlocfilehash: 5b842d67e46543b650c99d0c29ee2e35f219d1de
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889972"
---
# <a name="secure-access-to-secrets"></a><span data-ttu-id="c857e-103">シークレットへの安全なアクセス</span><span class="sxs-lookup"><span data-stu-id="c857e-103">Secure access to secrets</span></span>


| <span data-ttu-id="c857e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c857e-104">Enabled for</span></span>    |  <span data-ttu-id="c857e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c857e-105">Public preview</span></span> | <span data-ttu-id="c857e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c857e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c857e-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="c857e-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="c857e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c857e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c857e-109">2019 年 9 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c857e-109">Sep 3, 2019</span></span>| <span data-ttu-id="c857e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c857e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c857e-111">2019 年 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c857e-111">Nov 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="c857e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c857e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c857e-113">この機能では、Azure Key Vault を使用して顧客が所有するシークレットにアクセスするためのカスタマイズに対して、標準化された安全なメカニズムを可能にします。</span><span class="sxs-lookup"><span data-stu-id="c857e-113">This feature will enable a standardized and secure mechanism for customizations to access customer-owned secrets using Azure Key Vault.</span></span> <span data-ttu-id="c857e-114">Retail Cloud Scale Unit (RCSU) でホストされているカスタマイズは、顧客所有のキー コンテナーにアクセスして、シークレットを安全に取得して (たとえば外部システムに接続するために) 使用できます。</span><span class="sxs-lookup"><span data-stu-id="c857e-114">Customizations hosted in Retail Cloud Scale Unit (RCSU) will be able to access a customer-owned key vault to securely retrieve secrets and use them—for example, to connect to external systems.</span></span> <span data-ttu-id="c857e-115">これにより、カスタマイズでシークレットと認証情報を使用する安全で管理しやすい手段が提供されます。</span><span class="sxs-lookup"><span data-stu-id="c857e-115">This will provide a secure and manageable means of using secrets and credentials within customizations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c857e-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c857e-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c857e-117">この機能を使用すると、IT 技術者は、Azure Key Vault を使用して構成とシークレットを安全に使用し、Dynamics 365 内のサード パーティ システムと統合できます。</span><span class="sxs-lookup"><span data-stu-id="c857e-117">This feature will enable an IT pro to securely use configurations and secrets using Azure Key Vault for integrating with third-party systems within Dynamics 365.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c857e-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="c857e-118">See also</span></span>

<span data-ttu-id="c857e-119">[小売チャネルのシークレットを管理する](https://docs.microsoft.com/dynamics365/retail/dev-itpro/manage-secrets) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c857e-119">[Manage secrets for retail channels](https://docs.microsoft.com/dynamics365/retail/dev-itpro/manage-secrets) (docs)</span></span>

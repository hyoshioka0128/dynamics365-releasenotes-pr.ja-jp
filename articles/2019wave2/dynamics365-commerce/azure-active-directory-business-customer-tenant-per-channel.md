---
title: チャネルごとの Azure Active Directory 企業と顧客間テナント
description: チャネルごとの Azure Active Directory 企業と顧客間テナント
author: relnotes
ms.reviewer: josaw
ms.date: 11/25/2019
ms.assetid: a4013e72-aff6-e911-a813-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: c3ca473aef47b71a506de0f88081b2c1a6b06445
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890447"
---
# <a name="azure-active-directory-business-to-customer-tenant-per-channel"></a><span data-ttu-id="aba16-103">チャネルごとの Azure Active Directory 企業と顧客間テナント</span><span class="sxs-lookup"><span data-stu-id="aba16-103">Azure Active Directory business to customer tenant per channel</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="aba16-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="aba16-104">Enabled for</span></span>    |  <span data-ttu-id="aba16-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aba16-105">Public preview</span></span> | <span data-ttu-id="aba16-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="aba16-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aba16-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="aba16-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="aba16-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="aba16-108">Feb 2020</span></span>| <span data-ttu-id="aba16-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="aba16-109">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="aba16-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="aba16-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="aba16-111">この機能は、サイトとチャネルを個別のブランドとして扱う企業にとって価値があります。</span><span class="sxs-lookup"><span data-stu-id="aba16-111">This feature is valuable to companies that treat their sites and channels as distinct brands.</span></span> <span data-ttu-id="aba16-112">エンド ユーザーは、同じ法人の下で維持されるサイトおよびチャネルごとに別々のログイン資格情報を持ちます。</span><span class="sxs-lookup"><span data-stu-id="aba16-112">End users have separate login credentials per sites and channels maintained under the same legal entity.</span></span> <span data-ttu-id="aba16-113">この機能は、企業が自社のブランドのルック アンド フィールを別のビジネスのように見せたいが、ブランドを横断する可能性のある在庫や製品は複製したくない場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="aba16-113">This feature is used when a company wants their brand to look and feel like a separate business, but they don't want to replicate inventory and products that may cross brands.</span></span> <span data-ttu-id="aba16-114">この機能により、顧客は各ブランドの複製を別々の法人で実行する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="aba16-114">This feature will save customers from having to perform those replications for each brand in a separate legal entity.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="aba16-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aba16-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aba16-116">顧客は、エンド ユーザーからは別々のビジネスのように見え、感じられるサイトやチャネルを単一の法人の下で使用することを選択できます。</span><span class="sxs-lookup"><span data-stu-id="aba16-116">Customers can choose to use, under a single legal entity, sites and channels that look like and feel like separate businesses to their end users.</span></span> <span data-ttu-id="aba16-117">マイクロソフトは、個別の Azure AD B2C テナントをチャネルにマップする機能をサポートするようになったため、エンド ユーザーはチャネルおよびサイトごとに完全に異なるログイン資格情報を持ちます。</span><span class="sxs-lookup"><span data-stu-id="aba16-117">Microsoft now supports the ability to map a separate Azure AD B2C tenants to a channel, so the end user has fully distinct login credentials per channel and site.</span></span> <span data-ttu-id="aba16-118">エンド ユーザーは、チャネル固有のサイトに明確に移動し、参照し、そこでトランザクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="aba16-118">An end user would navigate to, browse, and perform transactions on the channel-specific site distinctly.</span></span> <span data-ttu-id="aba16-119">コマースの顧客は、自身の環境でこの機能を有効にする必要があります。システム管理者は、Web Storefront Administration ツールでチャネルベースの B2C テナントを構成できます。</span><span class="sxs-lookup"><span data-stu-id="aba16-119">Commerce customers will need to enable this feature for their environment, and system admins will have the ability to configure channel-based B2C tenants in the Web Storefront Administration tooling.</span></span> <span data-ttu-id="aba16-120">顧客は環境あたり 1 つの Azure AD B2C テナントに制限されなくなり、サイトレベルのログインおよび ID エクスペリエンスをより細かく制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="aba16-120">Customers will no longer be limited to a single Azure AD B2C tenant per environment, giving more control to the site-level login and Identity experience.</span></span>
<!--feature detail end -->










---
title: Regulatory Configuration Service での簡素化されたローカライズ構成管理
description: Regulatory Configuration Service (RCS) を使用すると、企業やパワー ユーザーは、法的要件の変更によって頻繁に影響を受ける規制レポート、請求書、支払方法、および税規則を構成できます。 これらの構成は、複数のアプリケーションで共有して再利用できます。 これらの構成の保存、処理、および共有を簡素化するために、RCS では新しいタイプのグローバル リポジトリがサポートされます。これを使用して、ユーザーは自分の構成を直接 RCS で一元的に格納および管理できます。
author: relnotes
ms.reviewer: sericks
ms.date: 09/18/2019
ms.assetid: dc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: janeaug
dynamics365pdf: true
ms.openlocfilehash: c9b0fd16e5ea2c785601d13ad2e83772e21c2f8a
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668007"
---
# <a name="simplified-localization-configuration-management-in-regulatory-configuration-service"></a><span data-ttu-id="aa627-105">Regulatory Configuration Service での簡素化されたローカライズ構成管理</span><span class="sxs-lookup"><span data-stu-id="aa627-105">Simplified localization configuration management in Regulatory Configuration Service</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="aa627-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="aa627-106">Enabled for</span></span>    |  <span data-ttu-id="aa627-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aa627-107">Public preview</span></span> | <span data-ttu-id="aa627-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="aa627-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aa627-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="aa627-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="aa627-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="aa627-110">Oct 2019</span></span>| <span data-ttu-id="aa627-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="aa627-111">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="aa627-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="aa627-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="aa627-113">現在、ユーザーは、Microsoft Dynamics Lifecycle Services (LCS) を利用して、構成を公開およびエクスポートし、それらを外部のユーザーまたは組織と共有するためには、複数ステップのプロセスを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="aa627-113">Currently, users need to complete a multistep process to leverage Microsoft Dynamics Lifecycle Services (LCS) in order to publish and export their configurations and share them with external users or organizations.</span></span> <span data-ttu-id="aa627-114">Regulatory Configuration Service (RCS) の新しい集中構成ストレージを使用することで、ユーザーは構成デザイナーから直接構成を簡単に共有できます。</span><span class="sxs-lookup"><span data-stu-id="aa627-114">By using the new centralized configuration storage in the Regulatory Configuration Service (RCS), users will be able to easily share their configurations directly from the configuration designer.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="aa627-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aa627-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aa627-116">2019 年リリース ウェーブ 2 の一部として、以下の機能が RCS でサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="aa627-116">As part of 2019 release wave 2, the following capabilities will be supported in RCS:</span></span> 

-  <span data-ttu-id="aa627-117">ユーザーは、Microsoft が作成したすべての構成に、RCS で直接アクセスできます (LCS を使用せずに)。</span><span class="sxs-lookup"><span data-stu-id="aa627-117">Users will have access to all Microsoft-produced configurations directly in RCS (without using LCS).</span></span> 
-  <span data-ttu-id="aa627-118">ユーザーは、自分の組織でそれらの構成を一元的に保存、公開、および共有することができます。</span><span class="sxs-lookup"><span data-stu-id="aa627-118">Users will be able to centrally store, publish, and share their configurations with their own organization.</span></span> 
-  <span data-ttu-id="aa627-119">ユーザーは、外部のユーザーまたは組織と構成を共有することができます。</span><span class="sxs-lookup"><span data-stu-id="aa627-119">Users will have the ability to share configurations with external users or organizations.</span></span> 
-  <span data-ttu-id="aa627-120">ユーザーは、新しい構成を外部のユーザーまたは組織に配信 (プッシュ) できます。</span><span class="sxs-lookup"><span data-stu-id="aa627-120">Users will be able to broadcast (push) new configurations to external users or organizations.</span></span>
<!--feature detail end -->










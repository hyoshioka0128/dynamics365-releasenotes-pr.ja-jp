---
title: Regulatory Configuration Service での簡素化されたローカライズ構成管理
description: Regulatory Configuration Service (RCS) を使用すると、企業やパワー ユーザーは、法的要件の変更によって頻繁に影響を受ける規制レポート、請求書、支払方法、および税規則を構成できます。 これらの構成は、複数のアプリケーションで共有して再利用できます。 これらの構成の保存、処理、および共有を簡素化するために、RCS では新しいタイプのグローバル リポジトリがサポートされます。これを使用して、ユーザーは自分の構成を直接 RCS で一元的に格納および管理できます。
author: relnotes
ms.reviewer: kfend
ms.date: 12/16/2019
ms.assetid: dc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: janeaug
dynamics365pdf: true
ms.openlocfilehash: a99a9a08c78d21959f3ac7200bcc24166ed273dd
ms.sourcegitcommit: ecf709e1d8de3b52e1156bceb99cb7e3819f9db3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/13/2020
ms.locfileid: "2950936"
---
# <a name="simplified-localization-configuration-management-in-regulatory-configuration-service"></a><span data-ttu-id="b5693-105">Regulatory Configuration Service での簡素化されたローカライズ構成管理</span><span class="sxs-lookup"><span data-stu-id="b5693-105">Simplified localization configuration management in Regulatory Configuration Service</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="b5693-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="b5693-106">Enabled for</span></span>    |  <span data-ttu-id="b5693-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b5693-107">Public preview</span></span> | <span data-ttu-id="b5693-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="b5693-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b5693-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b5693-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b5693-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b5693-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b5693-111">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="b5693-111">Oct 31, 2019</span></span>| <span data-ttu-id="b5693-112">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="b5693-112">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b5693-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b5693-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b5693-114">現在、ユーザーは、Microsoft Dynamics Lifecycle Services (LCS) を利用して、構成を公開およびエクスポートし、それらを外部のユーザーまたは組織と共有するためには、複数ステップのプロセスを完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b5693-114">Currently, users need to complete a multistep process to leverage Microsoft Dynamics Lifecycle Services (LCS) in order to publish and export their configurations and share them with external users or organizations.</span></span> <span data-ttu-id="b5693-115">Regulatory Configuration Service (RCS) の新しい集中構成ストレージを使用することで、ユーザーは構成デザイナーから直接構成を簡単に共有できます。</span><span class="sxs-lookup"><span data-stu-id="b5693-115">By using the new centralized configuration storage in the Regulatory Configuration Service (RCS), users will be able to easily share their configurations directly from the configuration designer.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b5693-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b5693-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b5693-117">2019 年リリース ウェーブ 2 の一部として、以下の機能が RCS でサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="b5693-117">As part of 2019 release wave 2, the following capabilities will be supported in RCS:</span></span> 

-  <span data-ttu-id="b5693-118">ユーザーは、Microsoft が作成したすべての構成に、RCS で直接アクセスできます (LCS を使用せずに)。</span><span class="sxs-lookup"><span data-stu-id="b5693-118">Users will have access to all Microsoft-produced configurations directly in RCS (without using LCS).</span></span> 
-  <span data-ttu-id="b5693-119">ユーザーは、自分の組織でそれらの構成を一元的に保存、公開、および共有することができます。</span><span class="sxs-lookup"><span data-stu-id="b5693-119">Users will be able to centrally store, publish, and share their configurations with their own organization.</span></span> 
-  <span data-ttu-id="b5693-120">ユーザーは、外部のユーザーまたは組織と構成を共有することができます。</span><span class="sxs-lookup"><span data-stu-id="b5693-120">Users will have the ability to share configurations with external users or organizations.</span></span> 
-  <span data-ttu-id="b5693-121">ユーザーは、新しい構成を外部のユーザーまたは組織に配信 (プッシュ) できます。</span><span class="sxs-lookup"><span data-stu-id="b5693-121">Users will be able to broadcast (push) new configurations to external users or organizations.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b5693-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="b5693-122">See also</span></span>

<span data-ttu-id="b5693-123">[コンフィギュレーション規制コンフィギュレーション サービス (RCS) からの電子申告 (ER) 構成のインポート](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/analytics/rcs-download-configurations?toc=/dynamics365/commerce/toc.json) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b5693-123">[Import Electronic reporting (ER) configurations from Regulatory Configuration Services (RCS)](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/analytics/rcs-download-configurations?toc=/dynamics365/commerce/toc.json) (docs)</span></span>

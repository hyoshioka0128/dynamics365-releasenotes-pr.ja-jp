---
title: Field Service Mobile に対する Intune のサポート
description: Microsoft Intune で Field Service Mobile アプリを管理します。
author: relnotes
ms.reviewer: krbjoran
ms.date: 01/13/2020
ms.assetid: ca0bd932-96ef-e911-a812-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jobaker
dynamics365pdf: true
ms.openlocfilehash: 7ff9e97e8171357b2930e697d375da1a3282744e
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986777"
---
# <a name="intune-support-for-field-service-mobile"></a><span data-ttu-id="3428f-103">Field Service Mobile に対する Intune のサポート</span><span class="sxs-lookup"><span data-stu-id="3428f-103">Intune support for Field Service Mobile</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="3428f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3428f-104">Enabled for</span></span>    |  <span data-ttu-id="3428f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3428f-105">Public preview</span></span> | <span data-ttu-id="3428f-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="3428f-106">Early access</span></span> | <span data-ttu-id="3428f-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="3428f-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="3428f-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3428f-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3428f-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="3428f-109">Feb 2020</span></span>|-| <span data-ttu-id="3428f-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="3428f-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3428f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3428f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3428f-112">企業は、Microsoft Intune の機能を利用して、Field Service Mobile アプリを管理できます。</span><span class="sxs-lookup"><span data-stu-id="3428f-112">Businesses can take advantage of the power of Microsoft Intune to manage the Field Service Mobile app.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3428f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3428f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3428f-114">セキュリティとデータ保護は、特に現場に展開する技術者と仕事をする場合、企業にとって重要です。</span><span class="sxs-lookup"><span data-stu-id="3428f-114">Security and data protection are important for businesses, especially when working with technical employees deployed in the field.</span></span> <span data-ttu-id="3428f-115">Intune により、一元的に管理された制御層がデバイスに形成されます。これは、企業が管理するデバイスと私的デバイスを活用するシナリオの両方に対応します。</span><span class="sxs-lookup"><span data-stu-id="3428f-115">Intune brings this layer of centrally managed control to devices, including corporate-managed devices and bring-your-own-device scenarios.</span></span> <span data-ttu-id="3428f-116">Intune によって管理者は、Intune の標準インフラストラクチャとコントロールを介して、Field Service Mobile アプリケーションを iOS と Android を使用するフィールド技術者に展開できます。</span><span class="sxs-lookup"><span data-stu-id="3428f-116">With Intune, administrators can roll out the Field Service Mobile application to their iOS and Android field technicians via standard Intune infrastructure and controls.</span></span>   

<span data-ttu-id="3428f-117">この機能により、Field Service Mobile アプリを Intune 管理エクスペリエンス内のファーストパーティ アプリケーションにすることができます。</span><span class="sxs-lookup"><span data-stu-id="3428f-117">This feature enables the Field Service Mobile app as a first-party application within the Intune administration experience.</span></span> <span data-ttu-id="3428f-118">Intune サポートを有効化すると、企業は、展開、構成、セキュリティ、更新など、Intune の機能をすべて利用できます。</span><span class="sxs-lookup"><span data-stu-id="3428f-118">By enabling Intune support, businesses can take advantage of all Intune features including deployment, configuration, security, and updates.</span></span>    

<span data-ttu-id="3428f-119">Intune に対応した Field Service Mobile アプリで IT 管理者は次のことが可能です。</span><span class="sxs-lookup"><span data-stu-id="3428f-119">With an Intune-enabled Field Service Mobile app, IT administrators can:</span></span> 

- <span data-ttu-id="3428f-120">Field Service Mobile アプリを追加して、特定のグループのユーザー、特定のグループのデバイスなどを含む、ユーザー グループとデバイスに割り当てます。</span><span class="sxs-lookup"><span data-stu-id="3428f-120">Add and assign your Field Service Mobile app to user groups and devices, including users in specific groups, devices in specific groups, and more.</span></span> 
- <span data-ttu-id="3428f-121">Field Service Mobile アプリを構成して、特定の設定を有効にして起動または実行し、既にデバイスにある場合は既存のアプリを更新します。</span><span class="sxs-lookup"><span data-stu-id="3428f-121">Configure the Field Service Mobile app to start or run with specific settings enabled and update your existing app when already on the device.</span></span> 
- <span data-ttu-id="3428f-122">レポートを表示してアプリの使用状況を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3428f-122">See reports and track app usage.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="3428f-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="3428f-123">This feature is available in the Unified Interface only.</span></span>







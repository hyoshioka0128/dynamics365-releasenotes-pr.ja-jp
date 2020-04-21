---
title: Field Service Mobile に対する Intune のサポート
description: Microsoft Intune で Field Service Mobile アプリを管理します。
author: relnotes
ms.reviewer: krbjoran
ms.date: 02/24/2020
ms.assetid: ca0bd932-96ef-e911-a812-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jobaker
dynamics365pdf: true
ms.openlocfilehash: de9e3fa60e9dfc1169affab8a57c298c54f711f0
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232079"
---
# <a name="intune-support-for-field-service-mobile"></a><span data-ttu-id="9d815-103">Field Service Mobile に対する Intune のサポート</span><span class="sxs-lookup"><span data-stu-id="9d815-103">Intune support for Field Service Mobile</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="9d815-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9d815-104">Enabled for</span></span>    |  <span data-ttu-id="9d815-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9d815-105">Public preview</span></span> | <span data-ttu-id="9d815-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9d815-106">Early access</span></span> | <span data-ttu-id="9d815-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9d815-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9d815-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9d815-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9d815-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9d815-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9d815-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9d815-110">Feb 3, 2020</span></span>|-| <span data-ttu-id="9d815-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="9d815-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9d815-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9d815-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9d815-113">企業は、Microsoft Intune の機能を利用して、Field Service Mobile アプリを管理できます。</span><span class="sxs-lookup"><span data-stu-id="9d815-113">Businesses can take advantage of the power of Microsoft Intune to manage the Field Service Mobile app.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9d815-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9d815-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9d815-115">セキュリティとデータ保護は、特に現場に展開する技術者と仕事をする場合、企業にとって重要です。</span><span class="sxs-lookup"><span data-stu-id="9d815-115">Security and data protection are important for businesses, especially when working with technical employees deployed in the field.</span></span> <span data-ttu-id="9d815-116">Intune により、一元的に管理された制御層がデバイスに形成されます。これは、企業が管理するデバイスと私的デバイスを活用するシナリオの両方に対応します。</span><span class="sxs-lookup"><span data-stu-id="9d815-116">Intune brings this layer of centrally managed control to devices, including corporate-managed devices and bring-your-own-device scenarios.</span></span> <span data-ttu-id="9d815-117">Intune によって管理者は、Intune の標準インフラストラクチャとコントロールを介して、Field Service Mobile アプリケーションを iOS と Android を使用するフィールド技術者に展開できます。</span><span class="sxs-lookup"><span data-stu-id="9d815-117">With Intune, administrators can roll out the Field Service Mobile application to their iOS and Android field technicians via standard Intune infrastructure and controls.</span></span>   

<span data-ttu-id="9d815-118">この機能により、Field Service Mobile アプリを Intune 管理エクスペリエンス内のファーストパーティ アプリケーションにすることができます。</span><span class="sxs-lookup"><span data-stu-id="9d815-118">This feature enables the Field Service Mobile app as a first-party application within the Intune administration experience.</span></span> <span data-ttu-id="9d815-119">Intune サポートを有効化すると、企業は、展開、構成、セキュリティ、更新など、Intune の機能をすべて利用できます。</span><span class="sxs-lookup"><span data-stu-id="9d815-119">By enabling Intune support, businesses can take advantage of all Intune features including deployment, configuration, security, and updates.</span></span>    

<span data-ttu-id="9d815-120">Intune に対応した Field Service Mobile アプリで IT 管理者は次のことが可能です。</span><span class="sxs-lookup"><span data-stu-id="9d815-120">With an Intune-enabled Field Service Mobile app, IT administrators can:</span></span> 

- <span data-ttu-id="9d815-121">Field Service Mobile アプリを追加して、特定のグループのユーザー、特定のグループのデバイスなどを含む、ユーザー グループとデバイスに割り当てます。</span><span class="sxs-lookup"><span data-stu-id="9d815-121">Add and assign your Field Service Mobile app to user groups and devices, including users in specific groups, devices in specific groups, and more.</span></span> 
- <span data-ttu-id="9d815-122">Field Service Mobile アプリを構成して、特定の設定を有効にして起動または実行し、既にデバイスにある場合は既存のアプリを更新します。</span><span class="sxs-lookup"><span data-stu-id="9d815-122">Configure the Field Service Mobile app to start or run with specific settings enabled and update your existing app when already on the device.</span></span> 
- <span data-ttu-id="9d815-123">レポートを表示してアプリの使用状況を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9d815-123">See reports and track app usage.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="9d815-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9d815-124">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="9d815-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="9d815-125">See also</span></span>


<!--docs start-->
<span data-ttu-id="9d815-126">[Microsoft Intune を使用して Field Service Mobile を管理する](https://docs.microsoft.com/dynamics365/field-service/field-service-mobile-intune) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="9d815-126">[Manage Field Service Mobile with Microsoft Intune](https://docs.microsoft.com/dynamics365/field-service/field-service-mobile-intune) (docs)</span></span>
<!--docs end-->


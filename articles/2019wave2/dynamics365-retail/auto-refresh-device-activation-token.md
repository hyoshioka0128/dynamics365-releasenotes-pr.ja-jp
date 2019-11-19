---
title: デバイス ライセンス認証トークンの自動更新
description: デバイス ライセンス認証トークンの自動更新
author: relnotes
ms.reviewer: josaw
ms.date: 09/30/2019
ms.assetid: 5463278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 2d1e596321e9b0a9761eb0499965e593bd000004
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660037"
---
# <a name="auto-refresh-device-activation-token"></a><span data-ttu-id="6b43b-103">デバイス ライセンス認証トークンの自動更新</span><span class="sxs-lookup"><span data-stu-id="6b43b-103">Auto-refresh device activation token</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="6b43b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6b43b-104">Enabled for</span></span>    |  <span data-ttu-id="6b43b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6b43b-105">Public preview</span></span> | <span data-ttu-id="6b43b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6b43b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6b43b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="6b43b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="6b43b-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="6b43b-108">Jan 2020</span></span>| <span data-ttu-id="6b43b-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="6b43b-109">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="6b43b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6b43b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6b43b-111">この機能により、小売業者は、店の POS デバイスのライセンス認証トークンの有効期限が切れるたびに、ライセンス認証をやり直す必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="6b43b-111">This will alleviate the need for retailers to reactivate POS devices in their stores each time the activation tokens expire.</span></span> <span data-ttu-id="6b43b-112">また、この機能では、既定のトークンの有効期間を短縮することでセキュリティが向上し、小売業者はこの値を手動で構成する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="6b43b-112">This feature will also improve security by reducing the default token expiration period, which will alleviate the need for retailers to manually configure this value.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6b43b-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6b43b-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6b43b-114">この機能では、業界標準の JSON Web トークンを使用して、デバイスのライセンス認証トークンの自動更新機能が導入されます。</span><span class="sxs-lookup"><span data-stu-id="6b43b-114">This feature will introduce auto-refresh capabilities for device activation tokens, using industry-standard JSON web tokens.</span></span>
<!--feature detail end -->










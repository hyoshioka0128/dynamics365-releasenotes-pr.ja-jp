---
title: チャネルに基づくサポート料金の自動請求の向上
description: この新しい機能は、既存の自動請求機能を強化してチャネル別に固有の請求を可能にし、料金の請求が必要な店舗、場所、またはチャネルに対してのみ料金が計算されるようにします。
author: relnotes
ms.reviewer: josaw
ms.date: 01/09/2020
ms.assetid: ea1fc046-1c9c-e911-a962-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: gmohanv
dynamics365pdf: true
ms.openlocfilehash: 577592c350596d79eb090daed897e80e589987a2
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986649"
---
# <a name="auto-charges-improvements-to-support-fees-based-on-channel"></a><span data-ttu-id="0490a-103">チャネルに基づくサポート料金の自動請求の向上</span><span class="sxs-lookup"><span data-stu-id="0490a-103">Auto-charges improvements to support fees based on channel</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="0490a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0490a-104">Enabled for</span></span>    |  <span data-ttu-id="0490a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0490a-105">Public preview</span></span> | <span data-ttu-id="0490a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0490a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0490a-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0490a-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0490a-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="0490a-108">Feb 2020</span></span>| <span data-ttu-id="0490a-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="0490a-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0490a-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0490a-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0490a-111">小売業者は、自動請求ルールを定義して、注文が作成されたチャネルに基づく料金を追加できます。</span><span class="sxs-lookup"><span data-stu-id="0490a-111">Retailers can define auto-charges rules to add a fee based on the channel the order was created in.</span></span> <span data-ttu-id="0490a-112">小売業者は、ヘッダー レベルと明細品目レベルの両方でチャネルベースの自動請求を構成できます。</span><span class="sxs-lookup"><span data-stu-id="0490a-112">Retailers can configure the channel-based auto-charges at both the header level and line item level.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0490a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0490a-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0490a-114">この機能は、Commerce チャネル別に自動請求を定義するための追加の基準を提供します。</span><span class="sxs-lookup"><span data-stu-id="0490a-114">This feature provides additional criteria to allow auto-charges to be defined by Commerce channel.</span></span> <span data-ttu-id="0490a-115">機能は、現在の Commerce で荷渡方法や品揃えをチャネル別にフィルター処理する方法と似たものになります。</span><span class="sxs-lookup"><span data-stu-id="0490a-115">Functionality will be similar to how Commerce currently filters modes of delivery or assortments by channel.</span></span> <span data-ttu-id="0490a-116">この機能は、Commerce 組織のモデル階層を使用して、**高度な自動請求**コンフィギュレーション キーが有効になっている本社ユーザーが自分の自動請求テーブルで Commerce チャネル別に追加のフィルターを定義できるようにします。</span><span class="sxs-lookup"><span data-stu-id="0490a-116">The feature will use the Commerce organizational model hierarchy and allow headquarters users who have the **Advanced auto charges** configuration key enabled to be able to define additional filters on their auto-charges table by Commerce channels.</span></span> <span data-ttu-id="0490a-117">Dynamics 365 Finance and Operations アプリの非 Commerce ユーザーがこれらの追加機能の影響を受けないようにするために、この機能はコンフィギュレーション キーに関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="0490a-117">The functionality will be tied to a configuration key to ensure that non-Commerce users of Dynamics 365 Finance and Operations apps are not impacted by these added features.</span></span>
<!--feature detail end -->










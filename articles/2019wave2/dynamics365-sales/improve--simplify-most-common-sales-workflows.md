---
title: 最も一般的な販売ワークフローの改善または簡素化
description: 営業担当者が簡単に Dynamics 365 Sales アプリを使用できるよう、最も一般的な営業ワークフローを改善または簡素化します。
author: relnotes
ms.reviewer: shujoshi
ms.date: 11/15/2019
ms.assetid: e061278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: adc1234100f10b3b4768439d0417c9bd6ae30cfc
ms.sourcegitcommit: b42a148c376fc4d3297326179cf301404448f570
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2888695"
---
# <a name="improve-or-simplify-most-common-sales-workflows"></a><span data-ttu-id="1fb50-103">最も一般的な販売ワークフローの改善または簡素化</span><span class="sxs-lookup"><span data-stu-id="1fb50-103">Improve or simplify most common sales workflows</span></span>


| <span data-ttu-id="1fb50-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1fb50-104">Enabled for</span></span>    |  <span data-ttu-id="1fb50-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1fb50-105">Public preview</span></span> | <span data-ttu-id="1fb50-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="1fb50-106">Early access</span></span> | <span data-ttu-id="1fb50-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1fb50-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="1fb50-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="1fb50-108">End users, automatically</span></span>|-|<span data-ttu-id="1fb50-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1fb50-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1fb50-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="1fb50-110">Aug 2, 2019</span></span>| <span data-ttu-id="1fb50-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1fb50-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1fb50-112">2019 年 10 月 6 日</span><span class="sxs-lookup"><span data-stu-id="1fb50-112">Oct 6, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="1fb50-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1fb50-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1fb50-114">簡素化されたワークフローにより、一般的に使用されるコンポーネントに簡単にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1fb50-114">Simplified workflows will introduce ease of access to commonly used components.</span></span> <span data-ttu-id="1fb50-115">営業関係者および営業チームの管理プロセスの強化により、生産性が向上し、製品管理と UI ベースの製品のリペアレントを柔軟に行えるようになります。</span><span class="sxs-lookup"><span data-stu-id="1fb50-115">Enhancements to sales stakeholder and sales team management processes will help improve their productivity while offering flexibility in product management and UI-based product reparenting.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1fb50-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1fb50-116">Feature details</span></span>
<!--feature detail start -->
-  <span data-ttu-id="1fb50-117">取引先担当者、営業案件、リード、取引先企業の各エンティティに対して、メイン フォームに**ドキュメント** タブが表示されるようにします</span><span class="sxs-lookup"><span data-stu-id="1fb50-117">Make the **Documents** tab visible in the main form for Contact, Opportunity, Lead, and Account entities.</span></span>
-  <span data-ttu-id="1fb50-118">営業案件フォームのユーザー エクスペリエンスを向上させます。</span><span class="sxs-lookup"><span data-stu-id="1fb50-118">Enhance the Opportunity form user experience.</span></span>
-  <span data-ttu-id="1fb50-119">製品のリペアレントおよび製品レベルでのプロパティの追加がサポートされます (従来の Web クライアントと統一インターフェイスの両方でサポートされます)。</span><span class="sxs-lookup"><span data-stu-id="1fb50-119">Support reparenting of products and the addition of properties at the product level (supported on both the legacy web client and Unified Interface).</span></span>
   <span data-ttu-id="1fb50-120">製品カタログを定義するとき、製品の再調整が必要であれば、管理者は製品、バンドル、またはファミリの親を更新できます。</span><span class="sxs-lookup"><span data-stu-id="1fb50-120">While defining a product catalog, admins can update the parent of a product, bundle, or family in cases where products need to be realigned.</span></span> <span data-ttu-id="1fb50-121">さらに、製品レベルまたはバンドル レベルでプロパティを直接追加できます。</span><span class="sxs-lookup"><span data-stu-id="1fb50-121">Additionally, they can add properties directly at the product or bundle level.</span></span> 

> [!NOTE] 
> <span data-ttu-id="1fb50-122">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="1fb50-122">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="1fb50-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="1fb50-123">This feature is available in the Unified Interface only.</span></span>



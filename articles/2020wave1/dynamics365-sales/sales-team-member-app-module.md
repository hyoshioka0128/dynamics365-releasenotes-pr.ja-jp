---
title: 営業チーム メンバー アプリ モジュール
description: 営業チーム メンバーは、Team Member ライセンスを持つユーザーが利用できる、新しいアプリ モジュールです。
author: relnotes
ms.reviewer: shujoshi
ms.date: 04/07/2020
ms.assetid: 848fe5cd-152e-ea11-a810-000d3a8f004f
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: bf6e9db822e81c3942e979dda3d4dfe4628038f4
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548354"
---
# <a name="sales-team-member-app-module"></a><span data-ttu-id="9d12b-103">営業チーム メンバー アプリ モジュール</span><span class="sxs-lookup"><span data-stu-id="9d12b-103">Sales Team Member app module</span></span>


| <span data-ttu-id="9d12b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9d12b-104">Enabled for</span></span>    |  <span data-ttu-id="9d12b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9d12b-105">Public preview</span></span> | <span data-ttu-id="9d12b-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9d12b-106">Early access</span></span> | <span data-ttu-id="9d12b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9d12b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9d12b-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="9d12b-108">End users, automatically</span></span>|-|<span data-ttu-id="9d12b-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9d12b-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9d12b-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9d12b-110">Feb 3, 2020</span></span>| <span data-ttu-id="9d12b-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9d12b-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9d12b-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9d12b-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9d12b-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9d12b-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9d12b-114">営業チーム メンバーは、Team Member ライセンスを持つユーザーが利用できる新しいアプリ モジュールであり、特定の機能に縛られていないが、営業シナリオ内で Dynamics 365 の基本機能を必要とするユーザー向けに設計されています。</span><span class="sxs-lookup"><span data-stu-id="9d12b-114">Sales Team Member is a new app module that will be available to users with the Team Member license and is designed for users who are not tied to a particular function, but require basic Dynamics 365 functionality within sales scenarios.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9d12b-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9d12b-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9d12b-116">Team Member ライセンスは、限定された一連のユース ケースの使用権を提供します。</span><span class="sxs-lookup"><span data-stu-id="9d12b-116">The Team Member license provides use rights to a limited set of use cases.</span></span> <span data-ttu-id="9d12b-117">営業チーム メンバー アプリ モジュールはこれらのユース ケースを有効にし、使用権に関するガイダンスを提供して明確にします。</span><span class="sxs-lookup"><span data-stu-id="9d12b-117">The Sales Team Member app module enables those use cases and provides guidance and clarity on the use rights.</span></span> <span data-ttu-id="9d12b-118">新しいアプリ モジュールは、営業にかかわる次のユース ケースをサポートします。</span><span class="sxs-lookup"><span data-stu-id="9d12b-118">The new app module will support the following sales use cases:</span></span>

- <span data-ttu-id="9d12b-119">顧客の詳細を表示します。</span><span class="sxs-lookup"><span data-stu-id="9d12b-119">View customer details.</span></span>
- <span data-ttu-id="9d12b-120">顧客に関連するリードと営業案件を表示します。</span><span class="sxs-lookup"><span data-stu-id="9d12b-120">View leads and opportunities related to a customer.</span></span>
- <span data-ttu-id="9d12b-121">顧客または関連するリードや営業案件のアクティビティを作成して表示します。</span><span class="sxs-lookup"><span data-stu-id="9d12b-121">Create and view activities for a customer or related leads or opportunities.</span></span>

<span data-ttu-id="9d12b-122">管理者は追加のシナリオに合わせてアプリを構成できますが、[Microsoft Dynamics 365 のライセンス ガイド](https://go.microsoft.com/fwlink/p/?LinkId=866544)にリストされている範囲を超えては構成できません。</span><span class="sxs-lookup"><span data-stu-id="9d12b-122">Admins can configure the app for additional scenarios, but not beyond those listed in the [Microsoft Dynamics 365 Licensing Guide](https://go.microsoft.com/fwlink/p/?LinkId=866544).</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="9d12b-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9d12b-123">This feature is available in Unified Interface only.</span></span> <span data-ttu-id="9d12b-124">この機能は、Dynamics 365 Team Member ライセンスで利用できます。</span><span class="sxs-lookup"><span data-stu-id="9d12b-124">This capability is available with the Dynamics 365 Team Member license.</span></span>







## <a name="see-also"></a><span data-ttu-id="9d12b-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="9d12b-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="9d12b-126">[Team Member ライセンスを持つユーザー向けの営業チーム メンバー アプリ](https://docs.microsoft.com/dynamics365/sales-enterprise/sales-team-member) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="9d12b-126">[Sales Team Member app for users with Team Member license](https://docs.microsoft.com/dynamics365/sales-enterprise/sales-team-member) (docs)</span></span>
<!--docs end-->

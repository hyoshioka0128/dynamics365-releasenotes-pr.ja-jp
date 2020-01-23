---
title: セルフサービス配置への移行
description: セルフサービス配置への移行
author: relnotes
ms.reviewer: sericks
ms.date: 01/08/2020
ms.assetid: 81b362b3-fd6d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: sarvanis
dynamics365pdf: true
ms.openlocfilehash: 59103357de0576e8b96234824d815155e998ff75
ms.sourcegitcommit: ecf709e1d8de3b52e1156bceb99cb7e3819f9db3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/13/2020
ms.locfileid: "2950969"
---
# <a name="migration-to-self-service-deployments"></a><span data-ttu-id="bdeab-103">セルフサービス配置への移行</span><span class="sxs-lookup"><span data-stu-id="bdeab-103">Migration to self-service deployments</span></span>


| <span data-ttu-id="bdeab-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bdeab-104">Enabled for</span></span>    |  <span data-ttu-id="bdeab-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bdeab-105">Public preview</span></span> | <span data-ttu-id="bdeab-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bdeab-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bdeab-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="bdeab-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="bdeab-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bdeab-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bdeab-109">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bdeab-109">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="bdeab-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bdeab-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bdeab-111">Microsoft は、2018 年秋に新規顧客向けのセルフサービス配置を有効にしました。</span><span class="sxs-lookup"><span data-stu-id="bdeab-111">Microsoft enabled self-service deployments for new customers in the fall of 2018.</span></span> <span data-ttu-id="bdeab-112">2019 年夏から、顧客と連携して、顧客の環境をセルフサービス配置に移行します。</span><span class="sxs-lookup"><span data-stu-id="bdeab-112">Starting in summer 2019, Microsoft coordinates with customers to migrate their environments to self-service deployment.</span></span> <span data-ttu-id="bdeab-113">まず、既定のサンドボックスが移行されます。</span><span class="sxs-lookup"><span data-stu-id="bdeab-113">The default sandbox is migrated first.</span></span> <span data-ttu-id="bdeab-114">2 通の通知メールも送信されます。</span><span class="sxs-lookup"><span data-stu-id="bdeab-114">Two notification emails are also sent.</span></span> <span data-ttu-id="bdeab-115">最初のメールは 30 日前の事前通知であり、2 番目のメールは予定された移行の 5 日前に送信されるアラーム通知です。</span><span class="sxs-lookup"><span data-stu-id="bdeab-115">The first email is a 30-day advance notice, and the second email is a reminder notice sent five days before the scheduled migration.</span></span> <span data-ttu-id="bdeab-116">状況によっては、オンライン フォームで移行を再スケジュールすることができます。</span><span class="sxs-lookup"><span data-stu-id="bdeab-116">Migration can be rescheduled through an online form in extenuating circumstances.</span></span>

### <a name="preparing-for-migration"></a><span data-ttu-id="bdeab-117">移行の準備</span><span class="sxs-lookup"><span data-stu-id="bdeab-117">Preparing for migration</span></span>
<span data-ttu-id="bdeab-118">お客様は最初に、将来展開可能なパッケージを組み合わせて、現在のオンライン サービスで環境を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bdeab-118">Customers should start updating their environments on the current online service with combined deployable packages going forward.</span></span> <span data-ttu-id="bdeab-119">これは常に推奨されるベスト プラクティスでしたが、今は強制されます。</span><span class="sxs-lookup"><span data-stu-id="bdeab-119">This was always the recommended best practice and will now be enforced.</span></span>

### <a name="whats-new-or-changed"></a><span data-ttu-id="bdeab-120">新機能および変更された機能</span><span class="sxs-lookup"><span data-stu-id="bdeab-120">What's new or changed</span></span>
<span data-ttu-id="bdeab-121">お客様は、Tier 2 以上の環境のサーバー管理者資格情報に直接アクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="bdeab-121">Customers will no longer have direct access to server admin credentials on Tier 2+ environments.</span></span> <span data-ttu-id="bdeab-122">引き続き Azure SQL Database にはアクセスでき、Lifecycle Services (LCS) から Just-In-Time アクセスを使用して接続できるようになります。</span><span class="sxs-lookup"><span data-stu-id="bdeab-122">They will continue to have access to Azure SQL Database and will be able to connect using just-in-time access from Lifecycle Services (LCS).</span></span> 

<span data-ttu-id="bdeab-123">お客様は、Tier 2 以上の環境のリモート デスクトップ資格情報にアクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="bdeab-123">Customers will no longer have access to remote desktop credentials on Tier 2+ environments.</span></span> <span data-ttu-id="bdeab-124">リモート デスクトップ アクセスを必要とするすべての操作は、LCS 上のセルフサービス操作として利用可能になりました。</span><span class="sxs-lookup"><span data-stu-id="bdeab-124">All operations needing remote desktop access have been made available as self-service operations in LCS.</span></span>


<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="bdeab-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="bdeab-125">See also</span></span>

<span data-ttu-id="bdeab-126">[セルフサービス配置の概要](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/deployment/infrastructure-stack) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="bdeab-126">[Self-service deployment overview](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/deployment/infrastructure-stack) (docs)</span></span>

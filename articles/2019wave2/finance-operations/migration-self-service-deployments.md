---
title: セルフサービス配置への移行
description: セルフサービス配置への移行
author: relnotes
ms.reviewer: kfend
ms.date: 09/16/2019
ms.assetid: 81b362b3-fd6d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: sarvanis
dynamics365pdf: true
ms.openlocfilehash: 01e085920cfa798293fb9a159cbcad71f2d2de1f
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143012"
---
# <a name="migration-to-self-service-deployments"></a><span data-ttu-id="de35f-103">セルフサービス配置への移行</span><span class="sxs-lookup"><span data-stu-id="de35f-103">Migration to self-service deployments</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="de35f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="de35f-104">Enabled for</span></span>    |  <span data-ttu-id="de35f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="de35f-105">Public preview</span></span> | <span data-ttu-id="de35f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="de35f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="de35f-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="de35f-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="de35f-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="de35f-108">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="de35f-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="de35f-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="de35f-110">Microsoft は、2018 年秋に新規顧客向けのセルフサービス配置を有効にしました。</span><span class="sxs-lookup"><span data-stu-id="de35f-110">Microsoft enabled self-service deployments for new customers in the fall of 2018.</span></span> <span data-ttu-id="de35f-111">2019 年夏から、顧客と連携して、顧客の環境をセルフサービス配置に移行します。</span><span class="sxs-lookup"><span data-stu-id="de35f-111">Starting in summer 2019, Microsoft will coordinate with customers to migrate their environments to self-service deployment.</span></span> <span data-ttu-id="de35f-112">最初に既定のサンドボックスが移行され、その 7 カレンダー日後に運用環境が移行されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-112">The default sandbox is migrated first, seven calendar days before the production environment is migrated.</span></span> <span data-ttu-id="de35f-113">2 通の通知メールも送信されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-113">Two notification emails are also sent.</span></span> <span data-ttu-id="de35f-114">最初のメールは 30 日前の事前通知であり、2 番目のメールは予定された移行の 5 日前のアラーム通知です。</span><span class="sxs-lookup"><span data-stu-id="de35f-114">The first email is a 30-day advance notice, and the second email is a reminder notice five days before the scheduled migration.</span></span> <span data-ttu-id="de35f-115">状況によっては、オンライン フォームで移行を再スケジュールすることができます。</span><span class="sxs-lookup"><span data-stu-id="de35f-115">Migration can be rescheduled through an online form in extenuating circumstances.</span></span>

### <a name="preparing-for-migration"></a><span data-ttu-id="de35f-116">移行の準備</span><span class="sxs-lookup"><span data-stu-id="de35f-116">Preparing for migration</span></span>
<span data-ttu-id="de35f-117">お客様は最初に、将来展開可能なパッケージを組み合わせて、現在のオンライン サービスで環境を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="de35f-117">Customers should start updating their environments on the current online service with combined deployable packages going forward.</span></span> <span data-ttu-id="de35f-118">これは常に推奨されるベスト プラクティスでしたが、今は強制されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-118">This was always the recommended best practice and will now be enforced.</span></span>

### <a name="whats-new-or-changed"></a><span data-ttu-id="de35f-119">新機能および変更された機能</span><span class="sxs-lookup"><span data-stu-id="de35f-119">What's new or changed</span></span>
<span data-ttu-id="de35f-120">お客様は、Tier 2 以上の環境のサーバー管理者資格情報に直接アクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="de35f-120">Customers will no longer have direct access to server admin credentials on Tier 2+ environments.</span></span> <span data-ttu-id="de35f-121">引き続き Azure SQL Database にはアクセスでき、Lifecycle Services (LCS) から Just-In-Time アクセスを使用して接続できるようになります。</span><span class="sxs-lookup"><span data-stu-id="de35f-121">They will continue to have access to Azure SQL Database and will be able to connect using just-in-time access from Lifecycle Services (LCS).</span></span> 

<span data-ttu-id="de35f-122">お客様は、Tier 2 以上の環境のリモート デスクトップ資格情報にアクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="de35f-122">Customers will no longer have access to remote desktop credentials on Tier 2+ environments.</span></span> <span data-ttu-id="de35f-123">リモート デスクトップ アクセスを必要とするすべての操作は、LCS 上のセルフサービス操作として利用可能になりました。</span><span class="sxs-lookup"><span data-stu-id="de35f-123">All operations needing remote desktop access have been made available as self-service operations on LCS.</span></span>

### <a name="zero-downtime-update-for-self-service-deployments"></a><span data-ttu-id="de35f-124">セルフサービス配置に対するゼロ ダウンタイム更新</span><span class="sxs-lookup"><span data-stu-id="de35f-124">Zero downtime update for self-service deployments</span></span>
<span data-ttu-id="de35f-125">2019 年リリース ウェーブ 2 では、お客様は Microsoft の毎月のサービス更新に対するゼロ ダウンタイム更新フローに追加されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-125">With 2019 release wave 2, customers will be added to the zero-downtime update flow for Microsoft monthly service updates.</span></span>
<span data-ttu-id="de35f-126">ゼロ ダウンタイムが有効になっているお客様は、更新が行われる更新ウィンドウを構成できます。</span><span class="sxs-lookup"><span data-stu-id="de35f-126">Customers with zero downtime enabled are now able to configure an update window during which the update will happen.</span></span> <span data-ttu-id="de35f-127">対話型ユーザーは、更新中に接続が失われることはありません。</span><span class="sxs-lookup"><span data-stu-id="de35f-127">Interactive users will not experience any connection loss during the update.</span></span> <span data-ttu-id="de35f-128">まれに、指定されたウィンドウで更新を完了するためにユーザー セッションを終了する必要がある場合は、ユーザーに作業を保存してブラウザーを更新するよう通知されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-128">In the unlikely event a user session has to be terminated to complete the update in the specified window, a notification indicates that the user should save their work and refresh their browser.</span></span> <span data-ttu-id="de35f-129">実行中のバッチ ジョブはすべて、事前構成された更新ウィンドウの間は終了されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-129">Any running batch jobs will be terminated during the preconfigured update window.</span></span> <span data-ttu-id="de35f-130">更新が完了すると、終了されたすべてのバッチ ジョブが再開されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-130">All terminated batch jobs will be restarted when the update completes.</span></span> <span data-ttu-id="de35f-131">更新ウィンドウの間に新しいバッチ ジョブを開始できます。</span><span class="sxs-lookup"><span data-stu-id="de35f-131">New  batch jobs can be started in the update window.</span></span> <span data-ttu-id="de35f-132">お客様には、メールおよび LCS の更新履歴を通じて、更新のステータスが通知されます。</span><span class="sxs-lookup"><span data-stu-id="de35f-132">Customers will be notified about the status of the update through email and through LCS update history.</span></span>
<!--feature detail end -->












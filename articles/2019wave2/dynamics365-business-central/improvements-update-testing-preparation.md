---
title: 更新のテストと準備の改善
description: 更新のテストと準備の改善
author: relnotes
ms.reviewer: edupont
ms.date: 07/01/2019
ms.assetid: b5c1c411-b66d-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jaredha
dynamics365pdf: true
ms.openlocfilehash: e2f9e38e0da3c3ba9ea9b5bfa37d090bed6debdc
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722941"
---
# <a name="improvements-in-update-testing-and-preparation"></a><span data-ttu-id="6d352-103">更新のテストと準備の改善</span><span class="sxs-lookup"><span data-stu-id="6d352-103">Improvements in update testing and preparation</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="6d352-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6d352-104">Enabled for</span></span>    |  <span data-ttu-id="6d352-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6d352-105">Public preview</span></span> | <span data-ttu-id="6d352-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6d352-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="6d352-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="6d352-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="6d352-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="6d352-108">August 2019</span></span>| <span data-ttu-id="6d352-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="6d352-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="6d352-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6d352-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6d352-111">Business Central 環境の更新プロセスをさらに効率化するいくつかの改善があります。</span><span class="sxs-lookup"><span data-stu-id="6d352-111">There are several improvements that further streamline the process of updating Business Central environments.</span></span> <span data-ttu-id="6d352-112">まず、カスタマイズの互換性検証が更新プロセスにいっそう確実に組み込まれます。</span><span class="sxs-lookup"><span data-stu-id="6d352-112">First, customization compatibility validation will be more firmly embedded in the update process.</span></span> <span data-ttu-id="6d352-113">新しい更新が入手可能になると、自動検証が実行されて、テナント環境のカスタマイズが新しいバージョンと互換性があることが確認されます。</span><span class="sxs-lookup"><span data-stu-id="6d352-113">When a new update is available, an automated validation runs to ensure that any tenant environment customizations are compatible with the new version.</span></span> <span data-ttu-id="6d352-114">互換性がないことがツールで検出されると、環境にフラグが付けられ、カスタマイズがベース アプリケーションの新バージョンと互換性があるように更新されるまで、新しいバージョンに更新したり更新をスケジュールしたりできません。</span><span class="sxs-lookup"><span data-stu-id="6d352-114">If the tool detects incompatibility, the environment is flagged and cannot be updated or scheduled for update to the new version until customizations are updated to be compatible with the new version of the base application.</span></span> <span data-ttu-id="6d352-115">これには、Business Central 管理センターの互換性インジケーター、および更新プロセスを通じて検証について管理者に通知する自動通知が含まれます。</span><span class="sxs-lookup"><span data-stu-id="6d352-115">This includes compatibility indicators in the Business Central Administration Center, as well as automated notifications to inform administrators about validations through the update process.</span></span>

<span data-ttu-id="6d352-116">2 つ目の重要な機能強化は、環境の更新が失敗したときにテナント管理者に提供されるフィードバックです。</span><span class="sxs-lookup"><span data-stu-id="6d352-116">A second key enhancement is in the feedback provided to tenant administrators when an environment update fails.</span></span> <span data-ttu-id="6d352-117">失敗の原因の修正に管理者のアクションが必要な場合の対処可能な情報など、更新の失敗に関する詳細情報が記載されたメールを管理者は受け取ります。</span><span class="sxs-lookup"><span data-stu-id="6d352-117">Administrators receive email notifications with detailed information on update failures, including actionable information when correcting the cause of the failure requires action from the administrator.</span></span>

<span data-ttu-id="6d352-118">3 つ目の機能強化では、AppSource 拡張機能に対する更新が利用可能かどうかを確認できます。</span><span class="sxs-lookup"><span data-stu-id="6d352-118">The third enhancement provides visibility into the availability of updates for AppSource extensions.</span></span> <span data-ttu-id="6d352-119">環境で公開されている AppSource 拡張機能に対する更新が利用可能になると、Business Central の拡張機能管理ページに管理者に対する通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="6d352-119">Administrators will see a notification in the Extension Management page in Business Central when an update is available for an AppSource extension that has been published on the environment.</span></span> <span data-ttu-id="6d352-120">このオプションは、**拡張機能管理**ページから直接新しい更新を適用するためにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="6d352-120">The option will also be available to apply the new update directly from the **Extension Management** page.</span></span>
<!--feature detail end -->











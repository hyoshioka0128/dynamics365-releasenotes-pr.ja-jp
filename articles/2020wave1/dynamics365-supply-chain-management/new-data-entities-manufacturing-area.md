---
title: 製造領域向けの新しいデータ エンティティ
description: ''
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/02/2020
ms.assetid: 4cad3e30-9068-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: johanho
dynamics365pdf: true
ms.openlocfilehash: 21d32900422f407bdf3d7c9694ad6150b2617009
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219207"
---
# <a name="new-data-entities-for-the-manufacturing-area"></a><span data-ttu-id="d6011-102">製造領域向けの新しいデータ エンティティ</span><span class="sxs-lookup"><span data-stu-id="d6011-102">New data entities for the manufacturing area</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="d6011-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="d6011-103">Enabled for</span></span>    |  <span data-ttu-id="d6011-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d6011-104">Public preview</span></span> | <span data-ttu-id="d6011-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="d6011-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d6011-106">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="d6011-106">End users, automatically</span></span>|<span data-ttu-id="d6011-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d6011-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d6011-108">2020 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d6011-108">Mar 1, 2020</span></span>| <span data-ttu-id="d6011-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="d6011-109">May 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="d6011-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d6011-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d6011-111">Supply Chain Management の製造領域向けデータ エンティティのコレクションを拡張して、管理者、システム インテグレーター、システム開発者に新たな可能性を開きます。</span><span class="sxs-lookup"><span data-stu-id="d6011-111">We are expanding the collection of data entities for the manufacturing area of Supply Chain Management, thus opening new possibilities for admins, system integrators, and system developers.</span></span> <span data-ttu-id="d6011-112">たとえば、これらのエンティティの中には、分析と視覚化を構築するためにデータの抽出に使用できるものや、Dynamics 365 Supply Chain Management の新しいインスタンスを準備するときにマスター データと参照データの移行に使用できるものがあります。</span><span class="sxs-lookup"><span data-stu-id="d6011-112">For example, some of these entities will let you extract data for building analytics and visualizations, while others will help you to migrate master and reference data when preparing new instances of Dynamics 365 Supply Chain Management.</span></span>

|    <span data-ttu-id="d6011-113">リリース</span><span class="sxs-lookup"><span data-stu-id="d6011-113">Release</span></span>    |    <span data-ttu-id="d6011-114">エンティティ</span><span class="sxs-lookup"><span data-stu-id="d6011-114">Entity</span></span>    |    <span data-ttu-id="d6011-115">目的</span><span class="sxs-lookup"><span data-stu-id="d6011-115">Purpose</span></span>    |
|----|----|----|
|    <span data-ttu-id="d6011-116">10.0.9</span><span class="sxs-lookup"><span data-stu-id="d6011-116">10.0.9</span></span>    |    <span data-ttu-id="d6011-117">能力の予約</span><span class="sxs-lookup"><span data-stu-id="d6011-117">Capacity reservation</span></span>    |    <span data-ttu-id="d6011-118">ユーザーが能力の予約をエクスポートできるようにします。これは (たとえば) 能力の概要の視覚化を構築するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-118">Enables users to export capacity reservations, which can   be useful  (for example) for building capacity overview visualizations.</span></span>    |
|    <span data-ttu-id="d6011-119">10.0.9</span><span class="sxs-lookup"><span data-stu-id="d6011-119">10.0.9</span></span>    |    <span data-ttu-id="d6011-120">バッチ オーダーのフォーミュラ明細行</span><span class="sxs-lookup"><span data-stu-id="d6011-120">Batch order formula lines</span></span>    |    <span data-ttu-id="d6011-121">ユーザーがバッチ オーダーのフォーミュラ明細行をインポートおよびエクスポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6011-121">Enables users to import and export batch order formula   lines.</span></span> <span data-ttu-id="d6011-122">インポート オプションは、データを移行するときに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-122">The import option can be useful when migrating data.</span></span>    |
|    <span data-ttu-id="d6011-123">10.0.9</span><span class="sxs-lookup"><span data-stu-id="d6011-123">10.0.9</span></span>    |    <span data-ttu-id="d6011-124">バッチ オーダーの連産品と副産物</span><span class="sxs-lookup"><span data-stu-id="d6011-124">Batch order co- and by-product</span></span>    |    <span data-ttu-id="d6011-125">ユーザーがバッチ オーダーの連産品と副産物をインポートおよびエクスポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6011-125">Enables users to import and export batch order co- and   by-products.</span></span> <span data-ttu-id="d6011-126">インポート オプションは、データを移行するときに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-126">The import option can be useful when migrating data.</span></span>    |
|    <span data-ttu-id="d6011-127">10.0.9</span><span class="sxs-lookup"><span data-stu-id="d6011-127">10.0.9</span></span>    |    <span data-ttu-id="d6011-128">生産ルート トランザクション</span><span class="sxs-lookup"><span data-stu-id="d6011-128">Production route transaction</span></span>    |    <span data-ttu-id="d6011-129">ユーザーが生産ルート トランザクションをエクスポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6011-129">Enables users to export production route transactions.</span></span>   <span data-ttu-id="d6011-130">これは製造パフォーマンスの分析を構築するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-130">This can be useful for building analytics for manufacturing performance.</span></span>    |
|    <span data-ttu-id="d6011-131">10.0.10</span><span class="sxs-lookup"><span data-stu-id="d6011-131">10.0.10</span></span>    |    <span data-ttu-id="d6011-132">生産ジョブ</span><span class="sxs-lookup"><span data-stu-id="d6011-132">Production jobs</span></span>    |    <span data-ttu-id="d6011-133">ユーザーが生産ジョブをエクスポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6011-133">Enables users to export production jobs.</span></span> <span data-ttu-id="d6011-134">これは生産計画の視覚化を構築するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-134">This can be   useful for building visualizations of the production plan.</span></span>    |
|    <span data-ttu-id="d6011-135">10.0.10</span><span class="sxs-lookup"><span data-stu-id="d6011-135">10.0.10</span></span>    |    <span data-ttu-id="d6011-136">間接活動 (JmgIpcActivity)</span><span class="sxs-lookup"><span data-stu-id="d6011-136">Indirect activities (JmgIpcActivity)</span></span>    |    <span data-ttu-id="d6011-137">ユーザーが間接活動をインポートおよびエクスポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6011-137">Enables users to import and export indirect activities.</span></span>   <span data-ttu-id="d6011-138">これは、新しいインスタンスのデータを準備するときに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-138">This can be useful when preparing data for new instances.</span></span>    |
|    <span data-ttu-id="d6011-139">10.0.10</span><span class="sxs-lookup"><span data-stu-id="d6011-139">10.0.10</span></span>    |    <span data-ttu-id="d6011-140">間接活動カテゴリ (JmgIpcCategory)</span><span class="sxs-lookup"><span data-stu-id="d6011-140">Indirect activity categories (JmgIpcCategory)</span></span>    |    <span data-ttu-id="d6011-141">ユーザーが間接活動のカテゴリをインポートおよびエクスポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6011-141">Enables users to import and export categories for indirect   activities.</span></span> <span data-ttu-id="d6011-142">これは、新しいインスタンスのデータを準備するときに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d6011-142">This can be useful when preparing data for new instances.</span></span>    |
|    <span data-ttu-id="d6011-143">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-143">10.0.11</span></span>    |    <span data-ttu-id="d6011-144">フォーミュラ バージョン (pmfFormulaVersionEntity)</span><span class="sxs-lookup"><span data-stu-id="d6011-144">Formula version (pmfFormulaVersionEntity)</span></span>    |    <span data-ttu-id="d6011-145">ユーザーが Excel で編集できるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-145">Enables users to edit in Excel</span></span>   |
|    <span data-ttu-id="d6011-146">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-146">10.0.11</span></span>    |    <span data-ttu-id="d6011-147">完成レポート仕訳帳 (ヘッダーおよび明細行)</span><span class="sxs-lookup"><span data-stu-id="d6011-147">Report as finished journal (header and lines)</span></span>    |    <span data-ttu-id="d6011-148">ユーザーが完了レポート仕訳帳をエクスポートおよびインポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-148">Enables users export and import report as finished journals</span></span>   |
|    <span data-ttu-id="d6011-149">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-149">10.0.11</span></span>    |    <span data-ttu-id="d6011-150">完成レポート仕訳帳 (ヘッダーおよび明細行)</span><span class="sxs-lookup"><span data-stu-id="d6011-150">Report as finished journal (header and lines)</span></span>    |    <span data-ttu-id="d6011-151">ユーザーが完了レポート仕訳帳をエクスポートおよびインポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-151">Enables users to export and import report as finished journals</span></span>   |
|    <span data-ttu-id="d6011-152">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-152">10.0.11</span></span>    |    <span data-ttu-id="d6011-153">工順カード仕訳帳 (ヘッダーおよび明細行)</span><span class="sxs-lookup"><span data-stu-id="d6011-153">Route card journal (header and lines)</span></span>    |    <span data-ttu-id="d6011-154">ユーザーが工順カード仕訳帳をエクスポートおよびインポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-154">Enables users to export and import route card journals</span></span>   |
|    <span data-ttu-id="d6011-155">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-155">10.0.11</span></span>    |    <span data-ttu-id="d6011-156">生産ピッキング リスト仕訳帳 (ヘッダーおよび明細行)</span><span class="sxs-lookup"><span data-stu-id="d6011-156">Production picking list journal (header and lines)</span></span>    |    <span data-ttu-id="d6011-157">ユーザーが生産ピッキング リスト仕訳帳をエクスポートおよびインポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-157">Enables users to export and import production picking list journals</span></span>   |
|    <span data-ttu-id="d6011-158">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-158">10.0.11</span></span>    |    <span data-ttu-id="d6011-159">プロファイル (JmgProfileTable)</span><span class="sxs-lookup"><span data-stu-id="d6011-159">Profiles (JmgProfileTable)</span></span>    |    <span data-ttu-id="d6011-160">ユーザーがプロファイルをインポートおよびエクスポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-160">Enables users to import and export profiles</span></span>   |
|    <span data-ttu-id="d6011-161">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-161">10.0.11</span></span>    |    <span data-ttu-id="d6011-162">支払協定 (JmgPayAgreementTable)</span><span class="sxs-lookup"><span data-stu-id="d6011-162">Pay agreements (JmgPayAgreementTable)</span></span>   |    <span data-ttu-id="d6011-163">ユーザーが支払協定をインポートおよびエクスポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-163">Enables users to import and export pay agreements</span></span>   |
|    <span data-ttu-id="d6011-164">10.0.11</span><span class="sxs-lookup"><span data-stu-id="d6011-164">10.0.11</span></span>    |    <span data-ttu-id="d6011-165">項目順序 (PmfSequencingItemTable)</span><span class="sxs-lookup"><span data-stu-id="d6011-165">Item sequence (PmfSequencingItemTable)</span></span>   |    <span data-ttu-id="d6011-166">ユーザーが支払項目順序をインポートおよびエクスポートできるようにします</span><span class="sxs-lookup"><span data-stu-id="d6011-166">Enables users to import and export pay item sequences</span></span>   |

<!--feature detail end -->










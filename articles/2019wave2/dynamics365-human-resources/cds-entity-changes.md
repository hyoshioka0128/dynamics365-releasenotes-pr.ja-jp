---
title: Common Data Service エンティティの変更
description: HCM Common ソリューションの Human Resources エンティティが更新され、Common Data Service での追跡用の新しいフィールドが追加されました。 追加のエンティティも利用できます。 これらのフィールドを更新すると、通常のプロセスの一部として Human Resources と同期されます。
author: relnotes
ms.reviewer: anbichse
ms.date: 04/15/2020
ms.assetid: d9810a84-9152-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: dkrame
dynamics365pdf: true
ms.openlocfilehash: e1c13773f54fc04c15d76c7a319f4c35c9c8acc3
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320371"
---
# <a name="common-data-service-entity-changes"></a><span data-ttu-id="ce10b-105">Common Data Service エンティティの変更</span><span class="sxs-lookup"><span data-stu-id="ce10b-105">Common Data Service entity changes</span></span>


| <span data-ttu-id="ce10b-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="ce10b-106">Enabled for</span></span>    |  <span data-ttu-id="ce10b-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ce10b-107">Public preview</span></span> | <span data-ttu-id="ce10b-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="ce10b-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ce10b-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ce10b-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ce10b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ce10b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ce10b-111">2020 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="ce10b-111">Mar 5, 2020</span></span>| <span data-ttu-id="ce10b-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ce10b-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ce10b-113">2020 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="ce10b-113">Mar 5, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ce10b-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ce10b-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ce10b-115">この新機能により、Human Resources 全体のケース データを新しいビューで見ることができます。</span><span class="sxs-lookup"><span data-stu-id="ce10b-115">This new capability allows for new views into the case data across Human Resources.</span></span> <span data-ttu-id="ce10b-116">これらの機能拡張により、分析のためにすべてのケース データをインポートおよびエクスポートするオプションも利用できます。</span><span class="sxs-lookup"><span data-stu-id="ce10b-116">Options to import and export all case data for analysis are also available with these enhancements.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ce10b-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ce10b-117">Feature details</span></span>
<!--feature detail start -->
| <span data-ttu-id="ce10b-118">説明</span><span class="sxs-lookup"><span data-stu-id="ce10b-118">Description</span></span> | <span data-ttu-id="ce10b-119">変更</span><span class="sxs-lookup"><span data-stu-id="ce10b-119">Change</span></span> |
| --- | --- |
| <span data-ttu-id="ce10b-120">**役職**エンティティの変更</span><span class="sxs-lookup"><span data-stu-id="ce10b-120">**Job/Position** entity changes</span></span> | <ul><li><span data-ttu-id="ce10b-121">**報酬地域**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-121">**Compensation region** added</span></span></li>|
| <span data-ttu-id="ce10b-122">**役職分析コード** エンティティの追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-122">**Job position dimension** entity added</span></span> | <ul><li><span data-ttu-id="ce10b-123">**財務分析コード**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-123">**Financial dimensions** added</span></span></li>
| <span data-ttu-id="ce10b-124">**作業者**エンティティの変更</span><span class="sxs-lookup"><span data-stu-id="ce10b-124">**Worker** entity changes</span></span> | <ul><li><span data-ttu-id="ce10b-125">**名前の順序**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-125">**Name sequence** added</span></span></li><li><span data-ttu-id="ce10b-126">**在宅勤務**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-126">**Works from home** added</span></span></li><li><span data-ttu-id="ce10b-127">**言語**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-127">**Language** added</span></span></li><li><span data-ttu-id="ce10b-128">**勤続日数**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-128">**Seniority date** added</span></span></li><li><span data-ttu-id="ce10b-129">**記念日**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-129">**Anniversary date** added</span></span></li><li><span data-ttu-id="ce10b-130">**初回入社日**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-130">**Original hire date** added</span></span></li></ul> |
| <span data-ttu-id="ce10b-131">**雇用**エンティティの変更</span><span class="sxs-lookup"><span data-stu-id="ce10b-131">**Employment** entity changes</span></span> | <ul><li><span data-ttu-id="ce10b-132">**財務分析コード**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-132">**Financial dimensions** added</span></span></li><li><span data-ttu-id="ce10b-133">**退職理由**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-133">**Termination reason** added</span></span></li><li><span data-ttu-id="ce10b-134">**退職日**を**移行日**に改名</span><span class="sxs-lookup"><span data-stu-id="ce10b-134">**Termination date** renamed from **Transition date**</span></span></li><li><span data-ttu-id="ce10b-135">**仮採用日**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-135">**Probation date** added</span></span></li></ul> |
| <span data-ttu-id="ce10b-136">**作業者住所**エンティティの変更</span><span class="sxs-lookup"><span data-stu-id="ce10b-136">**Worker address** entity changes</span></span> | <ul><li><span data-ttu-id="ce10b-137">**番地**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-137">**Street address** added</span></span></li><li><span data-ttu-id="ce10b-138">**住所 1**、**住所 2**、および**住所 3** を非推奨としてマーク</span><span class="sxs-lookup"><span data-stu-id="ce10b-138">**Address line 1**, **Address line 2**, and **Address line 3** marked for deprecation</span></span></li></ul> |
| <span data-ttu-id="ce10b-139">新しい変動報酬設定エンティティ</span><span class="sxs-lookup"><span data-stu-id="ce10b-139">New variable compensation setup entities</span></span> | <ul><li><span data-ttu-id="ce10b-140">**変動報酬プラン タイプ**</span><span class="sxs-lookup"><span data-stu-id="ce10b-140">**Compensation variable plan type**</span></span></li><li><span data-ttu-id="ce10b-141">**変動報酬プラン**</span><span class="sxs-lookup"><span data-stu-id="ce10b-141">**Compensation variable plan**</span></span></li><li><span data-ttu-id="ce10b-142">**給付ルール**</span><span class="sxs-lookup"><span data-stu-id="ce10b-142">**Vesting rules**</span></span></li><li><span data-ttu-id="ce10b-143">**変動報酬プラン レベル**</span><span class="sxs-lookup"><span data-stu-id="ce10b-143">**Compensation variable plan level**</span></span></li></ul> |
| <span data-ttu-id="ce10b-144">新しい**作業者カレンダー雇用**エンティティ</span><span class="sxs-lookup"><span data-stu-id="ce10b-144">New **Worker calendar employment** entity</span></span> | <ul><li><span data-ttu-id="ce10b-145">**作業カレンダー エンティティ**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-145">**Work calendar entity** added</span></span></li></ul> |
| <span data-ttu-id="ce10b-146">新しい**給与職位詳細**エンティティ</span><span class="sxs-lookup"><span data-stu-id="ce10b-146">New **Payroll position detail** entity</span></span> | <ul><li><span data-ttu-id="ce10b-147">**給与職位詳細**の追加</span><span class="sxs-lookup"><span data-stu-id="ce10b-147">**Payroll position detail** added</span></span></li></ul> |
| <span data-ttu-id="ce10b-148">新しい**肩書き**エンティティ</span><span class="sxs-lookup"><span data-stu-id="ce10b-148">New **Title** entity</span></span> | <ul><li><span data-ttu-id="ce10b-149">**肩書き**の追加。</span><span class="sxs-lookup"><span data-stu-id="ce10b-149">**Title** added.</span></span> <span data-ttu-id="ce10b-150">新しい**肩書き**エンティティは Common Data Service に含まれていますが、最初は**役職**または**ジョブ エンティティ**から参照されません。</span><span class="sxs-lookup"><span data-stu-id="ce10b-150">The new **Title** entity is included in Common Data Service, but won't be initially referenced from the **Job Position** or **Job entities**.</span></span></li></ul> |
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ce10b-151">関連項目</span><span class="sxs-lookup"><span data-stu-id="ce10b-151">See also</span></span>

<!--docs start-->
<span data-ttu-id="ce10b-152">[Common Data Service エンティティ](https://docs.microsoft.com/dynamics365/human-resources/hr-developer-entities) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ce10b-152">[Common Data Service entities](https://docs.microsoft.com/dynamics365/human-resources/hr-developer-entities) (docs)</span></span>
<!--docs end-->

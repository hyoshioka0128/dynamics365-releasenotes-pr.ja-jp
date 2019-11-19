---
title: リスト ビューの保存とパーソナライズ
description: リスト ビューの保存とパーソナライズ
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 10/01/2019
ms.assetid: 386fe1f3-5f76-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 245ac2938c80be77598daf93f5457286292ebfb8
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2666863"
---
# <a name="save-and-personalize-list-views"></a><span data-ttu-id="79ace-103">リスト ビューの保存とパーソナライズ</span><span class="sxs-lookup"><span data-stu-id="79ace-103">Save and personalize list views</span></span>


| <span data-ttu-id="79ace-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="79ace-104">Enabled for</span></span>    |  <span data-ttu-id="79ace-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="79ace-105">Public preview</span></span> | <span data-ttu-id="79ace-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="79ace-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="79ace-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="79ace-107">End users, automatically</span></span>|<span data-ttu-id="79ace-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="79ace-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="79ace-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="79ace-109">Aug 1, 2019</span></span>| <span data-ttu-id="79ace-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="79ace-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="79ace-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="79ace-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="79ace-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="79ace-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="79ace-113">ビジネスが成長するにつれて、データベース内のテーブル データも増加し、適切なツールがないと迅速な分析やレコードの検索が困難になります。</span><span class="sxs-lookup"><span data-stu-id="79ace-113">As the business grows, so does table data in the database, making quick analysis or finding records more challenging without the right tools.</span></span> <span data-ttu-id="79ace-114">完璧なフィルターのセットを定義することは、時間がかかる反復的なプロセスである場合があります。フィルターを維持することができれば、次に必要なときにそれらを作り直さなければならない時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="79ace-114">Defining the perfect set of filters can be a time-consuming, iterative process where the ability to persist filters will save having to recreate them the next time they are needed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="79ace-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="79ace-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="79ace-116">Business Central の強力なフィルター処理機能は、表示するデータを完全に制御することにより、リストの操作を加速します。</span><span class="sxs-lookup"><span data-stu-id="79ace-116">Powerful filtering capabilities in Business Central accelerate work on lists by providing absolute control over which data is shown.</span></span> <span data-ttu-id="79ace-117">2019 年リリース ウェーブ 2 更新プログラムでは、ユーザーがフィルターをビューとして永続的に保存し、個人用ビュー、システム ビュー、および拡張機能のビューを 1 つのペインの下に組み合わせられるようにすることで、共通で使用されるフィルターを再作成する必要をなくしています。</span><span class="sxs-lookup"><span data-stu-id="79ace-117">The 2019 release wave 2 update eliminates the need to recreate commonly used filters by allowing users to permanently save filters as a view and combining personal views, system views, and those from extensions under one pane.</span></span>

### <a name="saving-a-view"></a><span data-ttu-id="79ace-118">ビューの保存</span><span class="sxs-lookup"><span data-stu-id="79ace-118">Saving a view</span></span>
<span data-ttu-id="79ace-119">ユーザーは、フィルター ペインのフィルターを「自分が所有する項目」などの認識可能な名前を持つリスト ビューとして保存できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79ace-119">Users can now save filters in the filter pane as a list view with a recognizable name, such as "Items I own."</span></span>

- <span data-ttu-id="79ace-120">特定のフィールド、合計、その他の計算フィールドでカスタム フィルターを使用して、新しいリスト ビューを保存します。</span><span class="sxs-lookup"><span data-stu-id="79ace-120">Save a new list view with custom filters on specific fields, on totals, and other calculated fields.</span></span>
- <span data-ttu-id="79ace-121">ビューに対する変更を保存して、ビューを徐々に微調整して完成させます。</span><span class="sxs-lookup"><span data-stu-id="79ace-121">Fine-tune and perfect your views over time by saving changes to them.</span></span>
- <span data-ttu-id="79ace-122">変更可能な個人用コピーを保存して、システム ビューをクローンします。</span><span class="sxs-lookup"><span data-stu-id="79ace-122">Clone any system view by saving a personal copy that you can modify.</span></span>
- <span data-ttu-id="79ace-123">個人用ビューの名前の変更と削除を簡単に行います。</span><span class="sxs-lookup"><span data-stu-id="79ace-123">Easily rename and remove personal views.</span></span>
- <span data-ttu-id="79ace-124">フィルター式、範囲、フィルター トークン (%MyCustomers など) のあらゆる領域を適用して、適切なデータを動的にフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="79ace-124">Apply the full spectrum of filter expressions, ranges, and filter tokens (such as %MyCustomers) to dynamically filter to the right data.</span></span>
- <span data-ttu-id="79ace-125">そのページにアクセスした方法に関係なく、フィルター ペインまたはコマンド メニューのリストのさまざまなビューをすばやく切り替えます。</span><span class="sxs-lookup"><span data-stu-id="79ace-125">Quickly switch between different views of a list in the filter pane or from the command menu, no matter how you accessed that page.</span></span>

<span data-ttu-id="79ace-126">![フィルター ペインが開き、さまざまなビューを表示しているリスト ページのスクリーンショット](media/save-views-3000x2000.png "フィルター ペインが開き、さまざまなビューを表示しているリスト ページのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="79ace-126">![Screenshot of a list page where the filter pane is open and displaying various views](media/save-views-3000x2000.png "Screenshot of a list page where the filter pane is open and displaying various views")</span></span>

<!-- Picture 1 -->
<span data-ttu-id="79ace-127">他の UI 個人用設定と同様に、リスト ビューは、ユーザーがサインインしているデバイスやブラウザーに関係なく、ユーザーと一緒に移動します。</span><span class="sxs-lookup"><span data-stu-id="79ace-127">Similar to other UI personalization, list views roam with the users no matter which device or browser they sign in to.</span></span>

### <a name="personalizing-the-filter-pane"></a><span data-ttu-id="79ace-128">フィルター ウィンドウのパーソナライズ</span><span class="sxs-lookup"><span data-stu-id="79ace-128">Personalizing the filter pane</span></span>
<span data-ttu-id="79ace-129">ページ上のビューの数が増えると、フィルター ペインをパーソナライズおよび最適化するための新しいツールが Business Central によって提供されます。</span><span class="sxs-lookup"><span data-stu-id="79ace-129">As the number of views on a page grows, Business Central gives you new tools to personalize and optimize the filter pane.</span></span>

- <span data-ttu-id="79ace-130">不要になった個人用ビューを削除するか、不要なシステム ビューを非表示にします。</span><span class="sxs-lookup"><span data-stu-id="79ace-130">Remove personal views that you no longer need or hide unwanted system views.</span></span>
- <span data-ttu-id="79ace-131">ビューを並べ替えて、完全なシーケンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="79ace-131">Reorder your views to get the perfect sequence.</span></span>

<span data-ttu-id="79ace-132">![フィルター ペインがパーソナライズされているリスト ページのスクリーンショット](media/view-personalization-3000x2000.png "フィルター ペインがパーソナライズされているリスト ページのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="79ace-132">![Screenshot of a list page where the filter pane is being personalized](media/view-personalization-3000x2000.png "Screenshot of a list page where the filter pane is being personalized")</span></span>
<!-- Picture 2 -->

### <a name="upgrading-from-an-earlier-version-of-business-central"></a><span data-ttu-id="79ace-133">以前のバージョンの Business Central からのアップグレード</span><span class="sxs-lookup"><span data-stu-id="79ace-133">Upgrading from an earlier version of Business Central</span></span>
<span data-ttu-id="79ace-134">今回のリリースでは、個人用ビューの定義、保存、カスタマイズの方法が大幅に見直され、これらの機能がクラウドおよび最新のクライアントに向けに提供されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79ace-134">With this release, the way personal views are defined, stored, and customized has undergone a major overhaul to unlock these capabilities for the cloud and for the modern clients.</span></span> <span data-ttu-id="79ace-135">次の重要な変更に注意してください。</span><span class="sxs-lookup"><span data-stu-id="79ace-135">Notice the following important changes:</span></span>

- <span data-ttu-id="79ace-136">AL 言語は、リスト ビューが Visual Studio コードで開発者によって作成されたのか、特定のユーザーまたはロール用にクライアントに保存されているのかにかかわらず、一貫してリスト ビューを記述するために使用される基本的な構文になりました。</span><span class="sxs-lookup"><span data-stu-id="79ace-136">The AL language is now the underlying syntax used to consistently describe list views, whether they were authored by a developer in Visual Studio Code or saved in the client for a specific user or role.</span></span> <span data-ttu-id="79ace-137">この技術的な変更により、レガシー モデルの上位 5 つの欠点が解消されました。</span><span class="sxs-lookup"><span data-stu-id="79ace-137">Through this technical change, the top five shortcomings of the legacy model have been eliminated.</span></span> <span data-ttu-id="79ace-138">たとえば、個人用ビューは、ナビゲーション メニューと**操作アシスト** ウィンドウのどちらからリストにアクセスするかにかかわらず、フィルターを適用するリストで常に使用可能です。</span><span class="sxs-lookup"><span data-stu-id="79ace-138">For example, your personal views are always available on the list that they apply filters to, whether you access that list from the navigation menu or through the **Tell Me** window.</span></span>
- <span data-ttu-id="79ace-139">ロール センター オブジェクトのリスト ビューを定義するために使用されるレガシー モデルは、下位互換性のために開発者が引き続き利用できますが、将来のリリースで廃止される予定です。</span><span class="sxs-lookup"><span data-stu-id="79ace-139">The legacy model used to define list views on a Role Center object is still available to developers for backward compatibility and will become obsolete in a future release.</span></span>
- <span data-ttu-id="79ace-140">データベースをアップグレードすると、特定のユーザーまたはロールのレガシー ビューがすべて破棄されます。</span><span class="sxs-lookup"><span data-stu-id="79ace-140">When upgrading your database, any legacy views for a specific user or role are discarded.</span></span> <span data-ttu-id="79ace-141">以前のバージョンを使用して作成されたビューは、Business Central 2019 リリース ウェーブ 2 以降と互換性がありません。</span><span class="sxs-lookup"><span data-stu-id="79ace-141">Views created using earlier versions are not compatible with Business Central 2019 release wave 2 and later.</span></span> <span data-ttu-id="79ace-142">個人用ビューはすべて手動で再作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="79ace-142">Any personal views must be recreated manually.</span></span>

### <a name="more-to-come"></a><span data-ttu-id="79ace-143">今後の予定</span><span class="sxs-lookup"><span data-stu-id="79ace-143">More to come</span></span>
<span data-ttu-id="79ace-144">ビューは、2019 年 10 月の最初のリリース後に段階的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="79ace-144">Views will be updated incrementally after the initial release in October 2019.</span></span> <span data-ttu-id="79ace-145">以下のような更新を予定しています:</span><span class="sxs-lookup"><span data-stu-id="79ace-145">Updates to look forward to include:</span></span>

- <span data-ttu-id="79ace-146">ビューに固有の列レイアウトをパーソナライズする。</span><span class="sxs-lookup"><span data-stu-id="79ace-146">Personalizing the column layout that is unique to a view.</span></span>
- <span data-ttu-id="79ace-147">任意のフィルター フィールドで式とその式の解決された値の間を切り替える。</span><span class="sxs-lookup"><span data-stu-id="79ace-147">Toggling between the expression and resolved value of that expression in any filter field.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="79ace-148">フィードバック</span><span class="sxs-lookup"><span data-stu-id="79ace-148">Tell us what you think</span></span>
<span data-ttu-id="79ace-149">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="79ace-149">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="79ace-150">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="79ace-150">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="79ace-151">関連項目</span><span class="sxs-lookup"><span data-stu-id="79ace-151">See also</span></span>
<span data-ttu-id="79ace-152">[機能の探索](https://aka.ms/ROGBC19RW2ROV7) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="79ace-152">[Feature exploration](https://aka.ms/ROGBC19RW2ROV7) (video)</span></span>

<span data-ttu-id="79ace-153">[リスト ビューの保存とパーソナライズ](https://docs.microsoft.com/dynamics365/business-central/ui-views) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="79ace-153">[Save and Personalize List Views](https://docs.microsoft.com/dynamics365/business-central/ui-views) (docs)</span></span>

---
title: 管理センターで直ちに環境の更新を開始する
description: Business Central 環境で半年ごとのメジャー更新プログラムが提供されると、環境で利用できる更新プログラムを直ちにインストールするアクションが Business Central 管理センターで利用可能になります。 これによりユーザーは、新しいサンドボックス環境を作成し、新しいサンドボックスに対して直ちに更新プログラムを実行することができます。 このオプションを使用すると、更新のスケジュール設定での遅延がなくなり、サンドボックス環境で更新プログラムをテストするプロセスが合理化されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/26/2020
ms.assetid: 1136f364-0bc9-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: f0c30ef513740aab0a623b77e624660785211dfe
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232629"
---
# <a name="start-immediate-environment-updates-in-the-administration-center"></a><span data-ttu-id="debb7-105">管理センターで直ちに環境の更新を開始する</span><span class="sxs-lookup"><span data-stu-id="debb7-105">Start immediate environment updates in the administration center</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="debb7-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="debb7-106">Enabled for</span></span>    |  <span data-ttu-id="debb7-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="debb7-107">Public preview</span></span> | <span data-ttu-id="debb7-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="debb7-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="debb7-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="debb7-109">End users, automatically</span></span>|-| <span data-ttu-id="debb7-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="debb7-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="debb7-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="debb7-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="debb7-112">パートナーが新しいリリースを直ちに検証およびテストできるようにすることで、リリースおよびアップグレード プロセスでの時間のかかるステップを排除し、パートナーが新しいリリースの価値を顧客にすばやく提供できるようにします。</span><span class="sxs-lookup"><span data-stu-id="debb7-112">By enabling partners to immediately validate and test new releases, we are removing a time-consuming step in the release and upgrade process and, in turn, enabling our partners to quickly provide the value of new releases to their customers</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="debb7-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="debb7-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="debb7-114">ご利用の環境で 2020 年リリース ウェーブ 1 の更新プログラムが予定されているというメール通知を受け取ったら、Business Central 管理センターを使用して、より都合のよい日付に更新日を変更できます。</span><span class="sxs-lookup"><span data-stu-id="debb7-114">When you receive an email notification about your environment being scheduled for 2020 release wave 1 update, you can change the update date to a more convenient date by using the Business Central administration center.</span></span> <span data-ttu-id="debb7-115">運用環境のコピーとしてサンドボックス環境を作成して、更新プログラムをテストすることもできます。</span><span class="sxs-lookup"><span data-stu-id="debb7-115">You can also test the update by creating a sandbox environment as a copy of your production environment.</span></span> <span data-ttu-id="debb7-116">以前のリリースでは、新しく追加される環境は数日以内に更新プログラムのロールアウト プロセスに追加されるため、更新プログラムをテストできる可能性が非常に限られていました。</span><span class="sxs-lookup"><span data-stu-id="debb7-116">In the previous releases, newly added environments would be added to the update roll-out process within a few days, which significantly limited your ability to test the updates.</span></span> <span data-ttu-id="debb7-117">2020 年 リリース ウェーブ 1 で更新プログラムのロールアウト プロセスに導入された改善により、新しく作成されたサンドボックス環境が **1 時間以内**に 2020 年リリース ウェーブ 1 の更新プログラムのロールアウトに追加されるようになります。</span><span class="sxs-lookup"><span data-stu-id="debb7-117">With the improvements we've introduced to the update roll-out process in 2020 release wave 1, the newly created sandbox environment will be automatically added to 2020 release wave 1 update roll-out **within one hour**.</span></span> <span data-ttu-id="debb7-118">Business Central 管理センターで自分自身を通知の受信者として追加している場合は、メール通知が届き、管理センターにも更新通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="debb7-118">If you added yourself as a notification's recipient in the Business Central administration center, you will receive an email notification, and the update notification will also be visible in the administration center.</span></span> 

<span data-ttu-id="debb7-119">この環境の更新を直ちに開始する場合は、**環境**ページを開き、**更新**メニューから**更新のスケジュール設定**を選択します。</span><span class="sxs-lookup"><span data-stu-id="debb7-119">If you want to start the update of this environment immediately, open the **Environment** page, then select **Schedule Update** from the **Update** menu.</span></span> <span data-ttu-id="debb7-120">更新日を現在の日付に変更し、選択内容を確認します。</span><span class="sxs-lookup"><span data-stu-id="debb7-120">Change the update date to the current date and confirm your choice.</span></span> <span data-ttu-id="debb7-121">更新が直ちに開始されます。</span><span class="sxs-lookup"><span data-stu-id="debb7-121">The update will start immediately.</span></span> 

<span data-ttu-id="debb7-122">ご利用の環境に更新ウィンドウが定義されている場合、更新は最初の使用可能なウィンドウ (翌日になる場合があります) から開始されます。</span><span class="sxs-lookup"><span data-stu-id="debb7-122">If your environment has the update window defined, the update will start in the first available window (which may be on the next day).</span></span> <span data-ttu-id="debb7-123">更新が失敗した場合は、失敗を分析して修正し、同じ方法で更新をもう一度繰り返すことができます。</span><span class="sxs-lookup"><span data-stu-id="debb7-123">If the update fails, you can analyze and correct the failures and repeat the update attempt again in the same way.</span></span> 
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="debb7-124">フィードバック</span><span class="sxs-lookup"><span data-stu-id="debb7-124">Tell us what you think</span></span>
<span data-ttu-id="debb7-125">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="debb7-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="debb7-126">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="debb7-126">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="debb7-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="debb7-127">See also</span></span>


<!--docs start-->
<span data-ttu-id="debb7-128">[Business Central Online のメジャー更新](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/update-rollout-timelime) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="debb7-128">[Major Updates of Business Central Online](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/update-rollout-timelime) (docs)</span></span>
<!--docs end-->


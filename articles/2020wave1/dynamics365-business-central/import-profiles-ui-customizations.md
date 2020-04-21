---
title: プロファイルと UI のカスタマイズのインポート
description: プロファイルと UI のカスタマイズをインポートします。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 293aca07-3f36-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 4edc2eeeebde83c9b429d2a01d68152a040d6fba
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232233"
---
# <a name="import-profiles-and-ui-customizations"></a><span data-ttu-id="3ad66-103">プロファイルと UI のカスタマイズのインポート</span><span class="sxs-lookup"><span data-stu-id="3ad66-103">Import profiles and UI customizations</span></span>


| <span data-ttu-id="3ad66-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3ad66-104">Enabled for</span></span>    |  <span data-ttu-id="3ad66-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3ad66-105">Public preview</span></span> | <span data-ttu-id="3ad66-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3ad66-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3ad66-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="3ad66-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="3ad66-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3ad66-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3ad66-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3ad66-109">Feb 1, 2020</span></span>| <span data-ttu-id="3ad66-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3ad66-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3ad66-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3ad66-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3ad66-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3ad66-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3ad66-113">管理者やコンサルタントは、Business Central でのロール調整をサポートする豊富なツールセットを活用できます。</span><span class="sxs-lookup"><span data-stu-id="3ad66-113">Administrators and consultants benefit from a rich toolset that supports role-tailoring in Business Central.</span></span> <span data-ttu-id="3ad66-114">プロファイル (組織のロール) のエクスポート機能とインポート機能およびそれに対応するユーザー インターフェイスのカスタマイズを備えているため、お客様は、他の変更を行う前にプロファイルのカスタマイズを簡単にバックアップできます。</span><span class="sxs-lookup"><span data-stu-id="3ad66-114">By having both an export and import function for profiles (organizational roles) and their corresponding user interface customizations, customers can easily back up their profile customizations before making further changes.</span></span> <span data-ttu-id="3ad66-115">環境間でプロファイルを複製したり、運用環境にインポートする前にオンライン サンドボックスで可能性を安全に調べたりすることができます。</span><span class="sxs-lookup"><span data-stu-id="3ad66-115">They can replicate profiles across environments or safely explore possibilities in an online sandbox before importing into production.</span></span> <span data-ttu-id="3ad66-116">これらのすべてについて、開発者の手助けは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="3ad66-116">All this without requiring the assistance of developers.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3ad66-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3ad66-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3ad66-118">ステップバイステップ ウィザードでは、3 つの簡単なステップでパッケージをインポートするプロセスが説明されます。</span><span class="sxs-lookup"><span data-stu-id="3ad66-118">A step-by-step wizard walks you through the process of importing a package in three simple steps:</span></span>

1. <span data-ttu-id="3ad66-119">インポートするプロファイル パッケージを選択してください。</span><span class="sxs-lookup"><span data-stu-id="3ad66-119">Select the profile package to import.</span></span> <span data-ttu-id="3ad66-120">パッケージは、プロファイル リストから以前にエクスポートした **.zip** 拡張子付きのファイルです。</span><span class="sxs-lookup"><span data-stu-id="3ad66-120">The package is a file with the **.zip** extension that you exported earlier from the profiles list.</span></span>
2. <span data-ttu-id="3ad66-121">パッケージに含まれるプロファイルの概要を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ad66-121">Get an overview of which profiles are in the package.</span></span> <span data-ttu-id="3ad66-122">同じプロファイル ID を持つ環境内のプロファイルを上書きするかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="3ad66-122">Decide whether you want to overwrite any profiles in your environment that have the same Profile ID.</span></span>
3. <span data-ttu-id="3ad66-123">正常にインポートされたプロファイルと、解決する必要がある問題があるプロファイルを確認します。</span><span class="sxs-lookup"><span data-stu-id="3ad66-123">See which profiles were imported successfully and which have issues that you may need to resolve.</span></span>

<span data-ttu-id="3ad66-124">![プロファイルのリストへの変更は、再度エクスポートおよびインポートできます](media/export-and-import.png "プロファイルのリストへの変更は、再度エクスポートおよびインポートできます")</span><span class="sxs-lookup"><span data-stu-id="3ad66-124">![Changes to the list of profiles can be exported and imported again](media/export-and-import.png "Changes to the list of profiles can be exported and imported again")</span></span>

<span data-ttu-id="3ad66-125">![インポートするプロファイルの選択に役立つウィザードのステップ](media/choice-of-profiles-to-import.png "インポートするプロファイルの選択に役立つウィザードのステップ")</span><span class="sxs-lookup"><span data-stu-id="3ad66-125">![The wizard step that helps you choose which profiles to import](media/choice-of-profiles-to-import.png "The wizard step that helps you choose which profiles to import")</span></span>   

<span data-ttu-id="3ad66-126">プロファイルのパッケージを環境にインポートすると、プロファイルとその設定およびページのカスタマイズが追加または置換されます。</span><span class="sxs-lookup"><span data-stu-id="3ad66-126">Importing a package of profiles into your environment will add or replace profiles along with their settings and page customizations.</span></span>  

### <a name="try-it-now"></a><span data-ttu-id="3ad66-127">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="3ad66-127">Try it now</span></span>
<span data-ttu-id="3ad66-128">[ここで](https://businesscentral.dynamics.com/?page=9171)オンライン環境にログインし、プロファイルのページをカスタマイズし、そのプロファイルへの変更をエクスポートし、再度インポートするという完全なサイクルを体験してください。</span><span class="sxs-lookup"><span data-stu-id="3ad66-128">Sign in to your online environment [here](https://businesscentral.dynamics.com/?page=9171) and experience the full cycle of customizing pages for a profile, exporting the changes to that profile, and then importing again.</span></span>  

<span data-ttu-id="3ad66-129">プロファイルのインポート アクションを使用するには、関連するテーブルを変更するためのアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="3ad66-129">You must have permission to modify the relevant tables to use the Import Profiles action.</span></span>   
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="3ad66-130">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3ad66-130">Tell us what you think</span></span>
<span data-ttu-id="3ad66-131">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="3ad66-131">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3ad66-132">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3ad66-132">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="3ad66-133">関連項目</span><span class="sxs-lookup"><span data-stu-id="3ad66-133">See also</span></span>


<!--docs start-->
<span data-ttu-id="3ad66-134">[プロファイルの管理](https://docs.microsoft.com/dynamics365/business-central/admin-users-profiles-roles) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3ad66-134">[Managing Profiles](https://docs.microsoft.com/dynamics365/business-central/admin-users-profiles-roles) (docs)</span></span>
<!--docs end-->


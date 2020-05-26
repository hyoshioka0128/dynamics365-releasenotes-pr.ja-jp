---
title: アクセス許可管理の生産性の向上
description: アクセス許可セットを管理するためのオプションの追加
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/21/2020
ms.assetid: 7c301a0f-4aca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: bnielse
dynamics365pdf: true
ms.openlocfilehash: affb6f0c72187eb488f4b097a92f1a669d5ae8b9
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294217"
---
# <a name="productivity-improvements-in-permissions-management"></a><span data-ttu-id="ef0b1-103">アクセス許可管理の生産性の向上</span><span class="sxs-lookup"><span data-stu-id="ef0b1-103">Productivity improvements in permissions management</span></span>


| <span data-ttu-id="ef0b1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ef0b1-104">Enabled for</span></span>    |  <span data-ttu-id="ef0b1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ef0b1-105">Public preview</span></span> | <span data-ttu-id="ef0b1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ef0b1-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ef0b1-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ef0b1-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="ef0b1-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ef0b1-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ef0b1-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ef0b1-109">Feb 1, 2020</span></span>| <span data-ttu-id="ef0b1-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ef0b1-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ef0b1-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ef0b1-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ef0b1-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ef0b1-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ef0b1-113">企業は通常、特定のロール/職務の分離を必要とするため、一連の対応するユーザー グループとアクセス許可セットを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-113">Businesses usually require specific role/duty segregation and therefore maintain a corresponding set of user groups and permission sets.</span></span> <span data-ttu-id="ef0b1-114">この管理と、従来のアクセス許可セットを使用している Dynamics NAV からのお客様へのサービス提供がより効率的に行えるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-114">We've made it more efficient to manage this and also to service customers coming from Dynamics NAV with legacy permission sets.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ef0b1-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ef0b1-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ef0b1-116">以下の機能強化が導入されました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-116">The following improvements have been implemented:</span></span>

- <span data-ttu-id="ef0b1-117">[アクセス許可] および [テナント アクセス許可] ページに**オブジェクトのキャプション** フィールドが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-117">The **Object Caption** field is added on the Permissions and Tenant Permissions pages.</span></span> <span data-ttu-id="ef0b1-118">**オブジェクトのキャプション** フィールドは、既定では非表示になっています。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-118">The **Object Caption** field is hidden by default.</span></span>
- <span data-ttu-id="ef0b1-119">[アクセス許可セット] ページに、すべてのアクセス許可から古いオブジェクトを削除する新しいアクション、**古いアクセス許可を削除**が追加されました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-119">A new **Remove Obsolete Permissions** action is added on the Permission Sets page that will remove any obsolete objects from all permission sets.</span></span>
- <span data-ttu-id="ef0b1-120">**アクセス許可セットを除外**および**アクセス許可セットを含める**アクションで、複数のアクセス許可セットを選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-120">The possibility to select multiple permissions sets with **Exclude Permission Sets** and **Include Permission Sets** actions.</span></span> <span data-ttu-id="ef0b1-121">複数選択は、オンプレミスのインストールのシステム アクセス許可セットにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-121">Multiselect will also be available for System permission sets in on-premises installations.</span></span>
- <span data-ttu-id="ef0b1-122">オンプレミスのインストールで、システム アクセス許可をインポートおよびエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-122">The possibility to import and export system permissions is added for on-premises installations.</span></span>
- <span data-ttu-id="ef0b1-123">インポート時にアクセス許可をマージする機能が、システム アクセス許可とテナント アクセス許可の両方に追加されました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-123">The possibility to merge permissions when importing is added for both system and tenant permissions.</span></span> <span data-ttu-id="ef0b1-124">アクセス許可セットが既に存在する場合、ユーザーはインポートをスキップするか、またはアクセス許可セットをマージするように求められます。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-124">Users will be prompted to either skip import or merge permission sets when permission sets already exist.</span></span>
- <span data-ttu-id="ef0b1-125">**アクセス許可セットのフィルター処理**アクションで複数のアクセス許可セットを選択および表示する機能が、システム アクセス許可とテナント アクセス許可の両方に追加されました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-125">The possibility to select and display several permission sets with the **Filter Permission Sets** action is added for both system and tenant permissions.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="ef0b1-126">フィードバック</span><span class="sxs-lookup"><span data-stu-id="ef0b1-126">Tell us what you think</span></span>
<span data-ttu-id="ef0b1-127">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-127">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="ef0b1-128">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-128">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="ef0b1-129">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="ef0b1-129">Thank you for your idea</span></span>
<span data-ttu-id="ef0b1-130">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=bb59f6f9-b7f3-e811-a140-0003ff68d8c6)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-130">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=bb59f6f9-b7f3-e811-a140-0003ff68d8c6).</span></span> <span data-ttu-id="ef0b1-131">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="ef0b1-131">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="ef0b1-132">関連項目</span><span class="sxs-lookup"><span data-stu-id="ef0b1-132">See also</span></span>

<!--docs start-->
<span data-ttu-id="ef0b1-133">[ユーザーとグループにアクセス許可を割り当てる](https://docs.microsoft.com/dynamics365/business-central/ui-define-granular-permissions) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ef0b1-133">[Assign Permissions to Users and Groups](https://docs.microsoft.com/dynamics365/business-central/ui-define-granular-permissions) (docs)</span></span>
<!--docs end-->

---
title: 機能を事前に有効にする
description: 機能を事前に有効にする
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 2cd65e43-6c1a-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 39df9880564d4d2528acf22602f818b20cddc533
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219698"
---
# <a name="enable-features-ahead-of-time"></a><span data-ttu-id="aa150-103">機能を事前に有効にする</span><span class="sxs-lookup"><span data-stu-id="aa150-103">Enable features ahead of time</span></span>


| <span data-ttu-id="aa150-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="aa150-104">Enabled for</span></span>    |  <span data-ttu-id="aa150-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aa150-105">Public preview</span></span> | <span data-ttu-id="aa150-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="aa150-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aa150-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="aa150-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="aa150-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="aa150-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="aa150-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="aa150-109">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="aa150-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="aa150-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="aa150-111">サービスの変更によるビジネスの混乱を最小限に抑えることは、マイクロソフトにとって最も重要です。</span><span class="sxs-lookup"><span data-stu-id="aa150-111">Minimizing business disruption because of changes in the service is of utmost importance to Microsoft.</span></span>

<span data-ttu-id="aa150-112">Business Central のお客様は、6 か月ごとのメジャー更新を含む毎月の更新プログラムを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="aa150-112">Business Central customers receive monthly updates, including a major update every six months.</span></span> <span data-ttu-id="aa150-113">更新プログラムには、修正、設計強化、およびユーザー エクスペリエンスを変更することもある新機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="aa150-113">Updates include fixes, design enhancements, and new features that occasionally change the user experience.</span></span> <span data-ttu-id="aa150-114">管理者が変更を管理できるようにすることで、お客様は自信を持って準備を整え、独自の条件でビジネスのデジタル変革を推進できます。</span><span class="sxs-lookup"><span data-stu-id="aa150-114">By empowering administrators to manage change, customers can get ready with confidence and drive the digital transformation of the business on their own terms.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="aa150-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aa150-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aa150-116">管理者は新しい**機能管理**ページを使用して、以下を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="aa150-116">Administrators can use the new **Feature Management** page to:</span></span>

 - <span data-ttu-id="aa150-117">マイナー更新の前に有効にできる新機能と機能拡張について確認します。</span><span class="sxs-lookup"><span data-stu-id="aa150-117">Learn which new features and feature enhancements can be enabled ahead of time in minor updates.</span></span>
 - <span data-ttu-id="aa150-118">任意の環境のすべてのユーザーに対して、個々の機能を再度オンおよびオフにします。</span><span class="sxs-lookup"><span data-stu-id="aa150-118">Turn individual features on and off again for all users of any environment.</span></span>
 - <span data-ttu-id="aa150-119">すべてのユーザーに対して機能を有効にせずに、新しいブラウザー タブで機能を安全に試します。</span><span class="sxs-lookup"><span data-stu-id="aa150-119">Safely try out a feature in a new browser tab without enabling the feature for all users.</span></span>
 - <span data-ttu-id="aa150-120">今後の変更に間に合うようにテストと準備のアプローチを計画します。</span><span class="sxs-lookup"><span data-stu-id="aa150-120">Plan an approach to testing and preparation in time for upcoming change.</span></span> <span data-ttu-id="aa150-121">たとえば、運用環境で機能を有効にする前に、運用データのコピーを使用してサンドボックス環境でテストできます。</span><span class="sxs-lookup"><span data-stu-id="aa150-121">For example, they can test on a sandbox environment with a copy of production data before they enable a feature in production.</span></span>

<span data-ttu-id="aa150-122">![有効または無効になっている機能の例が表示された機能管理ページ](media/feature-management.png "有効または無効になっている機能の例が表示された機能管理ページ")</span><span class="sxs-lookup"><span data-stu-id="aa150-122">![Feature Management page with example features that are enabled or disabled](media/feature-management.png "Feature Management page with example features that are enabled or disabled")</span></span>

<span data-ttu-id="aa150-123">Update 16.0 (2020 年 4 月) で事前に有効にできる機能はありません。</span><span class="sxs-lookup"><span data-stu-id="aa150-123">There are no features that you can enable ahead of time in Update 16.0 (April 2020).</span></span> <span data-ttu-id="aa150-124">Update 16.1 以降、機能が一覧に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="aa150-124">Features will begin to appear in the list starting from Update 16.1.</span></span>  

<span data-ttu-id="aa150-125">**機能管理**ページに一覧表示される機能について:</span><span class="sxs-lookup"><span data-stu-id="aa150-125">About the features listed in the **Feature Management** page:</span></span>

 - <span data-ttu-id="aa150-126">このページでは、マイナー更新でリリースされる機能のサブセットのみを使用できます。</span><span class="sxs-lookup"><span data-stu-id="aa150-126">Only a subset of features releasing in minor updates are available in the page.</span></span>
 - <span data-ttu-id="aa150-127">機能は主に、ユーザー エクスペリエンスに影響するプラットフォームの変更です。</span><span class="sxs-lookup"><span data-stu-id="aa150-127">Features are primarily platform changes that affect the user experience.</span></span>
 - <span data-ttu-id="aa150-128">機能はしばらくの間オプションであり、その後、将来のサービス更新で完全に有効になります。</span><span class="sxs-lookup"><span data-stu-id="aa150-128">Features are optional for a while, after which they're permanently enabled in a future service update.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="aa150-129">フィードバック</span><span class="sxs-lookup"><span data-stu-id="aa150-129">Tell us what you think</span></span>
<span data-ttu-id="aa150-130">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="aa150-130">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="aa150-131">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="aa150-131">Use the forum at https://aka.ms/bcideas.</span></span>




---
title: Azure AD での POS サインインのサポート
description: この機能により、Azure Active Directory (Azure AD) に販売時点管理 (POS) サインインのサポートが提供されます。
author: relnotes
ms.reviewer: josaw
ms.date: 05/04/2020
ms.assetid: e6241ff2-f00c-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 00c760203dc47cccc87f5db7e402062a4c10d433
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3382168"
---
# <a name="azure-ad-support-for-pos-sign-in"></a><span data-ttu-id="3da3c-103">Azure AD での POS サインインのサポート</span><span class="sxs-lookup"><span data-stu-id="3da3c-103">Azure AD support for POS sign-in</span></span>


| <span data-ttu-id="3da3c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3da3c-104">Enabled for</span></span>    |  <span data-ttu-id="3da3c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3da3c-105">Public preview</span></span> | <span data-ttu-id="3da3c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3da3c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3da3c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3da3c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3da3c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3da3c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3da3c-109">2020 年 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="3da3c-109">Feb 24, 2020</span></span>| <span data-ttu-id="3da3c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3da3c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3da3c-111">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3da3c-111">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3da3c-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3da3c-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3da3c-113">現在、Commerce POS (販売時点管理) アプリケーションは、独自の ID プロバイダーに基づくスタッフ認証のみをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="3da3c-113">The Commerce point of sale (POS) application today only supports staff authentication based on our own identity provider.</span></span> <span data-ttu-id="3da3c-114">Azure Active Directory (Azure AD) での POS サインインのサポートは、さまざまな小売業者からリクエストされたもので、一般にセキュリティと保守性の 2 つの要件があります。</span><span class="sxs-lookup"><span data-stu-id="3da3c-114">Azure Active Directory (Azure AD) support for POS sign-in has been a request from various retailers, with generally two requirements: security and maintainability.</span></span> <span data-ttu-id="3da3c-115">企業のセキュリティ要件が厳しいお客様は通常、POS に対する認証をより安全に処理する方法として Azure AD を検討します。</span><span class="sxs-lookup"><span data-stu-id="3da3c-115">Customers with stringent corporate security requirements usually look at Azure AD as a more secure way to handle authentication against the POS.</span></span> <span data-ttu-id="3da3c-116">多くのお客様は通常、複数の Microsoft クラウド サービス (Azure、Office 365、Dynamics 365) を使用しており、Azure AD で既にワーカーをセットアップしています。</span><span class="sxs-lookup"><span data-stu-id="3da3c-116">Many customers typically use multiple Microsoft cloud services (Azure, Office 365, Dynamics 365), and already have their workers set up in Azure AD.</span></span> <span data-ttu-id="3da3c-117">Commerce ソリューションを使用するために、Dynamics 365 Commerce バック オフィスでそれら (およびそのパスワード) をもう一度管理したくはありません。</span><span class="sxs-lookup"><span data-stu-id="3da3c-117">They don’t want to manage them (and their passwords) again in the Dynamics 365 Commerce back office in order to use the Commerce solution.</span></span> <span data-ttu-id="3da3c-118">これにより、簡単に回避できる重複作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="3da3c-118">This creates duplicate effort for them that could be easily avoided.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3da3c-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3da3c-119">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3da3c-120">この機能では、以下のものが導入されます。</span><span class="sxs-lookup"><span data-stu-id="3da3c-120">This feature will introduce:</span></span>

- <span data-ttu-id="3da3c-121">POS サインインに必要な認証方法を指定するための Commerce Headquarters (HQ) の新しい構成パラメーター。</span><span class="sxs-lookup"><span data-stu-id="3da3c-121">A new configuration parameter in Commerce headquarters (HQ) to specify the desired authentication method for POS sign-in.</span></span>
- <span data-ttu-id="3da3c-122">ユーザー認証に Azure AD を活用するように変更された POS サインイン ページ。</span><span class="sxs-lookup"><span data-stu-id="3da3c-122">A modified POS sign-in page to leverage Azure AD for user authentication.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="3da3c-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="3da3c-123">See also</span></span>

<!--docs start-->
<span data-ttu-id="3da3c-124">[POS サインインの Azure Active Directory 認証の有効化](https://docs.microsoft.com/dynamics365/commerce/aad-pos-logon) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3da3c-124">[Enable Azure Active Directory authentication for POS sign-in](https://docs.microsoft.com/dynamics365/commerce/aad-pos-logon) (docs)</span></span>
<!--docs end-->

---
title: Azure AD での POS サインインのサポート
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 03/06/2020
ms.assetid: e6241ff2-f00c-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 91198f3bc6d55e212efa2cbf766f03ae17c57c47
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232651"
---
# <a name="azure-ad-support-for-pos-sign-in"></a><span data-ttu-id="657b8-102">Azure AD での POS サインインのサポート</span><span class="sxs-lookup"><span data-stu-id="657b8-102">Azure AD support for POS sign-in</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="657b8-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="657b8-103">Enabled for</span></span>    |  <span data-ttu-id="657b8-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="657b8-104">Public preview</span></span> | <span data-ttu-id="657b8-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="657b8-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="657b8-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="657b8-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="657b8-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="657b8-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="657b8-108">2020 年 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="657b8-108">Feb 24, 2020</span></span>| <span data-ttu-id="657b8-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="657b8-109">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="657b8-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="657b8-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="657b8-111">現在、Commerce POS (販売時点管理) アプリケーションは、独自の ID プロバイダーに基づくスタッフ認証のみをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="657b8-111">Our Commerce point of sale (POS) application today only supports staff authentication based on our own identity provider.</span></span> <span data-ttu-id="657b8-112">Azure Active Directory (Azure AD) での POS サインインのサポートは、さまざまな小売業者からリクエストされたもので、一般にセキュリティと保守性の 2 つの要件があります。</span><span class="sxs-lookup"><span data-stu-id="657b8-112">Azure Active Directory (Azure AD) support for POS sign-in has been a request from various retailers, with generally two requirements: security and maintainability.</span></span> <span data-ttu-id="657b8-113">企業のセキュリティ要件が厳しいお客様は通常、POS に対する認証をより安全に処理する方法として Azure AD を検討します。</span><span class="sxs-lookup"><span data-stu-id="657b8-113">Customers with stringent corporate security requirements usually look at Azure AD as a more secure way to handle authentication against the POS.</span></span> <span data-ttu-id="657b8-114">多くのお客様は通常、複数の Microsoft クラウド サービス (Azure、Office 365、Dynamics 365) を使用しており、Azure AD で既にワーカーをセットアップしています。</span><span class="sxs-lookup"><span data-stu-id="657b8-114">Many customers typically use multiple Microsoft cloud services (Azure, Office 365, Dynamics 365), and already have their workers set up in Azure AD.</span></span> <span data-ttu-id="657b8-115">Commerce ソリューションを使用するために、Dynamics 365 Commerce バック オフィスでそれら (およびそのパスワード) をもう一度管理したくはありません。</span><span class="sxs-lookup"><span data-stu-id="657b8-115">They don’t want to manage them (and their passwords) again in the Dynamics 365 Commerce back office in order to use the Commerce solution.</span></span> <span data-ttu-id="657b8-116">これにより、簡単に回避できる重複作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="657b8-116">This creates duplicate effort for them that could be easily avoided.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="657b8-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="657b8-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="657b8-118">この機能では、以下のものが導入されます。</span><span class="sxs-lookup"><span data-stu-id="657b8-118">This feature will introduce:</span></span>

- <span data-ttu-id="657b8-119">POS サインインに必要な認証方法を指定するための Commerce Headquarters (HQ) の新しい構成パラメーター。</span><span class="sxs-lookup"><span data-stu-id="657b8-119">A new configuration parameter in Commerce headquarters (HQ) to specify the desired authentication method for POS sign-in.</span></span>
- <span data-ttu-id="657b8-120">ユーザー認証に Azure AD を活用するように変更された POS サインイン ページ。</span><span class="sxs-lookup"><span data-stu-id="657b8-120">A modified POS sign-in page to leverage Azure AD for user authentication.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="657b8-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="657b8-121">See also</span></span>


<!--docs start-->
<span data-ttu-id="657b8-122">[POS サインインの Azure Active Directory 認証の有効化](https://docs.microsoft.com/dynamics365/commerce/aad-pos-logon) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="657b8-122">[Enable Azure Active Directory authentication for POS sign-in](https://docs.microsoft.com/dynamics365/commerce/aad-pos-logon) (docs)</span></span>
<!--docs end-->


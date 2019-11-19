---
title: eコマース チェックアウト時に Dynamics 365 Fraud Protection を呼び出す
description: 初めて Dynamics 365 Fraud Protection とそのまま統合できるようになったことで、eコマース チェックアウト フローに詐欺防止ロジックをそのまま統合できるようになりました。
author: relnotes
ms.reviewer: josaw
ms.date: 10/02/2019
ms.assetid: 5539f1c8-16e2-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 4882a8ad292620a09d4cd75544248b3412f9e698
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659817"
---
# <a name="invoke-dynamics-365-fraud-protection-during-e-commerce-checkout"></a><span data-ttu-id="1b984-103">eコマース チェックアウト時に Dynamics 365 Fraud Protection を呼び出す</span><span class="sxs-lookup"><span data-stu-id="1b984-103">Invoke Dynamics 365 Fraud Protection during e-commerce checkout</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="1b984-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1b984-104">Enabled for</span></span>    |  <span data-ttu-id="1b984-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1b984-105">Public preview</span></span> | <span data-ttu-id="1b984-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1b984-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1b984-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="1b984-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1b984-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="1b984-108">Nov 2019</span></span>| <span data-ttu-id="1b984-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="1b984-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1b984-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1b984-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1b984-111">この機能は、Dynamics 365 Commerce を使用したすぐに使用できる詐欺防止オプションを小売店に提供します。</span><span class="sxs-lookup"><span data-stu-id="1b984-111">This feature brings an out-of-box fraud protection option to retailers using Dynamics 365 Commerce.</span></span> <span data-ttu-id="1b984-112">そのまま使用できる Commerce 製品を使用する場合でも、SDK を通じてサード パーティのストアフロントと統合する場合でも、認証のために送信される前にクレジット カード トランザクションの詐欺についてチェックするオプションが用意されています。</span><span class="sxs-lookup"><span data-stu-id="1b984-112">Whether using out-of-box Commerce offerings or integrating with a third party storefront through the SDK, there will be an option to check credit card transactions for fraud prior to sending for authorization.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1b984-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1b984-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1b984-114">この機能により、トランザクションが認証のために送信される前に、Fraud Protection によってリスクが評価されるようにすることで、Dynamics 365 Fraud Protection との基本的な統合をもたらします。</span><span class="sxs-lookup"><span data-stu-id="1b984-114">This feature will bring basic integration with Dynamics 365 Fraud Protection by allowing transactions to have risk assessed with Fraud Protection prior to being sent for authorization.</span></span> <span data-ttu-id="1b984-115">アダプティブ AI 技術を使用することで、継続的に更新される詐欺モデルに対してトランザクションがチェックされ、eコマース トランザクションの不当な拒否と試行回数を減らします。</span><span class="sxs-lookup"><span data-stu-id="1b984-115">Using adaptive AI technology, transactions can be checked against continuously-updated fraud models to decrease wrongful rejections and challenge rates for e-commerce transactions.</span></span> <span data-ttu-id="1b984-116">将来の毎月の更新プログラムにより、Commerce と Fraud Protection の統合がさらに強化されます。</span><span class="sxs-lookup"><span data-stu-id="1b984-116">Future monthly updates will bring further integration between Commerce and Fraud Protection.</span></span>
<!--feature detail end -->










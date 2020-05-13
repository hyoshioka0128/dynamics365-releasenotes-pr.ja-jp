---
title: eコマース チェックアウト時に Dynamics 365 Fraud Protection を呼び出す
description: 初めて Dynamics 365 Fraud Protection とそのまま統合できるようになったことで、eコマース チェックアウト フローに詐欺防止ロジックをそのまま統合できるようになりました。
author: relnotes
ms.reviewer: josaw
ms.date: 03/20/2020
ms.assetid: 5539f1c8-16e2-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: cbb7aec8dd4e15ecbcec1c79cc5047c5a73a1cec
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320734"
---
# <a name="invoke-dynamics-365-fraud-protection-during-e-commerce-checkout"></a><span data-ttu-id="76b9c-103">eコマース チェックアウト時に Dynamics 365 Fraud Protection を呼び出す</span><span class="sxs-lookup"><span data-stu-id="76b9c-103">Invoke Dynamics 365 Fraud Protection during e-commerce checkout</span></span>


| <span data-ttu-id="76b9c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="76b9c-104">Enabled for</span></span>    |  <span data-ttu-id="76b9c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="76b9c-105">Public preview</span></span> | <span data-ttu-id="76b9c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="76b9c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="76b9c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="76b9c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="76b9c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="76b9c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="76b9c-109">2019 年 11 月 25 日</span><span class="sxs-lookup"><span data-stu-id="76b9c-109">Nov 25, 2019</span></span>| <span data-ttu-id="76b9c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="76b9c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="76b9c-111">2020 年 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="76b9c-111">Jan 31, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="76b9c-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="76b9c-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="76b9c-113">この機能は、Dynamics 365 Commerce を使用したすぐに使用できる詐欺防止オプションを小売業者に提供します。</span><span class="sxs-lookup"><span data-stu-id="76b9c-113">This feature brings an out-of-the-box fraud protection option to retailers using Dynamics 365 Commerce.</span></span> <span data-ttu-id="76b9c-114">そのまま使用できる Commerce 製品を使用する場合でも、SDK を通じてサード パーティのストアフロントと統合する場合でも、認証のために送信される前にクレジット カード トランザクションの不正についてチェックするオプションが用意されています。</span><span class="sxs-lookup"><span data-stu-id="76b9c-114">Whether using out-of-the-box Commerce offerings or integrating with a third-party storefront through the SDK, there will be an option to check credit card transactions for fraud prior to sending for authorization.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="76b9c-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="76b9c-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="76b9c-116">この機能により、トランザクションが認証のために送信される前に、Fraud Protection によってリスクが評価されるようにすることで、Dynamics 365 Fraud Protection との基本的な統合をもたらします。</span><span class="sxs-lookup"><span data-stu-id="76b9c-116">This feature will bring basic integration with Dynamics 365 Fraud Protection by allowing transactions to have risk assessed with Fraud Protection prior to being sent for authorization.</span></span> <span data-ttu-id="76b9c-117">アダプティブ AI 技術を使用することで、継続的に更新される詐欺モデルに対してトランザクションがチェックされ、eコマース トランザクションの不当な拒否と試行回数を減らします。</span><span class="sxs-lookup"><span data-stu-id="76b9c-117">Using adaptive AI technology, transactions can be checked against continuously updated fraud models to decrease wrongful rejections and challenge rates for e-commerce transactions.</span></span> <span data-ttu-id="76b9c-118">将来の毎月の更新プログラムにより、Commerce と Fraud Protection の統合がさらに強化されます。</span><span class="sxs-lookup"><span data-stu-id="76b9c-118">Future monthly updates will bring further integration between Commerce and Fraud Protection.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="76b9c-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="76b9c-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="76b9c-120">[Dynamics 365 Fraud Protection の Dynamics 365 Commerce との統合](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/dfp) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="76b9c-120">[Dynamics 365 Fraud Protection integration with Dynamics 365 Commerce](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/dfp) (docs)</span></span>
<!--docs end-->

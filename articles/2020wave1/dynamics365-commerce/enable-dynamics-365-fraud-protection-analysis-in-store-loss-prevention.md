---
title: 店内での損失防止のために Dynamics 365 Fraud Protection 分析を有効にする
description: この機能により、店内での返品と割引のデータを Dynamics 365 Fraud Protection で分析するために Azure Data Lake Storage に送ることができます。 Fraud Protection によって提供される損失防止機能は、人工知能 (AI) と業界レベルでパターンを識別するコンソーシアムベースのアプローチを通じて、このアクティビティの異常を検出できます。
author: relnotes
ms.reviewer: josaw
ms.date: 06/24/2020
ms.assetid: 82fe24d7-668e-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 0db2c545e4fa1052b26012e41f6f1a71dcc413b2
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522547"
---
# <a name="enable-dynamics-365-fraud-protection-analysis-for-in-store-loss-prevention"></a><span data-ttu-id="a5c9e-104">店内での損失防止のために Dynamics 365 Fraud Protection 分析を有効にする</span><span class="sxs-lookup"><span data-stu-id="a5c9e-104">Enable Dynamics 365 Fraud Protection analysis for in-store loss prevention</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="a5c9e-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="a5c9e-105">Enabled for</span></span>    |  <span data-ttu-id="a5c9e-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a5c9e-106">Public preview</span></span> | <span data-ttu-id="a5c9e-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="a5c9e-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a5c9e-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a5c9e-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a5c9e-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a5c9e-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a5c9e-110">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="a5c9e-110">May 18, 2020</span></span>| <span data-ttu-id="a5c9e-111">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="a5c9e-111">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a5c9e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a5c9e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a5c9e-113">返品と割引ポリシーの乱用につながる詐欺は、小売業者のシュリンケージの最大の原因です。</span><span class="sxs-lookup"><span data-stu-id="a5c9e-113">Fraud resulting in return and discount policy abuse is the number one cause of shrinkage for retailers.</span></span> <span data-ttu-id="a5c9e-114">既存の物理的な抑止は簡単に回避できるため、人工知能 (AI) で損失を特定することは、最も高度な形の悪用を捕捉するために重要です。</span><span class="sxs-lookup"><span data-stu-id="a5c9e-114">Existing physical deterrents are easy to work around, so identifying loss through artificial intelligence (AI) is critical to catching the most sophisticated forms of abuse.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a5c9e-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a5c9e-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a5c9e-116">この機能により、環境内に Azure Data Lake Storage Gen2 をプロビジョニングした Commerce のお客様は、店内の返品および割引トランザクション データを Fraud Protection で簡単に要約できる形式で Data Lake Storage Gen2 に送信できます。</span><span class="sxs-lookup"><span data-stu-id="a5c9e-116">This feature allows Commerce customers who have provisioned Azure Data Lake Storage Gen2 in their environment to send in-store return and discount transaction data to Data Lake Storage Gen2 in a format that can easily be digested by Fraud Protection.</span></span> <span data-ttu-id="a5c9e-117">損失防止を分析するには、お客様が自分の環境で Data Lake Storage Gen2 とこの機能を有効にし、Fraud Protection にサインアップする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a5c9e-117">Customers must enable Data Lake Storage Gen2 for their environment, enable this feature, and sign up for Fraud Protection in order for loss prevention to be analyzed.</span></span> <span data-ttu-id="a5c9e-118">セットアップとオプトインの要件が満たされている場合、お客様は Fraud Protection によって提供されるダッシュボード内で損失防止分析に直接アクセスできます。</span><span class="sxs-lookup"><span data-stu-id="a5c9e-118">When the setup and opt-in requirements have been met, the customer will have access to loss prevention analysis directly within dashboards provided by Fraud Protection.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="a5c9e-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="a5c9e-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="a5c9e-120">[Dynamics 365 Fraud Protection の Dynamics 365 Commerce との統合](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/dfp) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a5c9e-120">[Dynamics 365 Fraud Protection integration with Dynamics 365 Commerce](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/dfp) (docs)</span></span>
<!--docs end-->

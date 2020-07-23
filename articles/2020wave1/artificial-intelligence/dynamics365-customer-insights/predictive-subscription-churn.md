---
title: サブスクリプション解約予測
description: サブスクリプション解約予測
author: relnotes
ms.reviewer: mhart
ms.date: 05/29/2020
ms.assetid: 53c8e911-6395-ea11-a811-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: midevane
dynamics365pdf: true
ms.openlocfilehash: 5874be53e4a60b47f9a6a5d3bc41c210e17bc0da
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440569"
---
# <a name="subscription-churn-prediction"></a><span data-ttu-id="7839b-103">サブスクリプション解約予測</span><span class="sxs-lookup"><span data-stu-id="7839b-103">Subscription churn prediction</span></span>
[!include[artificial-intelligence/dynamics365-customer-insights banner](../includes/artificial-intelligence/dynamics365-customer-insights.md)]

| <span data-ttu-id="7839b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7839b-104">Enabled for</span></span>    |  <span data-ttu-id="7839b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7839b-105">Public preview</span></span> | <span data-ttu-id="7839b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7839b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7839b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="7839b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7839b-108">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="7839b-108">Jun 2020</span></span>| -|






## <a name="feature-details"></a><span data-ttu-id="7839b-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7839b-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7839b-110">シンプルなガイド付きエクスペリエンスに従って、クラウド サービス、顧客メンバーシップ、その他のセクターなどのサブスクリプション分野における解約予測を作成します。</span><span class="sxs-lookup"><span data-stu-id="7839b-110">Follow a simple, guided experience to create churn prediction in subscription areas like cloud services, customer membership, and other sectors.</span></span> 

<span data-ttu-id="7839b-111">サブスクリプション解約予測機能を使用すると、データ サイエンティストを採用せずに、顧客がサブスクリプション ベースの製品またはサービスの利用を停止する可能性を予測できます。</span><span class="sxs-lookup"><span data-stu-id="7839b-111">The subscription churn prediction feature enables you to predict the likelihood of a customer stopping the use of subscription-based products or services without engaging a data scientist.</span></span> <span data-ttu-id="7839b-112">予測スコアを使用すると、顧客に関する他の情報を組み合わせて、解約のリスクが高いセグメントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="7839b-112">Using the prediction score, you can combine other information about your customers to create segments of high churn risk.</span></span>  <span data-ttu-id="7839b-113">このセグメントの利用により、Customer Insights との統合を使用して、マーケティング、顧客サポート、およびその他のシナリオで顧客を直接ターゲット設定できます。また、特定の顧客の解約リスクを減らし、収益を改善して、コストを削減できます。</span><span class="sxs-lookup"><span data-stu-id="7839b-113">With the help of this segment, you can use integrations with Customer Insights to directly target customers in marketing, customer support, and other scenarios to reduce the risk of churn for specific customers to improve revenue and reduce cost.</span></span>

<span data-ttu-id="7839b-114">![サブスクリプション解約モデルのステップ 1 のビジュアル](media/june2020_subchurn_1.png "サブスクリプション解約モデルのステップ 1 のビジュアル")</span><span class="sxs-lookup"><span data-stu-id="7839b-114">![Visual of step 1 in subscription churn model](media/june2020_subchurn_1.png "Visual of step 1 in subscription churn model")</span></span>

<span data-ttu-id="7839b-115">エクスペリエンス内では、解約の定義をビジネスに固有の時間ベースのウィンドウとして構成できます。</span><span class="sxs-lookup"><span data-stu-id="7839b-115">Within the experience, you can configure the definition of churn as a time-based window specific to your business.</span></span>  <span data-ttu-id="7839b-116">たとえば、月単位のサブスクリプション プロセスがあるビデオ ストリーミング ビジネスでは、サブスクリプションの期限が切れてから 15 日後に顧客が解約したと見なすことができます。</span><span class="sxs-lookup"><span data-stu-id="7839b-116">For example, a video streaming business that has a monthly subscription process might want to consider a customer to have churned after 15 days after the expiration of their subscription.</span></span> 

<span data-ttu-id="7839b-117">予測の際には、必要なデータをガイドし、顧客の解約を予測するために必要なフィールドにビジネスに関するデータをマップできるようにします。</span><span class="sxs-lookup"><span data-stu-id="7839b-117">As you continue through the prediction, we'll guide you through what data is needed, and enable you to map data about your business to fields required to predict churn for your customers.</span></span> 

<span data-ttu-id="7839b-118">![ステップ 2 のビジュアル – 必要なデータを追加する – 解約モデル](media/june2020_subchurn_2.png "ステップ 2 のビジュアル – 必要なデータを追加する – 解約モデル")</span><span class="sxs-lookup"><span data-stu-id="7839b-118">![Visual of step 2 – add required data – in churn model](media/june2020_subchurn_2.png "Visual of step 2 – add required data – in churn model")</span></span>

<span data-ttu-id="7839b-119">ビジネス情報の変化に応じて、システムの新しい情報での再トレーニングを実施するスケジュールを設定し、変化するビジネス状況に適応することもできます。</span><span class="sxs-lookup"><span data-stu-id="7839b-119">As business information changes, you can also set a schedule to retrain on new information in your system to adapt to changing business circumstances.</span></span>

<span data-ttu-id="7839b-120">![サブスクリプション解約モデルのトレーニング スケジュールのビジュアル](media/june2020_subchurn_4.png "サブスクリプション解約モデルのトレーニング スケジュールのビジュアル")</span><span class="sxs-lookup"><span data-stu-id="7839b-120">![Visual of subscription churn model training schedule](media/june2020_subchurn_4.png "Visual of subscription churn model training schedule")</span></span>


<!--feature detail end -->










---
title: クライアンテリング - 販売担当者が信頼できるアドバイザーになり、顧客と長期的な関係を築けるようにする
description: クライアンテリング - 販売担当者が信頼できるアドバイザーになり、顧客と長期的な関係を築けるようにする
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 4219cbd5-546c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: shajain
dynamics365pdf: true
ms.openlocfilehash: fe5622b159add1ed98e6c9625d68c87aff6bdc24
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890192"
---
# <a name="clienteling--empower-sales-associates-to-become-trusted-advisors-and-establish-long-term-relationships-with-customers"></a><span data-ttu-id="10275-103">クライアンテリング - 販売担当者が信頼できるアドバイザーになり、顧客と長期的な関係を築けるようにする</span><span class="sxs-lookup"><span data-stu-id="10275-103">Clienteling – Empower sales associates to become trusted advisors and establish long-term relationships with customers</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="10275-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="10275-104">Enabled for</span></span>    |  <span data-ttu-id="10275-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="10275-105">Public preview</span></span> | <span data-ttu-id="10275-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="10275-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="10275-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="10275-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="10275-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="10275-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="10275-109">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="10275-109">Oct 21, 2019</span></span>| <span data-ttu-id="10275-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="10275-110">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="10275-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="10275-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="10275-112">多くの小売業者、特にハイエンドの専門小売業者は、販売担当者が主要な顧客と長期的な関係を築くことを望んでいます。</span><span class="sxs-lookup"><span data-stu-id="10275-112">Many retailers, especially high-end specialty retailers, want their sales associates to form long-term relationships with their key customers.</span></span> <span data-ttu-id="10275-113">販売担当者は、顧客の好き嫌い、購入履歴、商品の好み、記念日や誕生日などの重要な日付を知っている必要があります。</span><span class="sxs-lookup"><span data-stu-id="10275-113">The sales associates are expected to know their customers' likes and dislikes, purchase histories, product preferences, and important dates, such as anniversaries and birthdays.</span></span> <span data-ttu-id="10275-114">担当者には、そのような情報を収集したり簡単に見つけたりできる場所が必要です。</span><span class="sxs-lookup"><span data-stu-id="10275-114">The associates need a place to capture and easily find such information.</span></span> 

<span data-ttu-id="10275-115">さらに、小売業者は、複数のアプリケーション (購入のための eコマース、センチメント トラッキングのためのソーシャルメディア、プリセールスのための Dynamics 365 Sales、ポストセールスのための Dynamics 365 Customer Service など) を使用して顧客と関わります。</span><span class="sxs-lookup"><span data-stu-id="10275-115">Moreover, a retailer engages with the customer using multiple applications (for example, e-commerce for purchases, social media for sentiment tracking, Dynamics 365 Sales for presales, and Dynamics 365 Customer Service for post-sales).</span></span> <span data-ttu-id="10275-116">このすべてのデータは、販売担当者が顧客をよりよく理解することを可能にし、したがって顧客のニーズをよりよく満たすことができる、貴重な顧客分析情報を得るのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="10275-116">All this data can help with valuable customer insights that can empower the sales associate to better understand their customers and thus better meet their needs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="10275-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="10275-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="10275-118">担当者はクライアント ブックを使用して主要顧客を追跡し、誕生日、記念日、好き嫌いなどの追加情報を取得できます。</span><span class="sxs-lookup"><span data-stu-id="10275-118">Associates can use the client book to keep track of their key customers and capture additional information, such as birthdays, anniversaries, likes, and dislikes.</span></span> <span data-ttu-id="10275-119">小売業者は、取り込まれた情報を、顧客を管理する販売担当者だけが利用できるようにするか、またはすべての担当者が利用できるようにするかを構成できます。</span><span class="sxs-lookup"><span data-stu-id="10275-119">The retailer can configure whether the captured information is private to the sales associate who manages the customer or is available to all associates.</span></span> <span data-ttu-id="10275-120">さらに、小売業者が Dynamics 365 Customer Insights を使用している場合、小売業者は販売時点管理 (POS) に表示する分析情報を選択できます。</span><span class="sxs-lookup"><span data-stu-id="10275-120">Additionally, if the retailer uses Dynamics 365 Customer Insights, the retailer will be able to choose the insights that should be displayed in the point of sale (POS).</span></span> <span data-ttu-id="10275-121">販売担当者は、顧客プロファイルのメモやアクティビティを作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="10275-121">Sales associates will also be able to take notes and activities for the customer profile.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="10275-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="10275-122">See also</span></span>

<span data-ttu-id="10275-123">[クライアンテリングの概要](https://docs.microsoft.com/dynamics365/retail/clienteling-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="10275-123">[Clienteling overview](https://docs.microsoft.com/dynamics365/retail/clienteling-overview) (docs)</span></span>

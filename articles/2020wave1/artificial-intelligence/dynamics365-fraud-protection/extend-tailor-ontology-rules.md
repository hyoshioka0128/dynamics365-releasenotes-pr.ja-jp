---
title: オントロジーとルールの拡張と調整
description: カスタム ビジネス要件を満たすために、業者が Dynamics 365 Fraud Protection に用意されているコア機能を超えた機能を必要とするケースは複数あります。 業者は、拡張と調整機能を活用して、Fraud Protection を自社のシナリオに特化させることができます。
author: relnotes
ms.reviewer: v-davido
ms.date: 01/07/2020
ms.assetid: 5468c0e0-0ed0-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: abuckner
dynamics365pdf: true
ms.openlocfilehash: 80c9f6e33edee645245db2a2d01e49f1447f9386
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986686"
---
# <a name="extend-and-tailor-ontology-and-rules"></a><span data-ttu-id="17898-104">オントロジーとルールの拡張と調整</span><span class="sxs-lookup"><span data-stu-id="17898-104">Extend and tailor ontology and rules</span></span>
[!include[artificial-intelligence/dynamics365-fraud-protection banner](../includes/artificial-intelligence/dynamics365-fraud-protection.md)]

| <span data-ttu-id="17898-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="17898-105">Enabled for</span></span>    |  <span data-ttu-id="17898-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="17898-106">Public preview</span></span> | <span data-ttu-id="17898-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="17898-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="17898-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="17898-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="17898-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="17898-109">May 2020</span></span>| <span data-ttu-id="17898-110">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="17898-110">May 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="17898-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="17898-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="17898-112">業者が Dynamics 365 Fraud Protection に用意されているコア機能を超えた機能を必要とするケースは複数あります。</span><span class="sxs-lookup"><span data-stu-id="17898-112">There are several cases where a merchant might need capabilities beyond the core features that Dynamics 365 Fraud Protection provides.</span></span> 

<span data-ttu-id="17898-113">支払い詐欺とアカウント乗っ取りのマーキーのシナリオでは、加盟店が製品の詐欺防止機能を向上するために Fraud Protection の基本オントロジーを超える特殊なデータの使用を希望する場合があります。</span><span class="sxs-lookup"><span data-stu-id="17898-113">In the marquee scenarios of payment fraud and account takeover, merchants might want to use specialized data beyond the base ontology of Fraud Protection to help improve the fraud protection capability of the product.</span></span> <span data-ttu-id="17898-114">たとえば、航空券の購入では、座席クラスが考慮すべき重要な属性となる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="17898-114">For example, for airline ticket purchases, the seat class might be an important attribute to consider.</span></span> <span data-ttu-id="17898-115">さらに、顧客が返金、ロイヤルティ プログラム、保証プログラムなどのニッチな詐欺防止シナリオとそれに関連する独自のデータ セットを持っていることもあります。</span><span class="sxs-lookup"><span data-stu-id="17898-115">Furthermore, customers might have niche fraud protection scenarios, such as refunds, loyalty programs, and warranty programs, each of which has its own set of relevant data.</span></span> <span data-ttu-id="17898-116">業者は必要に応じてオントロジーを拡張して、特殊なデータを製品に取り込めるようになります。</span><span class="sxs-lookup"><span data-stu-id="17898-116">Merchants will be able to bring specialized data into the product by extending the ontology as needed.</span></span> 

<span data-ttu-id="17898-117">カスタム知識を使用して、特殊なデータを利用したモデル運用ポイントの構成を作成および更新できます。</span><span class="sxs-lookup"><span data-stu-id="17898-117">Custom knowledge can be used to create and update the configuration of model operating points by using specialized data.</span></span> <span data-ttu-id="17898-118">これらのモデル運用ポイントは、利用可能なあらゆる領域の知識を使用して、各種のイベントに対して決定を下すことができます。</span><span class="sxs-lookup"><span data-stu-id="17898-118">These model operating points can consume the full spectrum of available knowledge to produce decisions for each type of event.</span></span>


<!--feature detail end -->










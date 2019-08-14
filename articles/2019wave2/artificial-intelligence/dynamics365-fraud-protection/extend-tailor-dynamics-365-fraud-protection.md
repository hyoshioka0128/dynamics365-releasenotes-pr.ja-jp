---
title: Dynamics 365 Fraud Protection の拡張と調整
description: 詐欺防止に関連する属性のセットを Dynamics 365 Fraud Protection 加盟店が拡張できるようにすることで、顧客の収益をさらに増加させ、詐欺損失を削減します。 この拡張により、Dynamics 365 Fraud Protection を特定のビジネスや加盟店向けに特化させることができます。
author: relnotes
ms.reviewer: v-jegrif
ms.date: 07/24/2019
ms.assetid: 802f9f0d-c96d-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: v-jowigh
dynamics365pdf: true
ms.openlocfilehash: 3150d12d12463af150eea835bf563a00cca4f111
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795661"
---
# <a name="extend-and-tailor-dynamics-365-fraud-protection"></a><span data-ttu-id="8822d-104">Dynamics 365 Fraud Protection の拡張と調整</span><span class="sxs-lookup"><span data-stu-id="8822d-104">Extend and tailor Dynamics 365 Fraud Protection</span></span>
[!include[artificial-intelligence/dynamics365-fraud-protection banner](../includes/artificial-intelligence/dynamics365-fraud-protection.md)]

| <span data-ttu-id="8822d-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="8822d-105">Enabled for</span></span>    |  <span data-ttu-id="8822d-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8822d-106">Public preview</span></span> | <span data-ttu-id="8822d-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8822d-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="8822d-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="8822d-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8822d-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8822d-109">October 2019</span></span>| <span data-ttu-id="8822d-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="8822d-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8822d-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8822d-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8822d-112">加盟店が Dynamics 365 Fraud Protection で提供されているコア機能を超えた機能を必要とするケースは複数あります。</span><span class="sxs-lookup"><span data-stu-id="8822d-112">There are several cases where a merchant might need capabilities beyond the core features provided by Dynamics 365 Fraud Protection.</span></span> 

### <a name="extend-the-base-ontology-with-custom-knowledge"></a><span data-ttu-id="8822d-113">カスタム知識を使用した基本オントロジーの拡張</span><span class="sxs-lookup"><span data-stu-id="8822d-113">Extend the base ontology with custom knowledge</span></span>

<span data-ttu-id="8822d-114">支払い詐欺とアカウント乗っ取りのマーキーのシナリオでは、加盟店が製品の詐欺防止機能を向上するために Dynamics 365 Fraud Protection の基本オントロジーを超える特殊なデータの使用を希望する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8822d-114">In the marquee scenarios of payment fraud and account takeover, merchants might want to use specialized data beyond the base ontology of Dynamics 365 Fraud Protection to improve the fraud protection capability of the product.</span></span> <span data-ttu-id="8822d-115">たとえば、航空券の購入では、座席クラスが考慮すべき重要な属性となる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8822d-115">For example, for airline ticket purchases, the seat class might be an important attribute to consider.</span></span> <span data-ttu-id="8822d-116">さらに、顧客が返金、ロイヤルティ プログラム、保証プログラムなどのニッチな詐欺防止シナリオとそれに関連する独自のデータ セットを持っていることもあります。</span><span class="sxs-lookup"><span data-stu-id="8822d-116">Furthermore, customers might have niche fraud protection scenarios such as refunds, loyalty programs, and warranty programs, each with their own set of relevant data.</span></span> <span data-ttu-id="8822d-117">加盟店は必要に応じてオントロジーを拡張して、特殊なデータを製品に取り込めるようになります。</span><span class="sxs-lookup"><span data-stu-id="8822d-117">We will enable merchants to bring specialized data into the product by extending the ontology as needed.</span></span> 

### <a name="define-custom-rules"></a><span data-ttu-id="8822d-118">カスタム ルールの定義</span><span class="sxs-lookup"><span data-stu-id="8822d-118">Define custom rules</span></span>

<span data-ttu-id="8822d-119">カスタム知識を使用して、特殊なデータを利用したモデル運用ポイントを作成および更新することができます。</span><span class="sxs-lookup"><span data-stu-id="8822d-119">Custom knowledge can be used to create and update the model operating point configuration using specialized data.</span></span> <span data-ttu-id="8822d-120">これらのモデル運用ポイントは、利用可能なあらゆる領域の知識を使用して、各種のイベントに対して決定を下すことができます。</span><span class="sxs-lookup"><span data-stu-id="8822d-120">These model operating points can consume the full spectrum of available knowledge to produce decisions for each type of event.</span></span>
<!--feature detail end -->












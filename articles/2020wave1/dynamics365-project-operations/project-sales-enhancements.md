---
title: プロジェクト営業の機能拡張
description: このリリースでの投資分野は、プロジェクトベースのサービス組織における追加の契約モデルをサポートして、プロジェクトの販売から実行および納品フェーズへの構造化された遷移を提供できるようにします。 プロジェクト マネージャーには、完全な可視性を得て、顧客と交渉した契約モデルのコンテキスト内でプロジェクトの納品をより適切に制御できるというメリットがあります。
author: relnotes
ms.reviewer: kfend
ms.date: 02/04/2020
ms.assetid: d501a9d0-a530-ea11-a810-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: rumant
dynamics365pdf: true
ms.openlocfilehash: 600efa415d3e0832eb9c09bbb3dbbf48909ac375
ms.sourcegitcommit: 69c00a1d6cfa73067950bd9d9c08606c8807ed8c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/19/2020
ms.locfileid: "3072087"
---
# <a name="project-sales-enhancements"></a><span data-ttu-id="80125-104">プロジェクト営業の機能拡張</span><span class="sxs-lookup"><span data-stu-id="80125-104">Project Sales enhancements</span></span>
[!include[dynamics365-project-operations banner](../includes/dynamics365-project-operations.md)]

| <span data-ttu-id="80125-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="80125-105">Enabled for</span></span>    |  <span data-ttu-id="80125-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="80125-106">Public preview</span></span> | <span data-ttu-id="80125-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="80125-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="80125-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="80125-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="80125-109">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="80125-109">Jun 2020</span></span>| <span data-ttu-id="80125-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="80125-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="80125-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="80125-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="80125-112">Web 用の Microsoft Project と Dynamics 365 Project Service Automation の機能を Dynamics 365 Finance のプロジェクト財務機能と組み合わせて、**Dynamics 365 Project Operations** と呼ばれる単一の製品としました。</span><span class="sxs-lookup"><span data-stu-id="80125-112">We have combined the capabilities of Microsoft Project for Web and Dynamics 365 Project Service Automation with the Project Financials capabilities in Dynamics 365 Finance as a single product offering called **Dynamics 365 Project Operations**.</span></span> <span data-ttu-id="80125-113">これにより、プロジェクトベースの組織に包括的な機能セットが提供されます。</span><span class="sxs-lookup"><span data-stu-id="80125-113">This will provide a comprehensive set of capabilities for project-based organizations.</span></span> 

<span data-ttu-id="80125-114">このリリース ウェーブでは、プロジェクト営業と財務の既存の機能への次の機能の追加を目標としています。</span><span class="sxs-lookup"><span data-stu-id="80125-114">The following additions to the existing functionalities for Project Sales and Financials are targeted for this release wave:</span></span>

- <span data-ttu-id="80125-115">**プロジェクト契約に対して分割請求を設定する機能**: この機能を使用すると、Projects Operations のプロジェクト見積もりおよび契約機能を使用しているお客様は、各契約に対して複数の顧客を設定し、それぞれの顧客に対する請求額を割合で分割できます。</span><span class="sxs-lookup"><span data-stu-id="80125-115">**Ability to set up split-billing for project contracts**: With this feature, customers using the project-quoting and contracting capabilities of Projects Operations will be able to set up multiple customers for each contract with a percentage split of the billings for each of those customers.</span></span> <span data-ttu-id="80125-116">請求に対するこの設定は、顧客の要求に応じてカスタマイズされた実装または付加価値のコストの一部を支払う意思のあるメーカーまたは製品仕入先が関係しているシナリオに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="80125-116">This setup for billing will help in scenarios where there is a manufacturer or product vendor involved who is willing to pay a portion of the cost of a customized implementation or value-add, as required by the customer.</span></span>

- <span data-ttu-id="80125-117">**プロジェクトの契約と見積もりの "上限" を設定し、請求時にそれらを適用する機能**: 時間/実費払い (T&M) プロジェクト契約タイプでは、サービス提供での過剰や非効率を防ぐために、顧客とサービス プロバイダー (仕入先) との間で上限が交渉されることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="80125-117">**Ability to set up "not-to-exceed" limits for project contracts and quotes and enforce them during invoicing**: For Time and material (T&M) project contract types, there is often a cap negotiated between the customer and the service provider (vendor) to prevent overages and inefficiencies in service delivery.</span></span> <span data-ttu-id="80125-118">この機能を使用すると、請求書発行時にシステムによって適用される T&M プロジェクト契約の上限または金額制限を Projects Operations のお客様が設定できます。</span><span class="sxs-lookup"><span data-stu-id="80125-118">With this feature, customers of Projects Operations will be able to set up a cap or monetary limit on T&M project contracts that will be enforced by the system during invoicing.</span></span>

- <span data-ttu-id="80125-119">**WBS (作業分解構造) タスクの請求オプションと請求可否オプションを設定する機能**: プロジェクト組織では、作業のフェーズごとに異なる契約上の合意があるのが一般的です。</span><span class="sxs-lookup"><span data-stu-id="80125-119">**Ability to set up billing and chargeability options for work breakdown structure (WBS) tasks**: In project organizations, it is common to have different contractual agreements for different phases of work.</span></span> <span data-ttu-id="80125-120">たとえば、仕入先は、プロジェクトのプロトタイプ フェーズに対する固定価格請求設定と実際の実装に対する T&M タイプの取り決めについて交渉する場合があります。</span><span class="sxs-lookup"><span data-stu-id="80125-120">For example, a vendor could negotiate a fixed-price billing setup for the prototype phase of a project and a T&M type of arrangement for the actual implementation.</span></span> <span data-ttu-id="80125-121">プロジェクトの特定のタスクは請求可能として分類し、その他のタスクは請求不可または無料にすることもできます。</span><span class="sxs-lookup"><span data-stu-id="80125-121">Certain tasks on the project could also be categorized as chargeable while others could be non-chargeable or complimentary.</span></span> <span data-ttu-id="80125-122">この機能を使用すると、Projects Operations のお客様はプロジェクト タスクをプロジェクト契約品目に関連付けて、それらのタスクではその契約品目に同じ請求方法を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="80125-122">With this feature, it will be possible for Project Operations customers to associate project tasks with project contract lines, thereby subjecting them to the same billing method on that contract line.</span></span> <span data-ttu-id="80125-123">この機能を使用すると、プロジェクト マネージャーは特定のタスクを請求可能、請求不可、または無料としてマークすることもできます。これは、売上額を記録し、それらのプロジェクト タスクで発生したコストの請求書を作成するときに適用されます。</span><span class="sxs-lookup"><span data-stu-id="80125-123">The feature will also allow for a project manager to mark certain tasks as chargeable, non-chargeable, or complimentary, which will then be enforced when recording sales values and creating invoices for the costs incurred on those project tasks.</span></span>

- <span data-ttu-id="80125-124">**プロジェクト契約でのリテーナーのサポート**: 着手金型の契約は、顧客に予測可能なキャッシュ アウトフローを許可する契約です。</span><span class="sxs-lookup"><span data-stu-id="80125-124">**Support for retainers on project contracts**: Retainer-type contracts are those that will allow the customer to have a predictable cash outflow.</span></span> <span data-ttu-id="80125-125">顧客には、その期間に提供されたサービスのコストを引き落とすためにサービス プロバイダーによって使用される標準月次払いがあります。</span><span class="sxs-lookup"><span data-stu-id="80125-125">The customer will have a standard monthly payment that will be used by the services provider to draw down against for the cost of services delivered in that period.</span></span> <span data-ttu-id="80125-126">その期間内にリテーナーを超過したサービスは、その期間の終わりに請求されるか、プロジェクトの終わりまで次の期間の請求にプッシュされます。</span><span class="sxs-lookup"><span data-stu-id="80125-126">Any services in that period in excess of the retainer will be invoiced at the end of that period or pushed to the next period's billings until the end of the project.</span></span> <span data-ttu-id="80125-127">この機能を使用すると、Projects Operations のお客様は、リテーナー スケジュールとリテーナー請求が期間ごとに設定された顧客との契約を作成できます。</span><span class="sxs-lookup"><span data-stu-id="80125-127">With this feature, Project Operations customers will be able to draw up a contract with their customers that will have a set retainer schedule and retainer billings by period.</span></span> <span data-ttu-id="80125-128">これらのリテーナーは、請求書発行時に、提供されるサービスのコストを引き落とすために使用されます。</span><span class="sxs-lookup"><span data-stu-id="80125-128">These retainers will be used during invoicing to draw down against the cost of services delivered.</span></span> <span data-ttu-id="80125-129">この機能は、1 回限りの要求を表す前貸しと前払いをサポートするためにも機能しますが、スケジュールされたリテーナーの支払いとほぼ同じように使用および調整できます。</span><span class="sxs-lookup"><span data-stu-id="80125-129">This feature will also work to support advances and prepayments that represent one-off requests but can be used and reconciled much like a scheduled retainer payment.</span></span>

- <span data-ttu-id="80125-130">**Dynamics 365 Project Operations のプロジェクト会計と財務**: プロジェクトベースの契約に対する顧客との固定価格および時間/実費払いの請求の取り決めは、多くの場合、プロジェクトの仕掛品 (WIP) 残高を追跡するための 1 つ以上の収益認識プロセスと会計の概念によってサポートされます。</span><span class="sxs-lookup"><span data-stu-id="80125-130">**Project accounting and Financials in Dynamics 365 Project Operations**: Fixed-price and Time and material billing arrangements with customers for project-based contracts are often supported by one or more revenue recognition processes and accounting concepts for tracking Project Work in Process (WIP) balances.</span></span> <span data-ttu-id="80125-131">Project Operations のお客様は、充実した会計および収益認識機能を活用して、販売からプロジェクト会計までのプロジェクト管理プロセスを完了することができます。</span><span class="sxs-lookup"><span data-stu-id="80125-131">Project Operations customers will be able to leverage the rich accounting and revenue recognition capabilities to complete their project management processes from Sales to Project Accounting.</span></span>
<!--feature detail end -->










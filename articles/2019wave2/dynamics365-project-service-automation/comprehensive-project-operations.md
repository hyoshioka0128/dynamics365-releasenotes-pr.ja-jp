---
title: 包括的なプロジェクト運用
description: プロジェクトベースの組織に包括的なエンドツーエンドの運用ソリューションを提供する新しいイニシアチブ。
author: relnotes
ms.reviewer: kfend
ms.date: 08/01/2019
ms.assetid: 2862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: rumant
dynamics365pdf: true
ms.openlocfilehash: 770cd1a868452fbc3a7ab9954539fab8e8205f9a
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854605"
---
# <a name="comprehensive-project-operations"></a><span data-ttu-id="4a67b-103">包括的なプロジェクト運用</span><span class="sxs-lookup"><span data-stu-id="4a67b-103">Comprehensive project operations</span></span>
[!include[dynamics365-project-service-automation banner](../includes/dynamics365-project-service-automation.md)]

| <span data-ttu-id="4a67b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4a67b-104">Enabled for</span></span>    |  <span data-ttu-id="4a67b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4a67b-105">Public preview</span></span> | <span data-ttu-id="4a67b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4a67b-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="4a67b-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="4a67b-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="4a67b-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="4a67b-108">February 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="4a67b-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4a67b-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4a67b-110">新しい Project Service と Dynamics Sales Extensions for Project を Dynamics 365 for Finance and Operations の Project Financials 機能で拡張すると、プロジェクトベースの組織に包括的なオファリングが提供されます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-110">Extending the new Project Service and Dynamics Sales Extensions for Project with the Project Financials capabilities in Dynamics 365 for Finance and Operations will provide a comprehensive offering for project-based organizations.</span></span> <span data-ttu-id="4a67b-111">このイニシアチブは、既存の Project Service Automation と Finance and Operations のサービス業機能を組み合わせてプロジェクトのビジネス プロセスを完了することを中心としています。</span><span class="sxs-lookup"><span data-stu-id="4a67b-111">This initiative will center around combining the existing Project Service Automation and Finance and Operations service industries capabilities to complete the business processes for projects.</span></span>

<span data-ttu-id="4a67b-112">このリリース ウェーブでは、Project Service Automation 機能への次の機能の追加を目標としています。</span><span class="sxs-lookup"><span data-stu-id="4a67b-112">The following additions to the Project Service Automation functionality are targeted for this release wave:</span></span>

- <span data-ttu-id="4a67b-113">**プロジェクト契約に対して分割請求を設定する機能**: この機能を使用すると、連携性の強化または現在の Project Service Automation ソリューションのプロジェクト見積もりおよび契約機能を使用しているお客様は、各契約に対して複数の顧客を設定し、それぞれの顧客に対する請求額を割合で分割できます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-113">**Ability to set up split-billing for project contracts**: With this feature, customers using the project-quoting and contracting capabilities of the Better Together or the current Project Service Automation solution will be able to set up multiple customers for each contract with a percentage split of the billings for each of those customers.</span></span> <span data-ttu-id="4a67b-114">請求に対するこの設定は、顧客の要求に応じてカスタマイズされた実装または付加価値のコストの一部を支払う意思のあるメーカーまたは製品ベンダーが関係しているシナリオに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-114">This setup for billing will help in scenarios where there is a manufacturer or product vendor involved who is willing to pay a portion of the cost of customized implementation or value-add, as required by the customer.</span></span>

- <span data-ttu-id="4a67b-115">**プロジェクトの契約と見積もりの上限を設定し、請求時にそれらを適用する機能**: 時間/実費払い (T&M) プロジェクト契約タイプでは、サービス提供での過剰や非効率を防ぐために、顧客とサービス プロバイダー (仕入先) との間で上限が交渉されることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="4a67b-115">**Ability to set up not-to-exceed limits for project contracts and quotes and enforce them during invoicing**: For time and material (T&M) project contract types, there is often a cap negotiated between the customer and the service provider (vendor) in order to prevent overages and inefficiencies in service delivery.</span></span> <span data-ttu-id="4a67b-116">この機能を使用すると、Dynamics 365 for Project Operations のお客様は、請求書発行時にシステムによって適用される T&M プロジェクト契約の上限または金額制限を設定できます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-116">With this feature, customers of Dynamics 365 for Project Operations will be able to set up a cap or a monetary limit on T&M project contracts that will be enforced by the system during invoicing.</span></span>

- <span data-ttu-id="4a67b-117">**WBS (作業分解構造) タスクの請求オプションと請求可否オプションを設定する機能**: プロジェクト組織では、作業のフェーズごとに異なる契約上の合意があるのが一般的です。</span><span class="sxs-lookup"><span data-stu-id="4a67b-117">**Ability to set up billing and chargeability options for work breakdown structure (WBS) tasks**: In project organizations, it is common to have different contractual agreements for different phases of work.</span></span> <span data-ttu-id="4a67b-118">たとえば、仕入先は、プロジェクトのプロトタイプ フェーズに対する固定価格請求設定と実際の実装に対する T&M タイプの取り決めについて交渉する場合があります。</span><span class="sxs-lookup"><span data-stu-id="4a67b-118">For example, a vendor could negotiate a fixed-price billing setup for the prototype phase of a project and a T&M type of arrangement for the actual implementation.</span></span> <span data-ttu-id="4a67b-119">プロジェクトの特定のタスクは請求可能として分類し、その他のタスクは請求不可または無料にすることもできます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-119">Certain tasks on the project could also be categorized as chargeable while others could be non-chargeable or complimentary.</span></span> <span data-ttu-id="4a67b-120">この機能を使用すると、プロジェクト タスクをプロジェクト契約品目に関連付けて、それらのタスクではその契約品目に同じ請求方法を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-120">With this feature, it will be possible to associate project tasks to project contract lines, thereby subjecting them to the same billing method on that contract line.</span></span> <span data-ttu-id="4a67b-121">この機能を使用すると、プロジェクト マネージャーは特定のタスクを請求可能、請求不可、または無料としてマークすることもできます。これは、売上額を記録し、それらのプロジェクト タスクで発生したコストの請求書を作成するときに適用されます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-121">The feature will also allow for a project manager to mark certain tasks as chargeable, non-chargeable, or complimentary, which will then be enforced when recording sales values and creating invoices for the costs incurred on those project tasks.</span></span>

- <span data-ttu-id="4a67b-122">**プロジェクト契約でのリテーナーのサポート**: 着手金型の契約は、顧客に予測可能なキャッシュ アウトフローを許可する契約です。</span><span class="sxs-lookup"><span data-stu-id="4a67b-122">**Support for retainers on project contracts**: Retainer-type of contracts are those that will allow the customer to have a predictable cash outflow.</span></span> <span data-ttu-id="4a67b-123">顧客には、その期間に提供されたサービスのコストを引き落とすためにサービス プロバイダーによって使用される標準月次払いがあります。</span><span class="sxs-lookup"><span data-stu-id="4a67b-123">The customer will have a standard monthly payment that will be used by the services provider to draw down against for the cost of services delivered in that period.</span></span> <span data-ttu-id="4a67b-124">その期間内にリテーナーを超過したサービスは、その期間の終わりに請求されるか、プロジェクトの終わりまで次の期間の請求にプッシュされます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-124">Any services in that period in excess of the retainer will be invoiced at the end of that period or pushed to the next period's billings until the end of the project.</span></span> <span data-ttu-id="4a67b-125">この機能を使用すると、仕入先は、リテーナー スケジュールとリテーナー請求が期間ごとに設定された契約を作成できます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-125">With this feature, a vendor will be able to draw up a contract that will have a set retainer schedule and retainer billings by period.</span></span> <span data-ttu-id="4a67b-126">これらのリテーナーは、請求書発行時に、提供されるサービスのコストを引き落とすために使用されます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-126">These retainers will be used during invoicing to draw down against the cost of services delivered.</span></span>

- <span data-ttu-id="4a67b-127">**原点ベースのプロジェクト運用**: 販売から見積送り状作成までのプロジェクトは、Project Service Automation または Finance and Operations サービス業で発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="4a67b-127">**Point-of-origin-based project operations**: Projects from sales to pro forma invoicing can be originated in Project Service Automation or Finance and Operations service industries.</span></span> <span data-ttu-id="4a67b-128">どちらかのシステムで開始されたプロジェクトは、もう一方のシステムに読み取り専用で表示されます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-128">Projects initiated in either system will be visible in the other in a read-only fashion.</span></span> <span data-ttu-id="4a67b-129">この機能を使用すると、顧客は部門の要件に基づいて選択したシステムでプロジェクトを管理できます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-129">This feature will allow customers to manage their projects in their system of choice based on divisional requirements.</span></span> <span data-ttu-id="4a67b-130">Finance and Operations および Project Service Automation で重複するプロジェクト機能を削除するための Microsoft の取り組みは継続し、機能パリティが確保されれば、原点システムを選択する必要はなくなります。</span><span class="sxs-lookup"><span data-stu-id="4a67b-130">Our investments to remove duplicate project capabilities across Finance and Operations and Project Service Automation will continue and once we have feature-parity, the need to make a system-of-origin choice will be eliminated.</span></span>

- <span data-ttu-id="4a67b-131">**Project Service Automation プロジェクトの収益認識**: Project Service Automation で発生し、Project Service Automation アプリで管理されているプロジェクトの場合、そのデータの Finance and Operations サービス業モジュールへの統合がすぐに可能になります。これにより、Finance and Operations でビジネス プロセスを継続できます。</span><span class="sxs-lookup"><span data-stu-id="4a67b-131">**Revenue recognition for Project Service Automation projects**: For projects originating in Project Service Automation and being managed in the Project Service Automation app, there will be an out-of-the-box integration of that data to the Finance and Operations service industries module, which will then enable the continuation of the business process in Finance and Operations.</span></span> <span data-ttu-id="4a67b-132">プロジェクトは、Project Service Automation で販売から見積送り状作成までを管理でき、Finance and Operations サービス業では顧客向けの請求書の生成と収益認識が可能になります。</span><span class="sxs-lookup"><span data-stu-id="4a67b-132">Projects can be managed from sales to pro forma invoicing in Project Service Automation, and Finance and Operations service industries will enable the generation of a customer-facing invoice and revenue recognition.</span></span>
<!--feature detail end -->












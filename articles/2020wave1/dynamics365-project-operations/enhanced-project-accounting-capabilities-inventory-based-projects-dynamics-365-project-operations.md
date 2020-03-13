---
title: Dynamics 365 Project Operations の在庫ベースのプロジェクトのプロジェクト会計機能の強化
description: Project Operations での包括的な機能の提供という目標に向けて、会計の概念から請求を分離することにより、プロジェクト管理会計機能を強化します。 そのために、プロジェクト タイプとプロジェクト グループの依存関係を削除して、1 つのプロジェクトに対して複数の会計モデルを可能にします。
author: relnotes
ms.reviewer: kfend
ms.date: 02/04/2020
ms.assetid: 0bf85b16-a630-ea11-a810-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: rumant
dynamics365pdf: true
ms.openlocfilehash: 1284c5455172353bfa0f454ae4a9a4e6ef3a26cc
ms.sourcegitcommit: 69c00a1d6cfa73067950bd9d9c08606c8807ed8c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/19/2020
ms.locfileid: "3072089"
---
# <a name="enhanced-project-accounting-capabilities-for-inventory-based-projects-in-dynamics-365-project-operations"></a><span data-ttu-id="2ac9c-104">Dynamics 365 Project Operations の在庫ベースのプロジェクトのプロジェクト会計機能の強化</span><span class="sxs-lookup"><span data-stu-id="2ac9c-104">Enhanced Project Accounting capabilities for inventory-based projects in Dynamics 365 Project Operations</span></span>
[!include[dynamics365-project-operations banner](../includes/dynamics365-project-operations.md)]

| <span data-ttu-id="2ac9c-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="2ac9c-105">Enabled for</span></span>    |  <span data-ttu-id="2ac9c-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2ac9c-106">Public preview</span></span> | <span data-ttu-id="2ac9c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="2ac9c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2ac9c-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2ac9c-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2ac9c-109">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="2ac9c-109">Sep 2020</span></span>| <span data-ttu-id="2ac9c-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="2ac9c-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="2ac9c-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2ac9c-111">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="2ac9c-112">**プロジェクトからプロジェクト タイプの依存関係を削除する**: この機能を有効にすると、在庫ベースのプロジェクトは**固定価格**、**時間/実費払い**、**原価**、**時間**、**内部**、または**投資**のタイプを持たなくなります。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-112">**Remove project type dependency from project**: When this feature is enabled, an inventory-based project will no longer have a type of **Fixed-price**, **Time and material**, **Cost**, **Time**, **Internal**, or **Investment**.</span></span> <span data-ttu-id="2ac9c-113">プロジェクト契約品目によってプロジェクトが**固定価格**と**時間/実費払い**のどちらであるかが決まるため、同じプロジェクトが固定価格コンポーネントと時間/実費払いコンポーネントの両方を持てるようになります。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-113">The project contract line will determine whether a project is **Fixed-price** or **Time and material**, allowing for the same project to have both a fixed-price component and a time and material component.</span></span> <span data-ttu-id="2ac9c-114">契約を結んでいないプロジェクトでは原価が追跡されますが、収益は追跡されません。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-114">Projects that do not have a contract will track costs but will not track revenue.</span></span>

- <span data-ttu-id="2ac9c-115">**プロジェクトからプロジェクト グループの依存関係を削除する**: この機能を使用すると、在庫ベースのプロジェクトの**プロジェクト グループ**の依存関係を削除できます。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-115">**Remove project group dependency from project**: This feature will remove the dependency of **Project group** for inventory-based projects.</span></span> <span data-ttu-id="2ac9c-116">これらのプロジェクトでは、プロジェクト グループがオプションのグループ化メカニズムになります。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-116">Project group will become an optional grouping mechanism for these projects.</span></span> <span data-ttu-id="2ac9c-117">仕掛品 (WIP)/収益の見越計上および固定価格プロジェクトの収益認識に関連する構成を含む、**プロジェクト収益プロファイル**という新しいエンティティが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-117">A new entity, **Project revenue profile**, will be created and will contain the configuration related to work-in-progress (WIP)/revenue accrual and revenue recognition for fixed-price projects.</span></span> <span data-ttu-id="2ac9c-118">プロジェクト収益プロファイルは契約品目に設定されます。</span><span class="sxs-lookup"><span data-stu-id="2ac9c-118">The project revenue profile will be set on the contract line.</span></span>


<!--feature detail end -->










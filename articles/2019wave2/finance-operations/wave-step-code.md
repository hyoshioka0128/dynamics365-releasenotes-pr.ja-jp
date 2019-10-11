---
title: ウェーブ ステップ コード
description: この機能では、AWAX 機能と標準の WHS 機能が統合されます。 ウェーブ ステップ コードを使用すると、ユーザーは、特定のウェーブ メソッド インスタンスを対応するテンプレートにリンクするために使用されるコードを設定できます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/14/2019
ms.assetid: 8862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: henrikan
dynamics365pdf: true
ms.openlocfilehash: f64e5c447c592779aa0b90cd525708a6c4781ab1
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142729"
---
# <a name="wave-step-code"></a><span data-ttu-id="775f5-104">ウェーブ ステップ コード</span><span class="sxs-lookup"><span data-stu-id="775f5-104">Wave step code</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="775f5-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="775f5-105">Enabled for</span></span>    |  <span data-ttu-id="775f5-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="775f5-106">Public preview</span></span> | <span data-ttu-id="775f5-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="775f5-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="775f5-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="775f5-108">Users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="775f5-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="775f5-109">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="775f5-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="775f5-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="775f5-111">この機能では、フリー テキストからコードに変更されたウェーブ ステップ コードをいっそう確実に処理できます。</span><span class="sxs-lookup"><span data-stu-id="775f5-111">This feature allows for a more robust handling of the wave step codes that are modified from free text to code.</span></span> <span data-ttu-id="775f5-112">倉庫全体で設定および統一された固有の値など、その利用がいっそう堅牢になり、エラーが発生しにくくなります。</span><span class="sxs-lookup"><span data-stu-id="775f5-112">The utilization of it will become more robust, including unique values that are set up and unified throughout warehouses and that are less error prone.</span></span> <span data-ttu-id="775f5-113">ユーザーは使用中の値を変更できません。</span><span class="sxs-lookup"><span data-stu-id="775f5-113">Users will not be able to alter a value if it is in use.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="775f5-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="775f5-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="775f5-115">ウェーブ ステップ コードを使用すると、ユーザーは、特定のウェーブ メソッド インスタンスを対応するテンプレートにリンクするために使用されるコードを設定できます。</span><span class="sxs-lookup"><span data-stu-id="775f5-115">Wave step codes will allow users to set up codes that are used to link specific wave method instances with their corresponding template.</span></span> <span data-ttu-id="775f5-116">これには、補充、コンテナー詰め、ラベル印刷、積荷構築、および並べ替えに対するテンプレートが含まれます。</span><span class="sxs-lookup"><span data-stu-id="775f5-116">This includes templates for replenishment, containerization, label printing, load building, and sorting.</span></span> <span data-ttu-id="775f5-117">この機能がないと、ユーザーは、フリー テキストのみを使用してウェーブ プロセス メソッドから特定のテンプレートを参照する必要があります。</span><span class="sxs-lookup"><span data-stu-id="775f5-117">Without this feature, users will have to reference a specific template from the wave process method using free text only.</span></span> <span data-ttu-id="775f5-118">フリー テキストを使用すると、特定のウェーブ テンプレートに追加されたウェーブ ステップ テキストがターゲット テンプレートの正確なウェーブ ステップ テキストと一致することを確認する必要があるため、エラーが発生しやすくなります。</span><span class="sxs-lookup"><span data-stu-id="775f5-118">Using free text is error prone because it requires a user to ensure that the wave step text added for a specific wave template matches the exact wave step text in the target template.</span></span> <span data-ttu-id="775f5-119">ウェーブ ステップ コードは、別のフォームで特定のウェーブ ステップ タイプに対して設定されます。</span><span class="sxs-lookup"><span data-stu-id="775f5-119">Wave step codes are set up for a specific wave step type in a separate form.</span></span> <span data-ttu-id="775f5-120">ウェーブ ステップ コードを必要とするウェーブ テンプレートの各ウェーブ ステップ メソッドでは、ドロップダウン リストからウェーブ ステップ コードを選択する必要があります。</span><span class="sxs-lookup"><span data-stu-id="775f5-120">Each wave step method in a wave template that requires a wave step code will require the wave step code to be selected from a drop-down list.</span></span> <span data-ttu-id="775f5-121">ウェーブ テンプレートのウェーブ ステップ メソッドから、そのメソッドのターゲット テンプレートへのリンクは、フリー テキストではなく、セットアップ コードに依存するようになります。</span><span class="sxs-lookup"><span data-stu-id="775f5-121">Linking a wave step method in a wave template to a target template for the method will no longer rely on free text, but on setup codes.</span></span> <span data-ttu-id="775f5-122">これにより、ヒューマン エラーのリスクと影響が軽減されます。</span><span class="sxs-lookup"><span data-stu-id="775f5-122">This reduces the risk and impact of human errors.</span></span> 
 
<span data-ttu-id="775f5-123">ウェーブ ステップ コードを利用し、ウェーブ ステップ フリー テキストの使用をやめるのはオプションです。</span><span class="sxs-lookup"><span data-stu-id="775f5-123">It is optional to uptake wave step codes and move away from wave step free text.</span></span> <span data-ttu-id="775f5-124">取り込みは法人ごとに行われます。</span><span class="sxs-lookup"><span data-stu-id="775f5-124">The uptake is done per legal entity.</span></span> <span data-ttu-id="775f5-125">法人ごとの取り込みの一環として、特定の法人内の既存のすべてのウェーブ ステップ コードが新しい構造にアップグレードされます。</span><span class="sxs-lookup"><span data-stu-id="775f5-125">As part of the uptake per legal entity, all existing wave step codes in the specific legal entity are upgraded into the new structure.</span></span>
<!--feature detail end -->









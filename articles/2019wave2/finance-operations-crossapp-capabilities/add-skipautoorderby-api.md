---
title: skipAutoOrderBy API の追加
description: ORDER BY 句を含めないように明示的に指定して AX クエリ オブジェクトを使用している場合は、カーネルによってプライマリ キーが ORDER BY 句に追加されます。 この API では ORDER BY 句がスキップされ、API はクエリに追加されません。
author: relnotes
ms.reviewer: sericks
ms.date: 12/02/2019
ms.assetid: a853f0d2-58f0-e911-a812-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hasaid
dynamics365pdf: true
ms.openlocfilehash: 0aa1bc33f043b5d1af2d9caea671c935c1998026
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893931"
---
# <a name="add-skipautoorderby-api"></a><span data-ttu-id="20fb9-104">skipAutoOrderBy API の追加</span><span class="sxs-lookup"><span data-stu-id="20fb9-104">Add skipAutoOrderBy API</span></span>


| <span data-ttu-id="20fb9-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="20fb9-105">Enabled for</span></span>    |  <span data-ttu-id="20fb9-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="20fb9-106">Public preview</span></span> | <span data-ttu-id="20fb9-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="20fb9-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="20fb9-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="20fb9-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="20fb9-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="20fb9-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="20fb9-110">2019 年 11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="20fb9-110">Nov 15, 2019</span></span>| <span data-ttu-id="20fb9-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="20fb9-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="20fb9-112">2019 年 11 月 19 日</span><span class="sxs-lookup"><span data-stu-id="20fb9-112">Nov 19, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="20fb9-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="20fb9-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="20fb9-114">ORDER BY 句を含めないように明示的に指定して AX クエリ オブジェクトを使用している場合は、カーネルによってプライマリ キーが ORDER BY 句に追加されます。</span><span class="sxs-lookup"><span data-stu-id="20fb9-114">When using the AX Query object by explicitly specifying not to include an ORDER BY clause, the kernel adds the Primary key to the ORDER BY clause.</span></span> <span data-ttu-id="20fb9-115">この API では ORDER BY 句がスキップされ、API はクエリに追加されません。</span><span class="sxs-lookup"><span data-stu-id="20fb9-115">This API will skip the ORDER BY clause and it will not be added to the query.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="20fb9-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="20fb9-116">See also</span></span>

<span data-ttu-id="20fb9-117">[Q クラス](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/dev-ref/q-classes) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="20fb9-117">[Q classes](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/dev-ref/q-classes) (docs)</span></span>

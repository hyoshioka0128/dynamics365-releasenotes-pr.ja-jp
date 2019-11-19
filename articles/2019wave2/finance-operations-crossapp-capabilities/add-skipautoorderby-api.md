---
title: skipAutoOrderBy API の追加
description: ORDER BY 句を含めないように明示的に指定して AX クエリ オブジェクトを使用している場合は、カーネルによってプライマリ キーが ORDER BY 句に追加されます。 この API では ORDER BY 句がスキップされ、API はクエリに追加されません。
author: relnotes
ms.reviewer: sericks
ms.date: 10/18/2019
ms.assetid: a853f0d2-58f0-e911-a812-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hasaid
dynamics365pdf: true
ms.openlocfilehash: d018a30ac2dcc76e2b929383a683f8510416582b
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668315"
---
# <a name="add-skipautoorderby-api"></a><span data-ttu-id="df3cd-104">skipAutoOrderBy API の追加</span><span class="sxs-lookup"><span data-stu-id="df3cd-104">Add skipAutoOrderBy API</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="df3cd-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="df3cd-105">Enabled for</span></span>    |  <span data-ttu-id="df3cd-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="df3cd-106">Public preview</span></span> | <span data-ttu-id="df3cd-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="df3cd-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="df3cd-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="df3cd-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="df3cd-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="df3cd-109">Nov 2019</span></span>| <span data-ttu-id="df3cd-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="df3cd-110">Nov 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="df3cd-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="df3cd-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="df3cd-112">ORDER BY 句を含めないように明示的に指定して AX クエリ オブジェクトを使用している場合は、カーネルによってプライマリ キーが ORDER BY 句に追加されます。</span><span class="sxs-lookup"><span data-stu-id="df3cd-112">When using the AX Query object by explicitly specifying not to include an ORDER BY clause, the kernel adds the Primary key to the ORDER BY clause.</span></span> <span data-ttu-id="df3cd-113">この API では ORDER BY 句がスキップされ、API はクエリに追加されません。</span><span class="sxs-lookup"><span data-stu-id="df3cd-113">This API will skip the ORDER BY clause and it will not be added to the query.</span></span>
<!--feature detail end -->










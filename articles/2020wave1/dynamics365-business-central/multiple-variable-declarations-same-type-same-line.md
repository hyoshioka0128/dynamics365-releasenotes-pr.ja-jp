---
title: 同じ行に同じ型の変数を複数宣言する
description: 同じ行に同じ型の変数を複数宣言する
author: relnotes
ms.reviewer: solsen
ms.date: 12/12/2019
ms.assetid: 98be7068-dc1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 25dcaf7b391e49caca02b5266a10cd6e040714ce
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986660"
---
# <a name="multiple-variable-declarations-of-the-same-type-in-the-same-line"></a><span data-ttu-id="4dec8-103">同じ行に同じ型の変数を複数宣言する</span><span class="sxs-lookup"><span data-stu-id="4dec8-103">Multiple variable declarations of the same type in the same line</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="4dec8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4dec8-104">Enabled for</span></span>    |  <span data-ttu-id="4dec8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4dec8-105">Public preview</span></span> | <span data-ttu-id="4dec8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4dec8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4dec8-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="4dec8-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="4dec8-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="4dec8-108">Feb 2020</span></span>| <span data-ttu-id="4dec8-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="4dec8-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="4dec8-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4dec8-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4dec8-111">これまでは各変数をそれぞれの行で宣言する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="4dec8-111">Until now, each variable had to be declared on its own line.</span></span> <span data-ttu-id="4dec8-112">このため大規模なオブジェクトでは、ほとんどが同じ型の場合でも、何ページにもわたる変数の宣言が必要でした。</span><span class="sxs-lookup"><span data-stu-id="4dec8-112">In larger objects, this led to pages of variable declarations, even if most of these were of the same type.</span></span>

<span data-ttu-id="4dec8-113">スクロールを減らし、読みやすさを改善し、関連する型の表示と宣言を簡単にするため、同じ型の複数の変数宣言を 1 行で追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4dec8-113">To reduce scrolling, improve readability, and make it easier to see and declare related types, it is now possible to add multiple variable declarations of the same type in a singular line.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4dec8-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4dec8-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4dec8-115">コンマを使用して変数名を区切り、同じ行で同じ型の変数を複数宣言します。</span><span class="sxs-lookup"><span data-stu-id="4dec8-115">Declare multiple variables of the same type in the same line, using a comma to separate variable names.</span></span> <span data-ttu-id="4dec8-116">たとえば、"foo, bar : Integer;" のようにします。</span><span class="sxs-lookup"><span data-stu-id="4dec8-116">For example, "foo, bar : Integer;"</span></span>
<!--feature detail end -->










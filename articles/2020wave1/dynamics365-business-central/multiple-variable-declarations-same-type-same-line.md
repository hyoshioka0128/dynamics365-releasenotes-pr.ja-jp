---
title: 同じ行に同じ型の変数を複数宣言する
description: 同じ行に同じ型の変数を複数宣言する
author: relnotes
ms.reviewer: solsen
ms.date: 04/16/2020
ms.assetid: 98be7068-dc1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 83d9ca3445a02ad276eb354d58532e02f9cee3a5
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273403"
---
# <a name="multiple-variable-declarations-of-the-same-type-in-the-same-line"></a><span data-ttu-id="0faf2-103">同じ行に同じ型の変数を複数宣言する</span><span class="sxs-lookup"><span data-stu-id="0faf2-103">Multiple variable declarations of the same type in the same line</span></span>


| <span data-ttu-id="0faf2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0faf2-104">Enabled for</span></span>    |  <span data-ttu-id="0faf2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0faf2-105">Public preview</span></span> | <span data-ttu-id="0faf2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0faf2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0faf2-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="0faf2-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="0faf2-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0faf2-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0faf2-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0faf2-109">Feb 1, 2020</span></span>| <span data-ttu-id="0faf2-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0faf2-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0faf2-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0faf2-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0faf2-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0faf2-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0faf2-113">これまでは各変数をそれぞれの行で宣言する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="0faf2-113">Until now, each variable had to be declared on its own line.</span></span> <span data-ttu-id="0faf2-114">このため大規模なオブジェクトでは、ほとんどが同じ型の場合でも、何ページにもわたる変数の宣言が必要でした。</span><span class="sxs-lookup"><span data-stu-id="0faf2-114">In larger objects, this led to pages of variable declarations, even if most of these were of the same type.</span></span>

<span data-ttu-id="0faf2-115">スクロールを減らし、読みやすさを改善し、関連する型の表示と宣言を簡単にするため、同じ型の複数の変数宣言を 1 行で追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0faf2-115">To reduce scrolling, improve readability, and make it easier to see and declare related types, it is now possible to add multiple variable declarations of the same type in a singular line.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0faf2-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0faf2-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0faf2-117">コンマを使用して変数名を区切り、同じ行で同じ型の変数を複数宣言します。</span><span class="sxs-lookup"><span data-stu-id="0faf2-117">Declare multiple variables of the same type in the same line, using a comma to separate variable names.</span></span> <span data-ttu-id="0faf2-118">たとえば、"foo, bar : Integer;" のようにします。</span><span class="sxs-lookup"><span data-stu-id="0faf2-118">For example, "foo, bar : Integer;"</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="0faf2-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="0faf2-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="0faf2-120">[変数の宣言](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-programming-in-al#variable-declarations) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0faf2-120">[Variable declarations](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-programming-in-al#variable-declarations) (docs)</span></span>
<!--docs end-->

---
title: 同じ行に同じ型の変数を複数宣言する
description: 同じ行に同じ型の変数を複数宣言する
author: relnotes
ms.reviewer: solsen
ms.date: 02/12/2020
ms.assetid: 98be7068-dc1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 7f222d94a189837d1efd62f60e8528c582e5e41a
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079933"
---
# <a name="multiple-variable-declarations-of-the-same-type-in-the-same-line"></a><span data-ttu-id="5760b-103">同じ行に同じ型の変数を複数宣言する</span><span class="sxs-lookup"><span data-stu-id="5760b-103">Multiple variable declarations of the same type in the same line</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="5760b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5760b-104">Enabled for</span></span>    |  <span data-ttu-id="5760b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5760b-105">Public preview</span></span> | <span data-ttu-id="5760b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5760b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5760b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="5760b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="5760b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5760b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5760b-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5760b-109">Feb 1, 2020</span></span>| <span data-ttu-id="5760b-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="5760b-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5760b-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5760b-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5760b-112">これまでは各変数をそれぞれの行で宣言する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="5760b-112">Until now, each variable had to be declared on its own line.</span></span> <span data-ttu-id="5760b-113">このため大規模なオブジェクトでは、ほとんどが同じ型の場合でも、何ページにもわたる変数の宣言が必要でした。</span><span class="sxs-lookup"><span data-stu-id="5760b-113">In larger objects, this led to pages of variable declarations, even if most of these were of the same type.</span></span>

<span data-ttu-id="5760b-114">スクロールを減らし、読みやすさを改善し、関連する型の表示と宣言を簡単にするため、同じ型の複数の変数宣言を 1 行で追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5760b-114">To reduce scrolling, improve readability, and make it easier to see and declare related types, it is now possible to add multiple variable declarations of the same type in a singular line.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5760b-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5760b-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5760b-116">コンマを使用して変数名を区切り、同じ行で同じ型の変数を複数宣言します。</span><span class="sxs-lookup"><span data-stu-id="5760b-116">Declare multiple variables of the same type in the same line, using a comma to separate variable names.</span></span> <span data-ttu-id="5760b-117">たとえば、"foo, bar : Integer;" のようにします。</span><span class="sxs-lookup"><span data-stu-id="5760b-117">For example, "foo, bar : Integer;"</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="5760b-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="5760b-118">See also</span></span>

<span data-ttu-id="5760b-119">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5760b-119">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (docs)</span></span>

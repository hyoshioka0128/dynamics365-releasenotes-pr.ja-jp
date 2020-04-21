---
title: テーマの拡張機能のサポート
description: 現在は、SCSS/モジュール ビュー拡張機能やモジュール定義拡張機能などの共有コンポーネントを使用して複数のテーマを作成するときに、コードをそれぞれのテーマにコピーする必要があります。 基本テーマのサポートの追加により、共通のコードを 1 つの場所に追加して、各テーマが基本テーマからコードを継承するようにできます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/01/2020
ms.assetid: 061fa313-b059-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: samjar
dynamics365pdf: true
ms.openlocfilehash: 97d0bb2990800f042173676f7c21a1f7254029ea
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219710"
---
# <a name="support-for-theme-extensions"></a><span data-ttu-id="d0411-104">テーマの拡張機能のサポート</span><span class="sxs-lookup"><span data-stu-id="d0411-104">Support for theme extensions</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="d0411-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="d0411-105">Enabled for</span></span>    |  <span data-ttu-id="d0411-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d0411-106">Public preview</span></span> | <span data-ttu-id="d0411-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="d0411-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d0411-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="d0411-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="d0411-109">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="d0411-109">Sep 2020</span></span>| <span data-ttu-id="d0411-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="d0411-110">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="d0411-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d0411-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d0411-112">テーマ開発者は、すべてのテーマに単一の基本テーマを持たせることで時間を節約し、サイトのサービスを向上できます。</span><span class="sxs-lookup"><span data-stu-id="d0411-112">Theme developers can save time and make their sites more serviceable by having a single base theme for all themes.</span></span> <span data-ttu-id="d0411-113">わずかな違いしかない新しいテーマの、市場投入までの時間を短縮できます。</span><span class="sxs-lookup"><span data-stu-id="d0411-113">Time to market can be reduced for new themes that have only minor differences.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d0411-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d0411-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d0411-115">基本テーマのサポートにより、テーマの開発が容易になります。</span><span class="sxs-lookup"><span data-stu-id="d0411-115">Theme development will be easier with base theme support.</span></span> <span data-ttu-id="d0411-116">共通のコードを基本テーマに追加して、各テーマが基本テーマからコードを継承するようにできます。</span><span class="sxs-lookup"><span data-stu-id="d0411-116">Common code can now be added to a base theme so that individual themes inherit code from the base theme.</span></span> <span data-ttu-id="d0411-117">基本テーマが継承されたら、個別のテーマの変更を追加することができます。</span><span class="sxs-lookup"><span data-stu-id="d0411-117">When the base theme is inherited, individual theme changes can be added.</span></span> <span data-ttu-id="d0411-118">基本テーマに変更が必要な場合は、1 回行うだけで済みます。</span><span class="sxs-lookup"><span data-stu-id="d0411-118">If a change is needed in the base theme, it only has to be made once.</span></span> <span data-ttu-id="d0411-119">基本テーマによって、新しいテーマの作成に必要な時間が短縮され、コード チャーンを削減できます。</span><span class="sxs-lookup"><span data-stu-id="d0411-119">Base themes reduce the time needed to create new themes and reduce code churn.</span></span> 
<!--feature detail end -->










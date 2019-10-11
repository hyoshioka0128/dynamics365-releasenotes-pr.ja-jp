---
title: アクセス モディファイアー
description: 拡張機能の AL 言語要素にアクセス モディファイアーを追加します。
author: relnotes
ms.reviewer: edupont
ms.date: 08/13/2019
ms.assetid: 5e9bbd72-746d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 1abcbde69f293b96eaccee66eeca8f9b8d316cf0
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140779"
---
# <a name="access-modifiers"></a><span data-ttu-id="7c259-103">アクセス モディファイアー</span><span class="sxs-lookup"><span data-stu-id="7c259-103">Access modifiers</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="7c259-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7c259-104">Enabled for</span></span>    |  <span data-ttu-id="7c259-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7c259-105">Public preview</span></span> | <span data-ttu-id="7c259-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7c259-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7c259-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="7c259-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="7c259-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7c259-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7c259-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7c259-109">Aug 1, 2019</span></span>| <span data-ttu-id="7c259-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="7c259-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="7c259-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7c259-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7c259-112">アクセス モディファイアーを使用することで、独自のコードであるか、独自のコードを基に構築されたサードパーティのコードであるかにかかわらず、どこから呼び出すことができるかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="7c259-112">By using access modifiers, you have control over where it can be called from, be it your own code or third-party code building on top of your code.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7c259-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7c259-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7c259-114">local/private、protected、internal、または public のアクセス モディファイアーを AL 言語要素に追加することで、コードのアクセスとカプセル化を制御できます。</span><span class="sxs-lookup"><span data-stu-id="7c259-114">You can control access and encapsulation of your code by adding local/private, protected, internal, or public access modifiers to AL language elements.</span></span> <span data-ttu-id="7c259-115">これは、C# でアクセス モディファイアーを使用する方法と似ています。</span><span class="sxs-lookup"><span data-stu-id="7c259-115">This is similar to the way C# uses access modifiers.</span></span>
<!--feature detail end -->












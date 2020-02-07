---
title: AL インターフェイス
description: AL でインターフェイスを定義および実装して、コードがインターフェイスに準拠する任意のタイプと対話できるようにします。
author: relnotes
ms.reviewer: solsen
ms.date: 12/12/2019
ms.assetid: 2fc48a30-db1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 41380a1acd01ff676c86cf417ccda015bc5993dc
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986675"
---
# <a name="al-interfaces"></a><span data-ttu-id="970a5-103">AL インターフェイス</span><span class="sxs-lookup"><span data-stu-id="970a5-103">AL interfaces</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="970a5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="970a5-104">Enabled for</span></span>    |  <span data-ttu-id="970a5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="970a5-105">Public preview</span></span> | <span data-ttu-id="970a5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="970a5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="970a5-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="970a5-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="970a5-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="970a5-108">Feb 2020</span></span>| <span data-ttu-id="970a5-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="970a5-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="970a5-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="970a5-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="970a5-111">定義されたインターフェイスに準拠している限り、実際の実装が異なることを許可しながら、オブジェクトに対してどの機能を使用可能にする必要があるかを決定する場合、インターフェイスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="970a5-111">An interface is used when you want to decide which capabilities need to be available for an object, while allowing actual implementations to differ, as long as they comply with the defined interface.</span></span>

<span data-ttu-id="970a5-112">これにより、実装の詳細への依存を減らすコードを記述し、コードの再利用を容易にすることができます。また、オブジェクト メソッドを呼び出すポリモーフィング方法がサポートされ、これはビジネス ロジックを置き換えるためにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="970a5-112">This allows for writing code that reduces the dependency on implementation details, makes it easier to reuse code, and supports a polymorphing way of calling object methods, which again can be used for substituting business logic.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="970a5-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="970a5-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="970a5-114">新しいインターフェイス オブジェクトを使用して、そのメソッドと共にインターフェイス名を宣言し、インターフェイス メソッドを実装するオブジェクトにインターフェイス名と共に implements キーワードを適用します。</span><span class="sxs-lookup"><span data-stu-id="970a5-114">Use the new interface object to declare an interface name along with its methods, and apply the implements keyword along with the interface names on objects that implement the interface methods.</span></span> 

<span data-ttu-id="970a5-115">インターフェイス オブジェクト自体にはコードは含まれず、署名のみが含まれます。また、それ自体をコードから呼び出すことはできず、他のオブジェクトによって実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="970a5-115">The interface object itself does not contain any code, only signatures, and cannot itself be called from code, but must be implemented by other objects.</span></span>
 
<span data-ttu-id="970a5-116">コンパイラでは、実装が割り当てられたインターフェイスに準拠していることが確認されます。</span><span class="sxs-lookup"><span data-stu-id="970a5-116">The compiler checks to ensure implementations adhere to assigned interfaces.</span></span>

<span data-ttu-id="970a5-117">新しい QuickFix CodeAction を使用して、1 つ以上のインターフェイス実装のコンパイラ エラーが欠落している場合に、インターフェイス スタブを挿入できます。</span><span class="sxs-lookup"><span data-stu-id="970a5-117">A new QuickFix CodeAction can be used to insert interface stubs, if the compiler errors on one or more interface implementations are missing.</span></span>

<span data-ttu-id="970a5-118">変数を特定のインターフェイスとして宣言して、インターフェイスを実装するオブジェクトを渡せるようにし、渡されたオブジェクトに対するインターフェイス実装をポリモーフィックな方法で呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="970a5-118">You can declare variables as a given interface to allow passing objects that implement the interface, and then call interface implementations on the passed object in a polymorphic manner.</span></span>
<!--feature detail end -->










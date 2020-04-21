---
title: AL インターフェイス
description: AL でインターフェイスを定義および実装して、コードがインターフェイスに準拠する任意のタイプと対話できるようにします。
author: relnotes
ms.reviewer: solsen
ms.date: 04/02/2020
ms.assetid: 2fc48a30-db1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 1c2c301da721c4927d8b67232b838b5ecca7c54d
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3233014"
---
# <a name="al-interfaces"></a><span data-ttu-id="8e424-103">AL インターフェイス</span><span class="sxs-lookup"><span data-stu-id="8e424-103">AL interfaces</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="8e424-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8e424-104">Enabled for</span></span>    |  <span data-ttu-id="8e424-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8e424-105">Public preview</span></span> | <span data-ttu-id="8e424-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8e424-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8e424-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="8e424-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="8e424-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8e424-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8e424-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8e424-109">Feb 1, 2020</span></span>| <span data-ttu-id="8e424-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8e424-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8e424-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8e424-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8e424-112">定義されたインターフェイスに準拠している限り、実際の実装が異なることを許可しながら、オブジェクトに対してどの機能を使用可能にする必要があるかを決定する場合、インターフェイスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="8e424-112">An interface is used when you want to decide which capabilities need to be available for an object, while allowing actual implementations to differ, as long as they comply with the defined interface.</span></span>

<span data-ttu-id="8e424-113">これにより、実装の詳細への依存を減らすコードを記述し、コードの再利用を容易にすることができます。また、オブジェクト メソッドを呼び出すポリモーフィング方法がサポートされ、これはビジネス ロジックを置き換えるためにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="8e424-113">This allows for writing code that reduces the dependency on implementation details, makes it easier to reuse code, and supports a polymorphing way of calling object methods, which again can be used for substituting business logic.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8e424-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8e424-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8e424-115">新しいインターフェイス オブジェクトを使用して、そのメソッドと共にインターフェイス名を宣言し、インターフェイス メソッドを実装するオブジェクトにインターフェイス名と共に implements キーワードを適用します。</span><span class="sxs-lookup"><span data-stu-id="8e424-115">Use the new interface object to declare an interface name along with its methods, and apply the implements keyword along with the interface name(s) on objects that implement the interface methods.</span></span> 

<span data-ttu-id="8e424-116">インターフェイス オブジェクト自体にはコードは含まれず、署名のみが含まれます。また、それ自体をコードから呼び出すことはできず、他のオブジェクトによって実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8e424-116">The interface object itself does not contain any code, only signatures, and cannot itself be called from code, but must be implemented by other objects.</span></span>
 
<span data-ttu-id="8e424-117">コンパイラでは、実装が割り当てられたインターフェイスに準拠していることが確認されます。</span><span class="sxs-lookup"><span data-stu-id="8e424-117">The compiler checks to ensure implementations adhere to assigned interfaces.</span></span>

<span data-ttu-id="8e424-118">新しい QuickFix CodeAction を使用して、1 つ以上のインターフェイス実装のコンパイラ エラーが欠落している場合に、インターフェイス スタブを挿入できます。</span><span class="sxs-lookup"><span data-stu-id="8e424-118">A new QuickFix CodeAction can be used to insert interface stubs, if the compiler errors on one or more interface implementations are missing.</span></span>

<span data-ttu-id="8e424-119">変数を特定のインターフェイスとして宣言して、インターフェイスを実装するオブジェクトを渡せるようにし、渡されたオブジェクトに対するインターフェイス実装をポリモーフィックな方法で呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="8e424-119">You can declare variables as a given interface to allow passing objects that implement the interface, and then call interface implementations on the passed object in a polymorphic manner.</span></span>

<span data-ttu-id="8e424-120">![意図を把握し、代替実装を作成するためのインターフェイスを定義する](media/interface.png "意図を把握し、代替実装を作成するためのインターフェイスを定義する")</span><span class="sxs-lookup"><span data-stu-id="8e424-120">![Define interfaces to capture intent and create alternate implementations](media/interface.png "Define interfaces to capture intent and create alternate implementations")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="8e424-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="8e424-121">See also</span></span>


<!--docs start-->
<span data-ttu-id="8e424-122">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8e424-122">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (docs)</span></span>
<!--docs end-->


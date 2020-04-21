---
title: ベース アプリケーションのエイリアス用のアプリケーション バージョン
description: Business Central 2019 年リリース ウェーブ 2 では、ベース アプリケーションとシステム アプリケーションを導入しました。 これらに依存する拡張機能は、app.json ファイルで明示的な依存関係を指定する必要がありました。 現在は、以前のバージョンで使用できたものと同様のアプリケーション バージョン プロパティを再導入しています。
author: relnotes
ms.reviewer: solsen
ms.date: 02/12/2020
ms.assetid: 23c900bc-e41c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 379ba3e2e41c6d74a09e05f9e8d177d7973a9e2a
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3233003"
---
# <a name="application-version-for-aliasing-base-application"></a><span data-ttu-id="7dca2-105">ベース アプリケーションのエイリアス用のアプリケーション バージョン</span><span class="sxs-lookup"><span data-stu-id="7dca2-105">Application version for aliasing base application</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="7dca2-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="7dca2-106">Enabled for</span></span>    |  <span data-ttu-id="7dca2-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7dca2-107">Public preview</span></span> | <span data-ttu-id="7dca2-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="7dca2-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7dca2-109">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="7dca2-109">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="7dca2-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7dca2-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7dca2-111">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7dca2-111">Feb 1, 2020</span></span>| <span data-ttu-id="7dca2-112">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="7dca2-112">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7dca2-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7dca2-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7dca2-114">埋め込みアプリケーションとカスタマイズされたオンプレミス アプリケーションは、ベース アプリケーションの app.json ファイルとアプリケーション拡張機能の ID を変更できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="7dca2-114">Embed applications as well as customized on-premises applications should be able to modify the app.json file of the base application and change the identity of the application extensions.</span></span> <span data-ttu-id="7dca2-115">ただし、そうすることで、Microsoft ベース ID を指す上位ソリューションは、明示的な依存関係を使用している場合、埋め込みアプリケーションまたはオンプレミス コードのカスタマイズに対して解決されません。</span><span class="sxs-lookup"><span data-stu-id="7dca2-115">However, by doing so, solutions on top pointing to the Microsoft base identity will not resolve against the embed application or on-premises code customizations, if these are using explicit dependencies.</span></span> 

<span data-ttu-id="7dca2-116">したがって、Microsoft のベース アプリケーションの上に構築された拡張機能をソリューションに対してコンパイルできるように、埋め込みアプリケーションが Microsoft のベース アプリケーションのエイリアスであることを指定する方法をサポートするには、アプリケーション エイリアスを介した間接的なレベルが必要です。</span><span class="sxs-lookup"><span data-stu-id="7dca2-116">Therefore, to support a way for embed applications to specify that they are aliasing Microsoft's Base Application so that any extension built on top of Microsoft's Base Application can compile against their solutions, there needs to be a level of indirection through the application alias.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7dca2-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7dca2-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7dca2-118">埋込みパートナーとオンプレミス ソリューションでは、Application という名前の親拡張機能を作成できます。この拡張機能は、ベース バージョンに従ってバージョン管理され、適切な一意の発行元を持ちます。</span><span class="sxs-lookup"><span data-stu-id="7dca2-118">Embed partners and on-premises solutions can create a parent extension named Application, versioned according to base version, and with an appropriate, unique publisher.</span></span> <span data-ttu-id="7dca2-119">この親拡張機能は主に間接プロキシとして使用され、実際にアプリケーションを実装する拡張機能への明示的な依存関係を含む必要があります。</span><span class="sxs-lookup"><span data-stu-id="7dca2-119">This parent extension is mainly used as an indirection proxy, and should contain explicit dependencies to the extensions actually implementing the application.</span></span> <span data-ttu-id="7dca2-120">さらに、app.json ファイルの propagateDependencies プロパティを true に設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7dca2-120">In addition, the propagateDependencies property in the app.json file should be set to true.</span></span> <span data-ttu-id="7dca2-121">これにより、プロキシ アプリケーションのバージョンに依存する拡張機能への依存関係が公開されます。</span><span class="sxs-lookup"><span data-stu-id="7dca2-121">This will expose the dependencies to any extension taking dependency on the proxy Application version.</span></span> 

<span data-ttu-id="7dca2-122">パートナーは、拡張機能の app.json ファイルのアプリケーション バージョン プロパティを使用して、予想されるアプリケーション バージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="7dca2-122">Partners will use the Application version property in their extension's app.json file to specify the expected application version.</span></span>

<span data-ttu-id="7dca2-123">Visual Studio Code では、app.json ファイルでアプリケーション バージョンを指定すると、"application" を構成するシンボル パッケージの完全なセットが取り込まれます。</span><span class="sxs-lookup"><span data-stu-id="7dca2-123">In Visual Studio Code, the full set of symbol packages that make up the "application" will be pulled in when specifying an Application version in the app.json file.</span></span>

<span data-ttu-id="7dca2-124">Microsoft のベース アプリケーションへの明示的な依存関係は、アプリケーション バージョンよりも優先されますが、ベース アプリケーションがシステムに存在しない場合は "application" にリダイレクトされます。</span><span class="sxs-lookup"><span data-stu-id="7dca2-124">An explicit dependency to Microsoft's Base Application will take priority over the Application version, but is redirected to "application" if the Base Application is not present on the system.</span></span>

> [!NOTE] 
> <span data-ttu-id="7dca2-125">ApplicationVersion では、コンパイル時の依存関係のみを解決できます。</span><span class="sxs-lookup"><span data-stu-id="7dca2-125">ApplicationVersion only allows resolving dependencies on compile.</span></span> <span data-ttu-id="7dca2-126">拡張機能と提供されたエイリアスとの間に実際に互換性があるかどうかは、埋め込み拡張機能の作成者が確認およびテストするかどうかにかかっています。</span><span class="sxs-lookup"><span data-stu-id="7dca2-126">Whether the extension is in fact compatible with the provided alias is up to the embed extension authors to ensure and test.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="7dca2-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="7dca2-127">See also</span></span>


<!--docs start-->
<span data-ttu-id="7dca2-128">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7dca2-128">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (docs)</span></span>
<!--docs end-->


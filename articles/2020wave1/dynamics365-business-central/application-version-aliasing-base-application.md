---
title: ベース アプリケーションのエイリアス用のアプリケーション バージョン
description: Business Central 2019 年リリース ウェーブ 2 では、ベース アプリケーションとシステム アプリケーションを導入しました。 これらに依存する拡張機能は、app.json ファイルで明示的な依存関係を指定する必要がありました。 現在は、以前のバージョンで使用できたものと同様のアプリケーション バージョン プロパティを再導入しています。
author: relnotes
ms.reviewer: solsen
ms.date: 12/12/2019
ms.assetid: 23c900bc-e41c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 83e9d7833241a75d812d11e5e30acfd3fe429eee
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986833"
---
# <a name="application-version-for-aliasing-base-application"></a>ベース アプリケーションのエイリアス用のアプリケーション バージョン
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
埋め込みアプリケーションとカスタマイズされたオンプレミス アプリケーションは、ベース アプリケーションの app.json ファイルとアプリケーション拡張機能の ID を変更できる必要があります。 ただし、そうすることで、Microsoft ベース ID を指す上位ソリューションは、明示的な依存関係を使用している場合、埋め込みアプリケーションまたはオンプレミス コードのカスタマイズに対して解決されません。 

したがって、Microsoft のベース アプリケーションの上に構築された拡張機能をソリューションに対してコンパイルできるように、埋め込みアプリケーションが Microsoft のベース アプリケーションのエイリアスであることを指定する方法をサポートするには、アプリケーション エイリアスを介した間接的なレベルが必要です。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
埋込みパートナーとオンプレミス ソリューションでは、Application という名前の親拡張機能を作成できます。この拡張機能は、ベース バージョンに従ってバージョン管理され、適切な一意の発行元を持ちます。 この親拡張機能は主に間接プロキシとして使用され、実際にアプリケーションを実装する拡張機能への明示的な依存関係を含む必要があります。 さらに、app.json ファイルの propagateDependencies プロパティを true に設定する必要があります。 これにより、プロキシ アプリケーションのバージョンに依存する拡張機能への依存関係が公開されます。 

パートナーは、拡張機能の app.json ファイルのアプリケーション バージョン プロパティを使用して、予想されるアプリケーション バージョンを指定します。

Visual Studio Code では、app.json ファイルでアプリケーション バージョンを指定すると、"application" を構成するシンボル パッケージの完全なセットが取り込まれます。

Microsoft のベース アプリケーションへの明示的な依存関係は、アプリケーション バージョンよりも優先されますが、ベース アプリケーションがシステムに存在しない場合は "application" にリダイレクトされます。

> [!NOTE] 
> ApplicationVersion では、コンパイル時の依存関係のみを解決できます。 拡張機能と提供されたエイリアスとの間に実際に互換性があるかどうかは、埋め込み拡張機能の作成者が確認およびテストするかどうかにかかっています。
<!--feature detail end -->










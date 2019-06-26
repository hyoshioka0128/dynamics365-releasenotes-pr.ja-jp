---
title: ビルドと展開でのアプリの依存関係の処理の改善
description: 依存関係を含む拡張機能のコンパイルと展開では、依存関係グラフが自動的に走査されて、これらが正しい順序で行われることが確認されるので、手動で処理する必要はありません。
author: relnotes
ms.reviewer: solsen
ms.date: 05/29/2019
ms.assetid: 7e1c615d-886d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
---
# <a name="improved-app-dependency-handling-on-build-and-deploy"></a>ビルドと展開でのアプリの依存関係の処理の改善
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
正しい順序で拡張機能をコンパイルおよび展開する面倒な手作業を避けます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
これまでは、依存関係のあるプロジェクトが正しい順序でビルドされることを手動で確認する必要があり、依存関係のある拡張機能を展開するには依存する拡張機能を手動でアンインストールして再インストールする必要がありました。 2019 年リリース ウェーブ 2 では、これはツールによる依存関係グラフの走査によって管理されるようになります。
<!--feature detail end -->











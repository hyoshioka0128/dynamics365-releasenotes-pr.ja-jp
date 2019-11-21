---
title: ビルドと展開でのアプリの依存関係の処理の改善
description: 依存関係を含む拡張機能のコンパイルと展開では、依存関係グラフが自動的に走査されて、これらが正しい順序で行われることが確認されるので、手動で処理する必要はありません。
author: relnotes
ms.reviewer: solsen
ms.date: 10/04/2019
ms.assetid: 7e1c615d-886d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 25974668e0c1995b73ea5e596a44398435b9232d
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667325"
---
# <a name="improved-app-dependency-handling-on-build-and-deploy"></a>ビルドと展開でのアプリの依存関係の処理の改善


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
正しい順序で拡張機能を手作業でコンパイルして展開するという煩雑さを回避します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
これまでは、依存関係のあるプロジェクトが正しい順序でビルドされることを手動で確認する必要があり、依存関係のある拡張機能を展開するには依存する拡張機能を手動でアンインストールして再インストールする必要がありました。 2019 年リリース ウェーブ 2 では、これはツールによる依存関係グラフの走査によって管理されるようになります。
<!--feature detail end -->










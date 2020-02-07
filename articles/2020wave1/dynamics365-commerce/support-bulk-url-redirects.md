---
title: 一括 URL リダイレクトのサポート
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: d254d58e-631d-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: d53f5b68387cd80c5e193131fa0e9d7ebe330a15
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986636"
---
# <a name="support-for-bulk-url-redirects"></a>一括 URL リダイレクトのサポート
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 Commerce でサイトを構築している小売業者は、そのページに対するドメイン リダイレクトを一括形式で管理できるようになりました。 Commerce では、Site Builder を介した CSV マッピング ファイルのアップロードとダウンロードがサポートされ、リダイレクトの大きなリストを管理できます。 この機能により、顧客のドメインが Commerce のホスト ページを参照するように切り替えることで、時間と労力が軽減され、以前の URL で新しいホスト コンテンツが提供されるようになり、こうした URL にアクセスする可能性のあるユーザーのエラーを回避できます。 再マッピングでは、以前に確立された SEO も保持されます。 マッピング ファイルにより、Commerce ユーザーはドメイン マッピングを簡単な CSV 形式で効率的に管理できるため、時間を節約できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
特定のサイトに対する Site Builder で、CSV 形式の URL リダイレクト マッピング ファイルをアップロードまたはダウンロードできるメニュー オプションが用意されています。 CSV ファイルでは、"ソース" URL と "ターゲット" URL を参照すること、そのリダイレクション タイプ (301/302)、ソース URL で大文字と小文字を区別するかどうか (既定値は false) を指定できます。 このアップロード後に、Commerce レンダリング プラットフォームはユーザー トラフィックを管理し、ユーザーをターゲット URL に誘導します。 この CSV は Site Builder ツールからダウンロードし、ユーザーが取り込んで編集できます (この機能では Site Builder 内での編集はサポートされていません)。 編集後、ユーザーは CSV ファイルを再アップロードして、提供された以前のマッピング CSV を上書きできます。
<!--feature detail end -->










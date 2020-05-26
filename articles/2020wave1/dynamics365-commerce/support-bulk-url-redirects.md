---
title: 一括 URL リダイレクトのサポート
description: 小売業者は、簡単な方法でサイトの Web リダイレクトを一括で制御できるようになりました。 単純な CSV 形式を利用して必要なリダイレクトのタイプを指定することで、URL リダイレクトを制御できます。 これにより、ドメイン所有者は古い URL にランディングしたユーザーを前のサイトの SEO ランキングを維持しながら目的の Web エクスペリエンスにランディングさせて、目的のエクスペリエンスをエンド ユーザーに提供することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/07/2020
ms.assetid: d254d58e-631d-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: fe564094173dc32b4030774d95e261c9a48bda57
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272633"
---
# <a name="support-for-bulk-url-redirects"></a>一括 URL リダイレクトのサポート


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 3 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 Commerce でサイトを構築している小売業者は、そのページに対するドメイン リダイレクトを一括形式で管理できるようになりました。 Commerce では、Site Builder を介した CSV マッピング ファイルのアップロードとダウンロードがサポートされ、リダイレクトの大きなリストを管理できます。 この機能により、顧客のドメインが Commerce のホスト ページを参照するように切り替えることで、時間と労力が軽減され、以前の URL で新しいホスト コンテンツが提供されるようになり、こうした URL にアクセスする可能性のあるユーザーのエラーを回避できます。 再マッピングでは、以前に確立された SEO も保持されます。 マッピング ファイルにより、Commerce ユーザーはドメイン マッピングを簡単な CSV 形式で効率的に管理できるため、時間を節約できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
特定のサイトに対する Site Builder で、CSV 形式の URL リダイレクト マッピング ファイルをアップロードまたはダウンロードできるメニュー オプションが用意されています。 CSV ファイルでは、"ソース" URL と "ターゲット" URL を参照すること、そのリダイレクション タイプ (301/302)、ソース URL で大文字と小文字を区別するかどうか (既定値は false) を指定できます。 このアップロード後に、Commerce レンダリング プラットフォームはユーザー トラフィックを管理し、ユーザーをターゲット URL に誘導します。 この CSV は Site Builder ツールからダウンロードし、ユーザーが取り込んで編集できます (この機能では Site Builder 内での編集はサポートされていません)。 編集後、ユーザーは CSV ファイルを再アップロードして、提供された以前のマッピング CSV を上書きできます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[URL リダイレクトの一括アップロード](https://docs.microsoft.com/dynamics365/commerce/upload-bulk-redirects) (ドキュメント)
<!--docs end-->

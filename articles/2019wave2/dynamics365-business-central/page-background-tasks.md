---
title: ページ バックグラウンド タスク
description: ページ バックグラウンド タスク - AL 開発者は、ページ内に子セッションを作成して、必要な読み取り専用の計算を実行できます。 計算が完了すると、親セッションに通知されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: b0644392-306c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: a5f0fa44d17b1b88c11cad369e51bb507fdebf77
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178991"
---
# <a name="page-background-tasks"></a>ページ バックグラウンド タスク


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ページ バックグラウンド タスクでは、ページ セッションの読み取り専用の子セッションで codeunit を (UI なしで) 実行できます。 タスクが完了すると、その結果を伴う完了トリガーがページ セッションで呼び出されます。

タスクが完了する前、またはページ レコード ID が変更される前にページが閉じられると、タスクはキャンセルされます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[ページ バックグラウンド タスク](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-page-background-tasks) (ドキュメント)

---
title: ページ バックグラウンド タスク
description: ページ バックグラウンド タスク - AL 開発者は、ページ内に子セッションを作成して、必要な読み取り専用の計算を実行できます。 計算が完了すると、親セッションに通知されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 07/01/2019
ms.assetid: b0644392-306c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: f10c071abdbbccded005d386e5d2955e2dc89c5b
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722809"
---
# <a name="page-background-tasks"></a>ページ バックグラウンド タスク
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|2019 年 8 月| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ページ バックグラウンド タスクでは、ページ セッションの読み取り専用の子セッションで codeunit を (UI なしで) 実行できます。 タスクが完了すると、その結果を伴う完了トリガーがページ セッションで呼び出されます。

タスクが完了する前、またはページ レコード ID が変更される前にページが閉じられると、タスクはキャンセルされます。
<!--feature detail end -->











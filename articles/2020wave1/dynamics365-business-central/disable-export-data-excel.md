---
title: Excel へのデータのエクスポートを無効にする
description: Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 12/10/2019
ms.assetid: 33e8c1aa-d1f5-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 7298051244f5f8a519dff236b18fbdc7e5436a0e
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986829"
---
# <a name="disable-export-of-data-to-excel"></a>Excel へのデータのエクスポートを無効にする
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
**Excel で編集** および **Excel で開く** アクションを使用すると、ユーザーは Business Central データを含んだ Excel スプレッドシートをすばやく取得し、Excel でさらなる処理を行うことができます。 ただし、組織によっては、Excel でのデータ セットの保持に制限を設けたデータ制御規則があります。その場合は、制御や監査が通常よりも困難になります。 新機能では、Excel にデータをエクスポートできるユーザーを管理者が指定できるようになりました。これにより、組織においてデータをより厳密に制御できるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。 Business Central からデータをエクスポートする機能は、**D365 EXCEL EXPORT** という新しいアクセス許可セットによって制御されます。 特定のユーザーのアクセス許可が削除された場合、そのユーザーは、アプリケーションのどのページでも、**Excel で編集** および **Excel で開く** アクションを使用できなくなります。
<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a>アイデアをありがとうございます
[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c)をお送りいただき、ありがとうございました。 アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。

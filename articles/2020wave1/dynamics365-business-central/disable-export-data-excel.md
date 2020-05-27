---
title: Excel へのデータのエクスポートを無効にする
description: Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 05/05/2020
ms.assetid: 33e8c1aa-d1f5-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: d22dce96d62b8abe78786d4ff6b85bf992205dba
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349844"
---
# <a name="disable-export-of-data-to-excel"></a>Excel へのデータのエクスポートを無効にする


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Excel で編集および Excel で開くアクションを使用すると、ユーザーは Business Central データを含んだ Excel スプレッドシートをすばやく取得し、Excel でさらなる処理を行うことができます。 ただし、組織によっては、Excel でのデータ セットの保持に制限を設けたデータ制御規則があります。その場合は、制御や監査が通常よりも困難になります。 新機能では、Excel にデータをエクスポートできるユーザーを管理者が指定できるようになりました。これにより、組織においてデータをより厳密に制御できるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central の管理者は、ユーザーが Excel にデータをエクスポートできる機能を無効にできるようになりました。 Business Central からデータをエクスポートする機能は、**D365 Excel Export Action** という新しいアクセス許可セットと ID 6110 のシステム アクセス許可によって制御されます。 特定のユーザーのアクセス許可が削除された場合、そのユーザーは、アプリケーションのどのページでも、**Excel で編集**および **Excel で開く**アクションを使用できなくなります。

### <a name="upgrading-to-business-central-2020-release-wave-1"></a>Business Central 2020 リリース ウェーブ 1 へのアップグレード

以前のバージョンの Business Central からアップグレードするお客様は、データを Excel にエクスポートできなくなる場合があります。 2020 年リリース ウェーブ 1 にアップグレードした後、管理者は、関連するユーザー グループとアクセス許可セットに **D365 Excel Export Action** アクセス許可セットまたはシステム アクセス許可 6110 が含まれていることを確認する必要があります。  

### <a name="try-it-now"></a>試してみましょう
[https://businesscentral.dynamics.com/?page=9802](https://businesscentral.dynamics.com/?page=9802) でオンライン環境にログインして、アクセス許可セットの一覧で探してください。  

<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a>アイデアをありがとうございます
[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4ec3ffd8-2a70-e911-80e7-0003ff68897c)をお送りいただき、ありがとうございました。 アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。

## <a name="see-also"></a>関連項目

<!--docs start-->
[Excel での表示や編集を Business Central から実行する](https://docs.microsoft.com/dynamics365/business-central/across-work-with-excel) (ドキュメント)
<!--docs end-->

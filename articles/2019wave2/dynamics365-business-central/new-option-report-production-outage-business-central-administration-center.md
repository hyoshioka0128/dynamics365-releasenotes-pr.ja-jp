---
title: Business Central 管理センターでの稼働停止のレポート
description: 顧客のテナントが停止してだれもログインできない場合は、緊急の対応が必要な重大な状況です。 Business Central 管理センターでは、パートナーはサポート チケットを自動的に作成する新しい [稼働停止のレポート] オプションを使用できるようになりました。
author: relnotes
ms.reviewer: edupont
ms.date: 11/15/2019
ms.assetid: 320a4afe-037b-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jchrist
dynamics365pdf: true
ms.openlocfilehash: a75d3dd0f1edbc10d4d07527311b99499ea68f33
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892044"
---
# <a name="report-production-outage-in-the-business-central-administration-center"></a>Business Central 管理センターでの稼働停止のレポート


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
顧客のテナントが停止していると判断されたら、Business Central 管理センターですぐにサポート チケットを作成できます。 顧客の運用環境を選択すると、新しいオプション**稼働停止のレポート**が有効になります。 このオプションは、サンドボックス環境では使用できません。 このアクションを選択した場合、使用可能な停止タイプは**ログオンできません (すべてのユーザー)** と **API/Web サービスにアクセスできません**です。 

選択後、他の必須フィールドは [名前]、[電子メール アドレス]、[電話番号] です。 次の画面では、試行したブラウザー、ログインできる会社、受信したエラー メッセージなど、停止に関する詳細が表示されます。 最後の質問は、停止が開始された日時に関するものです。 

同意ボックスをオンにした後、**レポート**を選択して停止を作成します。 サポート チケットがすべての詳細と共に自動的に作成されます。 これは Business Central 管理センターの**報告された停止**ページで確認できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[顧客の機能停止を報告する](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/manage-technical-support#report-customer-outages) (ドキュメント)

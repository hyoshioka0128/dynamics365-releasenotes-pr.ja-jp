---
title: パートナー向け Application Insights のサインイン試行テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーはサインイン試行に関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/02/2020
ms.assetid: 2ad1dfcd-4446-ea11-a812-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: d29e7c1f60789b9327572edb219f0153701ae8aa
ms.sourcegitcommit: db53421debc891ea407773d0e9b39feb7a01fef3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "3110932"
---
# <a name="sign-in-attempt-telemetry-in-application-insights-for-partners"></a>パートナー向け Application Insights のサインイン試行テレメトリ


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 26 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 2 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
パートナーは Application Insights をセットアップして使用し、(たとえば、アクセス許可がないことによる) ユーザーのサインインの問題の発生を監視して、Microsoft サポートに連絡する必要なしに顧客を積極的に支援できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central Server は、サインイン試行に関するテレメトリ (成功または失敗) を送信します。 試行が失敗した場合、その理由もメッセージに記録されます。 

Business Central への承認が成功すると、サーバーは Open Company の運用に関するテレメトリー (成功または失敗) も送信します。 会社への承認に失敗した場合、理由もメッセージに記録されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[認可トレース テレメトリの分析](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-authorization-trace) (ドキュメント)

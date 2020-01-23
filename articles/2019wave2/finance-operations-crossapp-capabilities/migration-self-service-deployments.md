---
title: セルフサービス配置への移行
description: セルフサービス配置への移行
author: relnotes
ms.reviewer: sericks
ms.date: 01/08/2020
ms.assetid: 81b362b3-fd6d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: sarvanis
dynamics365pdf: true
ms.openlocfilehash: 59103357de0576e8b96234824d815155e998ff75
ms.sourcegitcommit: ecf709e1d8de3b52e1156bceb99cb7e3819f9db3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/13/2020
ms.locfileid: "2950969"
---
# <a name="migration-to-self-service-deployments"></a>セルフサービス配置への移行


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Microsoft は、2018 年秋に新規顧客向けのセルフサービス配置を有効にしました。 2019 年夏から、顧客と連携して、顧客の環境をセルフサービス配置に移行します。 まず、既定のサンドボックスが移行されます。 2 通の通知メールも送信されます。 最初のメールは 30 日前の事前通知であり、2 番目のメールは予定された移行の 5 日前に送信されるアラーム通知です。 状況によっては、オンライン フォームで移行を再スケジュールすることができます。

### <a name="preparing-for-migration"></a>移行の準備
お客様は最初に、将来展開可能なパッケージを組み合わせて、現在のオンライン サービスで環境を更新する必要があります。 これは常に推奨されるベスト プラクティスでしたが、今は強制されます。

### <a name="whats-new-or-changed"></a>新機能および変更された機能
お客様は、Tier 2 以上の環境のサーバー管理者資格情報に直接アクセスできなくなります。 引き続き Azure SQL Database にはアクセスでき、Lifecycle Services (LCS) から Just-In-Time アクセスを使用して接続できるようになります。 

お客様は、Tier 2 以上の環境のリモート デスクトップ資格情報にアクセスできなくなります。 リモート デスクトップ アクセスを必要とするすべての操作は、LCS 上のセルフサービス操作として利用可能になりました。


<!--feature detail end -->










## <a name="see-also"></a>関連項目

[セルフサービス配置の概要](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/deployment/infrastructure-stack) (ドキュメント)

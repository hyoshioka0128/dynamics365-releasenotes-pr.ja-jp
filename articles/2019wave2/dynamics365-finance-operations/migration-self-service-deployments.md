---
title: セルフサービス配置への移行
description: セルフサービス配置への移行
author: relnotes
ms.reviewer: kfend
ms.date: 05/29/2019
ms.assetid: 81b362b3-fd6d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: sarvanis
dynamics365pdf: true
---
# <a name="migration-to-self-service-deployments"></a>セルフサービス配置への移行
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Microsoft は、2018 年秋に新規顧客向けのセルフサービス配置を有効にしました。 2019 年夏から、Dynamics 365 for Finance and Operations の顧客と連携して、顧客の環境をセルフサービス配置に移行します。 最初に既定のサンドボックスが移行され、その 7 カレンダー日後に運用環境が移行されます。 2 通の通知メールも送信されます。 最初のメールは 30 日前の事前通知であり、2 番目のメールは予定された移行の 5 日前のアラーム通知です。 状況によっては、オンライン フォームで移行を再スケジュールすることができます。

### <a name="preparing-for-migration"></a>移行の準備
お客様は最初に、将来展開可能なパッケージを組み合わせて、現在のオンライン サービスで環境を更新する必要があります。 これは常に推奨されるベスト プラクティスでしたが、今は強制されます。

### <a name="whats-new-or-changed"></a>新機能および変更された機能
お客様は、Tier 2 以上の環境のサーバー管理者資格情報に直接アクセスできなくなります。 引き続き Azure SQL Database にはアクセスでき、Lifecycle Services (LCS) から Just-In-Time アクセスを使用して接続できるようになります。 

お客様は、Tier 2 以上の環境のリモート デスクトップ資格情報にアクセスできなくなります。 リモート デスクトップ アクセスを必要とするすべての操作は、LCS 上のセルフサービス操作として利用可能になりました。

### <a name="zero-downtime-update-for-self-service-deployments"></a>セルフサービス配置に対するゼロ ダウンタイム更新
2019 年リリース ウェーブ 2 では、お客様は Microsoft の毎月のサービス更新に対するゼロ ダウンタイム更新フローに追加されます。
ゼロ ダウンタイムが有効になっているお客様は、更新が行われる更新ウィンドウを構成できます。 対話型ユーザーは、更新中に接続が失われることはありません。 まれに、指定されたウィンドウで更新を完了するためにユーザー セッションを終了する必要がある場合は、ユーザーに作業を保存してブラウザーを更新するよう通知されます。 実行中のバッチ ジョブはすべて、事前構成された更新ウィンドウの間は終了されます。 更新が完了すると、終了されたすべてのバッチ ジョブが再開されます。 更新ウィンドウの間に新しいバッチ ジョブを開始できます。 お客様には、メールおよび LCS の更新履歴を通じて、更新のステータスが通知されます。
<!--feature detail end -->











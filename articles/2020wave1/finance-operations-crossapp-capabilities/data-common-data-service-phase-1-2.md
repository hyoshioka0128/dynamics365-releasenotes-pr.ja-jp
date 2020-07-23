---
title: Common Data Service のデータ - フェーズ 1 と 2
description: Common Data Service のデータ - フェーズ 1 と 2
author: RamaKrishnamoorthy
ms.reviewer: rhaertle
ms.date: 06/15/2020
ms.assetid: 5838d44d-8d1b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: f46f5b5d2dc0b6e5c3b8a8e080c53d5a9fc73a71
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548342"
---
# <a name="data-in-common-data-service--phase-1--2"></a>Common Data Service のデータ - フェーズ 1 と 2


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 19 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Finance and Operations アプリのデータを Common Data Service で取得し、最新の状態に保ちます。 

Finance and Operations アプリと Dynamics 365 の Customer Engagement アプリの間で収束する概念を調和させることで、二重書き込みフレームワークをシームレスなエクスペリエンスにしています。 これにより、企業はアプリの境界を超えて、凖リアルタイムのデータを同期的に、双方向で交換できるようになるため、統合されたエクスペリエンスがユーザーに提供されます。 

すべてのビジネスが固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。 これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフルに使用するための既存のエンティティへの拡張が含まれます。

## <a name="phased-release"></a>段階的リリース
フェーズ 1 の機能は、顧客、仕入先、および製品にマルチマスタリング機能を提供すると共に、Common Data Service に企業コンセプトを導入します。 また、会計と税の参照データも含まれています。 これらの機能は、2019 年 7 月からプレビューされています。 

次のエンティティがサポートされています。 

* 支払スケジュール - ヘッダー  
* 支払スケジュール – 明細行
* 支払期日 - ヘッダー
* 支払期日 - 明細行
* 顧客グループ
* 支払条件
* 顧客支払方法
* ロイヤルティ カード
* ロイヤルティ報酬ポイント
* 顧客
* 顧客の連絡先
* 通貨
* 会計カレンダー
* 会計暦年
* 為替レート タイプ
* 為替レート ペア
* 元帳会計期間および財務カレンダー期間
* 主勘定カテゴリ
* 主勘定
* 元帳
* 為替レート
* 分析コードの属性
* 分析コード統合形式
* 組織分類および組織階層の目的
* 組織階層
* 組織階層タイプ
* 会社
* リリースされた製品
* 特徴的リリース済製品
* 製品番号で特定されたバーコード エンティティ
* グローバル製品
* 製品の既定の注文設定エンティティ
* 製品固有の既定の注文設定
* 製品分析コード グループ エンティティ
* 追跡用分析コード グループ エンティティ
* 測定単位エンティティ
* 測定単位換算
* 製品固有の測定単位換算
* サイト エンティティ
* 倉庫エンティティ
* 色エンティティ
* サイズ エンティティ
* 保管分析コード グループ エンティティ
* スタイル エンティティ
* 構成エンティティ
* EcoResProductMasterColor エンティティ
* EcoResProductMasterSize エンティティ
* EcoResProductMasterStyle エンティティ
* EcoResProductMasterConfig エンティティ
* 製品カテゴリ
* 製品カテゴリの割り当て
* 製品カテゴリ階層
* 製品カテゴリ階層ロール
* 税グループ
* 税品目グループ
* 免税
* 税務当局
* 源泉徴収税コード
* 源泉徴収税グループ
* 税勘定科目グループと税転記グループ
* 仕入先
* 仕入先グループ
* 仕入先支払方法
* 仕入先連絡先
* 勘定科目表

[フェーズ 1](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/finance-operations-crossapp-capabilities/data-common-data-service-phase-1) のプレビュー時には、マスター データと参照データのシナリオに関する一連の機能が引き続き提供されます。**フェーズ 2** の機能では、価格設定、見積、注文、請求書、資産など、エンドツーエンドのシナリオがサポートされる予定です。 これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。 これらの領域に対するエンティティの対応範囲は、プレビュー時に発表されます。 

2020 年 3 月 27 日に出荷されたフェーズ 1 とフェーズ 2 の両方。 

次の増分機能とバグ修正は、2020 年 6 月 8 日にリリースされます。

* Customer Engagement アプリのフォームで手持在庫と納期回答可能在庫の日付を検索する機能。
* Customer Engagement アプリのフォームへの会社名の自動入力。
* 会社のコンテキストベースのデータ フィルタリング。
* Finance and Operations アプリで見積明細行と受注明細行の単位変換が行われる場合、Customer Engagement アプリでは単位変換が尊重され、見積明細と受注明細での単位と価格にそれぞれ変更が反映されます。
* ユーザーが Finance and Operations アプリで既存の見積もりまたは注文の通貨を変更しようとすると、変更は制限され、変更が失敗します。
* B2B および B2C のお客様向けの取引先企業および取引先担当者フォームの同等の属性。
* Customer Engagement アプリの見積もりまたは注文に対して作成または更新アクションがある場合、Finance and Operations アプリでアドレスは複製されません。
* B2B および B2C のお客様向けの取引先企業および取引先担当者フォームの消費税グループのサポート。
* Customer Engagement アプリの "クイック作成: 取引先担当者" フォームから販売可能な取引先担当者の作成を許可します。
* B2C 顧客の見積もりと注文の作成を有効にします。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[二重書き込みのホームページ](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/dual-write-home-page) (ドキュメント)
<!--docs end-->

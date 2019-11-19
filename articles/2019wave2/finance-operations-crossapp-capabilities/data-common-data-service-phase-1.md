---
title: Common Data Service のデータ – フェーズ 1
description: Common Data Service のデータ – フェーズ 1
author: RamaKrishnamoorthy
ms.reviewer: sericks
ms.date: 10/16/2019
ms.assetid: fc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: ddb07852b055f99000269f91304ef5fb66882957
ms.sourcegitcommit: 3e19a91181b001b74894328456d8da10d4f6d973
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2019
ms.locfileid: "2673853"
---
# <a name="data-in-common-data-service--phase-1"></a>Common Data Service のデータ – フェーズ 1
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 7 月 24 日| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、Common Data Service とのシームレスなデータ交換を容易にします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Common Data Service のデータを取得し、最新の状態に保ちます。 

Microsoft では、二重書き込みを追加設定なしで利用できるようにしています。 これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。 Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。 

すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。 これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。

## <a name="phase-1-release"></a>フェーズ 1 リリース
フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。 また、会計と税の参照データも含まれています。 これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。 対象となっているエンティティは次のとおりです。 

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
* 元帳会計期間/財務カレンダー期間
* 主勘定カテゴリ
* 主勘定
* 元帳
* 為替レート
* 分析コードの属性
* 分析コード統合形式
* 組織分類/組織階層の目的
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
* 税勘定科目グループ/税転記グループ
* 仕入先
* 仕入先グループ
* 仕入先支払方法
* 仕入先連絡先
* 勘定科目表

## <a name="phase-2-release"></a>フェーズ 2 リリース
フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。 これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。 これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。 

これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。 対象となるエンティティは後日発表されます。
<!--feature detail end -->





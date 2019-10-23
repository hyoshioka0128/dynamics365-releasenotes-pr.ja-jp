---
title: Dynamics 365 Retail の新機能と予定されている機能 (2019 年リリース ウェーブ 2)
description: Dynamics 365 Retail で計画されている機能の概要。
author: relnotes
ms.reviewer: josaw
ms.date: 09/18/2019
ms.topic: summary
ms.service: business-applications
ms.author: msalam
dynamics365pdf: true
ms.openlocfilehash: 5c7b18579fe570669b62911f4d1e333851841e2c
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143507"
---
# <a name="whats-new-and-planned-for-dynamics-365-retail"></a>Dynamics 365 Retail の新機能と予定されている機能

このトピックでは、2019 年 10 月から 2020 年 3 月までのリリースで予定されている機能の一覧を示します。 このトピックの一覧で示されている機能はまだリリースされていない可能性があるので、**提供タイムラインが変更されたり、予定されている機能がリリースされない場合があります** ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。

機能は**一般提供**列で示されている月内に提供されます。 提供日がその月内のどの日になるかはわかりません。 リリースされた機能には、リリース日を含む完全な日付が表示されます。

このチェック マーク (![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") ) は、パブリック プレビュー/早期アクセス向けおよび一般提供向けにリリース済みの機能を示しています。



## <a name="fundamentals"></a>基本機能

インフラストラクチャ、サービス、品質、およびパフォーマンスへの取り組み

 | 機能    | 有効対象    |  パブリック プレビュー | 一般提供 |
 | ---------- | ---------- | :----------: |:----------: |
 | [POS の請求コードの翻訳](translations-charges-codes-pos.md) | ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日|2019 年 10 月 | 
 | [小売明細転記の機能強化](enhancements-retail-statement-posting.md) | ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
 | [Cloud Async Client による CDX のスケーラビリティの向上](improved-cdx-scalability-through-cloud-async-client.md) | ユーザー、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
 | [Modern POS のオフライン可用性の向上](modern-pos-offline-availability-improvements.md) | ユーザー、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
 | [POS の在庫入荷フォームでテンキーを常に画面に表示する](numpad-remain-onscreen-pos-inventory-receiving-form.md) | 管理者、作成者、またはアナリスト、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
 | [POS および本社の拡張機能](pos-headquarters-extensions.md) | 管理者、作成者、またはアナリスト、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
 | [1 つのバージョン - Retail Cloud Scale Unit の自動更新](one-version---auto-update-retail-cloud-scale-unit.md) | 管理者、作成者、またはアナリスト、自動的  | 2019 年 10 月|2019 年 10 月 | 
 | [店舗のスケール ユニットの向上](store-scale-unit-improvements.md) | 管理者、作成者、またはアナリスト、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
| [POS での製品レコメンデーション](product-recommendations-pos.md) | ユーザー、管理者/作成者/アナリストによる有効化  |   - |2019 年 11 月 | 
 | [POS 用の Regression Suite Automation Tool](regression-suite-automation-tool-pos.md) | 管理者、作成者、またはアナリスト、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 3 日|2019 年 11 月 | 
 | [シークレットへの安全なアクセス](secure-access-secrets.md) | 管理者、作成者、またはアナリスト、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 3 日|2019 年 11 月 | 
 | [eコマース在庫 API の改善](e-commerce-inventory-api-improvements.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|2020 年 1 月 | 
| [指定された集荷、実行、電子的配送モードが POS のすべて出荷プロセスと選択された出荷プロセスに表示されないようにする](hide-designated-pickup-carryout-electronic-modes-delivery-ship-all-ship-selected-processes-pos.md) | ユーザー、管理者/作成者/アナリストによる有効化  |   2019 年 10 月 |2020 年 1 月 | 
 | [店舗内コンポーネントの大量展開](in-store-components-mass-deployment.md) | 管理者、作成者、またはアナリスト、自動的  | 2019 年 11 月|2020 年 1 月 | 
| [店舗での小売トランザクションの財務調整 (パブリック プレビュー)](financial-reconciliation-retail-transactions-store-public-preview.md) | ユーザー、管理者/作成者/アナリストによる有効化  |   2019 年 11 月 |2020 年 2 月 | 
 | [Retail Cloud Scale Unit の環境の履歴](environment-history-retail-cloud-scale-unit.md) | 管理者、作成者、またはアナリスト、自動的  | 2020 年 2 月|2020 年 2 月 | 
 | [デバイス ライセンス認証トークンの自動更新](auto-refresh-device-activation-token.md) | 管理者、作成者、またはアナリスト、自動的  | 2020 年 1 月|近日発表 | 


## <a name="industry-excellence"></a>業界の卓越性

中核的な小売事業プロセスおよび業界の要件と機能への取り組み

 | 機能    | 有効対象    |  パブリック プレビュー | 一般提供 |
 | ---------- | ---------- | :----------: |:----------: |
 | [製品の見つけやすさの改善](enhancements-product-discoverability.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|- | 
 | [販売促進の改善 - さまざまなカテゴリ階層に属するカテゴリの表示順序でカスタムの並べ替えをサポート](merchandising-improvements.md) | ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日|2019 年 10 月 | 
 | [インド用 POS からの顧客登録番号の管理](management-customer-registration-numbers-pos-india.md) | ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 6 日|2019 年 11 月 | 
 | [東ヨーロッパ向けコール センターのローカライズ](call-center-localization-eastern-europe.md) | ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 1 月 | 
 | [クライアンテリング - 販売担当者が信頼できるアドバイザーになり、顧客と長期的な関係を築けるようにする](clienteling--empower-associates-establish-relationships-customers.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|2020 年 1 月 | 
 | [コール センターでの外部ギフト カードのサポート](external-gift-card-support-adyen-connector-e-commerce-call-center.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|2020 年 1 月 | 
 | [販売促進の改善 – カテゴリ化製品、関連製品、分析コード グループに対するカスタム順序のサポートの追加](merchandising-improvements-add-support-custom-order-categorized-products-related-products-dimension-groups.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|2020 年 1 月 | 
 | [販売促進の改善 - 製品属性、リファイナー、値に対するカスタム順序を構成および遵守するためのサポートの追加](merchandising-improvements-add-support-configure-observe-custom-order-product-attributes-refiners-values..md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|2020 年 1 月 | 
 | [支払/入金ベースの割引](tender-based-discounts.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 10 月|2020 年 1 月 | 
 | [店舗での在庫 (入庫/出庫) 操作の改善](improved-inventory-inbound-outbound-operations-store.md) | ユーザー、管理者/作成者/アナリストによる有効化  | 2019 年 11 月|2020 年 1 月 | 

**有効対象**列の値の説明

- **ユーザー、自動的**: これらの機能には、ユーザーに対するユーザー エクスペリエンスへの変更が含まれており、自動的に有効になります。

- **管理者、作成者、またはアナリスト、自動的**: これらの機能は、管理者、作成者、またはビジネス アナリストによって使用されることが意図されており、自動的に有効になります。

- **ユーザー、管理者/作成者/アナリストによる有効化**: これらの機能をユーザーが利用するには、管理者、作成者、またはビジネス アナリストによって有効化または構成される必要があります。


Dynamics 365 ビジネス アプリケーションを利用できる国または地域の一覧については、[ご利用いただける国と地域に関するガイド](https://aka.ms/dynamics_365_international_availability_deck)を参照してください。 

地域、データ センター (リージョン)、データ ストレージ、レプリケーションの詳細については、[データの場所のページ](https://www.microsoft.com/trust-center/privacy/data-location)で**すべて展開**をクリックして、この機能に対する Microsoft Cloud Service を確認してください。 

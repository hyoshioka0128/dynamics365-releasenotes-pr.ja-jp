---
title: Dynamics 365 Finance の新機能と予定されている機能 (2020 年リリース ウェーブ 1)
description: Dynamics 365 Finance で計画されている機能の概要。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/02/2020
ms.topic: summary
ms.service: business-applications
ms.author: msalam
dynamics365pdf: true
ms.openlocfilehash: 00225dae248022717dd2261ce7ac3b59adb5454c
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219251"
---
# <a name="whats-new-and-planned-for-dynamics-365-finance"></a>Dynamics 365 Finance の新機能と予定されている機能

このトピックでは、2020 年 4 月から 2020 年 9 月にかけてリリースが計画されている機能の一覧を示します。 このトピックの一覧で示されている機能はまだリリースされていない可能性があるので、**提供タイムラインが変更されたり、予定されている機能がリリースされない場合があります** ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。

機能は**一般提供**列で示されている月内に提供されます。 提供日がその月内のどの日になるかはわかりません。 リリースされた機能には、リリース日を含む完全な日付が表示されます。

このチェック マーク (![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") ) は、パブリック プレビュー/早期アクセス向けおよび一般提供向けにリリース済みの機能を示しています。



## <a name="core-financials"></a>コア財務

このリリースでは、ユーザーが手動で実行するプロセスの数を減らすための一般的なタスクの自動化に重点が置かれています。 組織がリスクを管理し、下流のプロセスを自動化するのに役立つ与信管理機能も導入されています。 使いやすさも向上します。

 | 機能    | 有効対象    |  パブリック プレビュー | 一般提供 |
 | ---------- | ---------- | :----------: |:----------: |
 | [回収タスクの自動作成](automatic-collection-task-creation.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 7 月|- | 
 | [伝票トランザクション リスト ページに仕入先 ID、顧客 ID、仕入先名、顧客名を追加する](add-vendor-id-customer-id-vendor-name-customer-name-voucher-transactions-list-page.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 4 月 | 
 | [申告年による税の詳細レポート 1099 のフィルター処理の許可](allow-filtering-tax-1099-detail-report-reporting-year.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [パフォーマンスを高める予算計画クエリの最適化](budget-planning-query-optimization-performance.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [与信管理](credit-management.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [仕訳レポート別転記済トランザクションのデータ範囲](date-range-posted-transactions-journals-report.md) | エンド ユーザー、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止する](prohibit-submission-workflow-when-invoice-total-registered-invoice-total-are-not-equal.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [仕入先請求書明細行に請求金額をコピーする場合のパフォーマンスを向上させる](improve-performance-when-copying-charges-vendor-invoice-lines.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 5 月 | 
 | [元帳の会計カレンダーを変更するときに「期間残高の再計算」が必要](require-recalculate-ledger-periods-when-changing-fiscal-calendar-ledger.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 5 月 | 
 | [仕入先請求書のバッチ転記](add-automated-task-vendor-invoice-workflow-posting-vendor-invoice-using-batch-job.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 5 月 | 
 | [通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化](retained-earnings-calculation-enhancements-financial-reporting-when-using-currency-translation.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 6 月 | 
 | [詳細な元帳決済: 決済と決済取消を別個に処理する](advanced-ledger-settlement-settlement-reverse-settlement-processed-separately.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 7 月 | 
 | [取引詳細レポートを含む試算表](trial-balance-transactional-detail-report.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 7 月 | 
 | [自動仕入先支払提案](automatic-vendor-payment-proposal.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 7 月 | 
 | [顧客へのタッチレス メール アラーム](touchless-email-reminders-customer.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 8 月 | 


## <a name="finance-insights"></a>Finance Insights

Finance Insights の形式で提供される AI を活用した機能

 | 機能    | 有効対象    |  パブリック プレビュー | 一般提供 |
 | ---------- | ---------- | :----------: |:----------: |
 | [顧客支払予測](customer-payment-predictions.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|- | 
 | [キャッシュ フロー予測の外部データ](external-data-cash-forecasting.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|- | 
 | [銀行残高の予測](forecast-bank-balance.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|- | 
 | [インテリジェントな予算提案](intelligent-budget-proposal.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|- | 
 | [会計登録者ワークスペース](treasurer-workspace.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|- | 


## <a name="globalization"></a>グローバリゼーション

このリリースでは、イタリアのアドイン EXIL のコア ローカライズへの統合、フランスの国際支払い用の ISO 20022 形式の出荷 (Idea Portal で強く要望)、PDF 変換とダイレクト印刷機能を備えた構成可能なビジネス ドキュメントの拡張 (パブリック プレビューで) が行われます。

 | 機能    | 有効対象    |  パブリック プレビュー | 一般提供 |
 | ---------- | ---------- | :----------: |:----------: |
 | [電子レポートの高度な数式エディター](electronic-reporting-advanced-formula-editor.md) | 管理者、作成者、またはアナリスト、自動的  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット](extended-french-localization-iso20022-format-international-payment-treasury-transfer.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 詳細なメモの管理](extended-italian-localization-advanced-notes-management.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 銀行口座設定の強化](extended-italian-localization-bank-account-setup-enhancement.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 改善された借方/貸方の照会](extended-italian-localization-improved-inquiry-debitcredit.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: イントラスタット申告でのキログラムあたりの雑費](extended-italian-localization-miscellaneous-charges-per-kilogram-intrastat-declaration.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 金額がゼロの請求書の転記](extended-italian-localization-posting-invoices-zero-amount.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 梱包明細順での売上請求明細行の並べ替え](extended-italian-localization-sales-invoice-lines-sorting-packing-slips.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 訂正票用の個別勘定](extended-italian-localization-separate-accounts-credit-notes.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 無料で配送される物品の税金請求書](extended-italian-localization-tax-invoice-goods-delivered-free.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [拡張されたローカライズ (スイス): QR 請求書の実装](extended-swiss-localization-qr-bill-implementation.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 4 月 | 
 | [請求先/元 ID の会計データの使用](use-fiscal-data-invoice-account.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 6 日|2020 年 4 月 | 
 | [拡張されたイタリア語ローカライズ: 一般会計のシミュレーション](extended-italian-localization-general-ledger-simulations.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 8 月 | 
 | [拡張されたイタリア語ローカライズ: 覚書 – 定期輸出業者への請求書発行](extended-italian-localization-intent-letters--invoicing-usual-exporters.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 8 月 | 
 | [拡張されたイタリア語ローカライズ: 独自認証](extended-italian-localization-unique-certification.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|2020 年 8 月 | 
 | [拡張されたイタリア語ローカライズ: 支払時での手数料決済](extended-italian-localization-commission-settlement-payments.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|2020 年 8 月 | 
 | [拡張されたローカライズ (イタリア): 銀行および送金タイプ別に構成可能な転記プロファイル](extended-italian-localization-configurable-posting-profiles-banks-remittance-types.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|2020 年 8 月 | 
 | [拡張されたイタリア語ローカライズ: 受取手形の受取拒否処理](extended-italian-localization-protest-handling-bills-exchange.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 5 月|2020 年 8 月 | 
 | [拡張されたイタリア語ローカライズ: 税限度額](extended-italian-localization-tax-plafond.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 7 月|2020 年 8 月 | 
 | [構成可能なビジネス ドキュメントの PDF への変換](configurable-business-documents-conversion-pdf.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 4 月|近日発表 | 
 | [構成可能なビジネス ドキュメント: 直接印刷](configurable-business-documents-direct-printing.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 4 月|近日発表 | 


## <a name="public-sector"></a>公的機関

このリリースでは、予算編成、買掛金勘定、カナダの税の改善に重点が置かれています。

 | 機能    | 有効対象    |  パブリック プレビュー | 一般提供 |
 | ---------- | ---------- | :----------: |:----------: |
 | [会計登録者の会計責任に関する日次明細](daily-statement-treasurers-accountability.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 4 月 | 
 | [詳細な元帳エントリを使用してトランザクションを転記するときに銀行残高を更新する](update-bank-balances-when-posting-transactions-using-advanced-ledger-entry.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 2 日|2020 年 4 月 | 
 | [利息配賦および没収で転記時に銀行残高を更新できるようにする](allow-interest-distribution-escheatment-use-feature--lets-update-bank-balances-when-posting-advanced-ledger-entries.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 5 月 | 
 | [交付金に関する A-133 通達レポート (SEFA)](a-133-circular-report-grants-sefa.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 7 月 | 
 | [予算計画を置き換えるオプションの削除](remove-option-replace-budget-plan.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 7 月 | 
| [購買契約書に関連付けられた PO 請求書に明細を追加する](add-lines-po-invoices-associated-purchase-agreement.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  |   - |2020 年 7 月 | 
 | [つなぎ勘定トランザクションと小切手フォームに対する仕入先の詳細](vendor-details-bridged-transactions-check-forms.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | -|2020 年 7 月 | 
 | [カナダの統一消費税](canadian-harmonized-sales-tax.md) | エンド ユーザー、管理者/作成者/アナリストによる有効化  | 2020 年 6 月|2020 年 7 月 | 

**有効対象**列の値の説明:

- **エンド ユーザー、自動的**: これらの機能には、エンド ユーザーに対するユーザー エクスペリエンスへの変更が含まれており、自動的に有効になります。

- **管理者、作成者、またはアナリスト、自動的**: これらの機能は、管理者、作成者、またはビジネス アナリストによって使用されることが意図されており、自動的に有効になります。

- **エンド ユーザー、管理者/作成者/アナリストによる有効化**: これらの機能をエンド ユーザーが利用するには、管理者、作成者、またはビジネス アナリストによって有効化または構成される必要があります。


Dynamics 365 ビジネス アプリケーションを利用できる国または地域の一覧については、[ご利用いただける国と地域に関するガイド](https://aka.ms/dynamics_365_international_availability_deck)を参照してください。 

地域、データ センター (リージョン)、データ ストレージ、レプリケーションの詳細については、[データの場所のページ](https://www.microsoft.com/trust-center/privacy/data-location)で**すべて展開**をクリックして、この機能に対する Microsoft Cloud Service を確認してください。 

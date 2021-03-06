---
title: レポートをより効率的にフィルター処理する
description: より多くのフィルター フィールドを追加できるようにするなど、コミュニティのトップ リクエストのいくつかに対処して、レポートのフィルター処理エクスペリエンスを改善しています。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: b863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: c9131442e91cb9d6a55d9513a14d06a25a838c47
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892011"
---
# <a name="filter-reports-more-efficiently"></a>レポートをより効率的にフィルター処理する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ビジネスが拡大するにつれて、データ ソースを利用するレポートも拡大します。 これにより、処理されるデータ量を正確に制御する必要性が高まります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central でレポートを実行するときは、さまざまなオプションやフィルターを指定できるリクエスト ページが表示されます。

### <a name="filtering-report-data"></a>レポート データのフィルター処理
以下の操作を行えるリストのフィルター処理に似た機能により、フィルター エクスペリエンスが大幅に向上しました。

- ソース テーブルから任意のフィールドを選択するか、入力してフィールドをすばやく検索することにより、フィルター処理されたフィールドを好きなだけ追加します。
- ルックアップおよび類似のピッカーを使用して、複数オプション フィールド値でのフィルター処理など、フィルター値の指定に関するヘルプを入手します。
- 演算子、範囲、数式、フィルター トークンを使用して、複雑なフィルターを作成します。

Business Central では、適用したフィルターが記憶され、以前に行ったレポート設定から選択することもできます。

### <a name="filtering-totals"></a>合計のフィルター処理
Dynamics NAV の最も人気のある機能の 1 つをレポートにも使用できるようになりました。 レポートでは、合計金額など、集計値や計算値が FlowField で表示されることがよくあります。 このリリースの Business Central では、計算される値に影響する 1 つ以上のディメンションにフィルターを適用できます。

#### <a name="consistently-powerful"></a>一貫して強力
改善されたエクスペリエンスは、RunRequestPage コマンドまたは FilterPageBuilder コマンドから生成される XMLport オブジェクトと画面だけでなく、レポート オブジェクト全体で一貫しています。

<!--feature detail end -->

![さまざまなフィルター処理されたフィールドを示す顧客レポート](media/report-3000x2000.png "さまざまなフィルター処理されたフィールドを示す顧客レポート")
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目
[機能の探索](https://aka.ms/ROGBC19RW2ROV9) (ビデオ)

[レポート、バッチ ジョブ、XMLport でフィルターを設定する](https://docs.microsoft.com/dynamics365/business-central/ui-enter-criteria-filters#setting-filters-in-reports-batch-jobs-and-xmlports) (ドキュメント)

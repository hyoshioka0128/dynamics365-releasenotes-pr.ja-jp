---
title: ウェーブ ラベル印刷の機能強化
description: この機能では、ピッキング前のラベル作成の柔軟性が向上します。 ラベルはウェーブ プロセス中に作成されます。 ラベルとレイアウトの定義によって機能が拡充されます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 7c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 2231a3d2279084ef4a4d62616348f8a22b4a800e
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854660"
---
# <a name="wave-label-printing-enhancements"></a>ウェーブ ラベル印刷の機能強化
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 4 月| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
これらの変更により、パレット化前のカートンのラベル付けのサポートがより効率的になります。 コンプライアンスが問題となる一部のお客様は、各カートンのラベルのレイアウトと内容を義務付ける大規模小売業者に対する仕入先です。 これらの大規模顧客の "ラベル受け入れプロセス" では、受け入れ中にカートンがコンベア上に置かれ、バーコードが自動的に読み取られて、プット アウェイを自動的に作成できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ウェーブ ラベル印刷機能は、Dynamics 365 for Finance and Operations バージョン 10.0.0 で組み込まれました。 この機能は次のように強化されます。

-  単一の作業明細行でのカートン数に従ってラベルを印刷できます。 コンテナー詰め機能を使用しないと、100 個のカートンに対して、100 個のラベルが印刷されることを意味します。

- ラベルの列挙が含まれます (1/124、2/124…124/124)。

- 船荷証券 (BOL) を作成してラベルに印刷することができます。

- カートンごとに固有のシリアル配送コンテナー コード (SSCC) を作成して、ラベルに含めることができます。

- BOL および SSCC 番号に対して GS1 準拠の番号シーケンスを作成できます。

- HAZMAT コードをラベルに含めることができます (該当する場合)。

- ラベルの再印刷がサポートされます (リッチ クライアントからのようにハンドヘルド デバイスから) 。

- ラベル (たとえば、短いピッキング シナリオの場合) と再印刷の無効化がサポートされます。

- ウェーブ ラベル履歴のクリーンアップがサポートされます。 

これらの変更により、パレット化前のカートンのラベル付けのサポートがより効率的になります。 特に、個々のカートンのスキャンを使用して自動的に注文受領確認を実行する大規模小売業者に出荷する会社に役立ちます。
<!--feature detail end -->












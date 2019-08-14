---
title: 材料取り扱い/倉庫自動化
description: 材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 9a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 3a4b7a83b8d93a70b8e3c2d9708518b40bb50314
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855166"
---
# <a name="material-handlingwarehouse-automation"></a>材料取り扱い/倉庫自動化
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 8 月| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。 ユーザーは、作業の作成、完了、キャンセルなどの倉庫イベントで、アウトバウンド サブスクリプションを設定できます。 これらのイベントは、関連付けられたデータとともに、キューで追跡され、外部の機器から Web サービス経由でアクセスできます。 各トランザクションに関連付けられたデータは、完全にユーザー構成可能です。 各キュー レコードを追加するために、最大 10 個のフィールドを指定できます。 各レコードのステータスは、ブロック済みから送信済みまで追跡されます。 同様に、インバウンド キューが存在し、外部機器は Web サービス経由でこれを設定できます。 インバウンド キュー レコードが消費されると、作業の完了やライセンス プレートの受取などの倉庫アクションがトリガーされます。 作業は一度に 1 つずつ実行するか、またはピック/プットのペアを単一のトランザクションで実行することができます。 未処理ピッキングと場所の上書きもサポートされています。
<!--feature detail end -->












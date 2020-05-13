---
title: 材料取り扱い/倉庫自動化
description: 材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 4bdf6f3dab912d27d87dfb0419c09fecdac7b7b8
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320008"
---
# <a name="material-handlingwarehouse-automation"></a>材料取り扱い/倉庫自動化


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| 近日発表|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。 ユーザーは、作業の作成、完了、キャンセルなどの倉庫イベントで、アウトバウンド サブスクリプションを設定できます。 これらのイベントは、関連付けられたデータとともに、キューで追跡され、外部の機器から Web サービス経由でアクセスできます。 各トランザクションに関連付けられたデータは、完全にユーザー構成可能です。 各キュー レコードを追加するために、最大 10 個のフィールドを指定できます。 各レコードのステータスは、ブロック済みから送信済みまで追跡されます。 同様に、インバウンド キューが存在し、外部機器は Web サービス経由でこれを設定できます。 インバウンド キュー レコードが消費されると、作業の完了やライセンス プレートの受取などの倉庫アクションがトリガーされます。 作業は一度に 1 つずつ実行するか、またはピック/プットのペアを単一のトランザクションで実行することができます。 未処理ピッキングと場所の上書きもサポートされています。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)
<!--docs end-->

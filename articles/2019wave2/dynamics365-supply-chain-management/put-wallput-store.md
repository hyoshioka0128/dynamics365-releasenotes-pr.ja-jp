---
title: 壁へのプット/ストアへのプット
description: この機能を使用すると、構成可能な基準に基づいて、パッケージ品目ステージング領域への製品の統合が要求されるシナリオが可能になります。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/27/2020
ms.assetid: 8a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 65cdc07dfb6ccfcffbcf76a2ab6ff4568a9fda92
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058972"
---
# <a name="put-to-wallput-to-store"></a>壁へのプット/ストアへのプット


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 17 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能では、構成可能な基準に基づいて、パッケージ品目ステージング領域への製品の統合が要求されるシナリオを処理できます。 単一のターゲット ライセンス プレートへのピッキングが可能になり、クラスター ピッキングより多くのプット位置を活用できるため、店舗に出荷する企業や小さい商品を行う企業は、ピッキング時間が短縮されるため、この機能を使用するメリットがあります。 壁へのプット ワークフローでは、ピッキングされた製品は、さまざまな種類のコンテナーに分けるため選別場所に送られます。 一般に、各選別場所には複数の選別位置が含まれます。 各選別位置は、ビジネス プロセス、最も一般的な送り先、店舗、出荷、または積荷によって設定された基準に従って割り当てられます。 

ピッキングされた製品は、選別ステーションに運ばれ、注文、送り先、出荷、または積荷に関連する数量で選別位置に分配されます。 コンテナーがいっぱいになるか完成すると、ビジネス プロセスに応じて、さらに処理するためにステージング場所または出荷場所に移動されます。 技術的には、壁にプット機能により、個々の品目または数量を、ピッキング中に割り当てられたターゲット ライセンス プレートから取得し、選別位置に選別し、通常はコンテナーを表す選別ライセンス プレートに割り当てることができます。 選別位置がクローズされると、倉庫管理設定に従って作業が作成されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)

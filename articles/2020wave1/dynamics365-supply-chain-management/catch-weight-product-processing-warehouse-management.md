---
title: 倉庫管理での CW 製品処理
description: 農業、食品、鉱業、金属などの一部の産業では、ビジネス プロセス フローで複数の測定単位を使用して製品を追跡する必要があります。
author: relnotes
ms.reviewer: kamaybac
ms.date: 02/25/2020
ms.assetid: 80e7006d-1f1c-ea11-a811-000d3a8f0752
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 7aa5b421d5c59bd39c7b18f4af9f7847e24f19bd
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3231857"
---
# <a name="catch-weight-product-processing-with-warehouse-management"></a>倉庫管理での CW 製品処理
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
CW 製品で、倉庫管理プロセスに関連するビジネス シナリオを処理できるようになりました。

この機能では、割り当てられた CW 単位ごとにキャプチャされた重量を取得する CW タグが提供されます。 このアプローチの目的は、製品を受領時に 1 回のみ計量することです。 これは、時間がたっても重量が変化しない製品 (冷凍エビなど)、および出荷可能な材料取り扱い測定単位 (エビの箱など) がある製品に有効です。 このアプローチでは、ユーザーは、CW タグをスキャンし、製品の構成に基づいてピッキング時または梱包時に重量を識別します。 その後、キャプチャされた CW タグに関連付けられている重量に基づいて請求します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は、**機能管理**インターフェイスで有効になります。 新機能には、未処理の在庫トランザクションを持つ既存の CW 品目のアップグレード機能が含まれます。 品目は、**品目の分析コード グループの変更**オプションを通じて倉庫管理プロセスに対して有効にすることができます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目
[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4jzx8) (ビデオ)


<!--docs start-->
[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)
<!--docs end-->


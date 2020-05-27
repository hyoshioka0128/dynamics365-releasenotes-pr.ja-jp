---
title: 空間マークアップを介して資産の状態をキャプチャする
description: 空間マークアップを介して資産の状態をキャプチャする
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/06/2020
ms.assetid: 4113b068-081b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: becorn
dynamics365pdf: true
ms.openlocfilehash: 67db256b6184712d9d7405d391c1d7dab8a1d826
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255334"
---
# <a name="capture-asset-condition-through-spatial-markup"></a>空間マークアップを介して資産の状態をキャプチャする
[!include[mixed-reality/dynamics365-remote-assist banner](../includes/mixed-reality/dynamics365-remote-assist.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 6 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
第一線の作業者は、必ずしも遠隔地にいるエキスパートと電話でやり取りする必要はありません。特定のインシデントの解決や、資産のインストールでの品質レビューの実行などのシナリオでは、多くの場合に独立して作業する必要があります。 これらの操作を実行するとき、特定の資産に関する空間情報をキャプチャし、その情報をビジネス プロセスに統合できるという利点があります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は、もともとは電話をかけなくても注釈をキャプチャして共有できる機能として計画されていました。 広範な顧客の学習とフィードバックに基づいて、機能の範囲を広げました。 

この機能では、Dynamics 365 Remote Assist の「アセット キャプチャ」の概念が導入され、技術者は空間マークアップを使用して、電話をかけずに検査や調査を行い、後処理のために作業を保存できるようになりました。 検査担当者は、コンテキスト内の資産調査や資産検査をハンズフリーで実行して、紙や Excel でのプロセスを改善でき、検査がより速く、安全で、正確になります。

キャプチャされたデータは Common Data Service に保存され、Dynamics 365 Field Service の検査と統合されます。 Field Service 技術者は、Dynamics 365 Remote Assist で記録された情報を作業指示書で参照できるようになるので、資産の履歴をより正確に追跡できます。

プレビューは、HoloLens 2 でのみ使用できます。
<!--feature detail end -->










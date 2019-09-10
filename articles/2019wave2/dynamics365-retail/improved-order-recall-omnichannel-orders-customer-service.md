---
title: Customer Service におけるオムニチャネル注文の注文取り消しの改善
description: Customer Service におけるオムニチャネル注文の注文取り消しの改善
author: relnotes
ms.reviewer: josaw
ms.date: 07/22/2019
ms.assetid: 7863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: 442ce70c63ae239b46c8922280cbd7a93e816ba0
ms.sourcegitcommit: 4101748c25acf79b22e31a01b73969500926ff91
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1794280"
---
# <a name="improved-order-recall-for-omnichannel-orders-in-customer-service"></a>Customer Service におけるオムニチャネル注文の注文取り消しの改善
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 9 月| 2019 年 11 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 for Retail では、複数の販売チャネル (POS、コール センター、eコマースなど) を通じて注文のキャプチャと処理を可能にするソリューションが提供されます。 複数の注文キャプチャ システムを使用している場合、顧客に注文参照データを提供するために使用される方法はそれぞれ異なります。 販売時点管理 (POS) トランザクションではレシート ID が使用され、コール センターの注文では本社シーケンスからの注文番号が使用され、eコマースの注文では異なる注文番号シーケンスが使用されます。 最終的に、これらの注文は本社に集中し、本社の注文番号が再度割り当てられます。 顧客サービスの観点からすると、今日の本社ユーザーは、トランザクション/注文が "ゲスト チェックアウト" または "顧客不明" のトランザクションとして作成された場合、本社内でトランザクションや注文を正しく見つけることが課題となっています。 

本社と POS アプリケーションの両方で、Microsoft の顧客サービスと注文検索機能を使用して、これらのさまざまな注文 ID をより見やすくし、相互参照することで、顧客サービス シナリオで問題のある注文を見つけやすくなります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は、既存の本社 (HQ) の顧客サービス ページを拡張して、顧客番号または注文番号だけでなく、レシート ID または eコマース トランザクション ID による販売注文の相互参照および簡単な検索を可能にします。

POS 注文取り消し機能も改善され、レシート ID、注文番号、または eコマース注文番号による検索が可能になります。

eコマースを改善して、お客様がその注文履歴を表示し、必要に応じてレシート番号、本社の販売注文番号、eコマースの販売注文番号を参照できるようにします。
<!--feature detail end -->












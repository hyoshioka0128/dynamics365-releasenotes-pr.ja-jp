---
title: 手持在庫サービス
description: 手持在庫サービスは、独立した非常にスケーラブルなマイクロサービスであり、Dynamics 365 Supply Chain Management の手持ち在庫情報を外部システムで利用できるようにします。これにより、外部システムとの統合が簡素化され、手持在庫情報にほぼリアルタイムでアクセスする必要がある新しいシナリオが可能になります。
author: relnotes
ms.reviewer: josaw
ms.date: 12/18/2019
ms.assetid: 7f85fc5a-ea20-ea11-a810-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: sorenand
dynamics365pdf: true
ms.openlocfilehash: 9cdcec87b145ca99f6be8e39426bc73142df758b
ms.sourcegitcommit: 9ede92eba84a02579fc8fc63e6a9673b034ce30c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2020
ms.locfileid: "2976541"
---
# <a name="inventory-on-hand-service"></a>手持在庫サービス
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 5 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
個別のマイクロサービスを通じて手持在庫情報へのほぼリアルタイムのアクセスを提供することにより、Dynamics 365 Supply Chain Management での外部システムとの統合を簡素化し、応答時間を最適化して、増分的な負荷やパフォーマンスへの影響を軽減します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
手持在庫の管理に Dynamics 365 Supply Chain Management を活用している組織は、手持在庫情報によってメリットが得られる他の外部システムを使用している場合があります。 そのような例として、外部販売ソリューションやモバイル ソリューションがあります。 他のシナリオとして、取引相手と手持在庫情報を共有することが必要な場合もあります。 

手持在庫サービスは、Dynamics 365 Supply Chain Management の負荷を増加させたりパフォーマンスを低下させたりすることなく、非常にスケーラブルかつ高パフォーマンスな方法で手持在庫情報を提供する個別のマイクロサービスです。 

手持在庫情報に関連するすべての情報は、低レベルの SQL 統合により、ほぼリアルタイムで手持在庫サービスにエクスポートされます。 外部システムは、RESTful API を介して手持在庫サービスにアクセスします。それにより、特定の分析コード セットに関する手持在庫情報を照会し、利用可能な手持在庫の位置のリストを取得することができます。

また、外部システムが手持在庫サービスを使用して手持在庫情報を更新することもできます。 これらのシナリオでは、Dynamics 365 Supply Chain Management で手持在庫の変更が (たとえば日次のインポート ジョブによって) 大幅に遅れて処理される場合でも、サービスはほぼリアルタイムで正確な手持在庫情報を維持できます。
<!--feature detail end -->









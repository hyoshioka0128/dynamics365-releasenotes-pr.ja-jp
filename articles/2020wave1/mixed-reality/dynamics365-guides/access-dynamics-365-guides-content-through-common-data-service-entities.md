---
title: Common Data Service エンティティを通じて Dynamics 365 Guides のコンテンツにアクセスする
description: Common Data Service API を使用して、Dynamics 365 Guides のコンテンツ エンティティからデジタル エンタープライズ エコシステムに簡単かつ確実に接続できます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 01/10/2020
ms.assetid: 8a64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: e9917e1345ebfbe6f8c486d9c6cd03733020f282
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986705"
---
# <a name="access-dynamics-365-guides-content-through-common-data-service-entities"></a>Common Data Service エンティティを通じて Dynamics 365 Guides のコンテンツにアクセスする
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 8 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 Guides データに簡単かつ確実にアクセスして、顧客やパートナーがそれをデジタル エンタープライズ エコシステムに接続できるようにします。  
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 Guides では、すべてのコンテンツ (命令、テキスト、写真、ビデオ、3D モデル) が Common Data Service に格納されます。 このコンテンツへのアクセスを向上させるために、コンテンツが格納されるデータ構造を定義する一連の Common Data Service エンティティにこのデータを移行しています。 顧客やパートナーは、Common Data Service API を使用して、これらのコンテンツ エンティティの読み取りと書き込み、Dynamics 365 Guides との間でのコンテンツのプッシュとプル、カスタム統合の構築を行うことができます。 たとえば、システム インテグレーターは、Dynamics 365 Guides のコンテンツを読み取って、HoloLens にアクセスできないエキスパート ワーカーのためにモバイル デバイスに表示するアプリを、Power Apps で作成できます。 
<!--feature detail end -->










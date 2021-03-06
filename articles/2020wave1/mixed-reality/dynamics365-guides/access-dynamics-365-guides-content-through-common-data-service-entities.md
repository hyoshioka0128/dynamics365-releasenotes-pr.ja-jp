---
title: Common Data Service エンティティを通じて Dynamics 365 Guides のコンテンツにアクセスする
description: Common Data Service API を使用して、Dynamics 365 Guides のコンテンツ エンティティからデジタル エンタープライズ エコシステムに簡単かつ確実に接続できます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 05/08/2020
ms.assetid: 8a64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: b217af53b5a0f4a801616b454db9331572d548c1
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548150"
---
# <a name="access-dynamics-365-guides-content-through-common-data-service-entities"></a>Common Data Service エンティティを通じて Dynamics 365 Guides のコンテンツにアクセスする


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 28 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 Guides データに簡単かつ確実にアクセスして、顧客やパートナーがそれをデジタル エンタープライズ エコシステムに接続できるようにします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 Guides では、すべてのコンテンツ (命令、テキスト、写真、ビデオ、3D モデル) が Common Data Service に格納されます。 このコンテンツへのアクセスを向上させるために、コンテンツが格納されるデータ構造を定義する一連の Common Data Service エンティティにこのデータを移行しています。 顧客やパートナーは、Common Data Service API を使用して、これらのコンテンツ エンティティの読み取りと書き込み、Dynamics 365 Guides との間でのコンテンツのプッシュとプル、カスタム統合の構築を行うことができます。 たとえば、システム インテグレーターは、Dynamics 365 Guides のコンテンツを読み取って、HoloLens にアクセスできないエキスパート ワーカーのためにモバイル デバイスに表示するアプリを、Power Apps で作成できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[Dynamics 365 Guides のエンティティ参照](https://docs.microsoft.com/dynamics365/mixed-reality/guides/developer-entity-reference) (ドキュメント)
<!--docs end-->

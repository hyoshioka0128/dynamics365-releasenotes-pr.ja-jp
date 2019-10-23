---
title: Cloud Async Client による CDX のスケーラビリティの向上
description: Cloud Async Client による CDX のスケーラビリティの向上
author: relnotes
ms.reviewer: josaw
ms.date: 08/06/2019
ms.assetid: 7c9dc757-73aa-e911-a964-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: c6e924fa9b9fe71fc039d19f470241b42e58e243
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141967"
---
# <a name="improved-cdx-scalability-through-cloud-async-client"></a>Cloud Async Client による CDX のスケーラビリティの向上
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Commerce Data Exchange (CDX) は、チャネル データベースとオフライン データベースに対して重要なビジネス データを生成、提供、ダウンロード、適用する重要なプロセスです。 この目に見えないコア アーキテクチャは不可欠であり、高速かつ効率的に機能する必要があります。 この機能では、Async Client を本社から移行して、Azure の能力を最大限に活用できるようにします。 この機能は、CDX アーキテクチャのスケーラビリティ、パフォーマンス、可用性を向上して、データをより迅速に生成し、より効率的に提供し、オフライン データベース用の Modern POS 内の Async Clients またはチャネル データベースへの帯域幅を強化します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
CDX は、直接には本部の一部ではなくなります。 これを独自の Azure サービスに拡張することで、競合するリソースがなくなります。 代わりに、背後で Azure の完全なスケーラビリティとメリットが発揮され、現在および将来の最大限の改善が可能になります。
<!--feature detail end -->




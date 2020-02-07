---
title: レポートおよび Web サービス呼び出しに対するリソースの制限
description: Business Central インストールのリソースを保護するために、レポートおよび SOAP Web サービス呼び出しの最大実行時間に制限を構成できるようになりました
author: relnotes
ms.reviewer: jswymer
ms.date: 12/16/2019
ms.assetid: 075dbe76-ea1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 2ab4cdfd5c47e935f680426f99d8a27ebe58fa27
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986655"
---
# <a name="resource-limits-for-reports-and-web-service-calls"></a>レポートおよび Web サービス呼び出しに対するリソースの制限
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
誤って設定された Web サービス メソッドが実行されている場合や、ユーザーが誤ってフィルターなしでレポートを開始した場合でも、他のユーザーが作業できるようにします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central Server には、管理者がレポートおよび SOAP Web サービスの呼び出し実行時間を制限できる新しい設定が用意されています。 この制限に達すると、サーバーの操作がキャンセルされます。

Business Central online (サービスとしてのソフトウェア) では、既定値は Business Central 運用チームによって設定され、顧客やパートナーがそれを上書きすることはできません。 2020 年リリース ウェーブ 1 では、既定値は数時間に設定されます (実際の値は未定です)。

Business Central (オンプレミス) の場合、管理者がサーバーの設定を制御できます。
<!--feature detail end -->










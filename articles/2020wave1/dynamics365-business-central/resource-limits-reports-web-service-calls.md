---
title: レポートおよび Web サービス呼び出しに対するリソースの制限
description: Business Central インストールのリソースを保護するために、レポートおよび SOAP Web サービス呼び出しの最大実行時間に制限を構成できるようになりました
author: relnotes
ms.reviewer: jswymer
ms.date: 04/15/2020
ms.assetid: 075dbe76-ea1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 5e9709ea04b6bdff36f3c5cf9ffa085a313226db
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273700"
---
# <a name="resource-limits-for-reports-and-web-service-calls"></a>レポートおよび Web サービス呼び出しに対するリソースの制限


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


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










## <a name="see-also"></a>関連項目

<!--docs start-->
[Business Central Server の構成](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/configure-server-instance?) (ドキュメント)
<!--docs end-->

---
title: レポートおよび Web サービス呼び出しに対するリソースの制限
description: Business Central インストールのリソースを保護するために、レポートおよび SOAP Web サービス呼び出しの最大実行時間に制限を構成できるようになりました
author: relnotes
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: 075dbe76-ea1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 3c813481f4232599ba53124be8fa890f5ce6d872
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232684"
---
# <a name="resource-limits-for-reports-and-web-service-calls"></a>レポートおよび Web サービス呼び出しに対するリソースの制限
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|2020 年 4 月| 2020 年 4 月|


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


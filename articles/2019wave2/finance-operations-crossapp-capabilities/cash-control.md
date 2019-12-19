---
title: 現金管理
description: 現金管理では、利用可能な現金残高がない場合、またはトランザクションによって残高が定義した限度額を下回った場合に追加のトランザクションが転記されないようにする、その限度額を定義できます。
author: relnotes
ms.reviewer: roschlom
ms.date: 11/15/2019
ms.assetid: 2e7ce836-03d1-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: bcc5402a0d15406d6b065264a65036f01dbcddfd
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893910"
---
# <a name="cash-control"></a>現金管理


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 5 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、現金支出をさらに制御できるようになるほか、ビジネス ニーズに合理的に対応するための柔軟性が提供されます。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
買掛金勘定仕入先請求書および一般会計の詳細な元帳エントリは、作成、編集、および転記時に検証されます。 トランザクションの転記が原因で、関連する現金勘定の残高がその勘定に定義されている限度額を下回ると、エラー メッセージが表示され、続行するにはユーザーが勘定を変更する必要があります。

特定のユーザーが現金管理を上書きできるようにすることもできます。 許可されたユーザーが、勘定の現金残高が限度額を下回るという警告を受けた場合、そのユーザーはトランザクションの転記を続行できます。 たとえば、経費をカバーするための資金を受け取る前にその経費を転記する必要がある場合、または承認された送金が行われる必要があるがまだ入力も転記もされていない場合、ユーザーは現金管理限度額を上書きできます。

現金管理限度額は、現金管理残高 (現金勘定残高からすべての転記済み未払い AP 請求書を差し引いたもの) と比較されます。 現金管理残高が現金管理限度額 (しきい値) を下回ると、限度額を超過します。

<!--feature detail end -->










## <a name="see-also"></a>関連項目

[現金管理限度を使用する](https://docs.microsoft.com/dynamics365/unified-operations/financials/public-sector/cash-control) (ドキュメント)

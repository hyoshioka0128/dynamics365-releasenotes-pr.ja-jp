---
title: 場所のディレクティブ在庫ピッキング エイジング
description: 2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/06/2020
ms.assetid: 8262278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e21848902363fd9a5b154aa7193c3249ad2e1fde
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947980"
---
# <a name="location-directive-inventory-picking-aging"></a>場所のディレクティブ在庫ピッキング エイジング


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 4 月 8 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 12 月 19 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。 これらの戦略を、バッチと非バッチの両方の追跡対象品目、および在庫が倉庫に入った時期に基づいて顧客に品目を出荷するのに使用できます。 これは、有効期限がソートに使用できない非バッチの追跡対象在庫に対して特に便利です。 

在庫が倉庫内に最初に入庫または作成されたときに、現在の日付がエイジング日付として入力されてライセンス プレートが更新されます。 その後、この日付は、戦略で倉庫内の最も古い在庫または最も新しい在庫を特定するために使用されます。 在庫がライセンス プレートによる追跡対象でない場所に移動された場合、その場所自体がエイジング日付を反映して更新され、戦略でも使用されます。
<!--feature detail end -->






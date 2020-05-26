---
title: 技術者の時間キャプチャの精度
description: より正確なタイムスタンプ キャプチャを構成する機能。
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/20/2020
ms.assetid: 0ff76893-45cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: 02f845618384c246d5692c291e04754243ffedf7
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294019"
---
# <a name="technician-time-capture-precision"></a>技術者の時間キャプチャの精度


| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 Field Service では、基になる Field Service の状態が変更になったときの、予約タイムスタンプのキャプチャがサポートされています。 ただし、多くの顧客は、予約状態の変更について、より細かい頻度でタイムスタンプをキャプチャする必要があります。 顧客はこの機能により、原価計算の精度を高め、各予約と作業指示書のタイミングをより深く理解し、その他の拡張シナリオを推進できます。    これが、Field Service の構成を介してサポートされるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Field Service でこの構成設定が導入されたことで、Field Service の顧客の実装を簡素化し、顧客が作業の実施時にどの程度の詳細を収集するかを柔軟に決定できるようになりました。

これには次のものが含まれます。

- Field Service の設定で、予約ごとにタイムスタンプが収集される頻度を定義します。
- 予約ステータスの変更がモバイル デバイスまたは Web ブラウザーのいずれで行われたかにかかわらず、システムでその設定を適用できるようにします。
- 関連するタイムスタンプの適切な詳細をキャプチャします。
- 時間入力がタイムスタンプから作成された場合、時間入力が組織の設定に応じて適切な詳細レベルを保持していることを確認します。
<!--feature detail end -->


> [!NOTE]
> この機能は、統一インターフェイスでのみ使用できます。







## <a name="see-also"></a>関連項目

<!--docs start-->
[タイムスタンプの頻度の設定](https://docs.microsoft.com/dynamics365/field-service/booking-timestamps#timestamp-frequency-setting) (ドキュメント)
<!--docs end-->

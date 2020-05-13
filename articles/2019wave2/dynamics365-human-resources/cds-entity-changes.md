---
title: Common Data Service エンティティの変更
description: HCM Common ソリューションの Human Resources エンティティが更新され、Common Data Service での追跡用の新しいフィールドが追加されました。 追加のエンティティも利用できます。 これらのフィールドを更新すると、通常のプロセスの一部として Human Resources と同期されます。
author: relnotes
ms.reviewer: anbichse
ms.date: 04/15/2020
ms.assetid: d9810a84-9152-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: dkrame
dynamics365pdf: true
ms.openlocfilehash: e1c13773f54fc04c15d76c7a319f4c35c9c8acc3
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320371"
---
# <a name="common-data-service-entity-changes"></a>Common Data Service エンティティの変更


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 5 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 5 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この新機能により、Human Resources 全体のケース データを新しいビューで見ることができます。 これらの機能拡張により、分析のためにすべてのケース データをインポートおよびエクスポートするオプションも利用できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
| 説明 | 変更 |
| --- | --- |
| **役職**エンティティの変更 | <ul><li>**報酬地域**の追加</li>|
| **役職分析コード** エンティティの追加 | <ul><li>**財務分析コード**の追加</li>
| **作業者**エンティティの変更 | <ul><li>**名前の順序**の追加</li><li>**在宅勤務**の追加</li><li>**言語**の追加</li><li>**勤続日数**の追加</li><li>**記念日**の追加</li><li>**初回入社日**の追加</li></ul> |
| **雇用**エンティティの変更 | <ul><li>**財務分析コード**の追加</li><li>**退職理由**の追加</li><li>**退職日**を**移行日**に改名</li><li>**仮採用日**の追加</li></ul> |
| **作業者住所**エンティティの変更 | <ul><li>**番地**の追加</li><li>**住所 1**、**住所 2**、および**住所 3** を非推奨としてマーク</li></ul> |
| 新しい変動報酬設定エンティティ | <ul><li>**変動報酬プラン タイプ**</li><li>**変動報酬プラン**</li><li>**給付ルール**</li><li>**変動報酬プラン レベル**</li></ul> |
| 新しい**作業者カレンダー雇用**エンティティ | <ul><li>**作業カレンダー エンティティ**の追加</li></ul> |
| 新しい**給与職位詳細**エンティティ | <ul><li>**給与職位詳細**の追加</li></ul> |
| 新しい**肩書き**エンティティ | <ul><li>**肩書き**の追加。 新しい**肩書き**エンティティは Common Data Service に含まれていますが、最初は**役職**または**ジョブ エンティティ**から参照されません。</li></ul> |
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[Common Data Service エンティティ](https://docs.microsoft.com/dynamics365/human-resources/hr-developer-entities) (ドキュメント)
<!--docs end-->

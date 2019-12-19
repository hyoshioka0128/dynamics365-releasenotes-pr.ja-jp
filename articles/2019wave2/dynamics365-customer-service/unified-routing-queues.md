---
title: エンティティ レコードの統合ルーティング
description: 統合ルーティングとキュー
author: relnotes
ms.reviewer: kabala
ms.date: 11/15/2019
ms.assetid: 1062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: karthig
dynamics365pdf: true
ms.openlocfilehash: 652d583ed4c8e20602f122691efc00e72ab412f6
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893470"
---
# <a name="unified-routing-for-entity-records"></a>エンティティ レコードの統合ルーティング


| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 31 日|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 25 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
現在、Dynamics 365 の顧客サービス サポート案件ルーティングにより、組織は静的なキューにサポート案件をルーティングできます。 これらのサポート案件は、スーパーバイザーが手動で配分するか、エージェントが手動で選択します。 統合ルーティングを使用することで、チャットや SMS などの他のチャネルから発信された作業項目とともに、オムニチャネル対応キューにサポート案件をルーティングできるようになりました。 
 
> [!NOTE]
> オムニチャネルは既存の CDS キュー エンティティを活用します。サポート案件または他のエンティティ用のキューを既に設定している場合は、オムニチャネル作業配分でそのキューを引き続き使用できます。
 
これにより、組織はエージェントが対処する作業プロファイルを厳密に定義でき、チャネルにまたがるワークフローの割り当てを自動化し、エージェントの能力、空き時間、スキルに基づいて作業項目を割り当てることができます。
 
この統合された顧客サービス ルーティングは、カスタム エンティティやその他のすぐに使えるエンティティなど、任意のアクティビティ対応の CDS エンティティ レコードに対しても適用されます。
 
エージェントは、同じマルチセッション エクスペリエンスである顧客サービス用のオムニチャネル アプリを使用して、これらのエンティティ レコード作業項目を、チャットや SMS などの他のチャネルから発信された作業項目と一緒に処理できます。
 
> [!NOTE]
> 現在、Dynamics 365 ポータルを使用することで、サポート案件を作成してサポートを要求できるようになりました。 統合ルーティングを使用すると、ポータルから発信されるこれらのサポート作業項目を、空いている最適なエージェントにルーティングし、自動的に割り当てることができます。

> [!NOTE]
> サポート案件エンティティ レコードのルーティングは、パブリック プレビュー リリースで利用できます。 他のエンティティ レコードのルーティングは、GA (一般提供) リリースで利用可能になります。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[エンティティ レコードのルーティング](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/administrator/entity-channel) (ドキュメント)

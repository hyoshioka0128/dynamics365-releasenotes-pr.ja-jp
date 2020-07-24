---
title: サンドボックス環境のバックアップ保持ポリシーを 14 日に変更
description: バックアップ保持ポリシーと実践を Dynamics 365 と Power Platform 製品ラインの間で調整するために、Finance and Operations サンドボックス環境では、保持する自動バックアップが過去 30 日ではなく 14 日に短縮されます。
author: relnotes
ms.reviewer: sericks
ms.date: 06/05/2020
ms.assetid: 060d63ae-e58e-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: c21f5f03530832736fb68e774fdcfe6dab0ea411
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548414"
---
# <a name="backup-retention-policy-for-sandbox-environments-changed-to-14-days"></a>サンドボックス環境のバックアップ保持ポリシーを 14 日に変更
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 6 月 4 日| 2020 年 8 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 および Microsoft Power Platform 製品ライン内の複数製品の利用を開始するお客様が増えているため、Finance and Operations サンドボックスを Customer Engagement、Common Data Service、またはその他の Dynamics 365 タイプの環境より前の環境に復元する機能により、解決されるよりも多くの課題が生じます。  これは保持期間を 30 日間から 14 日間に短縮する最初のステップであり、今後、過去 14 日間から 7 日間に短縮する発表が行われます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
サンドボックス環境でポイントインタイム リストア アクションを実行して、データベースを以前の特定の時点に戻すお客様は、最大で過去 14 日間に制限されるようになります。  過去 14 日より前の日付の選択は禁止されます。  警告は、これらのアクションを実行しているユーザーの Lifecycle Services にも追加されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[データベース ポイントインタイム復元 (PITR)](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/database-point-in-time-restore) (ドキュメント)
<!--docs end-->

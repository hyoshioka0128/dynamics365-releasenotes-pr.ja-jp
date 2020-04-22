---
title: Tier 2-5 スタンダード承認テスト (サンドボックス) 環境へのリモート デスクトップ アクセスの除去
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 04/02/2020
ms.assetid: 7b7ebaba-8d74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: e2b7eb3913fc1c6cb651702bf17e76b524843d79
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219702"
---
# <a name="removing-remote-desktop-access-to-tier-2-5-standard-acceptance-test-or-sandbox-environments"></a>Tier 2-5 スタンダード承認テスト (サンドボックス) 環境へのリモート デスクトップ アクセスの除去
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 4 月| 2020 年 9 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
すべての診断、トラブルシューティング、パフォーマンス、テスト活動をセルフサービスに移行すること、および、お客様とパートナーからのインフラストラクチャ アクセスの制限によって全体的なセキュリティを強化することを目的に、完全なリモート デスクトップ アクセスの除去に向けた 2 段階のアプローチを取ります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
プレビューの一環として、Tier 2-5 サンドボックス環境への管理者アクセスを除去します。 新しい環境は、現在の Tier 1 環境と同様に、管理者以外のユーザー資格情報のみを受け入れます。  

GA (一般提供) では、お客様は Microsoft サブスクリプションに展開された Tier 2-5 サンドボックス環境への RDP アクセスができなくなります。 現在、お客様とパートナーは運用環境への RDP アクセスはできませんが、Microsoft サブスクリプションに展開された Tier 2-5 サンドボックス環境にリモート アクセスすることはできます。 

今後は、運用環境で実行される操作の安定性と信頼性を向上させ、Tier 2-5 サンドボックス環境が運用環境を模倣できるようにするために、これらの環境への RDP アクセス全体を制限します。 アクセスを制限する前に、これらの環境での、お客様がリモート アクセスを使用する必要があるすべてのプロセスを自動化します。
<!--feature detail end -->










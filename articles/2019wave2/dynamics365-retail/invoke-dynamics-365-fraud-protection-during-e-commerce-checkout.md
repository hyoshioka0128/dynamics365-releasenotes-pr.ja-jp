---
title: eコマース チェックアウト時に Dynamics 365 Fraud Protection を呼び出す
description: 初めて Dynamics 365 Fraud Protection とそのまま統合できるようになったことで、eコマース チェックアウト フローに詐欺防止ロジックをそのまま統合できるようになりました。
author: relnotes
ms.reviewer: josaw
ms.date: 10/02/2019
ms.assetid: 5539f1c8-16e2-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 4882a8ad292620a09d4cd75544248b3412f9e698
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659817"
---
# <a name="invoke-dynamics-365-fraud-protection-during-e-commerce-checkout"></a>eコマース チェックアウト時に Dynamics 365 Fraud Protection を呼び出す
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 11 月| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、Dynamics 365 Commerce を使用したすぐに使用できる詐欺防止オプションを小売店に提供します。 そのまま使用できる Commerce 製品を使用する場合でも、SDK を通じてサード パーティのストアフロントと統合する場合でも、認証のために送信される前にクレジット カード トランザクションの詐欺についてチェックするオプションが用意されています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、トランザクションが認証のために送信される前に、Fraud Protection によってリスクが評価されるようにすることで、Dynamics 365 Fraud Protection との基本的な統合をもたらします。 アダプティブ AI 技術を使用することで、継続的に更新される詐欺モデルに対してトランザクションがチェックされ、eコマース トランザクションの不当な拒否と試行回数を減らします。 将来の毎月の更新プログラムにより、Commerce と Fraud Protection の統合がさらに強化されます。
<!--feature detail end -->










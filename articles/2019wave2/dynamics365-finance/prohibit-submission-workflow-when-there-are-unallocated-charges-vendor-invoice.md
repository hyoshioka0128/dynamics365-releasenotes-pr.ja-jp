---
title: 仕入先請求書に配賦されていない費用がある場合は、ワークフローへの送信を禁止する
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 12/09/2019
ms.assetid: 40f67ec2-cce3-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 8df0fef6c6ec6eb7ea33c3705600838657fca606
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2910228"
---
# <a name="prohibit-submission-to-workflow-when-there-are-unallocated-charges-on-a-vendor-invoice"></a>仕入先請求書に配賦されていない費用がある場合は、ワークフローへの送信を禁止する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 25 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 11 月 26 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
請求書がワークフローに送信される前に問題を見つけることは、転記を中止し仕入先請求書をワークフローに再送信する必要が生じるエラーを防ぐのに役立ち、結果的に送信者と承認者の時間を節約します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、配賦されていない費用が仕入先請求書に含まれている場合に、仕入先請求書がワークフロー プロセスに送信されるのを防ぐことができます。 代わりに、請求書の送信者は、配賦されていない費用が請求書に含まれているという通知を受け取り、ワークフローに送信する前に修正するよう求められます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[10.0.5 での買掛金勘定の変更](https://community.dynamics.com/365/financeandoperations/b/financials/posts/accounts-payable-changes-in-10-0-5) (ブログ)



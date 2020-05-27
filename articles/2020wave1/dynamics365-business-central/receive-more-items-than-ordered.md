---
title: 注文量よりも多くの商品を受け取る
description: 注文数量に対する入庫数量について指定された許容範囲に基づいて、発注書と倉庫の超過入庫を許可します。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/06/2020
ms.assetid: 7c144f9f-4aca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 29ea96cf7973c24146fc8ca2a6b7b713259d63f2
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255873"
---
# <a name="receive-more-items-than-ordered"></a>注文量よりも多くの商品を受け取る


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
注文量よりも多くの商品を受け取り、そのような商品の価格が安く、返品しないか、仕入先が割引サービスを提供する場合、注文処理担当者と倉庫作業者は、新しい発注書の準備と承認を得る長いプロセスを経ることなく、そのような受け入れを処理できることが必要です。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
**超過入庫コード** ページで設定した超過入庫ポリシーに従って、発注書の注文数量よりも多い数量を受け取ることができるようになりました。 ここで**超過入庫許容率**フィールドに入力し、デフォルトで使用されるポリシーを選択できます。 

会社で発注書の承認を使用している場合、超過入庫により再承認がトリガーされる可能性があります。 これは、**超過入庫コード** ページで定義します。 **超過入庫の承認**ワークフローの応答は、この目的のためにワークフロー エンジンで使用できます。
 
商品や仕入先のカードの**超過入庫コード** フィールドで、購入時にデフォルトで使用されるフィールドを選択できます。
 
超過入庫コードを選択したら、リリース済みの発注書と倉庫入庫の**入庫する数量**フィールドに、注文数量よりも多い数量を入力できます。
<!--feature detail end -->

![超過入庫許容率フィールドがハイライトされた超過入庫コードの表示](media/over-receipt-codes.png "超過入庫許容率フィールドがハイライトされた超過入庫コードの表示")
<!-- Picture 1 -->
![発注書明細行での超過入庫の表示](media/over-receipt-purch-order.png "発注書明細行での超過入庫の表示")
<!-- Picture 2 -->





## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。



## <a name="thank-you-for-your-idea"></a>アイデアをありがとうございます
[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=7c83f7d7-8763-e911-b047-0003ff68b7ef)をお送りいただき、ありがとうございました。 アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。

## <a name="see-also"></a>関連項目

<!--docs start-->
[商品の受け取り](https://docs.microsoft.com/dynamics365/business-central/warehouse-how-receive-items) (ドキュメント)
<!--docs end-->

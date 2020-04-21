---
title: トランザクション メール用の新しいイベントとプレースホルダー
description: この機能では、オンラインで購入する顧客に対するトランザクション メールをトリガーするための新しいイベントと拡張機能が提供されます。
author: relnotes
ms.reviewer: josaw
ms.date: 03/17/2020
ms.assetid: 232005e9-451d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: stuharg
dynamics365pdf: true
ms.openlocfilehash: 55c4e7737b0d44366c532e1b1b3391aabb232f07
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3153884"
---
# <a name="new-events-and-placeholders-for-transactional-emails"></a>トランザクション メール用の新しいイベントとプレースホルダー
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 4 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
オンラインや店舗受け取りで購入する顧客は、トランザクション中の重要なイベントに関するメール通知を受け取ることを期待しています。 これらのイベントには、注文の確認、注文の店舗受け取り準備の完了を知らせる通知、出荷の確認などが含まれます。 また、トランザクション通知は、注文に関するタイムリーで有用なフィードバックを送信して顧客に働きかける機会を小売業者に提供します。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
### <a name="transactional-events"></a>トランザクション イベント

このリリースでは、小売業者は、注文の店舗受け取り準備が完了したときと注文が出荷されたときに顧客にメールを自動送信できます。

| **イベント**                        | **説明**                                              |
| -------------------------------- | ------------------------------------------------------------ |
| 注文の店舗受け取り準備完了 | modeofdelivery が "顧客による受け取り" に設定されている注文が梱包済としてマークされたときにトリガーされます。 |
| 注文出荷済                    | modeofdelivery が "標準" の注文が請求されたときにトリガーされます。 |


### <a name="new-placeholders"></a>新しいプレースホルダー

より充実した情報量の多い顧客向けメールを作成するために、追加のプレースホルダーも HTML メール テンプレートで利用可能になります。 

 
**ヘッダー**

| **プレースホルダー名** | **プレースホルダーの説明**                                  |
| -------------------- | ------------------------------------------------------------ |
| %ordernetamount%     | 割引、課税前金額、送料、またはギフト カード控除の適用を含めた注文の小計。 |
| %storename%          | 店舗受け取り用の小売店の名前。               |

 
**明細行**

| **プレースホルダー名**              | **プレースホルダーの説明**                                  |
| --------------------------------- | ------------------------------------------------------------ |
| %productid%                       | 製品の ID。 この ID を使用して、eコマース サイトの製品説明ページを開く URL を構築することができます。 |
| %linequantity_withoutunit%        | 測定単位 (UOM) が追加されていない製品の数量。 |
| %linequantitypicked_withoutunit%  | UOM なしの受け取り製品の数量。                    |
| %linequantitypacked_withoutunit%  | UOM が追加されていない梱包済製品の数量。 このプレースホルダーを ‘注文の受け取り準備完了’ イベントと共に使用して、受け取り準備が完了した数量 (注文された数量と異なる場合があります) を示します。 |
| %linequantityshipped_withoutunit% | UOM なしの出荷済数量。 このプレースホルダーを ‘注文出荷済’ イベントと共に使用して、実際に出荷された数量 (注文された数量と異なる場合があります) を示します。 |
<!--feature detail end -->










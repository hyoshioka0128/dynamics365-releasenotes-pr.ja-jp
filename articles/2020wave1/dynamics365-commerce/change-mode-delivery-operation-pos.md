---
title: POS の荷渡方法の変更操作
description: この機能では、POS トランザクションの 1 つ以上の明細行の荷渡方法をユーザーが更新できる、新しいオプションの販売時点管理 (POS) 操作が提供されます。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: a56ceb94-4711-ea11-a811-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: ad0ea827b8c6b3990effcf6455ecffc42084a278
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232570"
---
# <a name="change-mode-of-delivery-operation-for-pos"></a>POS の荷渡方法の変更操作
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 24 日| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
小売業者は、顧客注文明細行の荷渡方法を明細行のフルフィルメントの前にいつでも個別に変更できる柔軟性を求めています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
販売時点管理 (POS) 画面レイアウトに**荷渡方法の変更**を追加できます。 これは、POS での注文作成に "すべて出荷" または "選択された出荷" 方法を使用して以前に構成された明細行に対してのみ適用されます。 トランザクション明細行に対して元の荷渡方法が設定された後に、ユーザーが "すべて出荷" または "選択された出荷" フロー全体を経ずに 1 つ以上の対象明細行の荷渡方法を変更したくなる場合があります。 この荷渡方法操作は、そのような利便性を提供します。 これは POS 顧客注文の最初の注文作成処理時か、顧客注文の編集時に使用できます。 出荷明細行として構成されていない明細行には適用できず、フルフィルメントに既にリリースされた明細行や請求済みの明細行に対しては機能しません。
<!--feature detail end -->










## <a name="see-also"></a>関連項目


<!--docs start-->
[POS での荷渡方法の変更](https://docs.microsoft.com/dynamics365/commerce/pos-change-delivery-mode) (ドキュメント)
<!--docs end-->


---
title: POS の荷渡方法の変更操作
description: この機能では、POS トランザクションの 1 つ以上の明細行の荷渡方法をユーザーが更新できる、新しいオプションの販売時点管理 (POS) 操作が提供されます。
author: hhainesms
ms.reviewer: josaw
ms.date: 02/18/2020
ms.assetid: a56ceb94-4711-ea11-a811-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 5ceadc7fc94165033610e441cdecde96c0b9cdf4
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080685"
---
# <a name="change-mode-of-delivery-operation-for-pos"></a>POS の荷渡方法の変更操作
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 2 月| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
小売業者は、顧客注文明細行の荷渡方法を明細行のフルフィルメントの前にいつでも個別に変更できる柔軟性を求めています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
POS 画面レイアウトに**荷渡方法の変更**を追加できます。 これは、POS で以前に "すべて出荷" または "選択された出荷" 注文作成方法を使用して構成された明細行に対してのみ適用されます。 トランザクション明細行に対して元の荷渡方法が設定された後に、ユーザーが "すべて出荷" または "選択された出荷" フロー全体を経ずに 1 つ以上の対象明細行の荷渡方法を変更したくなる場合があります。 この荷渡方法操作は、そのような利便性を提供します。 これは POS 顧客注文の最初の注文作成処理時か、顧客注文の編集時に使用できます。 出荷明細行として構成されていない明細行には適用できず、フルフィルメントにリリース済みの明細行や請求済みの明細行に対しては機能しません。  
<!--feature detail end -->










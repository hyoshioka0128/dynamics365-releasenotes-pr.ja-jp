---
title: 同じ行に同じ型の変数を複数宣言する
description: 同じ行に同じ型の変数を複数宣言する
author: relnotes
ms.reviewer: solsen
ms.date: 12/12/2019
ms.assetid: 98be7068-dc1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 25dcaf7b391e49caca02b5266a10cd6e040714ce
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986660"
---
# <a name="multiple-variable-declarations-of-the-same-type-in-the-same-line"></a>同じ行に同じ型の変数を複数宣言する
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
これまでは各変数をそれぞれの行で宣言する必要がありました。 このため大規模なオブジェクトでは、ほとんどが同じ型の場合でも、何ページにもわたる変数の宣言が必要でした。

スクロールを減らし、読みやすさを改善し、関連する型の表示と宣言を簡単にするため、同じ型の複数の変数宣言を 1 行で追加できるようになりました。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
コンマを使用して変数名を区切り、同じ行で同じ型の変数を複数宣言します。 たとえば、"foo, bar : Integer;" のようにします。
<!--feature detail end -->










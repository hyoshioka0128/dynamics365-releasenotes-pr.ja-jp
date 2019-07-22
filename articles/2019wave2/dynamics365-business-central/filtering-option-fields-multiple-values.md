---
title: 複数の値によるオプション フィールドのフィルター処理
description: 複数のオプション値でのフィルター処理は、リストやレポートでの強力なフィルター処理機能を補完します。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 07/01/2019
ms.assetid: 823f20c6-e26b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ba35b04cfeabb0ef1cefa6f1ed6604700cbc18d6
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722622"
---
# <a name="filtering-option-fields-by-multiple-values"></a>複数の値によるオプション フィールドのフィルター処理
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、自動的|2019 年 9 月| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
バックオフィスのインフォメーション ワーカーは、リストやレポートを処理し、フィルターを適用してデータを関連するレコードに絞り込む作業に、多くの時間を費やします。 ビジネス データベースのサイズが大きくなるにつれて、ユーザーはより高度な制御を必要とすることが多くなります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
オプション フィールドは基本的に定義済みの値を持つ列挙です。 これまで、ユーザーはオプション フィールドでフィルターを設定するときに 1 つの値しか選択できませんでした。 このウェーブでは、ユーザーが複数の値でフィルター処理できるように、新しい複数選択コントロールが導入されました。 これは OR 演算として扱われます。 たとえば、**色**フィールドを赤、緑、または青でフィルター処理できます。 値の複数選択を使用できるのはフィルター処理のときだけであり、レコードでフィールド値を指定するときは使用できません。
<!--feature detail end -->











---
title: 複数の値によるオプション フィールドのフィルター処理
description: 複数のオプション値でフィルター処理することで、リストやレポートでの強力なフィルター処理機能を補完します。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 10/01/2019
ms.assetid: 823f20c6-e26b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 640d541e8d2f89d89e8c0378fe37f4fef8c52ac7
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667083"
---
# <a name="filter-option-fields-by-multiple-values"></a>複数の値によるオプション フィールドのフィルター処理


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
バックオフィスのインフォメーション ワーカーは、リストやレポートを処理し、フィルターを適用してデータを関連するレコードに絞り込む作業に、多くの時間を費やします。 ビジネス データベースのサイズが大きくなるにつれて、ユーザーはより高度な制御を必要とすることが多くなります。 オプション フィールドは基本的に定義済みの値を持つ列挙型です。 これまで、ユーザーはオプション フィールドでフィルターを設定するときに 1 つの値しか選択できませんでした。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
このウェーブでは、ユーザーが複数の値でフィルター処理できるように、タイプが**オプション**のフィールドのフィルターに新しい複数選択コントロールが導入されました。 これは OR 演算として扱われます。 たとえば、**色**フィールドを赤、緑、または青でフィルター処理できます。

複数の値によるオプション フィールドのフィルター処理は、リスト ページ、レポート、XmlPorts、および RunRequestPage コマンドや FilterPageBuilder コマンドによって駆動されるフィルター画面でのフィルター操作全体で一貫して使用できます。 値の複数選択を使用できるのはフィルター処理のときだけであり、レコードでフィールド値を指定するときは使用できません。

![複数のオプション値によるフィルターを含む、アイテム リストのフィルターのスクリーンショット](media/filtering-multiple-option-values.png "複数のオプション値によるフィルターを含む、アイテム リストのフィルターのスクリーンショット")
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目
[機能の探索](https://aka.ms/ROGBC19RW2ROV6) (ビデオ)

[オプション フィールドを使用したフィルター処理](https://docs.microsoft.com/dynamics365/business-central/ui-enter-criteria-filters#filtering-with-option-fields) (ドキュメント)

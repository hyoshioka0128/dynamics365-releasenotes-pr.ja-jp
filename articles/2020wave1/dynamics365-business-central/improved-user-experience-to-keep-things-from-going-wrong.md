---
title: 間違った方向に進まないようにするためのユーザー エクスペリエンスの向上
description: 潜在的な問題を発生前に指摘するビジュアル インジケーターがある Business Central を使用できるようになりました。
author: relnotes
ms.reviewer: edupont
ms.date: 06/23/2020
ms.assetid: bde2e299-ae99-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 2d365cc71744334692544c8f9cd917631c75fc47
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522799"
---
# <a name="improved-user-experience-to-keep-things-from-going-wrong"></a>間違った方向に進まないようにするためのユーザー エクスペリエンスの向上


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 6 月 19 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ドキュメントまたは仕訳帳の処理中に発生する可能性のある問題を示す初期の視覚的手掛かりと控えめなインジケーターにより、生産性を向上させることができます。 問題が最も頻繁に発生する場所を示す製品テレメトリに基づいて、問題を発生前に回避するのに役立ついくつかのことを行いました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
### <a name="document-status"></a>ドキュメント状態

ドキュメントの状態を簡単に認識できるようにして編集可能かどうかがわかるようにするために、販売注文や発注書などのドキュメントの**状態**フィールドをレベル上げおよび色分けしました。  

![レベル上げされて条件付きで書式設定された販売注文の状態フィールドのビュー](media/document-status.png "レベル上げされて条件付きで書式設定された販売注文の状態フィールドのビュー")

### <a name="reverse-register"></a>登録の取り消し

**G/L 登録**ページの**登録の取り消し**アクションはコンテキスト対応になったため、選択した G/L 登録を取り消せる場合にのみ使用できます。 反対に、[登録の取り消し] アクションを使用して指定された G/L 登録を取り消せない場合は使用できません。 

![G/L 登録ページで無効になっている登録の取り消しアクションのビュー](media/reverse-register.png "G/L 登録ページで無効になっている登録の取り消しアクションのビュー")

### <a name="document-line-actions"></a>ドキュメント明細行アクション

販売注文や発注書などのドキュメントに対する品目の在庫状態、品目の追跡などの明細行アクションは、コンテキスト対応になりました。 たとえば、選択した発注書明細行のタイプが**リソース**、**品目料金の割り当て**、または**繰り延べスケジュール**の場合、アクションは、**品目**、**G/L 勘定**、および**発注書**明細タイプにのみ適用されるため使用できません。 

![コンテキストにより無効になっている発注書明細行アクションのビュー](media/document-line-actions.png "コンテキストにより無効になっている発注書明細行アクションのビュー")

### <a name="mandatory-fields-on-journals"></a>仕訳帳の必須フィールド

一般仕訳帳などの仕訳帳の**ドキュメント番号**および**転記日付**フィールドには、仕訳帳を転記する前に特定のフィールドに入力する必要があることを示す赤いアスタリスク (\*) が表示されるようになりました。 仕訳帳により多くの、またはより少ない列が表示されている場合にも同じことが適用されます。 

![必須のアスタリスクが表示されている一般仕訳帳明細行のドキュメント番号の表示](media/mandatory-field-journal.png "必須のアスタリスクが表示されている一般仕訳帳明細行のドキュメント番号の表示")
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[データを入力する](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (ドキュメント)
<!--docs end-->

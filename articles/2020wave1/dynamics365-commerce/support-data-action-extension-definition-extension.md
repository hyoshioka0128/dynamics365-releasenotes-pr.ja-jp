---
title: 定義の拡張機能でのデータ アクション拡張機能のサポート
description: Dynamics 365 online SDK でモジュールを拡張する際、モジュール定義によってすべての拡張する構成、リソース、スロットを拡張できますが、データ アクションは拡張できません。 今回、データ アクションを拡張するためのサポートが追加されます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/30/2020
ms.assetid: e5e611f6-b059-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: samjar
dynamics365pdf: true
ms.openlocfilehash: b616bc4ba8b4bcd81b1ea7ceaa284d069fec41c5
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350916"
---
# <a name="support-data-action-extension-in-definition-extension"></a>定義の拡張機能でのデータ アクション拡張機能のサポート
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 9 月| 近日発表|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
テーマ開発者は、テーマ内の特定のモジュールに使用されるデータ アクションを変更したい場合があります。 現在これを行うには、モジュール全体を複製する必要があるため、モジュールのサービス性が失われます。 このサポートの追加により、モジュールのデータ アクションのみを変更するコストが大幅に削減されます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
モジュール定義拡張機能のサポートにより、データ アクションをモジュール定義ファイルに追加できるようになりました。 追加されると、定義ファイルで設定された設定に応じて、サーバー側またはクライアント側で実行されます。 モジュール ビュー拡張機能は、モジュールから返されたデータを使用して、必要に応じて適切なユーザー インターフェイス (UI) をレンダリングできます。
<!--feature detail end -->










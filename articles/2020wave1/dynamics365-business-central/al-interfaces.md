---
title: AL インターフェイス
description: AL でインターフェイスを定義および実装して、コードがインターフェイスに準拠する任意のタイプと対話できるようにします。
author: relnotes
ms.reviewer: solsen
ms.date: 02/12/2020
ms.assetid: 2fc48a30-db1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 79eacf0972e4626ff5ba72d97db3854da8fedaa8
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080041"
---
# <a name="al-interfaces"></a>AL インターフェイス
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
定義されたインターフェイスに準拠している限り、実際の実装が異なることを許可しながら、オブジェクトに対してどの機能を使用可能にする必要があるかを決定する場合、インターフェイスが使用されます。

これにより、実装の詳細への依存を減らすコードを記述し、コードの再利用を容易にすることができます。また、オブジェクト メソッドを呼び出すポリモーフィング方法がサポートされ、これはビジネス ロジックを置き換えるためにも使用できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しいインターフェイス オブジェクトを使用して、そのメソッドと共にインターフェイス名を宣言し、インターフェイス メソッドを実装するオブジェクトにインターフェイス名と共に implements キーワードを適用します。 

インターフェイス オブジェクト自体にはコードは含まれず、署名のみが含まれます。また、それ自体をコードから呼び出すことはできず、他のオブジェクトによって実装する必要があります。
 
コンパイラでは、実装が割り当てられたインターフェイスに準拠していることが確認されます。

新しい QuickFix CodeAction を使用して、1 つ以上のインターフェイス実装のコンパイラ エラーが欠落している場合に、インターフェイス スタブを挿入できます。

変数を特定のインターフェイスとして宣言して、インターフェイスを実装するオブジェクトを渡せるようにし、渡されたオブジェクトに対するインターフェイス実装をポリモーフィックな方法で呼び出すことができます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)

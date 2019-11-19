---
title: POS および本社の拡張機能
description: POS および本社の拡張機能
author: mugunthanm
ms.reviewer: josaw
ms.date: 10/14/2019
ms.assetid: 5e63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 01bf1bfb5e5179d417ba1dfe605de9701fb541b7
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659960"
---
# <a name="pos-and-headquarters-extensions"></a>POS および本社の拡張機能


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
多くの小売業者が、ビジネス目標を達成するために、Dynamics 365 Retail を拡張して、既存のビジネス ロジックを変更したり、製品に新しい機能を追加したりすることを必要とするか選択しています。 販売時点管理 (POS)、Commerce Runtime (CRT)、および本社 (HQ) では、カスタム ビジネス シナリオをサポートするための拡張ポイントを追加しています。 この機能の目標は、拡張シナリオをサポートするために製品に必要なコア拡張ポイントを追加することです。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
### <a name="framework-enhancements"></a>フレームワークの機能強化
バイナリ ベースの拡張モデルに移行した後、簡単にロジックを使用およびオーバーライドできるように、すべてのコア POS ロジックとユーザー インターフェイス (UI) コントロールをラップし、SDK (API) として公開しています。 これらの API がないと、拡張機能でカスタム ロジックを記述するのは困難です。 場合によっては、拡張機能で既存のコードの一部を書き換えたり、単純なシナリオを実行するには多すぎるコード行を書いたりする必要があります。 これを回避し、コード行数を減らすために、より高度な API と構成主導の開発を導入して、開発プロセス全体を簡素化しています。    

### <a name="pos-ui-and-api-extension"></a>POS UI と API 拡張機能
POS フレームワークを継続的に拡張し、拡張機能でロジックを使用するための POS API と、コア POS ビューにカスタム列、アプリ バー ボタン、カスタム コントロールを追加するための UI 拡張ポイントを追加しています。

### <a name="pos-overridable-requests-and-triggers"></a>POS オーバーライド可能な要求とトリガー
POS ワークフローまたは POS ビジネス ロジックをオーバーライドし、カスタム ロジックまたは検証を追加するために、新しいオーバーライド可能な要求が POS に追加されています。 POS トリガー フレームワークは、コア POS ロジックの前後でカスタム ロジックを実行するのに役立ちます。 この新しいパターンにより、開発者は POS のワークフローを簡単にカスタマイズできます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Retail POS API](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/pos-apis) (ドキュメント)

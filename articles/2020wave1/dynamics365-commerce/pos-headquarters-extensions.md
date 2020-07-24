---
title: POS および本社の拡張機能
description: POS および本社の拡張機能
author: mugunthanm
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: 2c9e2005-f5f6-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 5abf4ad84e9abec2ab15bc3e116d3979277ed9c1
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3415822"
---
# <a name="pos-and-headquarters-extensions"></a>POS および本社の拡張機能
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 18 日| 2020 年 7 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
### <a name="framework-enhancements"></a>フレームワークの機能強化
バイナリ ベースの拡張モデルに移行した後、簡単にロジックを使用およびオーバーライドできるように、すべてのコア POS ロジックとユーザー インターフェイス (UI) コントロールをラップし、SDK (API) として公開しています。 これらの API がないと、拡張機能でカスタム ロジックを実装するのは困難です。 場合によっては、拡張機能で既存のコードの一部を書き換えたり、単純なシナリオを実行するには多すぎるコード行を書いたりする必要があります。 これを回避し、コード行数を減らすために、より高度な API と構成主導の開発を導入して、開発プロセス全体を簡素化しています。    

### <a name="pos-ui-and-api-extension"></a>POS UI と API 拡張機能
拡張機能でロジックを使用するための POS API と、コア POS ビューにカスタム列、アプリ バー ボタン、カスタム コントロールを追加するための UI 拡張ポイントを追加することにより、POS フレームワークを拡張しました。

### <a name="pos-overridable-requests-and-triggers"></a>POS オーバーライド可能な要求とトリガー
POS ワークフローまたは POS ビジネス ロジックをオーバーライドし、カスタム ロジックまたは検証を追加するために、新しいオーバーライド可能な要求が POS に追加されました。 POS トリガー フレームワークは、コア POS ロジックの前後でカスタム ロジックを実行するのに役立ちます。 この新しいパターンにより、開発者は POS のワークフローを簡単にカスタマイズできます。
<!--feature detail end -->










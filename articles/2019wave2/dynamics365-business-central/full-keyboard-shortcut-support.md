---
title: フル キーボード ショートカットのサポート
description: ショートカットが追加されており、開発者はカスタム アクション用に独自のキーボード ショートカットを追加できます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: b663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 2c837041f8959db2a338f449cce01cfa28a1ea14
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892165"
---
# <a name="full-keyboard-shortcut-support"></a>フル キーボード ショートカットのサポート


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
熟練したユーザーは、それぞれの機能を見つけるためにアクション バーを探すのではなく、キーボードを使用してよく使う機能にアクセスできると、より生産的になります。 開発者は、ソリューションにキーボード ショートカットを追加することによって、エンド ユーザーのフィードバックに対応することもできます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central 用の拡張機能を作成する開発者は、AL プロパティによってほとんどのアクションや操作にキーボード ショートカットを追加できます。 つまり、アプリケーション開発者は、基本アプリケーションのアクションや、拡張機能の独自のオブジェクトに対して、キーボード ショートカットを指定できます。 そのためには、開発者は AL (Business Central 拡張機能用のプログラミング言語) の [ShortCutKey プロパティ](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-shortcutkey-property "ShortCutKey プロパティ")を使用する必要があります。

この機能により、Business Central のキーボード ショートカットの定義済みリストが補完され、パートナーはいっそう柔軟に開発できるようになります。

追加のキーボード ショートカットは 2019 年リリース ウェーブ 2 で追加されます。 これらのほとんどはビジネス アプリケーション領域で定義されたショートカットに基づいており、今後、柔軟性向上のために変更される可能性があります。


更新されたキーボード ショートカットの完全な一覧は、常に「[キーボード ショートカット](https://go.microsoft.com/fwlink/?LinkId=2064754)」で公開されます。 たとえば、新しく追加されたキーボード ショートカットの 1 つとして、ドキュメントを転記するための *F9* があります。

![キーボード ショートカットを使用した請求書の転記](media/posting.png "キーボード ショートカットを使用した請求書の転記")
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[キーボード ショートカット](https://docs.microsoft.com/dynamics365/business-central/keyboard-shortcuts) (ドキュメント)

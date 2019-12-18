---
title: ユーザーの生産性 - 新しいグリッド
description: ユーザーの生産性 - 新しいグリッド
author: relnotes
ms.reviewer: sericks
ms.date: 12/02/2019
ms.assetid: e662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: f7884d6057dabfd7308a0dd473518c981b441afa
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893822"
---
# <a name="user-productivity--new-grid"></a>ユーザーの生産性 - 新しいグリッド
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 5 日| 2020 年 3 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
2019 年 10 月の Platform update 29 で、新しく改善されたグリッド コントロールのプレビューが利用可能になります。 

新しいグリッドには多くの利点があります。 

- **パフォーマンス**: 新しいグリッドでは、レンダリング速度が向上し、スクロール エクスペリエンスが速くなっています。
- **特定の位置にスクロール**: ユーザーは Web ブラウザーに読み込まれたデータ内の特定の位置にスクロールできるようになりました。 たとえば、グリッド内の 10,000 行をスクロールするには、スクロール バーの中央を選択すると、サーバーからデータを取得する必要なしに、すぐにレコード 5,000 に移動します。
- **一般的な改善**: 既存のグリッドでは、グリッド ヘッダーとデータの位置がずれており、スクロールまたは新しいレコードの作成中にグリッドがジャンプします。 新しいグリッドではこれらの問題がなくなります。
- **列の並べ替え**: ユーザーは、列をドラッグして並べ替えることができるようになりました。 列ヘッダーにマウス ポインターを合わせ、列の左側に表示されるグリッパー コントロールをドラッグします。
- **公式**: ユーザーは、グリッドの数値セルに公式を入力できるようになりました。 たとえば、**=15\*4** と入力できます。 システムによって値が式として認識されるようにするには、値を等号 (**=**) から開始します。 

新しいグリッドでは、より複雑な機能を組み込むこともできます。 グリッドへのこれらの追加は、以降の月次アップデートで導入および強化されます。

- **合計**: ビジネス ユーザーは、表形式グリッドの数値列について合計を表示できます。 たとえば、会計担当のユーザーは、特定の顧客に対するフィルター処理されたトランザクション セットの合計を表示できます。 この機能は、Platform update 29 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。

  ![金額列に表示された合計](media/user-productivity-new-grid-1.png "金額列に表示された合計")

- **高速データ入力**: この機能を使用すると、ユーザーはサーバーに先行してグリッドにデータを入力できます。 したがって、ユーザーが別の行に移動する前にサーバーがグリッド内の 1 行を検証するのを待つ必要性が最小限に抑えられます。 この機能は、Platform update 31 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。

新しいグリッドを有効にする方法については、この記事の「関連項目」セクションのリンク先を参照してください。  
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Platform update 31 の新機能](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/get-started/whats-new-platform-update-31) (ドキュメント)

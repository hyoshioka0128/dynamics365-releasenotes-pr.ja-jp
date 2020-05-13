---
title: 推奨アクションから実行するアクション オプションを拡張する
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 01/31/2020
ms.assetid: eac57080-f3d4-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: nataln
dynamics365pdf: true
ms.openlocfilehash: e2bd192b3c5a23872f5c505697374eac86cdc3a4
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3059148"
---
# <a name="extend-action-options-taken-from-the-suggested-actions"></a>推奨アクションから実行するアクション オプションを拡張する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 18 日| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
販売担当者は、一度に多くのことを追跡する必要があります。 推奨アクションは、販売担当者が次のステップを決定するのに役立ちます。 それらをフォローアップするのは大変な作業ですが、自動化によって販売担当者の生産性を向上できます。 

今回のリリースでは、組織が販売担当者の実行可能なアクションを拡張できるようになります。 これまでは、販売担当者は営業案件などのエンティティを開くか、推奨アクションのフォローアップとして URL を開くことしかできませんでした。 カスタム アクション、REST API、プレイブックの起動、フローのトリガーのためにそれらのアクションを拡張する機能をプレビューできるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
- **表示されるアクションの名前を変更する**: アクションをよりわかりやすくします。 現在、販売担当者に表示されるオプションは**開く**のみです。 必要に応じてテキストをカスタマイズできるようになりました。
- **Flow で推奨アクションを自動化する**: Dynamics 365 のカスタム アクションと同様に、システムと対話する販売担当者への応答として Power Automate を実行できます。 たとえば、メールでのドキュメントの送信を自動化できます。
- **カスタム アクションで推奨アクションを自動化する**: 販売担当者が推奨アクションからカスタム アクションの実行をトリガーできるようにします。 フィールドの更新などの単純なアクションを推奨アクション内から直接トリガーできます。 
- **REST API を使用して自動化する**: Power Automate やカスタム アクションを使用してアクションを自動化できない場合は、販売担当者が Dynamics 365 内の推奨アクションから自動アクションを直接実行できるように REST API 呼び出しを構成できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[カードにアクションを追加する](https://docs.microsoft.com/dynamics365/ai/sales/create-insight-cards-flow#add-actions-to-cards) (ドキュメント)

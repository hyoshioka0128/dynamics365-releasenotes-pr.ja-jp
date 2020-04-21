---
title: 廃止されたタグ プロパティ
description: ObsoleteState プロパティまたは Obsolete 属性を現在サポートしているオブジェクトに、プロセスを追跡するための ObsoleteTag プロパティを追加して、廃止されたオブジェクトに関する情報を提供します。
author: relnotes
ms.reviewer: solsen
ms.date: 04/02/2020
ms.assetid: a5a76819-dd1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: c434aa7e556398510d977b7953ae5404765daaf3
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232739"
---
# <a name="obsolete-tag-property"></a>廃止されたタグ プロパティ
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
自由形式の ObsoleteTag を追加することで、パートナーは、廃止されたオブジェクト (分岐やビルド番号など) に関するコンテキスト データを提供して、廃止されたオブジェクトの最終的な削除を追跡および計画できます。

ObsoleteUrl を使用すると、保留中の古いオブジェクトの処理とコードを書き換える方法に関する追加情報の URI を提供できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ObsoleteState プロパティまたは Obsolete 属性を現在サポートしているオブジェクトに、プロセスを追跡するための ObsoleteTag プロパティを追加して、廃止されたオブジェクトに関する追加情報を提供します。

パートナーは、日付やビルドなどの ObsoleteTag で追跡する対象について独自のスキームを選択でき、これを開発時や内部ビルド プロセスで提供できます (カスタム ファイル修正が必要となります)。 また、開発者は、すべてのファイルにわたって ObsoleteTag コンテンツを検索できます (特定のバージョンでの変更の概要を取得する場合など)。

![ObsoleteTag によるコンテキスト メタデータの追跡](media/obsoletetag-search.jpg "ObsoleteTag によるコンテキスト メタデータの追跡")
<!--feature detail end -->










## <a name="see-also"></a>関連項目


<!--docs start-->
[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)
<!--docs end-->


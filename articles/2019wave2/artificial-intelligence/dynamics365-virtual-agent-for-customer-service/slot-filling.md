---
title: スロット充足機能
description: スロット充足機能
author: relnotes
ms.reviewer: iawilt
ms.date: 08/27/2019
ms.assetid: 1064278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: clmori
dynamics365pdf: true
ms.openlocfilehash: a0aea05871f63f6e24bc16a9e79210ff14f8dd4e
ms.sourcegitcommit: 856d36597ee54f817177a3682a0048ad1390c936
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2019
ms.locfileid: "2003616"
---
# <a name="slot-filling-capabilities"></a>スロット充足機能
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2019 年 12 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ユーザーがボットとの対話で何かを言うたびに、応答には会話を導くのに役立つ有用な情報が含まれている可能性があります。 システムは、ユーザーの応答で、会話をガイドするために使用する情報を継続的に解析します。 

これは、ユーザーが既に提供した情報または不足している情報をボットが認識し、必要に応じて明確化のための質問をして、対話を続けられることを意味します。 この機能はスロット充足と呼ばれます。

たとえば、天気についてたずねる場合、ユーザーは自然にトピック (天気予報)、場所 (レドモンド)、時間 (木曜日) を含める可能性があります。 次に例を示します。

 **ユーザー:**      *レドモンドの木曜日の天気はどうですか?*
 
 **ボット:**       *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*

ただし、ユーザーの応答があいまいで定型化されていない場合があり、タスクの実行に必要なすべての情報が提供されないことがあります。 スロット充足では、ボットはユーザーと短い会話を行って、タスクを完了するのに必要な不足している情報を見つけることができます。

たとえば、天気についての質問の会話でスロット充足が使われると次のようになります。

**ユーザー:**   *木曜日の天気はどうですか?*

**ボット:**    *天気をお調べできます。どこをチェックしますか?*

**ユーザー:**   *ワシントン州レドモンド*

**ボット:**    *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*
<!--feature detail end -->












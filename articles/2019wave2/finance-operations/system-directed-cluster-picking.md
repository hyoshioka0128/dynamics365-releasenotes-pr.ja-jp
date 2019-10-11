---
title: システム主導のクラスター ピッキング
description: この機能は、システムがクラスター プロファイルを使用してクラスターを作成する、手動のクラスター構築に代わる方法です。
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 8062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: ab60a90a03d7259d81d24f8fee67a987164cf5f8
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141153"
---
# <a name="system-directed-cluster-picking"></a>システム主導のクラスター ピッキング
[!include[finance-operations banner](../includes/finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|2019 年 8 月| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
システム主導のクラスター ピッキングでは、システム生成のクラスターに基づいてピッキング作業ヘッダーがクラスター化されます。 システムは、クラスター プロファイルで指定されているポジション数までピッキング注文をクラスター化します。 この機能は、システムがクラスター プロファイルを使用してクラスターを作成する、手動のクラスター構築に代わる方法です。 クラスター プロファイルでは次の情報が設定されます。[職位の数] は、クラスターに入れられる注文の数、つまりトートの数に対応します。[クラスターの分割] は、いつクラスターを分割するかを決定します。[クラスター ID の生成] は、システムによってクラスター ID を生成するか、またはユーザーが入力するかを制御します。[並べ替え検証タイプ] は、位置の検証が必要かどうかを決定します。 倉庫作業員には、ピッキング順序がクラスター位置に事前に割り当てられている作成済みのクラスターが自動的に提示されます。 作業者は、ユーザー主導のクラスター ピッキングと同様に、ピッキング場所に 1 回だけアクセスすることで、複数の作業指示書に対する品目のピッキングできます。
<!--feature detail end -->












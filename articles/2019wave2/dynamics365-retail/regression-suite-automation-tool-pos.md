---
title: POS 用の Regression Suite Automation Tool
description: POS 用の Regression Suite Automation Tool
author: mugunthanm
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 6463278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 1ca404890cefd64473add07147060110083bca73
ms.sourcegitcommit: ce44199897bc0c276cd02c99cc1d216f198734b0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1691779"
---
# <a name="regression-suite-automation-tool-for-pos"></a>POS 用の Regression Suite Automation Tool
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 11 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
小売業者またはパートナーは、Lifecycle Services (LCS) のタスク レコーダーとビジネス プロセス モデラー (BPM) を使用して、販売時点管理 (POS) 用のユーザー受け入れテスト ライブラリを作成できます。 タスク レコーダーはテスト ケースを記録するための強力なツールです。 その後、BPM を使用してビジネス プロセス別にテスト ケースを整理できます。 BPM は Azure DevOps と同期することができ、BPM で Azure DevOps プロジェクトのテスト ケース (テスト ステップを含む) を自動的に作成できます。 その後、Azure DevOps はテスト構成およびテスト管理ツールとして使用でき、ユーザーはターゲットを絞ったテスト計画やテスト スイートを作成し、テストの実行を管理して、結果を調査することができます。 テストでは、オムニチャネルのシナリオをサポートできます。たとえば、Dynamics 365 for Finance and Operations で注文を作成し、POS を使って店で取得できます。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
以下は、この機能で利用可能なエンドツーエンドのフローの例です。

- POS にアクセスできる環境で、Web ブラウザーを使用して、ビジネス サイクル テストを作成して実行します。

- 運用データベースのコピーを使用して、サンドボックス環境に対してテストを実行します。

- 一度記録し、異なるデータ セットや異なる法人で複数回再生します。

- 予想される値に対して検証します。 

- あるテスト ケースから次のテスト ケースにパラメーターを渡すことで、テスト ケースを連結します (エンドツーエンド テスト)。

- Azure DevOps を使用して、テスト スイートを管理し、テストを実行し、テスト結果を調査します。

- 次のようにして作成および配布します。

  - テスト計画を構成します。

  - テストを実行して結果を管理します。
<!--feature detail end -->











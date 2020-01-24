---
title: Finance and Operations AOS (カーネル) の改善
description: Finance and Operations AOS (カーネル) の改善
author: relnotes
ms.reviewer: sericks
ms.date: 01/06/2020
ms.assetid: 021a0697-4607-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hasaid
dynamics365pdf: true
ms.openlocfilehash: e5e1065f7a06c6ea5d66e88e1b35af34868b598e
ms.sourcegitcommit: ecf709e1d8de3b52e1156bceb99cb7e3819f9db3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/13/2020
ms.locfileid: "2950980"
---
# <a name="finance-and-operations-aos-kernel-improvements"></a>Finance and Operations AOS (カーネル) の改善


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 12 月 20 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
より信頼性が高く安定したエクスペリエンスを顧客に提供するための継続的な改善に注力する際に、これはこの体験に必要なマイルストーンです。

Platform update 32 以降、AOS (カーネル) は Visual C++ 17 ランタイム ライブラリを取り込んで、コンパイラのパフォーマンスの最適化を活用します。 プラットフォーム エンジニアは、開発環境の使用中に新しいアップグレードを利用して、より堅牢で信頼性の高いエクスペリエンスを顧客に提供できます。

そのためには、VC++ 17 再頒布可能パッケージを使用するように既存の環境を更新する必要があります。

- Microsoft が管理するスタンダード承認テスト サンドボックス以上 (Tier 2 以上) および実稼働環境の場合、VC++ 17 再頒布可能パッケージは既にインストールされており、アクションは不要です。
- Microsoft が管理する DEV 環境 (Tier 1) の場合、顧客、パートナー、および ISV は、Platform update 32 を適用する前に仮想マシンを再起動する必要があります。
- 管理されていない開発、ビルド、テスト、デモ (Tier 1) およびオンプレミス環境の場合、顧客、パートナー、および ISV は、Lifecycle Services の共有アセット ライブラリから VC++ 17 再頒布可能パッケージをダウンロードしてインストールし、マシンを再起動する必要があります。

最新の再頒布可能パッケージが既にインストールされている場合、アクションは不要です。

Platform update 32 を適用し、再頒布可能パッケージが欠落している場合、サービスの開始時にエラーが発生することがあります。 必要に応じて、次の手順を参照してこの問題を解決してください。

再頒布可能パッケージをインストールするには:

1. Lifecycle Services に移動します。
2. **共有アセット ライブラリ**を選択します。
3. アセット タイプの一覧から**モデル**を選択します。
4. **VC++ 17 再頒布可能パッケージ**を選択します。
5. ダウンロードが自動的に開始されます。
6. マシンに適用して再起動します。
<!--feature detail end -->








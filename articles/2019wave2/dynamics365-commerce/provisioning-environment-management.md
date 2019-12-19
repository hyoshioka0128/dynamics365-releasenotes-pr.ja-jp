---
title: プロビジョニングと環境管理
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: b263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brendans
dynamics365pdf: true
ms.openlocfilehash: 5dde02d5fec51ba2329d6ffb4612301c76ac5258
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890269"
---
# <a name="provisioning-and-environment-management"></a>プロビジョニングと環境管理
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日| 2020 年 2 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
IT エンジニアまたはシステム インテグレーター (SI) には、eコマース機能セットを有効にしてプロビジョニングする方法が必要です。 プロビジョニング機能により、IT エンジニアと SI は Dynamics Lifecycle Services (LCS) でこの作業を完了し、完全に機能する CMS、編集、レンダリング環境をプロビジョニングできます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
現在のペースの速いビジネス環境では、市場投入までの時間と、刻々と変化する市場に迅速に対応する能力が重要です。 これらの企業と連携する管理者は、環境を自由にプロビジョニングおよびデコミッションできる必要があります。 Dynamics 365 Commerce は Dynamics 365 Lifecycle Services ポータル (LCS) とシームレスに統合されます。 これにより、小売業者の管理者は、新しい eコマース環境をオンデマンドでプロビジョニングできるようになります。これは、自動化されたプロビジョニング サービスを通じて行われます。 プロビジョニングが完了すると、管理者はカスタマイズを管理し、さまざまな環境に展開できるようになります。 

環境のプロビジョニングと管理に対するこの自動化されたアプローチは、小売業者にとって大幅なコスト削減になります。これによって、新しい環境を稼働させる時間を短縮し、環境を維持するために必要な人員を削減できるからです。 開発作業と運用作業を安全に分離するために、さまざまな環境をプロビジョニングできます。 エンジニアは LCS に移動して、サンドボックス環境または運用環境を展開できます。 各環境タイプは別々の Azure データ クラスターによって完全に分離されているため、一方の作業中に他方に影響を与えるリスクはありません。 開発、テスト、レビューをサンドボックスで行います。 準備ができたら、エンジニアはサンドボックスの Commerce コンテンツを運用環境にレベル上げできます。 これにより、テスト済みの、完全に機能するコンテンツを顧客に提供するための安全な展開プロセスが可能になります。 

また、Dynamics 365 Commerce では、エンジニアは現実世界の環境で Microsoft のオファリングを探索するための評価環境をプロビジョニングできます。 評価環境を使用して製品オファリングのすべての機能を調べ、テストし、理解することができます。

![環境のプロビジョニング](media/environment_provisioning.png "環境のプロビジョニング")
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[eコマースの評価環境のコンフィギュレーション](https://docs.microsoft.com/dynamics365/commerce/provisioning-guide) (ドキュメント)

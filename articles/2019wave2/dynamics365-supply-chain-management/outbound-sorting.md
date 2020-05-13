---
title: 出庫の並べ替え
description: パレット作成では、梱包ステーションの後で梱包済みコンテナーを正しいパレットに並べて、梱包階層を作成することができます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/27/2020
ms.assetid: 8662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 848bca645a09ff05bc6dc7f1d8b51c1440b964bf
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058994"
---
# <a name="outbound-sorting"></a>出庫の並べ替え


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 6 月 3 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 17 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
パレット作成では、梱包ステーションの後で梱包済みコンテナーを正しいパレットに並べて、梱包階層を作成することができます。 後で、すべての梱包済みコンテナーを取り込む単一の作業指示書により、そのようなパレットを正しいステージング場所に移動できます。 倉庫作業者は、梱包済みコンテナーを置くパレット、パレットに置くことができるボックスの最大数、および特定のシナリオで必要なパレットの数を自由に選択できます。 

コンテナー梱包ポリシーと並べ替え場所プロファイルは、梱包ステーションから梱包済みコンテナーを取り扱う際の柔軟性を高めるためにまとめて導入されました。 さまざまな統合基準が導入され、ユーザーが各移動先パレットの基準を割り当てた後、後続のすべての梱包済みコンテナーは一致するパレットに誘導され、作業員は作業指図のプット ステップを確認するだけで済みます。 パレットがいっぱいになると、パレット位置は閉じられ、1 つの単位として移動できます。 これにより、倉庫内での梱包済みコンテナーの移動に必要な手順が減るため、コンテナーの取り扱いが速くなり、概要がわかりやすくなります。 この機能では、複数のコンテナーを 1 つのパレットにマージするときにコンテナー詰めプロセスを使用しませんが、既存のコンテナー グループ ライセンス プレート機能が拡張されます。 したがって、パレットの内容一覧はこの拡張では印刷できません。 この機能は既存のシステム機能と統合されるため、変更される場合があります。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)

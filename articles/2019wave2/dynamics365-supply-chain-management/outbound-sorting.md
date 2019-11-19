---
title: 出庫の並べ替え
description: パレット作成では、梱包ステーションの後で梱包済みコンテナーを正しいパレットに並べて、梱包階層を作成することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 8662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e730d2ef412264dffd5287f19c3f7ac35b1a49f3
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660599"
---
# <a name="outbound-sorting"></a>出庫の並べ替え
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 6 月 3 日| 2020 年 1 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
パレット作成では、梱包ステーションの後で梱包済みコンテナーを正しいパレットに並べて、梱包階層を作成することができます。 後で、すべての梱包済みコンテナーを取り込む単一の作業指示書により、そのようなパレットを正しいステージング場所に移動できます。 倉庫作業者は、梱包済みコンテナーを置くパレット、パレットに置くことができるボックスの最大数、および特定のシナリオで必要なパレットの数を自由に選択できます。 

コンテナー梱包ポリシーと並べ替え場所プロファイルは、梱包ステーションから梱包済みコンテナーを取り扱う際の柔軟性を高めるためにまとめて導入されました。 さまざまな統合基準が導入され、ユーザーが各移動先パレットの基準を割り当てた後、後続のすべての梱包済みコンテナーは一致するパレットに誘導され、作業員は作業指図のプット ステップを確認するだけで済みます。 パレットがいっぱいになると、パレット位置は閉じられ、1 つの単位として移動できます。 これにより、倉庫内での梱包済みコンテナーの移動に必要な手順が減るため、コンテナーの取り扱いが速くなり、概要がわかりやすくなります。 この機能では、複数のコンテナーを 1 つのパレットにマージするときにコンテナー詰めプロセスを使用しませんが、既存のコンテナー グループ ライセンス プレート機能が拡張されます。 したがって、パレットの内容一覧はこの拡張では印刷できません。 この機能は既存のシステム機能と統合されるため、変更される場合があります。
<!--feature detail end -->










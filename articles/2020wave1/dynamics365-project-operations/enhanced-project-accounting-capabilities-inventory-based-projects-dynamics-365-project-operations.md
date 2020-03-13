---
title: Dynamics 365 Project Operations の在庫ベースのプロジェクトのプロジェクト会計機能の強化
description: Project Operations での包括的な機能の提供という目標に向けて、会計の概念から請求を分離することにより、プロジェクト管理会計機能を強化します。 そのために、プロジェクト タイプとプロジェクト グループの依存関係を削除して、1 つのプロジェクトに対して複数の会計モデルを可能にします。
author: relnotes
ms.reviewer: kfend
ms.date: 02/04/2020
ms.assetid: 0bf85b16-a630-ea11-a810-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: rumant
dynamics365pdf: true
ms.openlocfilehash: 1284c5455172353bfa0f454ae4a9a4e6ef3a26cc
ms.sourcegitcommit: 69c00a1d6cfa73067950bd9d9c08606c8807ed8c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/19/2020
ms.locfileid: "3072089"
---
# <a name="enhanced-project-accounting-capabilities-for-inventory-based-projects-in-dynamics-365-project-operations"></a>Dynamics 365 Project Operations の在庫ベースのプロジェクトのプロジェクト会計機能の強化
[!include[dynamics365-project-operations banner](../includes/dynamics365-project-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 9 月| 近日発表|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
- **プロジェクトからプロジェクト タイプの依存関係を削除する**: この機能を有効にすると、在庫ベースのプロジェクトは**固定価格**、**時間/実費払い**、**原価**、**時間**、**内部**、または**投資**のタイプを持たなくなります。 プロジェクト契約品目によってプロジェクトが**固定価格**と**時間/実費払い**のどちらであるかが決まるため、同じプロジェクトが固定価格コンポーネントと時間/実費払いコンポーネントの両方を持てるようになります。 契約を結んでいないプロジェクトでは原価が追跡されますが、収益は追跡されません。

- **プロジェクトからプロジェクト グループの依存関係を削除する**: この機能を使用すると、在庫ベースのプロジェクトの**プロジェクト グループ**の依存関係を削除できます。 これらのプロジェクトでは、プロジェクト グループがオプションのグループ化メカニズムになります。 仕掛品 (WIP)/収益の見越計上および固定価格プロジェクトの収益認識に関連する構成を含む、**プロジェクト収益プロファイル**という新しいエンティティが作成されます。 プロジェクト収益プロファイルは契約品目に設定されます。


<!--feature detail end -->










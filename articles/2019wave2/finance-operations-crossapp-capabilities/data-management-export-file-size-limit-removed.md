---
title: データ管理エクスポート ファイルのサイズ制限の削除
description: データ管理エクスポート ファイルのサイズ制限の削除
author: relnotes
ms.reviewer: sericks
ms.date: 12/02/2019
ms.assetid: 15bdb94c-7605-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: sunilg
dynamics365pdf: true
ms.openlocfilehash: 3e11094af08b074161cfda54a7b67f8035f2a3e3
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2894045"
---
# <a name="data-management-export-file-size-limit-removed"></a>データ管理エクスポート ファイルのサイズ制限の削除
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 11 月 25 日| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、エクスポートされたファイル サイズを含めるためにフィルターに依存する必要のないエクスポート エクスペリエンスが可能になり、プロセス全体の効率が向上します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
データ管理を使用してファイルをエクスポートする場合、最大ファイル サイズは 256 MB でした。 フライト **DMFBlobSize256** を実装することにより、Platform update 32 でこの制限を削除できます。 必要に応じて、この機能を有効にしたために問題が発生した場合は以前の動作に戻すことができます。

<!--feature detail end -->










## <a name="see-also"></a>関連項目

[データ インポート/エクスポート ジョブの概要](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-import-export-job) (ドキュメント)

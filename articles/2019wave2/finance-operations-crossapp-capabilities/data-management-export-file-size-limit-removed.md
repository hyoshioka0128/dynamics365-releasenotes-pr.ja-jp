---
title: データ管理エクスポート ファイルのサイズ制限の削除
description: データ管理エクスポート ファイルのサイズ制限の削除
author: relnotes
ms.reviewer: sericks
ms.date: 01/06/2020
ms.assetid: 15bdb94c-7605-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: sunilg
dynamics365pdf: true
ms.openlocfilehash: 40d4ce794deca043b85f48b1d251cb0ba447fe21
ms.sourcegitcommit: ecf709e1d8de3b52e1156bceb99cb7e3819f9db3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/13/2020
ms.locfileid: "2950991"
---
# <a name="data-management-export-file-size-limit-removed"></a><span data-ttu-id="4decc-103">データ管理エクスポート ファイルのサイズ制限の削除</span><span class="sxs-lookup"><span data-stu-id="4decc-103">Data management export file size limit removed</span></span>


| <span data-ttu-id="4decc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4decc-104">Enabled for</span></span>    |  <span data-ttu-id="4decc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4decc-105">Public preview</span></span> | <span data-ttu-id="4decc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4decc-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4decc-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="4decc-107">End users, automatically</span></span>|<span data-ttu-id="4decc-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4decc-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4decc-109">2019 年 11 月 25 日</span><span class="sxs-lookup"><span data-stu-id="4decc-109">Nov 25, 2019</span></span>| <span data-ttu-id="4decc-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4decc-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4decc-111">2020 年 1 月 1 日</span><span class="sxs-lookup"><span data-stu-id="4decc-111">Jan 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="4decc-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4decc-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4decc-113">この機能により、エクスポートされたファイル サイズを含めるためにフィルターに依存する必要のないエクスポート エクスペリエンスが可能になり、プロセス全体の効率が向上します。</span><span class="sxs-lookup"><span data-stu-id="4decc-113">This feature enables an export experience that does not have to rely on filters to contain the exported file size, which improves the overall process efficiency.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4decc-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4decc-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4decc-115">データ管理を使用してファイルをエクスポートする場合、最大ファイル サイズは 256 MB でした。</span><span class="sxs-lookup"><span data-stu-id="4decc-115">When exporting files using Data management, there was a maximum file size of 256 MB.</span></span> <span data-ttu-id="4decc-116">フライト **DMFBlobSize256** を実装することにより、Platform update 32 でこの制限を削除できます。</span><span class="sxs-lookup"><span data-stu-id="4decc-116">You can remove this limitation in Platform update 32 by implementing flight **DMFBlobSize256**.</span></span> <span data-ttu-id="4decc-117">必要に応じて、この機能を有効にしたために問題が発生した場合は以前の動作に戻すことができます。</span><span class="sxs-lookup"><span data-stu-id="4decc-117">If needed, you can revert to the previous behavior if you encounter issues due to enabling this feature.</span></span>

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="4decc-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="4decc-118">See also</span></span>

[<span data-ttu-id="4decc-119">データ パッケージ処理のトラブルシューティング</span><span class="sxs-lookup"><span data-stu-id="4decc-119">Troubleshoot data package processing</span></span>](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-entities-data-packages#troubleshoot-data-package-processing)

<span data-ttu-id="4decc-120">[データ インポート/エクスポート ジョブの概要](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-import-export-job) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="4decc-120">[Data import and export jobs overview](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-import-export-job) (docs)</span></span>

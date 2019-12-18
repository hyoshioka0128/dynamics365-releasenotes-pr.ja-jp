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
# <a name="data-management-export-file-size-limit-removed"></a><span data-ttu-id="ea67a-103">データ管理エクスポート ファイルのサイズ制限の削除</span><span class="sxs-lookup"><span data-stu-id="ea67a-103">Data management export file size limit removed</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="ea67a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ea67a-104">Enabled for</span></span>    |  <span data-ttu-id="ea67a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ea67a-105">Public preview</span></span> | <span data-ttu-id="ea67a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ea67a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ea67a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ea67a-107">End users, automatically</span></span>|<span data-ttu-id="ea67a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ea67a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ea67a-109">2019 年 11 月 25 日</span><span class="sxs-lookup"><span data-stu-id="ea67a-109">Nov 25, 2019</span></span>| <span data-ttu-id="ea67a-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="ea67a-110">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ea67a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ea67a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ea67a-112">この機能により、エクスポートされたファイル サイズを含めるためにフィルターに依存する必要のないエクスポート エクスペリエンスが可能になり、プロセス全体の効率が向上します。</span><span class="sxs-lookup"><span data-stu-id="ea67a-112">This feature enables an export experience that does not have to rely on filters to contain the exported file size, which improves the overall process efficiency.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ea67a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ea67a-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ea67a-114">データ管理を使用してファイルをエクスポートする場合、最大ファイル サイズは 256 MB でした。</span><span class="sxs-lookup"><span data-stu-id="ea67a-114">When exporting files using Data management, there was a maximum file size of 256 MB.</span></span> <span data-ttu-id="ea67a-115">フライト **DMFBlobSize256** を実装することにより、Platform update 32 でこの制限を削除できます。</span><span class="sxs-lookup"><span data-stu-id="ea67a-115">You can remove this limitation in Platform update 32 by implementing flight **DMFBlobSize256**.</span></span> <span data-ttu-id="ea67a-116">必要に応じて、この機能を有効にしたために問題が発生した場合は以前の動作に戻すことができます。</span><span class="sxs-lookup"><span data-stu-id="ea67a-116">If needed, you can revert to the previous behavior if you encounter issues due to enabling this feature.</span></span>

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ea67a-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="ea67a-117">See also</span></span>

<span data-ttu-id="ea67a-118">[データ インポート/エクスポート ジョブの概要](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-import-export-job) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ea67a-118">[Data import and export jobs overview](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-import-export-job) (docs)</span></span>

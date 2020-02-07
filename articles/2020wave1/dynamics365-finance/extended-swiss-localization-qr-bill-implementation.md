---
title: '拡張されたローカライズ (スイス): QR 請求書の実装'
description: 2020 年 6 月 30 日より現在のスイスの支払伝票に変わる QR 請求書には、識別機能としてスイスの十字付きの QR コードが表示されます。 このスイス版 QR コードには、支払に必要なすべての情報のデジタル形式が含まれています。
author: relnotes
ms.reviewer: kfend
ms.date: 12/16/2019
ms.assetid: 07f2610b-f2db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 816069d773c06c488c6e4766a42179257e8d8804
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986604"
---
# <a name="extended-swiss-localization-qr-bill-implementation"></a><span data-ttu-id="31af3-104">拡張されたローカライズ (スイス): QR 請求書の実装</span><span class="sxs-lookup"><span data-stu-id="31af3-104">Extended Swiss localization: QR-bill implementation</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="31af3-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="31af3-105">Enabled for</span></span>    |  <span data-ttu-id="31af3-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="31af3-106">Public preview</span></span> | <span data-ttu-id="31af3-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="31af3-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="31af3-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="31af3-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="31af3-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="31af3-109">Feb 2020</span></span>| <span data-ttu-id="31af3-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="31af3-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="31af3-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="31af3-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="31af3-112">スイスで使用されている支払伝票は 100 年以上前のもので、年間で 1 億回使用されています。</span><span class="sxs-lookup"><span data-stu-id="31af3-112">The payment slips used in Switzerland go back over 100 years and are used 100 million times a year.</span></span> <span data-ttu-id="31af3-113">支払トラフィックに対する規制要件の増加により、システムの変更が必要になりました。</span><span class="sxs-lookup"><span data-stu-id="31af3-113">The increasing regulatory requirements for payment traffic have made some system modifications necessary.</span></span> <span data-ttu-id="31af3-114">QR 請求書はスイスで使用されているさまざまな支払伝票に取って代わるようになり、効率性を高め、支払トラフィックを簡略化するために、ERP 側でのカバレッジが必要になります。</span><span class="sxs-lookup"><span data-stu-id="31af3-114">The QR-bill now is replacing the existing multiplicity of payment slips in Switzerland, and the coverage on the ERP side is required to help with increasing efficiency and simplifying payment traffic.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="31af3-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="31af3-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="31af3-116">この機能は、特定された対応するビジネス シナリオに沿った、QR 請求書の作成と処理に関わるスイス固有の要件を満たしています。</span><span class="sxs-lookup"><span data-stu-id="31af3-116">This feature satisfies Swiss-specific requirements around QR-bill creation and processing aligned with identified and supported business scenarios.</span></span>
<!--feature detail end -->










---
title: '拡張されたローカライズ (スイス): QR 請求書の実装'
description: 2020 年 6 月 30 日より現在のスイスの支払伝票に変わる QR 請求書には、識別機能としてスイスの十字付きの QR コードが表示されます。 このスイス版 QR コードには、支払に必要なすべての情報のデジタル形式が含まれています。
author: relnotes
ms.reviewer: kfend
ms.date: 04/07/2020
ms.assetid: 07f2610b-f2db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: d139a50c34b0af22dac096c7c64524f7c0155b06
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255444"
---
# <a name="extended-swiss-localization-qr-bill-implementation"></a><span data-ttu-id="b9bb1-104">拡張されたローカライズ (スイス): QR 請求書の実装</span><span class="sxs-lookup"><span data-stu-id="b9bb1-104">Extended Swiss localization: QR-bill implementation</span></span>


| <span data-ttu-id="b9bb1-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="b9bb1-105">Enabled for</span></span>    |  <span data-ttu-id="b9bb1-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b9bb1-106">Public preview</span></span> | <span data-ttu-id="b9bb1-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="b9bb1-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b9bb1-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="b9bb1-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b9bb1-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b9bb1-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b9bb1-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="b9bb1-110">Feb 3, 2020</span></span>| <span data-ttu-id="b9bb1-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b9bb1-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b9bb1-112">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="b9bb1-112">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b9bb1-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b9bb1-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b9bb1-114">スイスで使用されている支払伝票は 100 年以上前のもので、年間で 1 億回使用されています。</span><span class="sxs-lookup"><span data-stu-id="b9bb1-114">The payment slips used in Switzerland go back over 100 years and are used 100 million times a year.</span></span> <span data-ttu-id="b9bb1-115">支払トラフィックに対する規制要件の増加により、システムの変更が必要になりました。</span><span class="sxs-lookup"><span data-stu-id="b9bb1-115">The increasing regulatory requirements for payment traffic have made some system modifications necessary.</span></span> <span data-ttu-id="b9bb1-116">QR 請求書はスイスで使用されているさまざまな支払伝票に取って代わるようになり、効率性を高め、支払トラフィックを簡略化するために、ERP 側でのカバレッジが必要になります。</span><span class="sxs-lookup"><span data-stu-id="b9bb1-116">The QR-bill now is replacing the existing multiplicity of payment slips in Switzerland, and the coverage on the ERP side is required to help with increasing efficiency and simplifying payment traffic.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b9bb1-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b9bb1-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b9bb1-118">この機能は、特定された対応するビジネス シナリオに沿った、QR 請求書の作成と処理にかかわるスイス固有の要件を満たしています。</span><span class="sxs-lookup"><span data-stu-id="b9bb1-118">This feature satisfies Swiss-specific requirements around QR-bill creation and processing aligned with identified and supported business scenarios.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b9bb1-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="b9bb1-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="b9bb1-120">[スイスの QR コード決済](https://docs.microsoft.com/dynamics365/finance/localizations/emea-che-swiss-qr-bills)</span><span class="sxs-lookup"><span data-stu-id="b9bb1-120">[Swiss QR-bills](https://docs.microsoft.com/dynamics365/finance/localizations/emea-che-swiss-qr-bills) (docs)</span></span>
<!--docs end-->

<!--kb start-->
<span data-ttu-id="b9bb1-121">[スイス QR-請求書をサポートする国固有の更新プログラム](https://support.microsoft.com/en-us/help/4540315) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b9bb1-121">[A country specific update to support Swiss QR-bills](https://support.microsoft.com/en-us/help/4540315) (docs)</span></span>
<!--kb end-->

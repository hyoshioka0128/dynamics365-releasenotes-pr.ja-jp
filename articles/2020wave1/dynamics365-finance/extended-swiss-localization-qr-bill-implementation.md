---
title: '拡張されたローカライズ (スイス): QR 請求書の実装'
description: 2020 年 6 月 30 日より現在のスイスの支払伝票に変わる QR 請求書には、識別機能としてスイスの十字付きの QR コードが表示されます。 このスイス版 QR コードには、支払に必要なすべての情報のデジタル形式が含まれています。
author: relnotes
ms.reviewer: kfend
ms.date: 03/24/2020
ms.assetid: 07f2610b-f2db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 334eb8cd0a1a9eb61bd2d1a5dadbd97729ce9c3b
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3231947"
---
# <a name="extended-swiss-localization-qr-bill-implementation"></a><span data-ttu-id="33018-104">拡張されたローカライズ (スイス): QR 請求書の実装</span><span class="sxs-lookup"><span data-stu-id="33018-104">Extended Swiss localization: QR-bill implementation</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="33018-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="33018-105">Enabled for</span></span>    |  <span data-ttu-id="33018-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="33018-106">Public preview</span></span> | <span data-ttu-id="33018-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="33018-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="33018-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="33018-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="33018-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="33018-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="33018-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="33018-110">Feb 3, 2020</span></span>| <span data-ttu-id="33018-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="33018-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="33018-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="33018-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="33018-113">スイスで使用されている支払伝票は 100 年以上前のもので、年間で 1 億回使用されています。</span><span class="sxs-lookup"><span data-stu-id="33018-113">The payment slips used in Switzerland go back over 100 years and are used 100 million times a year.</span></span> <span data-ttu-id="33018-114">支払トラフィックに対する規制要件の増加により、システムの変更が必要になりました。</span><span class="sxs-lookup"><span data-stu-id="33018-114">The increasing regulatory requirements for payment traffic have made some system modifications necessary.</span></span> <span data-ttu-id="33018-115">QR 請求書はスイスで使用されているさまざまな支払伝票に取って代わるようになり、効率性を高め、支払トラフィックを簡略化するために、ERP 側でのカバレッジが必要になります。</span><span class="sxs-lookup"><span data-stu-id="33018-115">The QR-bill now is replacing the existing multiplicity of payment slips in Switzerland, and the coverage on the ERP side is required to help with increasing efficiency and simplifying payment traffic.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="33018-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="33018-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="33018-117">この機能は、特定された対応するビジネス シナリオに沿った、QR 請求書の作成と処理に関わるスイス固有の要件を満たしています。</span><span class="sxs-lookup"><span data-stu-id="33018-117">This feature satisfies Swiss-specific requirements around QR-bill creation and processing aligned with identified and supported business scenarios.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="33018-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="33018-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="33018-119">[スイス QR-請求書をサポートする国固有の更新プログラム](https://support.microsoft.com/help/4540315) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="33018-119">[A country specific update to support Swiss QR-bills](https://support.microsoft.com/help/4540315) (docs)</span></span>
<!--docs end-->


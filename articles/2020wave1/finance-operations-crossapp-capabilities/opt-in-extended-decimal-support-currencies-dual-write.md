---
title: オプトインによる二重書き込みでの通貨の小数の拡張のサポート
description: Finance and Operations アプリと Common Data Service 間の二重書き込みを使用している組織では、Common Data Service の通貨と為替レートの小数点以下の桁数を増やすようにオプトインできます。
author: relnotes
ms.reviewer: sericks
ms.date: 06/26/2020
ms.assetid: b4fa7ba5-02b7-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: nhelgren
dynamics365pdf: true
ms.openlocfilehash: f2ba084d39efe1275c1e7eb07725e1fa60b066ce
ms.sourcegitcommit: 5c4dedb0e6948b1f237125c035518882f4cce114
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3530869"
---
# <a name="opt-in-extended-decimal-support-for-currencies-with-dual-write"></a><span data-ttu-id="65adf-103">オプトインによる二重書き込みでの通貨の小数の拡張のサポート</span><span class="sxs-lookup"><span data-stu-id="65adf-103">Opt-in extended decimal support for currencies with dual-write</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="65adf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="65adf-104">Enabled for</span></span>    |  <span data-ttu-id="65adf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="65adf-105">Public preview</span></span> | <span data-ttu-id="65adf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="65adf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="65adf-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="65adf-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="65adf-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="65adf-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="65adf-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="65adf-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="65adf-110">Finance and Operations アプリと Common Data Service での二重書き込みの使用時に、小数点以下の桁数が多いことが原因でデータが失われるのを防ぎます。</span><span class="sxs-lookup"><span data-stu-id="65adf-110">Prevent data loss on large decimals when using dual-write with Finance and Operations apps and Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="65adf-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="65adf-111">Feature details</span></span>
<!--feature detail start -->

<span data-ttu-id="65adf-112">Common Data Service の標準的なデプロイでは、通貨値の小数点以下の桁数は 4 桁、為替レート値の小数点以下の桁数は 10 桁です。</span><span class="sxs-lookup"><span data-stu-id="65adf-112">A standard Common Data Service deployment only provides four decimal places for currency values and 10 decimal places for exchange rate values.</span></span> <span data-ttu-id="65adf-113">Finance and Operations アプリで通貨値と為替レート値を二重書き込みする際にデータが失われないようにするために、ユーザーは Common Data Service で小数のサポートを拡張 (通貨の小数点以下の桁数を 10 桁、為替レートの小数点以下の桁数を 12 桁に) するようにオプトインできます。</span><span class="sxs-lookup"><span data-stu-id="65adf-113">To prevent data loss when dual writing currency and exchange rate values with Finance and Operations apps, users can opt in to extend the decimal support in Common Data Service to 10 decimal places on currency and 12 decimal places on exchange rate.</span></span> <span data-ttu-id="65adf-114">オプトインすると、通貨と為替レートのデータ型が新しい小数値に拡張され、既存のすべてのデータが新しい小数点以下の桁数に移行されます。</span><span class="sxs-lookup"><span data-stu-id="65adf-114">By opting in, the data type for currency and exchange rate will be extended to the new decimal values, and all existing data will be migrated to the new decimal place size.</span></span>

<span data-ttu-id="65adf-115">移行は任意です。</span><span class="sxs-lookup"><span data-stu-id="65adf-115">Migration is optional.</span></span> <span data-ttu-id="65adf-116">小数点以下の桁数を増やすことでメリットが得られる可能性のある場合は、移行を検討することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="65adf-116">If you might benefit from support for more decimal places, we recommend that you consider migration.</span></span> <span data-ttu-id="65adf-117">小数点以下の桁数が 4 桁を超える値が不要な組織では、移行の必要はありません。</span><span class="sxs-lookup"><span data-stu-id="65adf-117">Organizations that don't require values that have more than four decimal places don't have to migrate.</span></span>

> [!NOTE]
> <span data-ttu-id="65adf-118">この機能は現在、二重書き込みを使用する環境でのみサポートされています。</span><span class="sxs-lookup"><span data-stu-id="65adf-118">This feature is currently only supported for environments using dual-write.</span></span>
<!--feature detail end -->



## <a name="see-also"></a><span data-ttu-id="65adf-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="65adf-119">See also</span></span>

[<span data-ttu-id="65adf-120">二重書き込みの通貨データ型の移行</span><span class="sxs-lookup"><span data-stu-id="65adf-120">Currency data-type migration for dual-write</span></span>](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/currrency-decimal-places)






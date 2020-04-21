---
title: '拡張されたローカライズ (イタリア): 覚書 - 定期輸出業者への請求書発行'
description: Dynamics 365 Finance が、以前はイタリアのパートナー Cluster Reply によって提供された、拡張されたローカライズ (イタリア) (EXIL) アドインでのみ利用可能であった、イタリア語固有の機能セットが利用できるように拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 02/10/2020
ms.assetid: e6654f0b-f0db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: e5096815de30806d990c6604d9bede46d1a25f88
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3233102"
---
# <a name="extended-italian-localization-intent-letters--invoicing-of-usual-exporters"></a><span data-ttu-id="79d97-103">拡張されたローカライズ (イタリア): 覚書 - 定期輸出業者への請求書発行</span><span class="sxs-lookup"><span data-stu-id="79d97-103">Extended Italian localization: Intent letters – invoicing of usual exporters</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="79d97-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="79d97-104">Enabled for</span></span>    |  <span data-ttu-id="79d97-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="79d97-105">Public preview</span></span> | <span data-ttu-id="79d97-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="79d97-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="79d97-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="79d97-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="79d97-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="79d97-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="79d97-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="79d97-109">Feb 3, 2020</span></span>| <span data-ttu-id="79d97-110">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="79d97-110">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="79d97-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="79d97-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="79d97-112">イタリアに Dynamics 365 Finance を展開するグローバルおよびローカルの顧客は、拡張されたローカライズ (イタリア) (EXIL) アドインやその他イタリアの市場で利用できる類似の機能のアドインを適用することなく、厳選された競争力のあるイタリア語の規制機能をそのまま利用できます。</span><span class="sxs-lookup"><span data-stu-id="79d97-112">Global and local customers who deploy Dynamics 365 Finance in Italy receive selected regulatory and competitive Italian features out of the box without the need to apply the Extended Italian Localization (EXIL) add-in or any other add-in with similar features available in the Italian market.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="79d97-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="79d97-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="79d97-114">前の期間、前の会計年度 (固定限度額の場合)、前の 12 か月 (可変限度額の場合) にて、海外での売上が総売上の 10% を超える会社は、*定期輸出業者*と呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="79d97-114">A company is called a *usual exporter* when, in the previous period, the previous calendar year for fixed plafond or the previous 12 months for variable plafond, more than 10 percent of the whole revenue is from sales to foreign countries.</span></span> <span data-ttu-id="79d97-115">このタイプの会社は特別な免税措置が受けられ、前の期間における外国への売上の限度額以内で、消費税を支払うことなく物品やサービスを購入および輸入できます。</span><span class="sxs-lookup"><span data-stu-id="79d97-115">This type of company has a special tax-exemption process where they can purchase and import goods and services without paying sales tax, within a limited value (plafond) of their sales to foreign countries in a previous period.</span></span> 

<span data-ttu-id="79d97-116">その年度中にこの限度額に達したときは、通常の消費税率で購入を続行できます。</span><span class="sxs-lookup"><span data-stu-id="79d97-116">When this limit value is reached during the year, they continue to buy using the normal sales tax percentage.</span></span> <span data-ttu-id="79d97-117">*定期輸出業者*は、仕入先に税金の支払免除を宣言する覚書 (番号と日付が記載されたレター) を送付する必要があります。</span><span class="sxs-lookup"><span data-stu-id="79d97-117">The *usual exporter* company must send an intent declaration (a numbered and dated letter) to its vendors declaring its exemption to pay tax.</span></span>

<span data-ttu-id="79d97-118">*定期輸出業者*の免税限度額を超えたときは、仕入先が消費税込みの請求書をすぐに発行できるように、その旨を通知する必要があります。</span><span class="sxs-lookup"><span data-stu-id="79d97-118">When the *usual exporter* company exceeds its tax plafond, it must communicate this to its vendors so that they will immediately begin issuing invoices with sales tax.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="79d97-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="79d97-119">See also</span></span>


<!--docs start-->
<span data-ttu-id="79d97-120">[覚書 – 定期輸出業者への請求書発行](https://docs.microsoft.com/dynamics365/finance/localizations/emea-ita-exil-intent-letter) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="79d97-120">[Intent letters - Invoicing of usual exporters](https://docs.microsoft.com/dynamics365/finance/localizations/emea-ita-exil-intent-letter) (docs)</span></span>
<!--docs end-->


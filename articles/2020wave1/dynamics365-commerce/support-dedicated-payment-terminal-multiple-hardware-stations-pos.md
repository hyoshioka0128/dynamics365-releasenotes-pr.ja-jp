---
title: POS の複数のハードウェア ステーションをインストールした専用の支払ターミナルのサポート
description: この機能により、販売時点管理 (POS) デバイスと支払ターミナル間の一対一関連付けが可能になります。 この機能が有効になっていると、レシートの印刷やキャッシュ ドロワー用のハードウェア ステーションがなくても、電子メール レシートと現金以外の支払いを使用する取引を実行できます。 レシートまたはキャッシュ ドロワーへのアクセスを必要とするシナリオが発生した場合、店員は、必要なデバイスを備えたハードウェア ステーションを選択するよう求められます。
author: relnotes
ms.reviewer: josaw
ms.date: 06/24/2020
ms.assetid: c9e83539-618e-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: ad425704bf3e94391a449851cf4e8fc3e8c3ee6c
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522883"
---
# <a name="support-for-dedicated-payment-terminal-with-multiple-hardware-stations-in-pos"></a><span data-ttu-id="56775-105">POS の複数のハードウェア ステーションをインストールした専用の支払ターミナルのサポート</span><span class="sxs-lookup"><span data-stu-id="56775-105">Support for dedicated payment terminal with multiple hardware stations in POS</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="56775-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="56775-106">Enabled for</span></span>    |  <span data-ttu-id="56775-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="56775-107">Public preview</span></span> | <span data-ttu-id="56775-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="56775-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="56775-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="56775-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="56775-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="56775-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="56775-111">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="56775-111">May 18, 2020</span></span>| <span data-ttu-id="56775-112">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="56775-112">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="56775-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="56775-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="56775-114">現代の小売業者とその顧客は柔軟性を求めています。</span><span class="sxs-lookup"><span data-stu-id="56775-114">Modern retailers and their customers demand flexibility.</span></span> <span data-ttu-id="56775-115">この機能は、非接触型の取引を促し、紙形式のレシートの無駄を削減しながら柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="56775-115">This feature delivers flexibility while encouraging contactless transactions and reduced waste in the form of paper receipts.</span></span> <span data-ttu-id="56775-116">店員が現金を受け付けるかレシートを印刷する必要があるシナリオが発生した場合は、取引を完了するためにハードウェア ステーションを選択するよう求められます。</span><span class="sxs-lookup"><span data-stu-id="56775-116">If a scenario arises in which the store associate must accept cash or print a receipt, they are prompted to select a hardware station to complete the transaction.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="56775-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="56775-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="56775-118">この機能により、特定かつ専用の支払ターミナルを使用するようにレジスター上のハードウェア ステーションを設定できますが、レシート プリンターとキャッシュ ドロワー デバイスはアドホックで選択できます。</span><span class="sxs-lookup"><span data-stu-id="56775-118">This feature allows for the hardware station on the register to be set up so that it has a specific, dedicated payment terminal, but the receipt printer and cash drawer devices can be selected ad hoc.</span></span> <span data-ttu-id="56775-119">店員がレシートを印刷するか現金を受け付ける必要がある場合は、それらのデバイスを備えたハードウェア ステーションを選択するよう求められます。</span><span class="sxs-lookup"><span data-stu-id="56775-119">When a store associate needs to print a receipt or accept cash, they are prompted to select a hardware station that has those devices.</span></span> <span data-ttu-id="56775-120">選択したハードウェア ステーションは残りの取引に使用されます。ユーザーにハードウェア ステーションの選択を求めるメッセージが再度表示されることはありません。</span><span class="sxs-lookup"><span data-stu-id="56775-120">The hardware station selected will then be used for the rest of that transaction without reprompting the user.</span></span> <span data-ttu-id="56775-121">レシート プリンターまたはキャッシュ ドロワーを必要とする次回の取引では、店員は再びハードウェア ステーションを選択するよう求められます。</span><span class="sxs-lookup"><span data-stu-id="56775-121">For the next transaction that requires a receipt printer or cash drawer, the store associate will again be prompted to select a hardware station.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="56775-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="56775-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="56775-123">[専用の支払ターミナルおよびプリンターとキャッシュ ドロワーのプロンプト](https://docs.microsoft.com/dynamics365/commerce/pos-multi-hws) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="56775-123">[Dedicated payment terminals and prompts for a printer and cash drawer](https://docs.microsoft.com/dynamics365/commerce/pos-multi-hws) (docs)</span></span>
<!--docs end-->

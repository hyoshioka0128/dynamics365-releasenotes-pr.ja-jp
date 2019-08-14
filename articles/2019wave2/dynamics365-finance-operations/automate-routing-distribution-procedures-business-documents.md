---
title: ビジネス ドキュメントのルーティングと配布の手順を自動化する
description: 自社のドキュメント配布手順を自動化して時間と費用を節約します
author: relnotes
ms.reviewer: kfend
ms.date: 07/31/2019
ms.assetid: f662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 36213d3f2fbe934d842bd35a5bccd1961c3f1449
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854066"
---
# <a name="automate-routing-and-distribution-procedures-for-business-documents"></a><span data-ttu-id="77a8f-103">ビジネス ドキュメントのルーティングと配布の手順を自動化する</span><span class="sxs-lookup"><span data-stu-id="77a8f-103">Automate routing and distribution procedures for business documents</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="77a8f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="77a8f-104">Enabled for</span></span>    |  <span data-ttu-id="77a8f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="77a8f-105">Public preview</span></span> | <span data-ttu-id="77a8f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="77a8f-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="77a8f-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="77a8f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="77a8f-108">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="77a8f-108">December 2019</span></span>| |


## <a name="business-value"></a><span data-ttu-id="77a8f-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="77a8f-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="77a8f-110">あらゆる規模の組織に、外部の利害関係者と通信できる ERP ソリューションが必要です。</span><span class="sxs-lookup"><span data-stu-id="77a8f-110">Organizations of all sizes require an ERP solution capable of communicating with external stakeholders.</span></span> <span data-ttu-id="77a8f-111">Dynamics 365 for Finance and Operations では、ドキュメントが印刷形式か電子形式かにかかわらず、顧客の基本設定に基づいて複雑な配布手順を自動化できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="77a8f-111">With Dynamics 365 for Finance and Operations, customers can now automate complex distribution instructions based on customer preferences, whether documents are in printed or electronic format.</span></span> <span data-ttu-id="77a8f-112">ビジネス プロセス出力マネージャーにより、パワー ユーザーは、組織のために生成されるビジネス ドキュメントの製作を管理および監視できます。</span><span class="sxs-lookup"><span data-stu-id="77a8f-112">The business process output manager gives power users the ability to manage and monitor the production of business documents that are produced on behalf of the organization.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="77a8f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="77a8f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="77a8f-114">ビジネスでは、ドキュメントに依存して外の世界とやり取りします。</span><span class="sxs-lookup"><span data-stu-id="77a8f-114">Your business relies on documents to transact with the outside world.</span></span> <span data-ttu-id="77a8f-115">Dynamics 365 for Finance and Operations には、アプリケーション ビジネス プロセスによって生成されるドキュメント用の強力なルーティングおよび配布エンジンが用意されています。</span><span class="sxs-lookup"><span data-stu-id="77a8f-115">Dynamics 365 for Finance and Operations provides a powerful routing and distribution engine for documents that are produced by an application business process.</span></span> <span data-ttu-id="77a8f-116">パワー ユーザーは、複雑なビジネス要件を表す豊富なドキュメント ルーティングおよび印刷ルールを簡単に構成できます。</span><span class="sxs-lookup"><span data-stu-id="77a8f-116">Power users can easily configure rich document routing and printing rules that represent complex business requirements.</span></span> <span data-ttu-id="77a8f-117">顧客や仕入先へのドキュメントのルーティングに対処する自動配布手順を定義して、通信の詳細や基本設定の検索などの 1 回限りの操作に時間を費やさないようにすることで、時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="77a8f-117">You can save time by defining automatic distribution instructions that take care of routing documents to customers and vendors so they don’t spend time on one-off operations like looking up communication details and preferences.</span></span>  

<span data-ttu-id="77a8f-118">追加の機能には、単一のビジネス アクションから複数のドキュメントを送信する機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="77a8f-118">Additional capabilities include the ability to send multiple documents from a single business action.</span></span> <span data-ttu-id="77a8f-119">たとえば、次のアクションを実行する売上請求書を転記することによってトリガーされるビジネス プロセス出力手順を作成できます。</span><span class="sxs-lookup"><span data-stu-id="77a8f-119">For instance, you can create business process output instructions that are triggered by posting a sales invoice that performs the following actions:</span></span>

- <span data-ttu-id="77a8f-120">カスタマイズされたドキュメント デザインを使用して、顧客が希望する連絡先アドレスに請求書のコピーをメールで送信します。</span><span class="sxs-lookup"><span data-stu-id="77a8f-120">Emails the customer a copy of the invoice to their preferred contact address using a customized document design.</span></span>
- <span data-ttu-id="77a8f-121">ネットワーク デバイスで、購入した品目の在庫を含む販売梱包明細を印刷します。</span><span class="sxs-lookup"><span data-stu-id="77a8f-121">Prints a sales packing slip that includes an inventory of the items purchased on a network device.</span></span>
- <span data-ttu-id="77a8f-122">購入が事前に定義された金額を超えた場合、または顧客が特定の地域に居住しているか特定の支払条件がある場合に、システムに売上請求書のコピーをアーカイブします。</span><span class="sxs-lookup"><span data-stu-id="77a8f-122">Archives a copy of the sales invoice in the system when the purchase exceeds a pre-defined amount or the customer resides in a specific region or has specific payment terms.</span></span>
- <span data-ttu-id="77a8f-123">顧客の出荷地域にある倉庫ラベル プリンターで一連の梱包ラベルを印刷します。</span><span class="sxs-lookup"><span data-stu-id="77a8f-123">Print a series of packing labels on a warehouse label printer that's located in the customer's shipping region.</span></span>

<span data-ttu-id="77a8f-124">パワー ユーザー向けに設計された組み込みツールを活用して、エンタープライズ ドキュメントのルーティングと配布の要件を管理することにより、時間と費用を節約できます。</span><span class="sxs-lookup"><span data-stu-id="77a8f-124">Save time and money by taking advantage of built-in tools designed for power users to manage Enterprise document routing and distribution requirements.</span></span>
<!--feature detail end -->












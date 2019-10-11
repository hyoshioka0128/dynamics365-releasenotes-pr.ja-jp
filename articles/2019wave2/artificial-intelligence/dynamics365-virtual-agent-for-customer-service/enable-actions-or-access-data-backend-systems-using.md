---
title: Microsoft Flow でのバックエンド システムからのアクションまたはデータへのアクセスの有効化
description: Microsoft Flow でのバックエンド システムからのアクションまたはデータへのアクセスの有効化
author: relnotes
ms.reviewer: iawilt
ms.date: 08/27/2019
ms.assetid: fc63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: clmori
dynamics365pdf: true
ms.openlocfilehash: 43eef055dff34249f4cc739f18b499e3cb6401d5
ms.sourcegitcommit: 856d36597ee54f817177a3682a0048ad1390c936
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2019
ms.locfileid: "2003385"
---
# <a name="enable-actions-or-access-data-from-back-end-systems-with-microsoft-flow"></a><span data-ttu-id="e537b-103">Microsoft Flow でのバックエンド システムからのアクションまたはデータへのアクセスの有効化</span><span class="sxs-lookup"><span data-stu-id="e537b-103">Enable actions or access data from back-end systems with Microsoft Flow</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="e537b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e537b-104">Enabled for</span></span>    |  <span data-ttu-id="e537b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e537b-105">Public preview</span></span> | <span data-ttu-id="e537b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e537b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e537b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e537b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="e537b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e537b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e537b-109">2019 年 5 月 30 日</span><span class="sxs-lookup"><span data-stu-id="e537b-109">May 30, 2019</span></span>| <span data-ttu-id="e537b-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="e537b-110">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="e537b-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e537b-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e537b-112">ソリューションでバックエンドのワークフローまたはビジネス プロセスを起動するためにボットを必要とする状況があります。たとえば、ユーザーがメール アドレスに送信される今後の取引について質問する場合です。</span><span class="sxs-lookup"><span data-stu-id="e537b-112">There are situations where solutions require a bot to trigger a back-end workflow or business process—for example, when a user asks a question about upcoming deals to be sent to an email address.</span></span>

<span data-ttu-id="e537b-113">Virtual Agent for Customer Service は Microsoft Flow と統合して、顧客サービス マネージャーが既存のフローを起動したり、コードを書かずにバックエンド システムを呼び出す新しいフローを作成したりできるようにします。</span><span class="sxs-lookup"><span data-stu-id="e537b-113">Virtual Agent for Customer Service integrates with Microsoft Flow, empowering customer service managers to trigger existing flows or create new ones that call back-end systems, without writing code.</span></span> 

<!--
![](media/enable-actions-or-access-data-backend-systems-using-flows-1.png "")--> <!-- Picture 462209731 -->  

<span data-ttu-id="e537b-114">Microsoft Flow には、一般的なサービスへの何百ものコネクタがあり、それらを使用して既存の内部ワークフローを自動化することができます。</span><span class="sxs-lookup"><span data-stu-id="e537b-114">Microsoft Flow has hundreds of connectors to common services that can be used to automate existing internal workflows.</span></span> <span data-ttu-id="e537b-115">その後、これらのコネクタを Virtual Agent for Customer Service で作成されたダイアログから直接呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="e537b-115">These connectors can then be called directly from dialogs authored in the Virtual Agent for Customer Service.</span></span> 

<span data-ttu-id="e537b-116">カスタム コネクタを介したカスタム コードおよびレガシ システムへの接続にも対応するため、ビジネス ニーズの変化や拡大に伴い Virtual Agent for Customer Service を拡張する機会が得られます。</span><span class="sxs-lookup"><span data-stu-id="e537b-116">Custom code and connections to legacy systems can also be supported through custom connectors, providing opportunities to extend the Virtual Agent for Customer Service as your business needs change and grow.</span></span> 

<!--
![](media/enable-actions-or-access-data-backend-systems-using-flows-2.png "")--> <!-- Picture 1566914757 -->
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="e537b-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="e537b-117">See also</span></span>

<span data-ttu-id="e537b-118">[Microsoft Flow を使用してボットにアクションを追加する](https://docs.microsoft.com/dynamics365/ai/customer-service-virtual-agent/how-to-flow) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e537b-118">[Add actions to your bot using Microsoft Flow](https://docs.microsoft.com/dynamics365/ai/customer-service-virtual-agent/how-to-flow) (docs)</span></span>

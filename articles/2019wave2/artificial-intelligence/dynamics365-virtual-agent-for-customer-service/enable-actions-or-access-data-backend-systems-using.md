---
title: Microsoft Flow でのバックエンド システムからのアクションまたはデータへのアクセスの有効化
description: Microsoft Flow でのバックエンド システムからのアクションまたはデータへのアクセスの有効化
author: relnotes
ms.reviewer: shellyha
ms.date: 07/31/2019
ms.assetid: fc63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omaraf
dynamics365pdf: true
ms.openlocfilehash: 2c243ccdd7690fd261bcff6f3be0fc1c2ff3b1ed
ms.sourcegitcommit: d7e3131b7435c3c6581f61ee059895f9045cc379
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/03/2019
ms.locfileid: "1856109"
---
# <a name="enable-actions-or-access-data-from-back-end-systems-with-microsoft-flow"></a><span data-ttu-id="fac1a-103">Microsoft Flow でのバックエンド システムからのアクションまたはデータへのアクセスの有効化</span><span class="sxs-lookup"><span data-stu-id="fac1a-103">Enable actions or access data from back-end systems with Microsoft Flow</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="fac1a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="fac1a-104">Enabled for</span></span>    |  <span data-ttu-id="fac1a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="fac1a-105">Public preview</span></span> | <span data-ttu-id="fac1a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="fac1a-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="fac1a-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="fac1a-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="fac1a-108">2019 年 5 月</span><span class="sxs-lookup"><span data-stu-id="fac1a-108">May 2019</span></span>| <span data-ttu-id="fac1a-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="fac1a-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="fac1a-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="fac1a-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="fac1a-111">ソリューションでバックエンドのワークフローまたはビジネス プロセスを起動するためにボットを必要とする状況があります。たとえば、ユーザーが今後の取引についての質問をメール アドレスに送信するように要求する場合です。</span><span class="sxs-lookup"><span data-stu-id="fac1a-111">There are situations where solutions require a bot to trigger a back-end workflow or business process—for example, when a user asks a question about upcoming deals to be sent to an email address.</span></span>

<span data-ttu-id="fac1a-112">Virtual Agent for Customer Service は Microsoft Flow と統合して、顧客サービス マネージャーが既存のフローを起動したり、コードを書かずにバックエンド システムを呼び出す新しいフローを作成したりできるようにします。</span><span class="sxs-lookup"><span data-stu-id="fac1a-112">Virtual Agent for Customer Service integrates with Microsoft Flow, empowering customer service managers to trigger existing flows or create new ones that call back-end systems, without writing code.</span></span> 

<!--
![](media/enable-actions-or-access-data-backend-systems-using-flows-1.png "")--> <!-- Picture 462209731 -->  

<span data-ttu-id="fac1a-113">Microsoft Flow には、一般的なサービスへの何百ものコネクタがあり、それらを使用して既存の内部ワークフローを自動化することができます。</span><span class="sxs-lookup"><span data-stu-id="fac1a-113">Microsoft Flow has hundreds of connectors to common services that can be used to automate existing internal workflows.</span></span> <span data-ttu-id="fac1a-114">その後、これらのコネクタを Virtual Agent for Customer Service で作成されたダイアログから直接呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="fac1a-114">These connectors can then be called directly from dialogs authored in the Virtual Agent for Customer Service.</span></span> 

<span data-ttu-id="fac1a-115">カスタム コネクタを介してカスタム コードおよびレガシ システムへの接続もサポートでき、ビジネス ニーズの変化や拡大に伴い Virtual Agent for Customer Service を拡張する機会が提供されます。</span><span class="sxs-lookup"><span data-stu-id="fac1a-115">Custom code and connections to legacy systems can also be supported through custom connectors, providing opportunities to extend the Virtual Agent for Customer Service as your business needs change and grow.</span></span> 

<!--
![](media/enable-actions-or-access-data-backend-systems-using-flows-2.png "")--> <!-- Picture 1566914757 -->
<!--feature detail end -->












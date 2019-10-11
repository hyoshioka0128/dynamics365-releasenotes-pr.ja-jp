---
title: 変数の機能
description: 変数の機能
author: relnotes
ms.reviewer: iawilt
ms.date: 08/30/2019
ms.assetid: 0064278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: clmori
dynamics365pdf: true
ms.openlocfilehash: dd4de3f915ed88aab0019b22a515fa3ce9fbf928
ms.sourcegitcommit: 856d36597ee54f817177a3682a0048ad1390c936
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2019
ms.locfileid: "2003572"
---
# <a name="variable-capabilities"></a><span data-ttu-id="8a7a5-103">変数の機能</span><span class="sxs-lookup"><span data-stu-id="8a7a5-103">Variable capabilities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="8a7a5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8a7a5-104">Enabled for</span></span>    |  <span data-ttu-id="8a7a5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8a7a5-105">Public preview</span></span> | <span data-ttu-id="8a7a5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8a7a5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8a7a5-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="8a7a5-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="8a7a5-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8a7a5-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8a7a5-109">2019 年 5 月 30 日</span><span class="sxs-lookup"><span data-stu-id="8a7a5-109">May 30, 2019</span></span>| <span data-ttu-id="8a7a5-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="8a7a5-110">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8a7a5-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8a7a5-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8a7a5-112">変数は、後で会話で参照できる顧客情報を格納するために使用され、複雑な対話を作成したり他のシステムと通信したりする際にボット作成者の時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="8a7a5-112">Variables are used to store customer information that can be referenced later in a conversation, saving the bot author time when creating complex interactions and communicating with other systems.</span></span> 
 
<span data-ttu-id="8a7a5-113">システムは、ユーザーの自然言語応答を解析し、適切な顧客情報を抽出して、それを会話で使用するために変数に割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="8a7a5-113">The system can parse a user’s natural language response, extracting the appropriate customer information and assigning it to a variable for use in the conversation.</span></span> <span data-ttu-id="8a7a5-114">変数は、顧客との複雑で豊かな会話を可能にし、顧客サービス エージェントの呼び出しを減らす強力なツールです。</span><span class="sxs-lookup"><span data-stu-id="8a7a5-114">Variables enable complex and rich conversations with a customer and are powerful tools to reduce customer service agent calls.</span></span>

<span data-ttu-id="8a7a5-115">**変数の主な機能**</span><span class="sxs-lookup"><span data-stu-id="8a7a5-115">**Key capabilities for variables**</span></span> 

-  <span data-ttu-id="8a7a5-116">会話での変数の使用</span><span class="sxs-lookup"><span data-stu-id="8a7a5-116">Use variables in conversations</span></span> 
-  <span data-ttu-id="8a7a5-117">Microsoft Flow の入力および出力としての変数の使用</span><span class="sxs-lookup"><span data-stu-id="8a7a5-117">Use variables for Microsoft Flow inputs and outputs</span></span> 
-  <span data-ttu-id="8a7a5-118">強力なツールを使用した変数のデバッグ</span><span class="sxs-lookup"><span data-stu-id="8a7a5-118">Debug variables with powerful tools</span></span>
-  <span data-ttu-id="8a7a5-119">変数に対する算術演算のサポート</span><span class="sxs-lookup"><span data-stu-id="8a7a5-119">Support for mathematical operations on variables</span></span> 
-  <span data-ttu-id="8a7a5-120">変数の再割り当て</span><span class="sxs-lookup"><span data-stu-id="8a7a5-120">Variable reassignment</span></span> 
-  <span data-ttu-id="8a7a5-121">カスタム変数の型と同義語</span><span class="sxs-lookup"><span data-stu-id="8a7a5-121">Custom variable types and synonyms</span></span> 
-  <span data-ttu-id="8a7a5-122">システム提供の変数の型</span><span class="sxs-lookup"><span data-stu-id="8a7a5-122">System-supplied variable types</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="8a7a5-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="8a7a5-123">See also</span></span>

<span data-ttu-id="8a7a5-124">[変数を操作する](https://docs.microsoft.com/dynamics365/ai/customer-service-virtual-agent/how-to-variables) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8a7a5-124">[Work with variables](https://docs.microsoft.com/dynamics365/ai/customer-service-virtual-agent/how-to-variables) (docs)</span></span>

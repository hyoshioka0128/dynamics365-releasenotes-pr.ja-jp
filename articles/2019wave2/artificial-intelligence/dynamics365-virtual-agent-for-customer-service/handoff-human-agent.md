---
title: 人間のエージェントへの引き継ぎ
description: ボットから人のエージェントに顧客の会話を適切に引き渡します。
author: relnotes
ms.reviewer: shellyhaverkamp
ms.date: 06/13/2019
ms.assetid: cc096b69-725d-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: omaraf
dynamics365pdf: true
ms.openlocfilehash: 327ae484591b3c17a83bbae9fc8fabe58f2b58c0
ms.sourcegitcommit: 59f5bc1ad5c9bbbfbeff6608476b60c0b2da58c0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2019
ms.locfileid: "1735990"
---
# <a name="handoff-to-a-human-agent"></a><span data-ttu-id="e871a-103">人間のエージェントへの引き継ぎ</span><span class="sxs-lookup"><span data-stu-id="e871a-103">Handoff to a human agent</span></span>

[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

<span data-ttu-id="e871a-104">ボットがユーザーの要求を処理できない場合、またはユーザーが会話の任意の時点でエージェントとの会話を要求した場合、人間のエージェントに適切に切り替えることが重要です。</span><span class="sxs-lookup"><span data-stu-id="e871a-104">When a bot can’t handle the user’s requests or the user asks to talk to an agent at any point in the conversation, it’s important to gracefully bring in a human agent.</span></span> <span data-ttu-id="e871a-105">Dynamics 365 Virtual Agent for Customer Service では、顧客サービス マネージャーは複数のライブチャット エンゲージメント ハブを構成して接続できるようになります。</span><span class="sxs-lookup"><span data-stu-id="e871a-105">In Dynamics 365 Virtual Agent for Customer Service, we are providing customer service managers with the ability to configure and connect to multiple live chat engagement hubs.</span></span>
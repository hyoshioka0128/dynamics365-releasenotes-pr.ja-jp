---
title: すべての顧客に関する完全なコンテキストを一元的に取得する
description: すべての顧客の履歴コンテキストなど、必要なすべての情報を 1 か所で入手できます。
author: relnotes
ms.reviewer: udag
ms.date: 04/06/2020
ms.assetid: 8e04c2f7-5ecb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: efgilboa
dynamics365pdf: true
ms.openlocfilehash: 25f43ef6303c280c31e8e8e1e28b6a6d38273e0f
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255257"
---
# <a name="gain-full-context-on-every-customer-in-one-place"></a><span data-ttu-id="131e2-103">すべての顧客に関する完全なコンテキストを一元的に取得する</span><span class="sxs-lookup"><span data-stu-id="131e2-103">Gain full context on every customer in one place</span></span>


| <span data-ttu-id="131e2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="131e2-104">Enabled for</span></span>    |  <span data-ttu-id="131e2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="131e2-105">Public preview</span></span> | <span data-ttu-id="131e2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="131e2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="131e2-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="131e2-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="131e2-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="131e2-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="131e2-109">2020 年 4 月 6 日</span><span class="sxs-lookup"><span data-stu-id="131e2-109">Apr 6, 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="131e2-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="131e2-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="131e2-111">顧客と交わすすべてのコミュニケーションは、顧客を獲得するチャンスになります。</span><span class="sxs-lookup"><span data-stu-id="131e2-111">Every communication with a customer is an opportunity to win them over.</span></span> <span data-ttu-id="131e2-112">インサイド販売担当者が潜在顧客リストに目を通すと、その数の多さから、コミュニケーションの履歴、顧客のニーズ、具体的な状況など、全体像を把握するのに苦労することがよくあります。</span><span class="sxs-lookup"><span data-stu-id="131e2-112">As inside sellers run through a long list of potential customers, they often struggle to gain a holistic view, including history of communications, customer needs, and specific circumstances.</span></span> <span data-ttu-id="131e2-113">このビューは、顧客にとって最も関連性が高く、できるだけプラスの結果が得られる、正しいピッチを作成するために必要です。</span><span class="sxs-lookup"><span data-stu-id="131e2-113">This view is necessary for crafting the right pitch most relevant to the customer and likely to achieve a positive outcome.</span></span> 

<span data-ttu-id="131e2-114">インサイド セールス担当者が顧客との会話を最大限活用するのを支援するために、営業の加速は複数のエンティティにわたって過去の活動、製品、アカウント、リレーションシップ スコアなどの関連コンテキストを 1 つにまとめ、すべて専用フォームで利用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="131e2-114">To help inside sellers make the most out of every customer conversation, Sales Acceleration brings together relevant context across multiple entities, including past activities, product, account, relationship scores and more—all made available in a dedicated form.</span></span> <span data-ttu-id="131e2-115">この一目でわかる概要により、販売担当者がコンテキストを切り替えることなく、時間を節約し、リードを変換して、より短時間で商談を成立させるために、すべてのコミュニケーションを最大限活用するのを支援します。</span><span class="sxs-lookup"><span data-stu-id="131e2-115">This at-a-glance summary helps sellers make the most out of every communication, without switching context—saving time, converting leads, and closing deals, faster.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="131e2-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="131e2-116">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="131e2-117">**必要なすべての情報を 1 か所で入手できる**: 関連するエンティティから顧客情報を収集して表示するマルチタブ エクスペリエンスを活用することで、すべてのコミュニケーションで効果的なメッセージを作成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="131e2-117">**Get all the information you need in a single place**: Benefit from a multitab experience that collects and surfaces customer information from related entities to help craft winning messages for every communication.</span></span>

- <span data-ttu-id="131e2-118">**すべての顧客の履歴コンテキストを受け取る**: システム全体にわたって統合されたデータを通じて、タイムライン、メモ、追加データを介して現在および過去のアクティビティを、すべてエンティティ フォーム上の内部タブで確認できます。</span><span class="sxs-lookup"><span data-stu-id="131e2-118">**Receive historical context for every customer**: View present and past activities via the timeline, note, and additional data through integrated data across the system, all available with internal tabs on the entity form.</span></span>
<!--feature detail end -->

<!--note from editor: this image needs to be edited down to show more focus. A full screenshot is too busy and does not yield a positive user experience. ![Form](media/work-queue-form.png "Form")-->
<!-- Picture 1 -->









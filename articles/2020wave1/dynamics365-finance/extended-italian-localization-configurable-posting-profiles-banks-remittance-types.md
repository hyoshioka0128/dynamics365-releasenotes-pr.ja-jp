---
title: '拡張されたローカライズ (イタリア): 銀行や送金タイプ別に構成可能な転記プロファイル'
description: Dynamics 365 Finance が、以前はイタリアのパートナー Cluster Reply によって提供された、拡張されたローカライズ (イタリア) (EXIL) アドインでのみ利用可能であった、イタリア語固有の機能セットが利用できるように拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 05/05/2020
ms.assetid: 4e761e5a-f1db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 28d561dbe7c95707b0d2ce1b9c5ae99da8512c0e
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349338"
---
# <a name="extended-italian-localization-configurable-posting-profiles-for-banks-and-remittance-types"></a><span data-ttu-id="a850f-103">拡張されたローカライズ (イタリア): 銀行や送金タイプ別に構成可能な転記プロファイル</span><span class="sxs-lookup"><span data-stu-id="a850f-103">Extended Italian localization: Configurable posting profiles for banks and remittance types</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="a850f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a850f-104">Enabled for</span></span>    |  <span data-ttu-id="a850f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a850f-105">Public preview</span></span> | <span data-ttu-id="a850f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a850f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a850f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a850f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a850f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a850f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a850f-109">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a850f-109">May 1, 2020</span></span>| <span data-ttu-id="a850f-110">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="a850f-110">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a850f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a850f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a850f-112">イタリアに Dynamics 365 Finance を展開するグローバルおよびローカルの顧客は、拡張されたローカライズ (イタリア) (EXIL) アドインやその他イタリアの市場で利用できる類似の機能のアドインを適用することなく、厳選された競争力のあるイタリア語の規制機能をそのまま利用できます。</span><span class="sxs-lookup"><span data-stu-id="a850f-112">Global and local customers who deploy Dynamics 365 Finance in Italy receive selected regulatory and competitive Italian features out of the box without the need to apply the Extended Italian Localization (EXIL) add-in or any other add-in with similar features available in the Italian market.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a850f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a850f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a850f-114">ドラフトが会社の銀行の 1 つに送金されるときは、一般会計の別の相手勘定を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a850f-114">When the drafts are remitted to one of the company banks, it is necessary to update a different offset account in the general ledger.</span></span> <span data-ttu-id="a850f-115">これは、受取手形の場合はユーザーによって選択された銀行や送金タイプに基づいており、支払手形の場合はユーザーによって選択された銀行に基づいています。</span><span class="sxs-lookup"><span data-stu-id="a850f-115">This is based on the bank and the remittance type selected by the user in the case of bills of exchange, and based on the bank selected by the user in the case of promissory notes.</span></span> 

<span data-ttu-id="a850f-116">この機能を使用すると、会社の銀行口座ごとに異なる専用の転記プロファイルを作成し、選択した銀行にリンクされた勘定科目にそのトランザクションを転記できます。</span><span class="sxs-lookup"><span data-stu-id="a850f-116">The feature allows you to create a different dedicated posting profile for every company bank account to post the transactions in the ledger account linked to the selected bank.</span></span> <span data-ttu-id="a850f-117">銀行口座は仕訳作成時に指定され、その銀行口座は特定の転記プロファイルにリンクされているため、送金のトランザクションはその銀行に接続された主勘定を使用します。</span><span class="sxs-lookup"><span data-stu-id="a850f-117">The bank account is specified during the journal creation, and because it is linked to a specific posting profile, the transactions for the remittance will use the main account connected to the bank.</span></span>
<!--feature detail end -->










---
title: '拡張されたローカライズ (イタリア): 銀行や送金タイプ別に構成可能な転記プロファイル'
description: Dynamics 365 Finance が、以前はイタリアのパートナー Cluster Reply によって提供された、拡張されたローカライズ (イタリア) (EXIL) アドインでのみ利用可能であった、イタリア語固有の機能セットが利用できるように拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 12/15/2019
ms.assetid: 4e761e5a-f1db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: d2da1ae619e7171f8798ff481781fdadcbc518b0
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219273"
---
# <a name="extended-italian-localization-configurable-posting-profiles-for-banks-and-remittance-types"></a><span data-ttu-id="f9d2e-103">拡張されたローカライズ (イタリア): 銀行や送金タイプ別に構成可能な転記プロファイル</span><span class="sxs-lookup"><span data-stu-id="f9d2e-103">Extended Italian localization: Configurable posting profiles for banks and remittance types</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="f9d2e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f9d2e-104">Enabled for</span></span>    |  <span data-ttu-id="f9d2e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f9d2e-105">Public preview</span></span> | <span data-ttu-id="f9d2e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f9d2e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f9d2e-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f9d2e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f9d2e-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="f9d2e-108">May 2020</span></span>| <span data-ttu-id="f9d2e-109">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="f9d2e-109">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f9d2e-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f9d2e-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f9d2e-111">イタリアに Dynamics 365 Finance を展開するグローバルおよびローカルの顧客は、拡張されたローカライズ (イタリア) (EXIL) アドインやその他イタリアの市場で利用できる類似の機能のアドインを適用することなく、厳選された競争力のあるイタリア語の規制機能をそのまま利用できます。</span><span class="sxs-lookup"><span data-stu-id="f9d2e-111">Global and local customers who deploy Dynamics 365 Finance in Italy receive selected regulatory and competitive Italian features out of the box without the need to apply the Extended Italian Localization (EXIL) add-in or any other add-in with similar features available in the Italian market.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f9d2e-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f9d2e-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f9d2e-113">ドラフトが会社の銀行の 1 つに送金されるときは、一般会計の別の相手勘定を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f9d2e-113">When the drafts are remitted to one of the company banks, it is necessary to update a different offset account in the general ledger.</span></span> <span data-ttu-id="f9d2e-114">これは、受取手形の場合はユーザーによって選択された銀行や送金タイプに基づいており、支払手形の場合はユーザーによって選択された銀行に基づいています。</span><span class="sxs-lookup"><span data-stu-id="f9d2e-114">This is based on the bank and the remittance type selected by the user in the case of bills of exchange, and based on the bank selected by the user in the case of promissory notes.</span></span> 

<span data-ttu-id="f9d2e-115">この機能を使用すると、会社の銀行口座ごとに異なる専用の転記プロファイルを作成し、選択した銀行にリンクされた勘定科目にそのトランザクションを転記できます。</span><span class="sxs-lookup"><span data-stu-id="f9d2e-115">The feature allows you to create a different dedicated posting profile for every company bank account to post the transactions in the ledger account linked to the selected bank.</span></span> <span data-ttu-id="f9d2e-116">銀行口座は仕訳作成時に指定され、その銀行口座は特定の転記プロファイルにリンクされているため、送金のトランザクションはその銀行に接続された主勘定を使用します。</span><span class="sxs-lookup"><span data-stu-id="f9d2e-116">The bank account is specified during the journal creation, and because it is linked to a specific posting profile, the transactions for the remittance will use the main account connected to the bank.</span></span>
<!--feature detail end -->










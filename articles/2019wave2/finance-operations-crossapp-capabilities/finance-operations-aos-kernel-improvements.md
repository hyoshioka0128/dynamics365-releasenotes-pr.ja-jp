---
title: Finance and Operations AOS (カーネル) の改善
description: Finance and Operations AOS (カーネル) の改善
author: relnotes
ms.reviewer: sericks
ms.date: 01/06/2020
ms.assetid: 021a0697-4607-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hasaid
dynamics365pdf: true
ms.openlocfilehash: e5e1065f7a06c6ea5d66e88e1b35af34868b598e
ms.sourcegitcommit: ecf709e1d8de3b52e1156bceb99cb7e3819f9db3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/13/2020
ms.locfileid: "2950980"
---
# <a name="finance-and-operations-aos-kernel-improvements"></a><span data-ttu-id="abd9a-103">Finance and Operations AOS (カーネル) の改善</span><span class="sxs-lookup"><span data-stu-id="abd9a-103">Finance and Operations AOS (kernel) improvements</span></span>


| <span data-ttu-id="abd9a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="abd9a-104">Enabled for</span></span>    |  <span data-ttu-id="abd9a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="abd9a-105">Public preview</span></span> | <span data-ttu-id="abd9a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="abd9a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="abd9a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="abd9a-107">End users, automatically</span></span>|<span data-ttu-id="abd9a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="abd9a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="abd9a-109">2019 年 12 月 20 日</span><span class="sxs-lookup"><span data-stu-id="abd9a-109">Dec 20, 2019</span></span>| <span data-ttu-id="abd9a-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="abd9a-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="abd9a-111">2020 年 1 月 1 日</span><span class="sxs-lookup"><span data-stu-id="abd9a-111">Jan 1, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="abd9a-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="abd9a-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="abd9a-113">より信頼性が高く安定したエクスペリエンスを顧客に提供するための継続的な改善に注力する際に、これはこの体験に必要なマイルストーンです。</span><span class="sxs-lookup"><span data-stu-id="abd9a-113">As we focus on continuous improvements to provide a more reliable and stable experience for our customers, this is a required milestone on this journey.</span></span>

<span data-ttu-id="abd9a-114">Platform update 32 以降、AOS (カーネル) は Visual C++ 17 ランタイム ライブラリを取り込んで、コンパイラのパフォーマンスの最適化を活用します。</span><span class="sxs-lookup"><span data-stu-id="abd9a-114">Starting with Platform update 32, AOS (kernel) will uptake Visual C++ 17 runtime libraries to take advantage of compiler performance optimizations.</span></span> <span data-ttu-id="abd9a-115">プラットフォーム エンジニアは、開発環境の使用中に新しいアップグレードを利用して、より堅牢で信頼性の高いエクスペリエンスを顧客に提供できます。</span><span class="sxs-lookup"><span data-stu-id="abd9a-115">Platform engineers will benefit from the new upgrade while using their development environments to provide a more robust and reliable experience for our customers.</span></span>

<span data-ttu-id="abd9a-116">そのためには、VC++ 17 再頒布可能パッケージを使用するように既存の環境を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="abd9a-116">This will require that existing environments be updated to use the VC++ 17 redistributables.</span></span>

- <span data-ttu-id="abd9a-117">Microsoft が管理するスタンダード承認テスト サンドボックス以上 (Tier 2 以上) および実稼働環境の場合、VC++ 17 再頒布可能パッケージは既にインストールされており、アクションは不要です。</span><span class="sxs-lookup"><span data-stu-id="abd9a-117">For Microsoft-managed Standard Acceptance Test Sandbox and higher (Tier 2 and higher) and Production environments, VC++ 17 redistributables are already installed and no action is needed.</span></span>
- <span data-ttu-id="abd9a-118">Microsoft が管理する DEV 環境 (Tier 1) の場合、顧客、パートナー、および ISV は、Platform update 32 を適用する前に仮想マシンを再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="abd9a-118">For Microsoft-managed DEV environment (Tier 1), customers, partners, and ISVs will need to restart their virtual machines before applying Platform update 32.</span></span>
- <span data-ttu-id="abd9a-119">管理されていない開発、ビルド、テスト、デモ (Tier 1) およびオンプレミス環境の場合、顧客、パートナー、および ISV は、Lifecycle Services の共有アセット ライブラリから VC++ 17 再頒布可能パッケージをダウンロードしてインストールし、マシンを再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="abd9a-119">For non-managed Dev, Build, Test, Demo (Tier 1) and on-premises environments, customers, partners, and ISVs will need to download and install VC++ 17 redistributable from the shared asset library in Lifecycle Services and restart their machines.</span></span>

<span data-ttu-id="abd9a-120">最新の再頒布可能パッケージが既にインストールされている場合、アクションは不要です。</span><span class="sxs-lookup"><span data-stu-id="abd9a-120">If you have the latest redistributables already installed, then no action is needed.</span></span>

<span data-ttu-id="abd9a-121">Platform update 32 を適用し、再頒布可能パッケージが欠落している場合、サービスの開始時にエラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="abd9a-121">If you apply Platform update 32 and redistributables are missing, you might get an error when starting your services.</span></span> <span data-ttu-id="abd9a-122">必要に応じて、次の手順を参照してこの問題を解決してください。</span><span class="sxs-lookup"><span data-stu-id="abd9a-122">If needed, refer to the following instructions to resolve this issue.</span></span>

<span data-ttu-id="abd9a-123">再頒布可能パッケージをインストールするには:</span><span class="sxs-lookup"><span data-stu-id="abd9a-123">To install the redistributables:</span></span>

1. <span data-ttu-id="abd9a-124">Lifecycle Services に移動します。</span><span class="sxs-lookup"><span data-stu-id="abd9a-124">Go to Lifecycle Services.</span></span>
2. <span data-ttu-id="abd9a-125">**共有アセット ライブラリ**を選択します。</span><span class="sxs-lookup"><span data-stu-id="abd9a-125">Select **Shared asset library**.</span></span>
3. <span data-ttu-id="abd9a-126">アセット タイプの一覧から**モデル**を選択します。</span><span class="sxs-lookup"><span data-stu-id="abd9a-126">Select **Model** from the asset type list.</span></span>
4. <span data-ttu-id="abd9a-127">**VC++ 17 再頒布可能パッケージ**を選択します。</span><span class="sxs-lookup"><span data-stu-id="abd9a-127">Select **VC++ 17 Redistributables**.</span></span>
5. <span data-ttu-id="abd9a-128">ダウンロードが自動的に開始されます。</span><span class="sxs-lookup"><span data-stu-id="abd9a-128">The download will automatically start.</span></span>
6. <span data-ttu-id="abd9a-129">マシンに適用して再起動します。</span><span class="sxs-lookup"><span data-stu-id="abd9a-129">Apply on your machine and restart.</span></span>
<!--feature detail end -->








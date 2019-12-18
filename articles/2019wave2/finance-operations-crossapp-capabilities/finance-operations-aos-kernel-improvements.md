---
title: Finance and Operations AOS (カーネル) の改善
description: Finance and Operations AOS (カーネル) の改善
author: relnotes
ms.reviewer: sericks
ms.date: 11/22/2019
ms.assetid: 021a0697-4607-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hasaid
dynamics365pdf: true
ms.openlocfilehash: d156f4a7c3106ede94af227b5c685020d463c80e
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2894933"
---
# <a name="finance-and-operations-aos-kernel-improvements"></a><span data-ttu-id="45f53-103">Finance and Operations AOS (カーネル) の改善</span><span class="sxs-lookup"><span data-stu-id="45f53-103">Finance and Operations AOS (kernel) improvements</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="45f53-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="45f53-104">Enabled for</span></span>    |  <span data-ttu-id="45f53-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="45f53-105">Public preview</span></span> | <span data-ttu-id="45f53-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="45f53-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="45f53-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="45f53-107">End users, automatically</span></span>|<span data-ttu-id="45f53-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="45f53-108">Nov 2019</span></span>| <span data-ttu-id="45f53-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="45f53-109">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="45f53-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="45f53-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="45f53-111">より信頼性が高く安定したエクスペリエンスを顧客に提供するための継続的な改善に注力する際に、これはこの体験に必要なマイルストーンです。</span><span class="sxs-lookup"><span data-stu-id="45f53-111">As we focus on continuous improvements to provide more reliable and stable experience for our customers, this is a required milestone on this journey.</span></span>

<span data-ttu-id="45f53-112">Platform update 32 以降、AOS (カーネル) は Visual C++ 17 ランタイム ライブラリを取り込んで、コンパイラのパフォーマンスの最適化を活用します。</span><span class="sxs-lookup"><span data-stu-id="45f53-112">Starting with Platform update 32, AOS (kernel) will uptake Visual C++ 17 runtime libraries to take advantage of compiler performance optimizations.</span></span> <span data-ttu-id="45f53-113">プラットフォーム エンジニアは、開発環境の使用中に新しいアップグレードを利用して、より堅牢で信頼性の高いエクスペリエンスを顧客に提供できます。</span><span class="sxs-lookup"><span data-stu-id="45f53-113">Platform engineers will benefit from the new upgrade while using their development environments to provide more robust and reliable experience for our customers.</span></span>

<span data-ttu-id="45f53-114">そのためには、VC++ 17 再頒布可能パッケージを使用するように既存の環境を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="45f53-114">This will require that existing environments be updated to use the VC++ 17 redistributables.</span></span>

- <span data-ttu-id="45f53-115">Microsoft が管理するスタンダード承認テスト サンドボックス以上 (Tier 2 以上) および実稼働環境の場合、VC++ 17 再頒布可能パッケージは既にインストールされており、アクションは不要です。</span><span class="sxs-lookup"><span data-stu-id="45f53-115">For Microsoft-managed Standard Acceptance Test Sandbox and higher (Tier 2 and higher) and Production environments, VC++ 17 redistributables are already installed and no action is needed.</span></span>
- <span data-ttu-id="45f53-116">Microsoft が管理する DEV 環境 (Tier 1) の場合、顧客、パートナー、および ISV は、Platform update 32 を適用する前に仮想マシンを再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="45f53-116">For Microsoft-managed DEV environment (Tier 1), customers, partners, and ISVs will need to reboot their virtual machines before applying Platform update 32.</span></span>
- <span data-ttu-id="45f53-117">管理されていない開発、ビルド、テスト、デモ (Tier 1) およびオンプレミス環境の場合、顧客、パートナー、および ISV は、Lifecycle Services の共有アセット ライブラリから VC++ 17 再頒布可能パッケージをダウンロードしてインストールし、マシンを再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="45f53-117">For non-managed Dev, Build, Test, Demo (Tier 1) and on-premises environments, customers, partners, and ISVs will need to download and install VC++ 17 redistributable from the shared asset library in Lifecycle Services and reboot their machines.</span></span>

<span data-ttu-id="45f53-118">最新の再頒布可能パッケージが既にインストールされている場合、アクションは不要です。</span><span class="sxs-lookup"><span data-stu-id="45f53-118">If you have the latest redistributables already installed, then no action is needed.</span></span>

<span data-ttu-id="45f53-119">Platform update 32 を適用し、再頒布可能パッケージが欠落している場合、サービスの開始時にエラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="45f53-119">If you apply Platform update 32 and redistributables are missing, you might get an error when starting your services.</span></span> <span data-ttu-id="45f53-120">必要に応じて、次の手順を参照してこの問題を解決してください。</span><span class="sxs-lookup"><span data-stu-id="45f53-120">If needed, refer to the following instructions to resolve this issue.</span></span>

<span data-ttu-id="45f53-121">再頒布可能パッケージをインストールするには:</span><span class="sxs-lookup"><span data-stu-id="45f53-121">To install the redistributables:</span></span>

1. <span data-ttu-id="45f53-122">Lifecycle Services に移動します。</span><span class="sxs-lookup"><span data-stu-id="45f53-122">Go to Lifecycle Services.</span></span>
2. <span data-ttu-id="45f53-123">**共有アセット ライブラリ**を選択します。</span><span class="sxs-lookup"><span data-stu-id="45f53-123">Select **Shared asset library**.</span></span>
3. <span data-ttu-id="45f53-124">アセット タイプの一覧から**モデル**を選択します。</span><span class="sxs-lookup"><span data-stu-id="45f53-124">Select **Model** from the asset type list.</span></span>
4. <span data-ttu-id="45f53-125">**VC++ 17 再頒布可能パッケージ**を選択します。</span><span class="sxs-lookup"><span data-stu-id="45f53-125">Select **VC++ 17 Redistributables**.</span></span>
5. <span data-ttu-id="45f53-126">ダウンロードが自動的に開始されます。</span><span class="sxs-lookup"><span data-stu-id="45f53-126">The download will automatically start.</span></span>
6. <span data-ttu-id="45f53-127">マシンに適用して再起動します。</span><span class="sxs-lookup"><span data-stu-id="45f53-127">Apply on your machine and reboot.</span></span>

<!--feature detail end -->










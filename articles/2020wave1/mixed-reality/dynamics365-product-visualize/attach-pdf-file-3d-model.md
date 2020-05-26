---
title: 3D モデルに PDF ファイルを添付する
description: 3D モデルに PDF ファイルを添付する
author: relnotes
ms.reviewer: shjais
ms.date: 04/13/2020
ms.assetid: 2079bc8b-8918-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: michtan
dynamics365pdf: true
ms.openlocfilehash: b1e87e9bd94ba108edb779de2c18f8e98b55b2b3
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273271"
---
# <a name="attach-a-pdf-file-to-a-3d-model"></a><span data-ttu-id="7305b-103">3D モデルに PDF ファイルを添付する</span><span class="sxs-lookup"><span data-stu-id="7305b-103">Attach a PDF file to a 3D model</span></span>
[!include[mixed-reality/dynamics365-product-visualize banner](../includes/mixed-reality/dynamics365-product-visualize.md)]

| <span data-ttu-id="7305b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7305b-104">Enabled for</span></span>    |  <span data-ttu-id="7305b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7305b-105">Public preview</span></span> | <span data-ttu-id="7305b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7305b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7305b-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7305b-107">End users, automatically</span></span>|<span data-ttu-id="7305b-108">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="7305b-108">Jun 2020</span></span>| <span data-ttu-id="7305b-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="7305b-109">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="7305b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7305b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7305b-111">3D モデルのさまざまなポイントに PDF コンテンツを添付すると、Dynamics 365 Product Visualize のお客様にとって、営業の会話を豊かにするための柔軟性が大幅に向上します。</span><span class="sxs-lookup"><span data-stu-id="7305b-111">Attaching PDF content to various points on a 3D model will give Dynamics 365 Product Visualize customers much more flexibility to enrich the sales conversation.</span></span> <span data-ttu-id="7305b-112">例として、大規模な消費者向けパッケージ商品ブランドでは、販売担当者が最適な製品の品揃えを分析および決定できるように営業データを提供したい場合があります。</span><span class="sxs-lookup"><span data-stu-id="7305b-112">As an example, a large consumer package goods brand might want to provide sales data to enable sellers to analyze and determine their optimal product assortment.</span></span> <span data-ttu-id="7305b-113">お客様は、サービス マニュアル、パンフレット、または営業の会話を強化するその他の PDF リソースにリンクすることもできます。</span><span class="sxs-lookup"><span data-stu-id="7305b-113">Customers can also link to a service manual, brochure, or any other PDF resource that will enhance the sales conversation.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7305b-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7305b-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7305b-115">ユーザーは、PDF コンテンツをモデルの特定のポイントに添付する (固定) か、一般にモデルの周囲に添付する (非固定) ことができます。</span><span class="sxs-lookup"><span data-stu-id="7305b-115">Users will be able to attach PDF content to a specific point on the model (anchored), or attach it generally around the model (unanchored).</span></span> <span data-ttu-id="7305b-116">PDF コンテンツは 2D としてレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="7305b-116">The PDF content will be rendered as 2D.</span></span> <span data-ttu-id="7305b-117">3D モデルのコンテキストでは空間的にレンダリングされません。</span><span class="sxs-lookup"><span data-stu-id="7305b-117">It won't be spatially rendered in the context of the 3D model.</span></span> <span data-ttu-id="7305b-118">PDF コンテンツは Common Data Service に保存されます。</span><span class="sxs-lookup"><span data-stu-id="7305b-118">The PDF content will be stored in Common Data Service.</span></span>
<!--feature detail end -->

<span data-ttu-id="7305b-119">![PDF メモ](media/pdfnotes.jpg "PDF メモ")</span><span class="sxs-lookup"><span data-stu-id="7305b-119">![PDF notes](media/pdfnotes.jpg "PDF notes")</span></span>
<!-- Picture 1 -->









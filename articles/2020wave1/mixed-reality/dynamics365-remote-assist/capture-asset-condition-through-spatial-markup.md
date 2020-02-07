---
title: 空間マークアップを介して資産の状態をキャプチャする
description: 空間マークアップを介して資産の状態をキャプチャする
author: relnotes
ms.reviewer: v-brycho
ms.date: 01/14/2020
ms.assetid: 4113b068-081b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: hegate
dynamics365pdf: true
ms.openlocfilehash: e70acd72ec3211764060990995bb1787f6eeed02
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986574"
---
# <a name="capture-asset-condition-through-spatial-markup"></a><span data-ttu-id="f1dfd-103">空間マークアップを介して資産の状態をキャプチャする</span><span class="sxs-lookup"><span data-stu-id="f1dfd-103">Capture asset condition through spatial markup</span></span>
[!include[mixed-reality/dynamics365-remote-assist banner](../includes/mixed-reality/dynamics365-remote-assist.md)]

| <span data-ttu-id="f1dfd-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f1dfd-104">Enabled for</span></span>    |  <span data-ttu-id="f1dfd-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f1dfd-105">Public preview</span></span> | <span data-ttu-id="f1dfd-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f1dfd-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f1dfd-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f1dfd-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="f1dfd-108">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="f1dfd-108">Jun 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="f1dfd-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f1dfd-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f1dfd-110">第一線の作業者は、必ずしも遠隔地にいるエキスパートと電話でやり取りする必要はありません。特定のインシデントの解決や、資産のインストールでの品質レビューの実行などのシナリオでは、多くの場合に独立して作業する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-110">First-line workers don't always need to engage with a remote expert through a call; they often have to work independently, in scenarios such as solving a specific incident or performing a quality review on an asset installation.</span></span> <span data-ttu-id="f1dfd-111">これらの操作を実行するとき、特定の資産に関する空間情報をキャプチャし、その情報をビジネス プロセスに統合できるという利点があります。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-111">When performing these operations, they'll benefit from being able to capture spatial information about a specific asset and integrate that information with their business processes.</span></span>

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f1dfd-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f1dfd-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f1dfd-113">この機能は、もともとは電話をかけなくても注釈をキャプチャして共有できる機能として計画されていました。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-113">This feature was originally planned as the ability to capture and share annotations without being in a call.</span></span> <span data-ttu-id="f1dfd-114">広範な顧客の学習とフィードバックに基づいて、機能の範囲を広げました。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-114">We've evolved the feature scope based on extensive customer learnings and feedback.</span></span> 

<span data-ttu-id="f1dfd-115">この機能では、Dynamics 365 Remote Assist の「アセット キャプチャ」の概念が導入され、技術者は空間マークアップを使用して、電話をかけずに検査や調査を行い、後処理のために作業を保存できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-115">Now, the feature will introduce the concept of "asset capture" in Dynamics 365 Remote Assist, which will enable technicians to use spatial markups to do checkups and inspections without being on a call, and save their work for post-processing.</span></span> <span data-ttu-id="f1dfd-116">検査担当者は、コンテキスト内の資産調査や資産検査をハンズフリーで実行して、紙や Excel でのプロセスを改善でき、検査がより速く、安全で、正確になります。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-116">Inspectors will be able to do an asset survey or asset inspection hands-free and in context, which will improve their paper and Excel processes and result in faster, safer, and more accurate inspections.</span></span>

<span data-ttu-id="f1dfd-117">キャプチャされたデータは Common Data Service に保存され、Dynamics 365 Field Service の検査と統合されます。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-117">Captured data will be stored in Common Data Service and integrated with Dynamics 365 Field Service inspection.</span></span> <span data-ttu-id="f1dfd-118">Field Service 技術者は、Dynamics 365 Remote Assist で記録された情報を作業指示書で参照できるようになるので、資産の履歴をより正確に追跡できます。</span><span class="sxs-lookup"><span data-stu-id="f1dfd-118">Field Service technicians will be able to reference the information recorded in Dynamics 365 Remote Assist in their work orders, so they can better keep track of asset history.</span></span>

<!--feature detail end -->










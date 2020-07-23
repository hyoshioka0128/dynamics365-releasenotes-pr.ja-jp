---
title: 空間マークアップを介して資産の状態をキャプチャする
description: 空間マークアップを介して資産の状態をキャプチャする
author: relnotes
ms.reviewer: krbjoran
ms.date: 06/14/2020
ms.assetid: 4113b068-081b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: becorn
dynamics365pdf: true
ms.openlocfilehash: 1921943b78b9595bd5575e5056910f395fcfaff8
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3488469"
---
# <a name="capture-asset-condition-through-spatial-markup"></a><span data-ttu-id="459af-103">空間マークアップを介して資産の状態をキャプチャする</span><span class="sxs-lookup"><span data-stu-id="459af-103">Capture asset condition through spatial markup</span></span>


| <span data-ttu-id="459af-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="459af-104">Enabled for</span></span>    |  <span data-ttu-id="459af-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="459af-105">Public preview</span></span> | <span data-ttu-id="459af-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="459af-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="459af-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="459af-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="459af-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="459af-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="459af-109">2020 年 6 月 10 日</span><span class="sxs-lookup"><span data-stu-id="459af-109">Jun 10, 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="459af-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="459af-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="459af-111">第一線の作業者は、必ずしも遠隔地にいるエキスパートと電話でやり取りする必要はありません。特定のインシデントの解決や、資産のインストールでの品質レビューの実行などのシナリオでは、多くの場合に独立して作業する必要があります。</span><span class="sxs-lookup"><span data-stu-id="459af-111">First-line workers don't always need to engage with a remote expert through a call; they often have to work independently, in scenarios such as solving a specific incident or performing a quality review on an asset installation.</span></span> <span data-ttu-id="459af-112">これらの操作を実行するとき、特定の資産に関する空間情報をキャプチャし、その情報をビジネス プロセスに統合できるという利点があります。</span><span class="sxs-lookup"><span data-stu-id="459af-112">When performing these operations, they'll benefit from being able to capture spatial information about a specific asset and integrate that information with their business processes.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="459af-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="459af-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="459af-114">この機能は、もともとは電話をかけなくても注釈をキャプチャして共有できる機能として計画されていました。</span><span class="sxs-lookup"><span data-stu-id="459af-114">This feature was originally planned as the ability to capture and share annotations without being in a call.</span></span> <span data-ttu-id="459af-115">広範な顧客の学習とフィードバックに基づいて、機能の範囲を広げました。</span><span class="sxs-lookup"><span data-stu-id="459af-115">We've evolved the feature scope based on extensive customer learnings and feedback.</span></span> 

<span data-ttu-id="459af-116">この機能では、Dynamics 365 Remote Assist の「アセット キャプチャ」の概念が導入され、技術者は空間マークアップを使用して、電話をかけずに検査や調査を行い、後処理のために作業を保存できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="459af-116">Now, the feature will introduce the concept of "asset capture" in Dynamics 365 Remote Assist, which will enable technicians to use spatial markups to do checkups and inspections without being on a call, and save their work for post-processing.</span></span> <span data-ttu-id="459af-117">検査担当者は、コンテキスト内の資産調査や資産検査をハンズフリーで実行して、紙や Excel でのプロセスを改善でき、検査がより速く、安全で、正確になります。</span><span class="sxs-lookup"><span data-stu-id="459af-117">Inspectors will be able to do an asset survey or asset inspection hands-free and in context, which will improve their paper and Excel processes and result in faster, safer, and more accurate inspections.</span></span>

<span data-ttu-id="459af-118">キャプチャされたデータは Common Data Service に保存され、Dynamics 365 Field Service の検査と統合されます。</span><span class="sxs-lookup"><span data-stu-id="459af-118">Captured data will be stored in Common Data Service and integrated with Dynamics 365 Field Service inspection.</span></span> <span data-ttu-id="459af-119">Field Service 技術者は、Dynamics 365 Remote Assist で記録された情報を作業指示書で参照できるようになるので、資産の履歴をより正確に追跡できます。</span><span class="sxs-lookup"><span data-stu-id="459af-119">Field Service technicians will be able to reference the information recorded in Dynamics 365 Remote Assist in their work orders, so they can better keep track of asset history.</span></span>

<span data-ttu-id="459af-120">プレビューは、HoloLens 2 でのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="459af-120">The preview will only be available in HoloLens 2.</span></span>
<!--feature detail end -->










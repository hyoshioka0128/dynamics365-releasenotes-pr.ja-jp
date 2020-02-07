---
title: Common Data Service の人事管理データにアクセスして維持する
description: Common Data Service の人事管理データにアクセスして維持する
author: relnotes
ms.reviewer: anbichse
ms.date: 01/07/2020
ms.assetid: 8f01d52f-e3c9-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: dkrame
dynamics365pdf: true
ms.openlocfilehash: 32a8e8b6e6c17d14ea0428ed5e1dcbedf5bf8046
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986600"
---
# <a name="access-and-maintain-hr-data-in-common-data-service"></a><span data-ttu-id="cdefc-103">Common Data Service の人事管理データにアクセスして維持する</span><span class="sxs-lookup"><span data-stu-id="cdefc-103">Access and maintain HR data in Common Data Service</span></span>
[!include[dynamics365-human-resources banner](../includes/dynamics365-human-resources.md)]

| <span data-ttu-id="cdefc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cdefc-104">Enabled for</span></span>    |  <span data-ttu-id="cdefc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cdefc-105">Public preview</span></span> | <span data-ttu-id="cdefc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cdefc-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cdefc-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="cdefc-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="cdefc-108">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="cdefc-108">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="cdefc-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cdefc-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cdefc-110">Human Resources を拡張および統合するシナリオを有効にします。</span><span class="sxs-lookup"><span data-stu-id="cdefc-110">Enable scenarios to extend and integrate with Human Resources.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cdefc-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cdefc-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cdefc-112">統合、拡張性、およびレポートはすべて、ソリューション全体で必要なデータのソースとして Common Data Service に依存しています。</span><span class="sxs-lookup"><span data-stu-id="cdefc-112">Integrations, extensibility, and reporting all have dependencies on Common Data Service as the source for the data needed across solutions.</span></span> <span data-ttu-id="cdefc-113">Common Data Service への追加データの取り込みは継続的な取り組みであり、2020 年リリース ウェーブ 1 および 2020 年リリース ウェーブ 2 の過程で継続されます。</span><span class="sxs-lookup"><span data-stu-id="cdefc-113">Bringing additional data to Common Data Service has been an ongoing effort and will continue over the course of 2020 release wave 1 and 2020 release wave 2.</span></span> 

<span data-ttu-id="cdefc-114">注力している取り組みは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="cdefc-114">Our focused efforts include:</span></span>

- <span data-ttu-id="cdefc-115">追加のエンティティを通じて新しいシナリオを有効にし、既存のシナリオを完了します。</span><span class="sxs-lookup"><span data-stu-id="cdefc-115">Enabling new scenarios and completing existing scenarios through additional entities.</span></span>
- <span data-ttu-id="cdefc-116">既存のエンティティを完成させます。</span><span class="sxs-lookup"><span data-stu-id="cdefc-116">Completing existing entities.</span></span>
- <span data-ttu-id="cdefc-117">存在し、時間と共に変化する Common Data Service データの更新の信頼性に焦点を当てます。</span><span class="sxs-lookup"><span data-stu-id="cdefc-117">Focusing on the reliability of updating the Common Data Service data that exists and changes over time.</span></span>
<!--feature detail end -->










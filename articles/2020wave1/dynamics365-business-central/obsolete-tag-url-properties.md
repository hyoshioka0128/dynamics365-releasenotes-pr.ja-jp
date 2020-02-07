---
title: 廃止されたタグと URL プロパティ
description: ObsoleteState プロパティまたは Obsolete 属性を現在サポートしているオブジェクトに、プロセスを追跡するための ObsoleteTag と ObsoleteUrl プロパティを追加して、廃止されたオブジェクトに関する追加情報を提供します。
author: relnotes
ms.reviewer: solsen
ms.date: 12/12/2019
ms.assetid: a5a76819-dd1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 4ab745f1c84c9c7adc97584e74eb982ffe777c7b
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986816"
---
# <a name="obsolete-tag-and-url-properties"></a><span data-ttu-id="c1825-103">廃止されたタグと URL プロパティ</span><span class="sxs-lookup"><span data-stu-id="c1825-103">Obsolete tag and URL properties</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="c1825-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c1825-104">Enabled for</span></span>    |  <span data-ttu-id="c1825-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c1825-105">Public preview</span></span> | <span data-ttu-id="c1825-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c1825-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c1825-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="c1825-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="c1825-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="c1825-108">Feb 2020</span></span>| <span data-ttu-id="c1825-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c1825-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c1825-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c1825-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c1825-111">自由形式の ObsoleteTag を追加することで、パートナーは、廃止されたオブジェクト (分岐やビルド番号など) に関するコンテキストデータを提供して、廃止されたオブジェクトの最終的な削除を追跡および計画できます。</span><span class="sxs-lookup"><span data-stu-id="c1825-111">Adding a free-form ObsoleteTag allows partners, for example, to provide contextual data around obsoleting objects—such as branches and build numbers—to track and plan a final removal of obsoleted objects.</span></span>

<span data-ttu-id="c1825-112">ObsoleteUrl を使用すると、保留中の古いオブジェクトの処理とコードを書き換える方法に関する追加情報の URI を提供できます。</span><span class="sxs-lookup"><span data-stu-id="c1825-112">The ObsoleteUrl allows providing a URI with additional information on how to handle and rewrite code due to obsolete pending objects.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c1825-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c1825-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c1825-114">ObsoleteState プロパティまたは Obsolete 属性を現在サポートしているオブジェクトに、プロセスを追跡するための ObsoleteTag と ObsoleteUrl プロパティを追加して、廃止されたオブジェクトに関する追加情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="c1825-114">Objects that support the ObsoleteState property or Obsolete attribute today will get additional ObsoleteTag and ObsoleteUrl properties for tracking processes and provide additional information on obsoleted objects.</span></span> <span data-ttu-id="c1825-115">パートナーは、日付やビルドなど ObsoleteTag で追跡する対象について独自のスキームを選択し、開発中に提供できます。</span><span class="sxs-lookup"><span data-stu-id="c1825-115">Partners can choose their own scheme for what to track in ObsoleteTag, such as date or build, and it could be provided during development.</span></span> <span data-ttu-id="c1825-116">同様にパートナーは、変更に関するドキュメントと下流の処理への影響に関する URL の提供を選択できます。</span><span class="sxs-lookup"><span data-stu-id="c1825-116">Likewise, partners can choose to provide URLs for documentation on changes and handling impact downstream.</span></span>
<!--feature detail end -->










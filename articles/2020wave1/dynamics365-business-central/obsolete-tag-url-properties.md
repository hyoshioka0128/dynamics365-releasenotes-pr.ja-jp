---
title: 廃止されたタグ プロパティ
description: ObsoleteState プロパティまたは Obsolete 属性を現在サポートしているオブジェクトに、プロセスを追跡するための ObsoleteTag プロパティを追加して、廃止されたオブジェクトに関する情報を提供します。
author: relnotes
ms.reviewer: solsen
ms.date: 04/02/2020
ms.assetid: a5a76819-dd1c-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: c434aa7e556398510d977b7953ae5404765daaf3
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232739"
---
# <a name="obsolete-tag-property"></a><span data-ttu-id="bf359-103">廃止されたタグ プロパティ</span><span class="sxs-lookup"><span data-stu-id="bf359-103">Obsolete tag property</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="bf359-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bf359-104">Enabled for</span></span>    |  <span data-ttu-id="bf359-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bf359-105">Public preview</span></span> | <span data-ttu-id="bf359-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bf359-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bf359-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="bf359-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="bf359-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bf359-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bf359-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bf359-109">Feb 1, 2020</span></span>| <span data-ttu-id="bf359-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="bf359-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="bf359-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bf359-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bf359-112">自由形式の ObsoleteTag を追加することで、パートナーは、廃止されたオブジェクト (分岐やビルド番号など) に関するコンテキスト データを提供して、廃止されたオブジェクトの最終的な削除を追跡および計画できます。</span><span class="sxs-lookup"><span data-stu-id="bf359-112">Adding a free-form ObsoleteTag allows partners, for example, to provide contextual data around obsoleting objects—such as branches and build numbers—to track and plan a final removal of obsoleted objects.</span></span>

<span data-ttu-id="bf359-113">ObsoleteUrl を使用すると、保留中の古いオブジェクトの処理とコードを書き換える方法に関する追加情報の URI を提供できます。</span><span class="sxs-lookup"><span data-stu-id="bf359-113">The ObsoleteUrl allows providing a URI with additional information on how to handle and rewrite code due to obsolete pending objects.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bf359-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bf359-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bf359-115">ObsoleteState プロパティまたは Obsolete 属性を現在サポートしているオブジェクトに、プロセスを追跡するための ObsoleteTag プロパティを追加して、廃止されたオブジェクトに関する追加情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="bf359-115">Objects that support the ObsoleteState property or Obsolete attribute today will get additional ObsoleteTag property for tracking processes and provide additional information on obsoleted objects.</span></span>

<span data-ttu-id="bf359-116">パートナーは、日付やビルドなどの ObsoleteTag で追跡する対象について独自のスキームを選択でき、これを開発時や内部ビルド プロセスで提供できます (カスタム ファイル修正が必要となります)。</span><span class="sxs-lookup"><span data-stu-id="bf359-116">Partners can choose their own scheme for what to track in ObsoleteTag, such as date or build, and it could be provided during development or internal build processes (requiring custom file patching).</span></span> <span data-ttu-id="bf359-117">また、開発者は、すべてのファイルにわたって ObsoleteTag コンテンツを検索できます (特定のバージョンでの変更の概要を取得する場合など)。</span><span class="sxs-lookup"><span data-stu-id="bf359-117">Developers can also search for ObsoleteTag content across all files (e.g., to get an overview of changes in a certain version).</span></span>

<span data-ttu-id="bf359-118">![ObsoleteTag によるコンテキスト メタデータの追跡](media/obsoletetag-search.jpg "ObsoleteTag によるコンテキスト メタデータの追跡")</span><span class="sxs-lookup"><span data-stu-id="bf359-118">![ObsoleteTag tracks contextual metadata](media/obsoletetag-search.jpg "ObsoleteTag tracks contextual metadata")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="bf359-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="bf359-119">See also</span></span>


<!--docs start-->
<span data-ttu-id="bf359-120">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="bf359-120">[AL Development Environment](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview) (docs)</span></span>
<!--docs end-->


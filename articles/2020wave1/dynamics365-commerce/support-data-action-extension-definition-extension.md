---
title: 定義の拡張機能でのデータ アクション拡張機能のサポート
description: Dynamics 365 online SDK でモジュールを拡張する際、モジュール定義によってすべての拡張する構成、リソース、スロットを拡張できますが、データ アクションは拡張できません。 今回、データ アクションを拡張するためのサポートが追加されます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/30/2020
ms.assetid: e5e611f6-b059-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: samjar
dynamics365pdf: true
ms.openlocfilehash: b616bc4ba8b4bcd81b1ea7ceaa284d069fec41c5
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350916"
---
# <a name="support-data-action-extension-in-definition-extension"></a><span data-ttu-id="69e93-104">定義の拡張機能でのデータ アクション拡張機能のサポート</span><span class="sxs-lookup"><span data-stu-id="69e93-104">Support data action extension in definition extension</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="69e93-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="69e93-105">Enabled for</span></span>    |  <span data-ttu-id="69e93-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="69e93-106">Public preview</span></span> | <span data-ttu-id="69e93-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="69e93-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="69e93-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="69e93-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="69e93-109">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="69e93-109">Sep 2020</span></span>| <span data-ttu-id="69e93-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="69e93-110">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="69e93-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="69e93-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="69e93-112">テーマ開発者は、テーマ内の特定のモジュールに使用されるデータ アクションを変更したい場合があります。</span><span class="sxs-lookup"><span data-stu-id="69e93-112">Theme developers might want to change the data action used for a particular module inside of a theme.</span></span> <span data-ttu-id="69e93-113">現在これを行うには、モジュール全体を複製する必要があるため、モジュールのサービス性が失われます。</span><span class="sxs-lookup"><span data-stu-id="69e93-113">To do so today, they must clone the whole module and thereby lose out on serviceability of the module.</span></span> <span data-ttu-id="69e93-114">このサポートの追加により、モジュールのデータ アクションのみを変更するコストが大幅に削減されます。</span><span class="sxs-lookup"><span data-stu-id="69e93-114">By adding this support, the cost to change just the data action on a module is significantly reduced.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="69e93-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="69e93-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="69e93-116">モジュール定義拡張機能のサポートにより、データ アクションをモジュール定義ファイルに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="69e93-116">Module definition extension support now allows data actions to be added to the module definition file.</span></span> <span data-ttu-id="69e93-117">追加されると、定義ファイルで設定された設定に応じて、サーバー側またはクライアント側で実行されます。</span><span class="sxs-lookup"><span data-stu-id="69e93-117">When added, they will be run either server-side or client-side, depending on the setting set in the definition file.</span></span> <span data-ttu-id="69e93-118">モジュール ビュー拡張機能は、モジュールから返されたデータを使用して、必要に応じて適切なユーザー インターフェイス (UI) をレンダリングできます。</span><span class="sxs-lookup"><span data-stu-id="69e93-118">The module view extension can then use the returned data from the module and render the appropriate user interface (UI) as needed.</span></span>
<!--feature detail end -->










---
title: 以前は日付仮想テーブルに基づいていた ListPlus ページの拡張
description: 以前は**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間** などの ListPlus ページを拡張できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/06/2020
ms.assetid: de25edaf-9e4d-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 981e683a8ad65420c4819525e2daaeb95a8e1bc5
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255081"
---
# <a name="extend-listplus-pages-previously-based-on-the-date-virtual-table"></a><span data-ttu-id="ccb4b-103">以前は日付仮想テーブルに基づいていた ListPlus ページの拡張</span><span class="sxs-lookup"><span data-stu-id="ccb4b-103">Extend ListPlus pages previously based on the Date virtual table</span></span>


| <span data-ttu-id="ccb4b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ccb4b-104">Enabled for</span></span>    |  <span data-ttu-id="ccb4b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ccb4b-105">Public preview</span></span> | <span data-ttu-id="ccb4b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ccb4b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ccb4b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ccb4b-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="ccb4b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ccb4b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ccb4b-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ccb4b-109">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ccb4b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ccb4b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ccb4b-111">**日付**仮想テーブルに基づくサブページを含む ListPlus ページの拡張は、顧客が**品目**や**リソースの空き時間**などのページに関して特定の要件がある場合や、追加の測定値を分析する必要がある場合に関係します。</span><span class="sxs-lookup"><span data-stu-id="ccb4b-111">Extending ListPlus pages that contain subpages based on the **Date** virtual table is relevant if a customer has specific requirements or wants to analyze additional measurements on pages, such as **Item** and **Resource Availability**.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ccb4b-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ccb4b-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ccb4b-113">基になっているバッファー テーブルを拡張し、OnAfterCalcLine イベントにサブスクライブすることで、**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間**などの ListPlus ページを拡張できます。</span><span class="sxs-lookup"><span data-stu-id="ccb4b-113">You can now extend ListPlus pages such as the **Item** and **Resource Availability** pages that were based on the **Date** virtual table by extending the underlying buffer table and subscribing to the OnAfterCalcLine event.</span></span> <span data-ttu-id="ccb4b-114">このようなベース アプリケーションのすべてのページで、この拡張性モデルがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="ccb4b-114">All such pages in the base application now support this extensibility model.</span></span>
<!--feature detail end -->










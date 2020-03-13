---
title: 以前は日付仮想テーブルに基づいていた ListPlus ページの拡張
description: 以前は**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間** などの ListPlus ページを拡張できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 02/14/2020
ms.assetid: de25edaf-9e4d-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 53d9b0514fd8c5fd1e70e865cccc324a7e41d418
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080686"
---
# <a name="extend-listplus-pages-previously-based-on-the-date-virtual-table"></a><span data-ttu-id="25ca3-103">以前は日付仮想テーブルに基づいていた ListPlus ページの拡張</span><span class="sxs-lookup"><span data-stu-id="25ca3-103">Extend ListPlus pages previously based on the Date virtual table</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="25ca3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="25ca3-104">Enabled for</span></span>    |  <span data-ttu-id="25ca3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="25ca3-105">Public preview</span></span> | <span data-ttu-id="25ca3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="25ca3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="25ca3-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="25ca3-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="25ca3-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="25ca3-108">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="25ca3-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="25ca3-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="25ca3-110">**日付**仮想テーブルに基づくサブページを含む ListPlus ページの拡張は、顧客が**品目**や**リソースの空き時間**などのページに関して特定の要件がある場合や、追加の測定値を分析する必要がある場合に関係します。</span><span class="sxs-lookup"><span data-stu-id="25ca3-110">Extending ListPlus pages that contain subpages based on the **Date** virtual table is relevant if a customer has specific requirements or wants to analyze additional measurements on pages, such as **Item** and **Resource Availability**.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="25ca3-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="25ca3-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="25ca3-112">基になっているバッファー テーブルを拡張し、OnAfterCalcLine イベントにサブスクライブすることで、**日付**仮想テーブルに基づいていた**品目**や**リソースの空き時間**などの ListPlus ページを拡張できます。</span><span class="sxs-lookup"><span data-stu-id="25ca3-112">You can now extend ListPlus pages such as the **Item** and **Resource Availability** pages that were based on the **Date** virtual table by extending the underlying buffer table and subscribing to the OnAfterCalcLine event.</span></span> <span data-ttu-id="25ca3-113">このようなベース アプリケーションのすべてのページで、この拡張性モデルがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="25ca3-113">All such pages in the base application now support this extensibility model.</span></span>
<!--feature detail end -->










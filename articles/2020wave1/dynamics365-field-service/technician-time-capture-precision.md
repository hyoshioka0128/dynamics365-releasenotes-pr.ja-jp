---
title: 技術者の時間キャプチャの精度
description: より正確なタイムスタンプ キャプチャを構成する機能。
author: relnotes
ms.reviewer: krbjoran
ms.date: 01/10/2020
ms.assetid: 0ff76893-45cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: 3bf7a726ae15f2c1d4895ecbb93aa9e8c1da6b47
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986615"
---
# <a name="technician-time-capture-precision"></a><span data-ttu-id="ee403-103">技術者の時間キャプチャの精度</span><span class="sxs-lookup"><span data-stu-id="ee403-103">Technician time-capture precision</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="ee403-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ee403-104">Enabled for</span></span>    |  <span data-ttu-id="ee403-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ee403-105">Public preview</span></span> | <span data-ttu-id="ee403-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="ee403-106">Early access</span></span> | <span data-ttu-id="ee403-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ee403-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="ee403-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ee403-108">Admins, makers, or analysts, automatically</span></span>|-|<span data-ttu-id="ee403-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="ee403-109">Feb 2020</span></span>| <span data-ttu-id="ee403-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="ee403-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ee403-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ee403-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ee403-112">Dynamics 365 Field Service では、基になる Field Service の状態が変更になったときの、予約タイムスタンプのキャプチャがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="ee403-112">Dynamics 365 Field Service has supported capture of booking timestamps when the underlying Field Service states are changed.</span></span> <span data-ttu-id="ee403-113">ただし、多くの顧客は、予約状態の変更について、より細かい頻度でタイムスタンプをキャプチャする必要があります。</span><span class="sxs-lookup"><span data-stu-id="ee403-113">However, many customers need to capture timestamps at the more granular frequency of the change of booking status.</span></span> <span data-ttu-id="ee403-114">顧客はこの機能により、原価計算の精度を高め、各予約と作業指示書のタイミングをより深く理解し、その他の拡張シナリオを推進できます。</span><span class="sxs-lookup"><span data-stu-id="ee403-114">They use this to drive increased accuracy of costing, better understanding of where time goes on each booking and work order, or other extension scenarios.</span></span>    <span data-ttu-id="ee403-115">これが、Field Service の構成を介してサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ee403-115">This is now supported via configuration in Field Service.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ee403-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ee403-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ee403-117">Field Service でこの構成設定が導入されたことで、Field Service の顧客の実装を簡素化し、顧客が作業の実施時にどの程度の詳細を収集するかを柔軟に決定できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ee403-117">Field Service has introduced this configuration setting to simplify implementations for Field Service customers and to allow customers the flexibility of deciding the level of detail they wish to capture when performing work.</span></span>

<span data-ttu-id="ee403-118">これには次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="ee403-118">This includes:</span></span>

- <span data-ttu-id="ee403-119">Field Service の設定で、予約ごとにタイムスタンプが収集される頻度を定義します。</span><span class="sxs-lookup"><span data-stu-id="ee403-119">Define in Field Service settings the frequency at which timestamps will be captured for each booking.</span></span>
- <span data-ttu-id="ee403-120">予約ステータスの変更がモバイル デバイスまたは Web ブラウザーのいずれで行われたかにかかわらず、システムでその設定を適用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="ee403-120">Enabling the system to respect that setting regardless of whether the booking status change occurs on the mobile device or via a web browser.</span></span>
- <span data-ttu-id="ee403-121">関連するタイムスタンプの適切な詳細をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="ee403-121">Capturing appropriate details on the relevant timestamps.</span></span>
- <span data-ttu-id="ee403-122">時間入力がタイムスタンプから作成された場合、時間入力が組織の設定に応じて適切な詳細レベルを保持していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="ee403-122">When a time entry is created from a timestamp, ensure that the time entry holds the right level of detail depending on the org's setting.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="ee403-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="ee403-123">This feature is available in the Unified Interface only.</span></span>







---
title: 技術者の時間キャプチャの精度
description: より正確なタイムスタンプ キャプチャを構成する機能。
author: relnotes
ms.reviewer: krbjoran
ms.date: 02/17/2020
ms.assetid: 0ff76893-45cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: 288ed02715eb9254396a05ac7a23bb36dc987569
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079568"
---
# <a name="technician-time-capture-precision"></a><span data-ttu-id="c7115-103">技術者の時間キャプチャの精度</span><span class="sxs-lookup"><span data-stu-id="c7115-103">Technician time-capture precision</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="c7115-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c7115-104">Enabled for</span></span>    |  <span data-ttu-id="c7115-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c7115-105">Public preview</span></span> | <span data-ttu-id="c7115-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="c7115-106">Early access</span></span> | <span data-ttu-id="c7115-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="c7115-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="c7115-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="c7115-108">Admins, makers, or analysts, automatically</span></span>|-|<span data-ttu-id="c7115-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c7115-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c7115-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c7115-110">Feb 3, 2020</span></span>| <span data-ttu-id="c7115-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c7115-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c7115-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c7115-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c7115-113">Dynamics 365 Field Service では、基になる Field Service の状態が変更になったときの、予約タイムスタンプのキャプチャがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="c7115-113">Dynamics 365 Field Service has supported capture of booking timestamps when the underlying Field Service states are changed.</span></span> <span data-ttu-id="c7115-114">ただし、多くの顧客は、予約状態の変更について、より細かい頻度でタイムスタンプをキャプチャする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7115-114">However, many customers need to capture timestamps at the more granular frequency of the change of booking status.</span></span> <span data-ttu-id="c7115-115">顧客はこの機能により、原価計算の精度を高め、各予約と作業指示書のタイミングをより深く理解し、その他の拡張シナリオを推進できます。</span><span class="sxs-lookup"><span data-stu-id="c7115-115">They use this to drive increased accuracy of costing, better understanding of where time goes on each booking and work order, or other extension scenarios.</span></span>    <span data-ttu-id="c7115-116">これが、Field Service の構成を介してサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c7115-116">This is now supported via configuration in Field Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c7115-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c7115-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c7115-118">Field Service でこの構成設定が導入されたことで、Field Service の顧客の実装を簡素化し、顧客が作業の実施時にどの程度の詳細を収集するかを柔軟に決定できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c7115-118">Field Service has introduced this configuration setting to simplify implementations for Field Service customers and to allow customers the flexibility of deciding the level of detail they wish to capture when performing work.</span></span>

<span data-ttu-id="c7115-119">これには次のものが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7115-119">This includes:</span></span>

- <span data-ttu-id="c7115-120">Field Service の設定で、予約ごとにタイムスタンプが収集される頻度を定義します。</span><span class="sxs-lookup"><span data-stu-id="c7115-120">Define in Field Service settings the frequency at which timestamps will be captured for each booking.</span></span>
- <span data-ttu-id="c7115-121">予約ステータスの変更がモバイル デバイスまたは Web ブラウザーのいずれで行われたかにかかわらず、システムでその設定を適用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="c7115-121">Enabling the system to respect that setting regardless of whether the booking status change occurs on the mobile device or via a web browser.</span></span>
- <span data-ttu-id="c7115-122">関連するタイムスタンプの適切な詳細をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="c7115-122">Capturing appropriate details on the relevant timestamps.</span></span>
- <span data-ttu-id="c7115-123">時間入力がタイムスタンプから作成された場合、時間入力が組織の設定に応じて適切な詳細レベルを保持していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="c7115-123">When a time entry is created from a timestamp, ensure that the time entry holds the right level of detail depending on the org's setting.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="c7115-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7115-124">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="c7115-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="c7115-125">See also</span></span>

<span data-ttu-id="c7115-126">[タイムスタンプの頻度の設定](https://docs.microsoft.com/dynamics365/field-service/booking-timestamps#timestamp-frequency-setting) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c7115-126">[Timestamp frequency setting](https://docs.microsoft.com/dynamics365/field-service/booking-timestamps#timestamp-frequency-setting) (docs)</span></span>

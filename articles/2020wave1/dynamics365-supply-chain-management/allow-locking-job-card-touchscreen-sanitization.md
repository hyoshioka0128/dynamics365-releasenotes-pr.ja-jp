---
title: サニタイズのためにジョブ カードのタッチスクリーンをロックできるようにする
description: この機能により、ジョブ カード デバイスまたは端末のユーザーは、タッチスクリーンを一時的にロックして、画面のサニタイズ中に意図しない入力を防ぐことができます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/02/2020
ms.assetid: 1691ee10-fd8d-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: johanho
dynamics365pdf: true
ms.openlocfilehash: 40f40048cbbe50e69eda2b8d411dfea077fb40d4
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441757"
---
# <a name="allow-locking-the-job-card-touchscreen-for-sanitization"></a><span data-ttu-id="b6a86-103">サニタイズのためにジョブ カードのタッチスクリーンをロックできるようにする</span><span class="sxs-lookup"><span data-stu-id="b6a86-103">Allow locking the job card touchscreen for sanitization</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="b6a86-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b6a86-104">Enabled for</span></span>    |  <span data-ttu-id="b6a86-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b6a86-105">Public preview</span></span> | <span data-ttu-id="b6a86-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b6a86-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b6a86-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="b6a86-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b6a86-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b6a86-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b6a86-109">2020 年 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="b6a86-109">May 29, 2020</span></span>| <span data-ttu-id="b6a86-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="b6a86-110">Jul 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b6a86-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b6a86-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b6a86-112">この機能により、ユーザーはジョブ カードのタッチスクリーンを数秒間ロックしてサニタイズできます。</span><span class="sxs-lookup"><span data-stu-id="b6a86-112">This feature lets users lock the job card touchscreen for a few seconds so they can sanitize it.</span></span> <span data-ttu-id="b6a86-113">機能を有効化および構成するには、**デバイスのジョブ カードの構成**および**端末のジョブ カードの構成**ページを使用します。</span><span class="sxs-lookup"><span data-stu-id="b6a86-113">Use the **Configure job card devices** and the **Configure job card for terminals** pages to enable and configure the feature.</span></span> <span data-ttu-id="b6a86-114">この機能を有効にすると、**サニタイズのために画面をロックする**というボタンがデバイスのサインイン ページに追加されます。</span><span class="sxs-lookup"><span data-stu-id="b6a86-114">When enabled, the feature adds a button called **Lock screen for sanitizing** to the device sign-in page.</span></span> <span data-ttu-id="b6a86-115">ユーザーがこのボタンを選択すると、意図しない入力を防ぐためにタッチスクリーンが一時的にロックされ、カウントダウン タイマーが表示されます。</span><span class="sxs-lookup"><span data-stu-id="b6a86-115">When a user selects this button, the touchscreen temporarily locks to prevent unintended input and a countdown timer is shown.</span></span> <span data-ttu-id="b6a86-116">これで、ユーザーはデバイスと画面を安全にクリーニングできます。</span><span class="sxs-lookup"><span data-stu-id="b6a86-116">The user can now safely clean the device and the screen.</span></span> <span data-ttu-id="b6a86-117">カウントダウンが完了すると、タッチスクリーンは自動的に再びロック解除されます。</span><span class="sxs-lookup"><span data-stu-id="b6a86-117">When the countdown completes, the touchscreen automatically unlocks again.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b6a86-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="b6a86-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="b6a86-119">[デバイスのジョブ カードのコンフィギュレーション](https://docs.microsoft.com/dynamics365/supply-chain/production-control/config-job-card-device) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b6a86-119">[Configure job card for devices](https://docs.microsoft.com/dynamics365/supply-chain/production-control/config-job-card-device) (docs)</span></span>
<!--docs end-->

---
title: ライセンスの適用 - 新しい Team Member ライセンスを持つユーザー
description: 新しい Team Member ライセンスを持つユーザーに対するライセンス ベースのアクセス。
author: relnotes
ms.reviewer: nenellim
ms.date: 02/04/2020
ms.assetid: 28ed5bc6-6c36-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: sriknair
dynamics365pdf: true
ms.openlocfilehash: cf1a969c3003664b1ce644be5800aa408e2c11f7
ms.sourcegitcommit: 0a73f7354797bcbf643214c5f32d32a0b03a2899
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/08/2020
ms.locfileid: "3033250"
---
# <a name="license-enforcement---users-with-new-team-member-licenses"></a><span data-ttu-id="ceeb1-103">ライセンスの適用 - 新しい Team Member ライセンスを持つユーザー</span><span class="sxs-lookup"><span data-stu-id="ceeb1-103">License enforcement - users with new Team Member licenses</span></span>
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| <span data-ttu-id="ceeb1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ceeb1-104">Enabled for</span></span>    |  <span data-ttu-id="ceeb1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ceeb1-105">Public preview</span></span> | <span data-ttu-id="ceeb1-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="ceeb1-106">Early access</span></span> | <span data-ttu-id="ceeb1-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ceeb1-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="ceeb1-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ceeb1-108">End users, automatically</span></span>|-|<span data-ttu-id="ceeb1-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ceeb1-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ceeb1-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="ceeb1-110">Feb 3, 2020</span></span>| <span data-ttu-id="ceeb1-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="ceeb1-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ceeb1-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ceeb1-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ceeb1-113">ライセンス ガイドに記載されている Team Member ライセンス ベースのアクセスにお客様が合わせるのを支援します。</span><span class="sxs-lookup"><span data-stu-id="ceeb1-113">Helps customers to be aligned with the Team Member license-based access mentioned in the licensing guide.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ceeb1-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ceeb1-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ceeb1-115">2018 年 10 月中またはそれ以降に購入された Team Member ライセンスの場合、ライセンスベースのアクセス機能により、ユーザーは以下の指定されたアプリ モジュールのセットに制限されます。</span><span class="sxs-lookup"><span data-stu-id="ceeb1-115">For Team Member licenses purchased during or after October 2018, the license-based access feature will restrict users to the following set of designated app modules:</span></span>

- <span data-ttu-id="ceeb1-116">顧客サービス チーム メンバー</span><span class="sxs-lookup"><span data-stu-id="ceeb1-116">Customer Service Team Member</span></span>
- <span data-ttu-id="ceeb1-117">営業チーム メンバー</span><span class="sxs-lookup"><span data-stu-id="ceeb1-117">Sales Team Member</span></span>
- <span data-ttu-id="ceeb1-118">プロジェクト リソース ハブ</span><span class="sxs-lookup"><span data-stu-id="ceeb1-118">Project Resource Hub</span></span>

<span data-ttu-id="ceeb1-119">早期アクセス フェーズの間、Team Member ライセンスを持つユーザーは、指定されたアプリ モジュールと共に既存のすべてのアプリを使用できます。</span><span class="sxs-lookup"><span data-stu-id="ceeb1-119">During the early access phase, users with the Team Member licenses will be able to use the designated app modules alongside all existing apps.</span></span> <span data-ttu-id="ceeb1-120">ライセンスが適用されると (2020 年 4 月 1 日以降)、Team Member ライセンスを持つユーザーは、顧客サービスハブ、営業ハブ、カスタム アプリなど、制限されたアプリをご利用いただけなくなります。</span><span class="sxs-lookup"><span data-stu-id="ceeb1-120">After the licenses are enforced (starting April 1, 2020), restricted apps, such as Customer Service Hub, Sales Hub, and custom apps, will not be accessible to users with the Team Member licenses.</span></span> <span data-ttu-id="ceeb1-121">お客様は、一般提供の前に完全な適用を事前にプレビューすることもできます。</span><span class="sxs-lookup"><span data-stu-id="ceeb1-121">Customers can also proactively preview full enforcement before general availability.</span></span> <span data-ttu-id="ceeb1-122">Team Member シナリオをテストし、必要に応じてカスタマイズ内容を指定されたアプリに移行することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="ceeb1-122">We recommend that the Team Member scenarios be tested and customizations migrated to the designated app modules, as needed.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ceeb1-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="ceeb1-123">See also</span></span>

<span data-ttu-id="ceeb1-124">[顧客サービス チーム メンバー アプリ](https://docs.microsoft.com/dynamics365/customer-service/customer-service-team-member) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ceeb1-124">[Customer Service Team Member app](https://docs.microsoft.com/dynamics365/customer-service/customer-service-team-member) (docs)</span></span>

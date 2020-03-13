---
title: ライセンスの適用 - 新しい Team Member ライセンスを持つユーザー
description: 新しい Team Member ライセンスを持つユーザーに対するライセンスの適用。
author: relnotes
ms.reviewer: shujoshi
ms.date: 02/04/2020
ms.assetid: c37b195e-6736-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: sriknair
dynamics365pdf: true
ms.openlocfilehash: efc5ed73a5dd0be865d3132c1c56aaaf0afad39f
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032146"
---
# <a name="license-enforcement---users-with-new-team-member-licenses"></a><span data-ttu-id="4d8c0-103">ライセンスの適用 - 新しい Team Member ライセンスを持つユーザー</span><span class="sxs-lookup"><span data-stu-id="4d8c0-103">License enforcement - users with new Team Member licenses</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="4d8c0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4d8c0-104">Enabled for</span></span>    |  <span data-ttu-id="4d8c0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4d8c0-105">Public preview</span></span> | <span data-ttu-id="4d8c0-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="4d8c0-106">Early access</span></span> | <span data-ttu-id="4d8c0-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="4d8c0-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="4d8c0-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="4d8c0-108">End users, automatically</span></span>|-|<span data-ttu-id="4d8c0-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4d8c0-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4d8c0-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="4d8c0-110">Feb 3, 2020</span></span>| <span data-ttu-id="4d8c0-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="4d8c0-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="4d8c0-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4d8c0-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4d8c0-113">このライセンスの適用により、お客様は、「[Microsoft Dynamics 365 ライセンス ガイド](https://go.microsoft.com/fwlink/p/?LinkId=866544)」で説明されている Team Member ライセンスの制限に合わせることができます。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-113">This licensing enforcement helps customers align with the Team Member license restrictions described in the [Microsoft Dynamics 365 Licensing Guide](https://go.microsoft.com/fwlink/p/?LinkId=866544).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4d8c0-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4d8c0-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4d8c0-115">2018 年 10 月中またはそれ以降に購入された Team Member ライセンスの場合、ライセンス ベースのアクセスにより、ユーザーは指定されたアプリ モジュールのセットに制限されます。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-115">For Team Member licenses purchased during or after October 2018, license-based access will restrict users to a set of designated app modules.</span></span> <span data-ttu-id="4d8c0-116">これらのユーザーは、顧客サービス ハブ、セールス ハブ、またはカスタム アプリ モジュールにアクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-116">These users will no longer be able to access Customer Service Hub, Sales Hub, or custom app modules.</span></span> <span data-ttu-id="4d8c0-117">指定されているアプリ モジュールは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-117">The designated app modules are as follows:</span></span>

- <span data-ttu-id="4d8c0-118">顧客サービス チーム メンバー</span><span class="sxs-lookup"><span data-stu-id="4d8c0-118">Customer Service Team Member</span></span> 
- <span data-ttu-id="4d8c0-119">営業チーム メンバー</span><span class="sxs-lookup"><span data-stu-id="4d8c0-119">Sales Team Member</span></span>
- <span data-ttu-id="4d8c0-120">プロジェクト リソース ハブ</span><span class="sxs-lookup"><span data-stu-id="4d8c0-120">Project Resource Hub</span></span>

<span data-ttu-id="4d8c0-121">早期アクセス フェースの間、Team Member ライセンスを持つユーザーは、上記の指定されたアプリ モジュールと共に既存のすべてのアプリを使用できます。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-121">During the early access phase, users with Team Member licenses will be able to use the designated app modules mentioned above alongside all existing apps.</span></span> <span data-ttu-id="4d8c0-122">ライセンスの適用が有効になると (2020 年 4 月 1 日以降)、顧客サービス ハブ、営業ハブ、カスタム アプリなどの資格のないアプリにはアクセスできなくなります。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-122">Once license enforcement is turned on (starting April 1, 2020), unentitled apps such as Customer Service Hub, Sales Hub, and custom apps will not be accessible.</span></span> 

<span data-ttu-id="4d8c0-123">お客様は、一般提供の前に完全な適用を事前にプレビューすることもできます。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-123">Customers can also proactively preview full enforcement before general availability.</span></span> <span data-ttu-id="4d8c0-124">Team Member シナリオをテストし、必要に応じてカスタマイズ内容を指定されたアプリに移行することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-124">We recommend that the Team Member scenarios be tested and customizations migrated to the designated app modules, as needed.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="4d8c0-125">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="4d8c0-125">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="4d8c0-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="4d8c0-126">See also</span></span>

<span data-ttu-id="4d8c0-127">[Team Member ライセンスを持つユーザー向けの営業チーム メンバー アプリ](https://docs.microsoft.com/dynamics365/sales-enterprise/sales-team-member) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="4d8c0-127">[Sales Team Member app for users with Team Member license](https://docs.microsoft.com/dynamics365/sales-enterprise/sales-team-member) (docs)</span></span>

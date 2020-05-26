---
title: Dynamics GP からすべてまたはアクティブな顧客マスター レコードを移行する
description: 現在の Dynamics GP Cloud Migration ツールにサポートを追加して、ユーザーがすべてまたはアクティブな顧客マスター レコードを移行する必要があるかどうかを指定して追加のアドレスを移行できるようにします。
author: relnotes
ms.reviewer: edupont
ms.date: 04/06/2020
ms.assetid: bca1bc47-ac16-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 797fb05dea8f6729665b7feaf113ae4a30d769ee
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256005"
---
# <a name="migrate-all-or-only-active-customer-master-records-from-dynamics-gp"></a><span data-ttu-id="1576e-103">Dynamics GP からすべてまたはアクティブな顧客マスター レコードを移行する</span><span class="sxs-lookup"><span data-stu-id="1576e-103">Migrate all or only active customer master records from Dynamics GP</span></span>


| <span data-ttu-id="1576e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1576e-104">Enabled for</span></span>    |  <span data-ttu-id="1576e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1576e-105">Public preview</span></span> | <span data-ttu-id="1576e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1576e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1576e-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1576e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1576e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1576e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1576e-109">2020 年 3 月 2 日</span><span class="sxs-lookup"><span data-stu-id="1576e-109">Mar 2, 2020</span></span>| <span data-ttu-id="1576e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1576e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1576e-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="1576e-111">Apr 1, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="1576e-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1576e-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1576e-113">ユーザーはこの移行ツールを使用して、すべての顧客を移行するか、Dynamics GP でアクティブな状態の顧客のみを移行することができます。</span><span class="sxs-lookup"><span data-stu-id="1576e-113">The migration tool will allow the user to migrate either all customers or only customers who have an active status in Dynamics GP.</span></span> <span data-ttu-id="1576e-114">この変更に加えて、顧客のアドレスもすべて移行します。</span><span class="sxs-lookup"><span data-stu-id="1576e-114">Along with that change, we will also migrate all customer addresses.</span></span> <span data-ttu-id="1576e-115">現在は Dynamics GP で顧客カードに関連付けられたプライマリ アドレスのみを移行します。</span><span class="sxs-lookup"><span data-stu-id="1576e-115">Currently we only migrate the primary address associated with the customer card in Dynamics GP.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1576e-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="1576e-116">See also</span></span>

<!--docs start-->
<span data-ttu-id="1576e-117">[Dynamics GP から Business Central Online に移行する](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/migrate-dynamics-gp) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1576e-117">[Migrate to Business Central Online from Dynamics GP](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/migrate-dynamics-gp) (docs)</span></span>
<!--docs end-->

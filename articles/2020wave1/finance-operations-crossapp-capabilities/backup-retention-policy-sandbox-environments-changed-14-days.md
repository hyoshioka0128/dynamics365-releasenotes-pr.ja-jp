---
title: サンドボックス環境のバックアップ保持ポリシーを 14 日に変更
description: バックアップ保持ポリシーと実践を Dynamics 365 と Power Platform 製品ラインの間で調整するために、Finance and Operations サンドボックス環境では、保持する自動バックアップが過去 30 日ではなく 14 日に短縮されます。
author: relnotes
ms.reviewer: sericks
ms.date: 06/05/2020
ms.assetid: 060d63ae-e58e-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: c21f5f03530832736fb68e774fdcfe6dab0ea411
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548414"
---
# <a name="backup-retention-policy-for-sandbox-environments-changed-to-14-days"></a><span data-ttu-id="6e0ed-103">サンドボックス環境のバックアップ保持ポリシーを 14 日に変更</span><span class="sxs-lookup"><span data-stu-id="6e0ed-103">Backup retention policy for sandbox environments changed to 14 days</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="6e0ed-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6e0ed-104">Enabled for</span></span>    |  <span data-ttu-id="6e0ed-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6e0ed-105">Public preview</span></span> | <span data-ttu-id="6e0ed-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6e0ed-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6e0ed-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="6e0ed-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="6e0ed-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6e0ed-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6e0ed-109">2020 年 6 月 4 日</span><span class="sxs-lookup"><span data-stu-id="6e0ed-109">Jun 4, 2020</span></span>| <span data-ttu-id="6e0ed-110">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="6e0ed-110">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="6e0ed-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6e0ed-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6e0ed-112">Dynamics 365 および Microsoft Power Platform 製品ライン内の複数製品の利用を開始するお客様が増えているため、Finance and Operations サンドボックスを Customer Engagement、Common Data Service、またはその他の Dynamics 365 タイプの環境より前の環境に復元する機能により、解決されるよりも多くの課題が生じます。</span><span class="sxs-lookup"><span data-stu-id="6e0ed-112">As more customers begin to make use of multiple products within the Dynamics 365 and Microsoft Power Platform product lines, the ability to restore a Finance and Operations sandbox back further in time than a Customer Engagement, Common Data Service, or other Dynamics 365 type environment creates more challenges than it solves.</span></span>  <span data-ttu-id="6e0ed-113">これは保持期間を 30 日間から 14 日間に短縮する最初のステップであり、今後、過去 14 日間から 7 日間に短縮する発表が行われます。</span><span class="sxs-lookup"><span data-stu-id="6e0ed-113">This is the first step to reduce retention from 30 days to 14 days, and a follow-up announcement will be made in the future to reduce it from 14 days to 7 days of history.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6e0ed-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6e0ed-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6e0ed-115">サンドボックス環境でポイントインタイム リストア アクションを実行して、データベースを以前の特定の時点に戻すお客様は、最大で過去 14 日間に制限されるようになります。</span><span class="sxs-lookup"><span data-stu-id="6e0ed-115">Customers who perform point-in-time restore actions on their sandbox environments, to take the database back to a previous point in time, will now be limited to a maximum of 14 days of history.</span></span>  <span data-ttu-id="6e0ed-116">過去 14 日より前の日付の選択は禁止されます。</span><span class="sxs-lookup"><span data-stu-id="6e0ed-116">Choosing a date beyond 14 days will be prohibited.</span></span>  <span data-ttu-id="6e0ed-117">警告は、これらのアクションを実行しているユーザーの Lifecycle Services にも追加されます。</span><span class="sxs-lookup"><span data-stu-id="6e0ed-117">Warnings will also be added to Lifecycle Services for users who are performing these actions.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6e0ed-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="6e0ed-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="6e0ed-119">[データベース ポイントインタイム復元 (PITR)](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/database-point-in-time-restore) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6e0ed-119">[Database point-in-time restore (PITR)](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/database-point-in-time-restore) (docs)</span></span>
<!--docs end-->

---
title: Business Central 管理センターでの稼働停止のレポート
description: 顧客のテナントが停止してだれもログインできない場合は、緊急の対応が必要な重大な状況です。 Business Central 管理センターでは、パートナーはサポート チケットを自動的に作成する新しい [稼働停止のレポート] オプションを使用できるようになりました。
author: relnotes
ms.reviewer: edupont
ms.date: 11/15/2019
ms.assetid: 320a4afe-037b-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jchrist
dynamics365pdf: true
ms.openlocfilehash: a75d3dd0f1edbc10d4d07527311b99499ea68f33
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892044"
---
# <a name="report-production-outage-in-the-business-central-administration-center"></a><span data-ttu-id="88bcb-104">Business Central 管理センターでの稼働停止のレポート</span><span class="sxs-lookup"><span data-stu-id="88bcb-104">Report production outage in the Business Central Administration Center</span></span>


| <span data-ttu-id="88bcb-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="88bcb-105">Enabled for</span></span>    |  <span data-ttu-id="88bcb-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="88bcb-106">Public preview</span></span> | <span data-ttu-id="88bcb-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="88bcb-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="88bcb-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="88bcb-108">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="88bcb-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="88bcb-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="88bcb-110">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="88bcb-110">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="88bcb-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="88bcb-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="88bcb-112">顧客のテナントが停止していると判断されたら、Business Central 管理センターですぐにサポート チケットを作成できます。</span><span class="sxs-lookup"><span data-stu-id="88bcb-112">Once it is determined that the customer's tenant is down, you can quickly create a support ticket in the Business Central Administration Center.</span></span> <span data-ttu-id="88bcb-113">顧客の運用環境を選択すると、新しいオプション**稼働停止のレポート**が有効になります。</span><span class="sxs-lookup"><span data-stu-id="88bcb-113">When you choose the customer's production environment, a new option, **Report Production Outage**, is enabled.</span></span> <span data-ttu-id="88bcb-114">このオプションは、サンドボックス環境では使用できません。</span><span class="sxs-lookup"><span data-stu-id="88bcb-114">This option is not available for a sandbox environment.</span></span> <span data-ttu-id="88bcb-115">このアクションを選択した場合、使用可能な停止タイプは**ログオンできません (すべてのユーザー)** と **API/Web サービスにアクセスできません**です。</span><span class="sxs-lookup"><span data-stu-id="88bcb-115">If you choose this action, the available outage types are **Unable to log on (all users)** and **Cannot access API/Web Service**.</span></span> 

<span data-ttu-id="88bcb-116">選択後、他の必須フィールドは [名前]、[電子メール アドレス]、[電話番号] です。</span><span class="sxs-lookup"><span data-stu-id="88bcb-116">Once selected, the other required fields are Name, Email address, and Phone number.</span></span> <span data-ttu-id="88bcb-117">次の画面では、試行したブラウザー、ログインできる会社、受信したエラー メッセージなど、停止に関する詳細が表示されます。</span><span class="sxs-lookup"><span data-stu-id="88bcb-117">The next screen allows more details about the outage such as the browsers tried, any companies they can sign in to, and error messages received.</span></span> <span data-ttu-id="88bcb-118">最後の質問は、停止が開始された日時に関するものです。</span><span class="sxs-lookup"><span data-stu-id="88bcb-118">The last question is about the date and time the outage began.</span></span> 

<span data-ttu-id="88bcb-119">同意ボックスをオンにした後、**レポート**を選択して停止を作成します。</span><span class="sxs-lookup"><span data-stu-id="88bcb-119">After marking the consent box, select **Report** to create the outage.</span></span> <span data-ttu-id="88bcb-120">サポート チケットがすべての詳細と共に自動的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="88bcb-120">A support ticket is created automatically with all details.</span></span> <span data-ttu-id="88bcb-121">これは Business Central 管理センターの**報告された停止**ページで確認できます。</span><span class="sxs-lookup"><span data-stu-id="88bcb-121">It can be viewed in the **Reported Outages** page in the Business Central Administration Center.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="88bcb-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="88bcb-122">See also</span></span>

<span data-ttu-id="88bcb-123">[顧客の機能停止を報告する](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/manage-technical-support#report-customer-outages) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="88bcb-123">[Report customer outages](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/manage-technical-support#report-customer-outages) (docs)</span></span>

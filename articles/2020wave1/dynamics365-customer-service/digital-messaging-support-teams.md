---
title: Microsoft Teams 向けデジタル メッセージング サポート
description: Microsoft Teams チャネルを通じて顧客に働きかけ、時間のあるときに会話に参加できる利便性を提供します。
author: relnotes
ms.reviewer: laalexan
ms.date: 04/09/2020
ms.assetid: b94b0f50-f31d-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: srikot
dynamics365pdf: true
ms.openlocfilehash: c95ded8e651a67ffa90422c44a728d4f6c5f8112
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273359"
---
# <a name="digital-messaging-support-for-microsoft-teams"></a><span data-ttu-id="7176c-103">Microsoft Teams 向けデジタル メッセージング サポート</span><span class="sxs-lookup"><span data-stu-id="7176c-103">Digital messaging support for Microsoft Teams</span></span>


| <span data-ttu-id="7176c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7176c-104">Enabled for</span></span>    |  <span data-ttu-id="7176c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7176c-105">Public preview</span></span> | <span data-ttu-id="7176c-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="7176c-106">Early access</span></span> | <span data-ttu-id="7176c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="7176c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="7176c-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="7176c-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7176c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7176c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7176c-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7176c-110">Apr 1, 2020</span></span>|-| -|


## <a name="business-value"></a><span data-ttu-id="7176c-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7176c-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7176c-112">内部のビジネス コラボレーションに Microsoft Teams を既に使用している企業は、これを利用して従業員への内部サポートの提供を容易にすることができます。</span><span class="sxs-lookup"><span data-stu-id="7176c-112">Businesses that already use Microsoft Teams for internal business collaboration can now use it to facilitate internal support delivery to employees.</span></span> <span data-ttu-id="7176c-113">これにより、企業は既に使用しているソリューションに応じて、内部のビジネス運営のために管理する必要があるツールとインフラストラクチャの数を減らし、ユーザー エクスペリエンスを簡素化することができます。</span><span class="sxs-lookup"><span data-stu-id="7176c-113">This may reduce the number of tools and infrastructure a business has to manage for internal business operations and simplify the user experience, depending on the solutions they already use.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7176c-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7176c-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7176c-115">内部のチームのコラボレーションとビジネス運営のために Microsoft Teams を採用する組織が増え続けるのに伴い、従業員が Teams を通じて内部サポートを受けられるようにしたいという要望が高まっています。</span><span class="sxs-lookup"><span data-stu-id="7176c-115">As organizations continue to adopt Microsoft Teams for internal team collaboration and business operations, there is an increasing desire to allow their employees to obtain internal support through Teams.</span></span> <span data-ttu-id="7176c-116">この機能を使用すると、組織は Customer Service 用オムニチャネルを使用し、テクニカル サポート、人事管理、財務などの内部機能のサポート用のエンゲージメント チャネルとして Microsoft Teams を導入することで、従業員を内部のサポート担当者とつなげることができます。</span><span class="sxs-lookup"><span data-stu-id="7176c-116">This feature allows organizations to connect their employees with internal support personnel using Omnichannel for Customer Service by bringing in Microsoft Teams as an engagement channel for support of internal functions like tech support, human resources, and finance.</span></span> 

-   <span data-ttu-id="7176c-117">管理者は、**オムニチャネル管理**アプリで Microsoft Teams チャネルを構成できます。</span><span class="sxs-lookup"><span data-stu-id="7176c-117">Administrators can configure the Microsoft Teams channel in the **Omnichannel Administration** app.</span></span>
-   <span data-ttu-id="7176c-118">顧客は、Microsoft Teams を通じて企業に連絡し、非同期的なサポートを得ることができます。</span><span class="sxs-lookup"><span data-stu-id="7176c-118">Employees can contact the business through Microsoft Teams and seek support in an asynchronous nature.</span></span>
-   <span data-ttu-id="7176c-119">エージェントは、同じ統一された状況依存の生産的な **Customer Service 用オムニチャネル** アプリ インターフェイスを使用して顧客とやり取りし、顧客の問題を解決することができます。</span><span class="sxs-lookup"><span data-stu-id="7176c-119">Agents can use the same unified, contextual, and productive **Omnichannel for Customer Service** app interface to engage with customers and resolve their issues.</span></span>
-   <span data-ttu-id="7176c-120">スーパーバイザーとマネージャーは、サポート センターを効率的かつ効果的に運営するのに役立つ充実したレポートにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="7176c-120">Supervisors and managers can access the rich reports to run the support center efficiently and effectively.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="7176c-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="7176c-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="7176c-122">[Microsoft Teams チャネルを構成する](https://docs.microsoft.com/dynamics365/omnichannel/administrator/configure-microsoft-teams) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7176c-122">[Configure a Microsoft Teams channel](https://docs.microsoft.com/dynamics365/omnichannel/administrator/configure-microsoft-teams) (docs)</span></span>
<!--docs end-->

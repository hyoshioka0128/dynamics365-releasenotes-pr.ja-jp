---
title: Tier 2-5 スタンダード承認テスト (サンドボックス) 環境へのリモート デスクトップ アクセスの除去
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 04/02/2020
ms.assetid: 7b7ebaba-8d74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: e2b7eb3913fc1c6cb651702bf17e76b524843d79
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219702"
---
# <a name="removing-remote-desktop-access-to-tier-2-5-standard-acceptance-test-or-sandbox-environments"></a><span data-ttu-id="7331e-102">Tier 2-5 スタンダード承認テスト (サンドボックス) 環境へのリモート デスクトップ アクセスの除去</span><span class="sxs-lookup"><span data-stu-id="7331e-102">Removing Remote Desktop access to Tier 2-5 Standard Acceptance Test (or sandbox) environments</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="7331e-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="7331e-103">Enabled for</span></span>    |  <span data-ttu-id="7331e-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7331e-104">Public preview</span></span> | <span data-ttu-id="7331e-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="7331e-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7331e-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="7331e-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="7331e-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="7331e-107">Apr 2020</span></span>| <span data-ttu-id="7331e-108">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="7331e-108">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7331e-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7331e-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7331e-110">すべての診断、トラブルシューティング、パフォーマンス、テスト活動をセルフサービスに移行すること、および、お客様とパートナーからのインフラストラクチャ アクセスの制限によって全体的なセキュリティを強化することを目的に、完全なリモート デスクトップ アクセスの除去に向けた 2 段階のアプローチを取ります。</span><span class="sxs-lookup"><span data-stu-id="7331e-110">With the goal of moving all diagnostic, troubleshooting, performance, and testing activities to be self-service, as well as increasing overall security by limiting infrastructure access from customers and partners, we will be taking a two-phased approach to full Remote Desktop access removal.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7331e-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7331e-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7331e-112">プレビューの一環として、Tier 2-5 サンドボックス環境への管理者アクセスを除去します。</span><span class="sxs-lookup"><span data-stu-id="7331e-112">As part of the preview, we will be removing administrator access to Tier 2-5 sandbox environments.</span></span> <span data-ttu-id="7331e-113">新しい環境は、現在の Tier 1 環境と同様に、管理者以外のユーザー資格情報のみを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="7331e-113">New environments will only receive non-admin user credentials, similar to Tier 1 environments today.</span></span>  

<span data-ttu-id="7331e-114">GA (一般提供) では、お客様は Microsoft サブスクリプションに展開された Tier 2-5 サンドボックス環境への RDP アクセスができなくなります。</span><span class="sxs-lookup"><span data-stu-id="7331e-114">For GA, customers will no longer have RDP access to Tier 2-5 sandbox environments deployed in a Microsoft subscription.</span></span> <span data-ttu-id="7331e-115">現在、お客様とパートナーは運用環境への RDP アクセスはできませんが、Microsoft サブスクリプションに展開された Tier 2-5 サンドボックス環境にリモート アクセスすることはできます。</span><span class="sxs-lookup"><span data-stu-id="7331e-115">Today, customers and partners do not have RDP access to production environments, but they are able to have remote access to the Tier 2-5 sandbox environments deployed in a Microsoft subscription.</span></span> 

<span data-ttu-id="7331e-116">今後は、運用環境で実行される操作の安定性と信頼性を向上させ、Tier 2-5 サンドボックス環境が運用環境を模倣できるようにするために、これらの環境への RDP アクセス全体を制限します。</span><span class="sxs-lookup"><span data-stu-id="7331e-116">Going forward, to improve the stability and reliability of the operations performed in production environments and to ensure that Tier 2-5 sandbox environments mimic the production environment, we will restrict complete RDP access to these environments.</span></span> <span data-ttu-id="7331e-117">アクセスを制限する前に、これらの環境での、お客様がリモート アクセスを使用する必要があるすべてのプロセスを自動化します。</span><span class="sxs-lookup"><span data-stu-id="7331e-117">We will automate all the processes that require customers to use remote access for these environments before restricting access.</span></span>
<!--feature detail end -->










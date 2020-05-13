---
title: 状況依存のメール通信
description: メールは、顧客とコミュニケーションをとる事実上すべての営業担当者にとって中心的なシナリオです。
author: relnotes
ms.reviewer: shujoshi
ms.date: 04/07/2020
ms.assetid: ca61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: ead16717af30f6ad32b8f7893c917eb751874119
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320195"
---
# <a name="contextual-email-communication"></a><span data-ttu-id="ca66b-103">状況依存のメール通信</span><span class="sxs-lookup"><span data-stu-id="ca66b-103">Contextual email communication</span></span>


| <span data-ttu-id="ca66b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ca66b-104">Enabled for</span></span>    |  <span data-ttu-id="ca66b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ca66b-105">Public preview</span></span> | <span data-ttu-id="ca66b-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="ca66b-106">Early access</span></span> | <span data-ttu-id="ca66b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ca66b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="ca66b-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ca66b-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ca66b-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ca66b-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ca66b-110">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ca66b-110">Oct 1, 2019</span></span>|-| <span data-ttu-id="ca66b-111">近日発表</span><span class="sxs-lookup"><span data-stu-id="ca66b-111">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="ca66b-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ca66b-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ca66b-113">顧客から最も多い要望です。</span><span class="sxs-lookup"><span data-stu-id="ca66b-113">A top request by customers.</span></span> 

<span data-ttu-id="ca66b-114">Microsoft は Dynamics 365 Sales と Outlook の統合をいくつか提供しているので、長年にわたり軽量メール エディターのエクスペリエンスに頼ってきました。</span><span class="sxs-lookup"><span data-stu-id="ca66b-114">Because Microsoft provides several integrations of Dynamics 365 Sales with Outlook, we have relied on lightweight email editor experiences for many years.</span></span> <span data-ttu-id="ca66b-115">メールは、リードや関係者と絶えず連絡を取り合う営業担当者の日常における中心的な要素です。</span><span class="sxs-lookup"><span data-stu-id="ca66b-115">Email is a central component every day in the life of salespeople, who are in constant contact with their leads and stakeholders.</span></span> <span data-ttu-id="ca66b-116">メールを作成するときに、セールス チームはページに表示されているデータを頻繁に参照し、そこから移動したくないと考えます。</span><span class="sxs-lookup"><span data-stu-id="ca66b-116">When composing emails, sales teams frequently refer to data displayed on a page and they don't want to navigate away from it.</span></span> <span data-ttu-id="ca66b-117">既存のフォームの上にメール作成画面をオーバーレイすることで、販売担当者は現在表示している画面から移動することなくメールを作成できます。</span><span class="sxs-lookup"><span data-stu-id="ca66b-117">By overlaying an email composition screen on top of the existing form, sellers will be able to compose an email without having to navigate away from the screen they are on.</span></span> <span data-ttu-id="ca66b-118">これにより、顧客に対してより思慮深いメールを作成し、エンゲージメントの質を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="ca66b-118">This allows them to compose more thoughtful emails to their customers and improve the quality of engagement.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ca66b-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ca66b-119">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ca66b-120">リッチ テキスト エディターとポップアップ (非ブロッキング ウィンドウ) により、Dynamics 365 Sales でのメールの作成は、これまでにないほど便利になっています。</span><span class="sxs-lookup"><span data-stu-id="ca66b-120">With a rich text editor and a pop-up, non-blocking window, composing email has never been better in Dynamics 365 Sales.</span></span> <span data-ttu-id="ca66b-121">営業担当者は、作業中のレコードのコンテキストでメールを作成し、レコード間を移動し、複数のアクティブなドラフト メールを同時に開き、送信前にコンテンツをプレビューし、添付ファイルを追加し、メール テンプレートを使用してよく使用されるタスクを最適化できるようになります。</span><span class="sxs-lookup"><span data-stu-id="ca66b-121">Salespeople will be able to write email with context of the record they are working on, navigate between records, have multiple active draft emails open simultaneously, preview the content before sending, add attachments, and use email templates to optimize commonly used tasks.</span></span> <span data-ttu-id="ca66b-122">非ブロッキング ウィンドウに開かれるメール ウィンドウにより、営業担当者は顧客へのメールを作成しながらすべての関連コンテンツをひと目で確認できます。</span><span class="sxs-lookup"><span data-stu-id="ca66b-122">The email opening up in a non-blocking window gives salespeople all the relevant content at a glance while they compose their email to the customer.</span></span> 

<!--
![Compose email without losing context](media/features-1.png "Compose email without losing context") -->
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="ca66b-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="ca66b-123">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="ca66b-124">この機能は、Dynamics 365 Sales Enterprise のみを対象としています</span><span class="sxs-lookup"><span data-stu-id="ca66b-124">This capability is intended only for Dynamics 365 Sales Enterprise</span></span>







## <a name="see-also"></a><span data-ttu-id="ca66b-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="ca66b-125">See also</span></span>
<span data-ttu-id="ca66b-126">[機能の探索](https://aka.ms/ROGS19RW2ROV2) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="ca66b-126">[Feature exploration](https://aka.ms/ROGS19RW2ROV2) (video)</span></span>

<!--docs start-->
<span data-ttu-id="ca66b-127">[拡張されたメール エクスペリエンスを使用してメールを送信する](https://docs.microsoft.com/dynamics365/sales-enterprise/enhanced-email) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ca66b-127">[Send email using enhanced email experience](https://docs.microsoft.com/dynamics365/sales-enterprise/enhanced-email) (docs)</span></span>
<!--docs end-->

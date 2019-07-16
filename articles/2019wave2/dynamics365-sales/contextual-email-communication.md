---
title: 状況依存のメール通信
description: メールは、顧客とコミュニケーションをとる事実上すべての営業担当者にとって中心的なシナリオです。
author: relnotes
ms.reviewer: shujoshi
ms.date: 07/01/2019
ms.assetid: ca61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: goravi
dynamics365pdf: true
ms.openlocfilehash: 3116a5b1d39a9e9ad8299afa520ba8f392c1d309
ms.sourcegitcommit: 0c53eb8711a7594ec968a8d531a78b6ab5b98bf6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/03/2019
ms.locfileid: "1725471"
---
# <a name="contextual-email-communication"></a><span data-ttu-id="cbe8e-103">状況依存のメール通信</span><span class="sxs-lookup"><span data-stu-id="cbe8e-103">Contextual email communication</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="cbe8e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cbe8e-104">Enabled for</span></span>    |  <span data-ttu-id="cbe8e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cbe8e-105">Public preview</span></span> | <span data-ttu-id="cbe8e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cbe8e-106">General availability</span></span> | <span data-ttu-id="cbe8e-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="cbe8e-107">Early Access</span></span> |
| ---------- | ---------- |---------- |---------- |
|<span data-ttu-id="cbe8e-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="cbe8e-108">End users by admins, makers, or analysts</span></span>|| |<span data-ttu-id="cbe8e-109">いいえ</span><span class="sxs-lookup"><span data-stu-id="cbe8e-109">No</span></span> |


## <a name="business-value"></a><span data-ttu-id="cbe8e-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cbe8e-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cbe8e-111">顧客から最も多い要求です。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-111">A top request by customers.</span></span> 

<span data-ttu-id="cbe8e-112">Microsoft は Dynamics 365 for Sales と Outlook の統合をいくつか提供しているので、長年にわたり軽量メール エディターのエクスペリエンスに頼ってきました。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-112">Because Microsoft provides several integrations of Dynamics 365 for Sales with Outlook, we have relied on lightweight email editor experiences for many years.</span></span> <span data-ttu-id="cbe8e-113">メールは、リードや関係者と絶えず連絡を取り合う営業担当者の日常における中心的な要素です。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-113">Email is a central component every day in the life of salespeople, who are in constant contact with their leads and stakeholders.</span></span> <span data-ttu-id="cbe8e-114">メールを作成するときに、セールス チームはページに表示されているデータを頻繁に参照し、そこから移動したくないと考えます。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-114">When composing emails, sales teams frequently refer to data displayed on a page and they don't want to navigate away from it.</span></span> <span data-ttu-id="cbe8e-115">既存のフォームの上にメール作成画面をオーバーレイすることで、販売担当者は現在表示している画面から移動することなくメールを作成できます。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-115">By overlaying an email composition screen on top of the existing form, sellers will be able to compose an email without having to navigate away from the screen they are on.</span></span> <span data-ttu-id="cbe8e-116">これにより、顧客に対してより思慮深いメールを作成し、エンゲージメントの質を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-116">This allows them to compose more thoughtful emails to their customers and improve the quality of engagement.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cbe8e-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cbe8e-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cbe8e-118">リッチ テキスト エディターとポップアップの非ブロッキング ウィンドウにより、Dynamics 365 for Sales ではメールの作成がかつてないほど向上しています。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-118">With a rich text editor and a pop-up non-blocking window, composing email has never been better in Dynamics 365 for Sales.</span></span> <span data-ttu-id="cbe8e-119">営業担当者は、作業中のレコードのコンテキストでメールを作成し、レコード間を移動し、複数のアクティブなドラフト メールを同時に開き、送信前にコンテンツをプレビューし、添付ファイルを追加し、メール テンプレートを使用してよく使用されるタスクを最適化できるようになります。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-119">Salespeople will be able to write email with context of the record they are working on, navigate between records, have multiple active draft emails open simultaneously, preview the content before sending, add attachments, and be able to use email templates to optimize commonly used tasks.</span></span> <span data-ttu-id="cbe8e-120">非ブロッキング ウィンドウに開かれるメール ウィンドウにより、営業担当者は顧客へのメールを作成しながらすべての関連コンテンツをひと目で確認できます。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-120">The email opening up in a non-blocking window gives salespeople all the relevant content at a glance, while they compose their email to the customer.</span></span> 

<!--
![Compose email without losing context](media/features-1.png "Compose email without losing context") -->
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="cbe8e-121">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="cbe8e-121">This feature is available in the Unified Interface only.</span></span>








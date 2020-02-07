---
title: 動的なメール メッセージをテスト送信する機能
description: ''
author: jain-shailesh
ms.reviewer: shellyha
ms.date: 01/09/2020
ms.assetid: 014e97e2-18ce-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: shjain
dynamics365pdf: true
ms.openlocfilehash: 499d1dc8d8566f1d5829f57f62998095be86b318
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986746"
---
# <a name="ability-to-test-send-dynamic-email-messages"></a><span data-ttu-id="81f86-102">動的なメール メッセージをテスト送信する機能</span><span class="sxs-lookup"><span data-stu-id="81f86-102">Ability to test-send dynamic email messages</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]

| <span data-ttu-id="81f86-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="81f86-103">Enabled for</span></span>    |  <span data-ttu-id="81f86-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="81f86-104">Public preview</span></span> | <span data-ttu-id="81f86-105">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="81f86-105">Early access</span></span> | <span data-ttu-id="81f86-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="81f86-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="81f86-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="81f86-107">End users, automatically</span></span>|-|<span data-ttu-id="81f86-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="81f86-108">Feb 2020</span></span>| <span data-ttu-id="81f86-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="81f86-109">Apr 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="81f86-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="81f86-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="81f86-111">Dynamics 365 Marketing を使用すると、マーケティング担当者は、パーソナライズされた動的コンテンツを含む視覚的に充実したマーケティング電子メール メッセージを設計できます。</span><span class="sxs-lookup"><span data-stu-id="81f86-111">Dynamics 365 Marketing enables marketers to design visually rich marketing email messages that include personalized dynamic content.</span></span> <span data-ttu-id="81f86-112">電子メール クライアントではメッセージのレンダリング方法が少し異なるため、また動的コンテンツでは慎重なテストが必要になることが多いため、実稼働する前にメッセージを徹底的にプレビューおよびテストすることをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="81f86-112">Because email clients render messages slightly differently, and because dynamic content often requires careful testing, we recommend that you preview and test your messages thoroughly before going into production.</span></span> 

<span data-ttu-id="81f86-113">このリリースでは、以下を提供するようにテスト送信機能が改善されました。</span><span class="sxs-lookup"><span data-stu-id="81f86-113">With this release, the test-send function has been improved to provide:</span></span>

- <span data-ttu-id="81f86-114">送信テスト メッセージ用の改善されたエラー チェック。</span><span class="sxs-lookup"><span data-stu-id="81f86-114">Improved error checking for outgoing test messages.</span></span>
- <span data-ttu-id="81f86-115">選択したサンプル連絡先レコードに基づいて、完全にレンダリングされた動的コンテンツ (動的フィールド値、エンティティ関係、ループ、条件など) を含むテスト メッセージ。</span><span class="sxs-lookup"><span data-stu-id="81f86-115">Test messages that contain fully rendered dynamic content (including dynamic field values, entity relationships, loops, and conditionals) based on a selected sample contact record.</span></span>


<!--feature detail end -->

<span data-ttu-id="81f86-116">![テスト メッセージ内のパーソナライズされた動的データ](media/personalizedtestsend.png "テスト メッセージ内のパーソナライズされた動的データ")</span><span class="sxs-lookup"><span data-stu-id="81f86-116">![Personalized dynamic data in a test message](media/personalizedtestsend.png "Personalized dynamic data in a test message")</span></span>
<!-- Picture 1 -->









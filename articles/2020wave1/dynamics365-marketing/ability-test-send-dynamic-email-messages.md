---
title: 動的なメール メッセージをテスト送信する機能
description: 本番環境に移行する前にメッセージをプレビューしてテストし、メッセージの一貫性を確保します。
author: relnotes
ms.reviewer: alfergus
ms.date: 04/21/2020
ms.assetid: 014e97e2-18ce-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: prrana
dynamics365pdf: true
ms.openlocfilehash: a191acfc9b0711883ecb88d8960495866a203d75
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350614"
---
# <a name="ability-to-test-send-dynamic-email-messages"></a><span data-ttu-id="53d5e-103">動的なメール メッセージをテスト送信する機能</span><span class="sxs-lookup"><span data-stu-id="53d5e-103">Ability to test-send dynamic email messages</span></span>


| <span data-ttu-id="53d5e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="53d5e-104">Enabled for</span></span>    |  <span data-ttu-id="53d5e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="53d5e-105">Public preview</span></span> | <span data-ttu-id="53d5e-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="53d5e-106">Early access</span></span> | <span data-ttu-id="53d5e-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="53d5e-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="53d5e-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="53d5e-108">Admins, makers, or analysts, automatically</span></span>|-|-| <span data-ttu-id="53d5e-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="53d5e-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="53d5e-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="53d5e-110">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="53d5e-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="53d5e-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="53d5e-112">Dynamics 365 Marketing で、パーソナライズされた動的コンテンツを含む視覚的に充実した電子メール メッセージを設計できます。</span><span class="sxs-lookup"><span data-stu-id="53d5e-112">With Dynamics 365 Marketing, you can design visually rich email messages that include personalized dynamic content.</span></span> <span data-ttu-id="53d5e-113">しかし、電子メール クライアントのレンダリングのばらつきを考慮し、動的コンテンツが正確であることを確認するには、これらのメッセージを慎重にテストする必要があります。</span><span class="sxs-lookup"><span data-stu-id="53d5e-113">But these messages require careful testing to account for variation in email client rendering and to confirm that dynamic content is accurate.</span></span> <span data-ttu-id="53d5e-114">改善されたテスト送信機能により、実稼働前にメッセージをプレビューしてテストできるため、メッセージの一貫性を確保できます。</span><span class="sxs-lookup"><span data-stu-id="53d5e-114">Improved test-send functionality enables you to preview and test your messages before going into production, ensuring that your messages are consistent.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="53d5e-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="53d5e-115">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="53d5e-116">**アップグレードされたエラー検出**: 送信テスト メッセージ用の改善されたエラー チェック。</span><span class="sxs-lookup"><span data-stu-id="53d5e-116">**Upgraded error detection**: Improved error checking for outgoing test messages.</span></span>
- <span data-ttu-id="53d5e-117">**動的コンテンツのテスト送信**: 選択したサンプル連絡先レコードに基づいて、完全にレンダリングされた動的コンテンツ (動的フィールド値、エンティティ関係、ループ、条件など) を含むテスト送信メッセージ。</span><span class="sxs-lookup"><span data-stu-id="53d5e-117">**Test-send dynamic content**: Test-send messages with fully rendered dynamic content (including dynamic field values, entity relationships, loops, and conditionals) based on a selected sample contact record.</span></span>


<!--feature detail end -->

<span data-ttu-id="53d5e-118">![テスト メッセージ内のパーソナライズされた動的データ](media/personalizedtestsend.png "テスト メッセージ内のパーソナライズされた動的データ")</span><span class="sxs-lookup"><span data-stu-id="53d5e-118">![Personalized dynamic data in a test message](media/personalizedtestsend.png "Personalized dynamic data in a test message")</span></span>
<!-- Picture 1 -->









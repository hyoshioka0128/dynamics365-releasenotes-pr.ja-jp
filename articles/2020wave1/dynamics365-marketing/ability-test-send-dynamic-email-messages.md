---
title: 動的なメール メッセージをテスト送信する機能
description: ''
author: relnotes
ms.reviewer: alfergus
ms.date: 02/19/2020
ms.assetid: 014e97e2-18ce-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: yukom
dynamics365pdf: true
ms.openlocfilehash: c562c7b2d35c7e7aab9c630952d43f4eb7678bce
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3098764"
---
# <a name="ability-to-test-send-dynamic-email-messages"></a><span data-ttu-id="7564c-102">動的なメール メッセージをテスト送信する機能</span><span class="sxs-lookup"><span data-stu-id="7564c-102">Ability to test-send dynamic email messages</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]

| <span data-ttu-id="7564c-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="7564c-103">Enabled for</span></span>    |  <span data-ttu-id="7564c-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7564c-104">Public preview</span></span> | <span data-ttu-id="7564c-105">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="7564c-105">Early access</span></span> | <span data-ttu-id="7564c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7564c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="7564c-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="7564c-107">Admins, makers, or analysts, automatically</span></span>|-|-| <span data-ttu-id="7564c-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="7564c-108">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7564c-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7564c-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7564c-110">Dynamics 365 Marketing を使用すると、マーケティング担当者は、パーソナライズされた動的コンテンツを含む視覚的に充実したマーケティング電子メール メッセージを設計できます。</span><span class="sxs-lookup"><span data-stu-id="7564c-110">Dynamics 365 Marketing enables marketers to design visually rich marketing email messages that include personalized dynamic content.</span></span> <span data-ttu-id="7564c-111">ただし、電子メール クライアントのレンダリングのばらつきを考慮し、動的コンテンツが正確であることを確認するには、慎重なテストが必要です。</span><span class="sxs-lookup"><span data-stu-id="7564c-111">Careful testing is necessary, however, to account for variation in email client rendering and to confirm that dynamic content is accurate.</span></span> <span data-ttu-id="7564c-112">改善されたテスト送信機能により、実稼働前にメッセージをプレビューしてテストできるため、メッセージの一貫性を確保できます。</span><span class="sxs-lookup"><span data-stu-id="7564c-112">Improved test-send functionality enables you to preview and test your messages before going into production, ensuring that your messages are consistent.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7564c-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7564c-113">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="7564c-114">**アップグレードされたエラー検出**: 送信テスト メッセージ用の改善されたエラー チェック。</span><span class="sxs-lookup"><span data-stu-id="7564c-114">**Upgraded error detection**: Improved error checking for outgoing test messages.</span></span>
- <span data-ttu-id="7564c-115">**動的コンテンツのテスト送信**: 選択したサンプル連絡先レコードに基づいて、完全にレンダリングされた動的コンテンツ (動的フィールド値、エンティティ関係、ループ、条件など) を含むテスト メッセージ。</span><span class="sxs-lookup"><span data-stu-id="7564c-115">**Test-send dynamic content**: Test messages that contain fully rendered dynamic content (including dynamic field values, entity relationships, loops, and conditionals) based on a selected sample contact record.</span></span>


<!--feature detail end -->

<span data-ttu-id="7564c-116">![テスト メッセージ内のパーソナライズされた動的データ](media/personalizedtestsend.png "テスト メッセージ内のパーソナライズされた動的データ")</span><span class="sxs-lookup"><span data-stu-id="7564c-116">![Personalized dynamic data in a test message](media/personalizedtestsend.png "Personalized dynamic data in a test message")</span></span>
<!-- Picture 1 -->









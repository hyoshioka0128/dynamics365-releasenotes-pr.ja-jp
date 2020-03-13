---
title: ナレッジ機能に対するエージェントの生産性強化
description: ナレッジ機能に対するエージェントの生産性強化
author: relnotes
ms.reviewer: laalexan
ms.date: 02/14/2020
ms.assetid: b54697cf-3adb-e911-a812-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: xiaoyad
dynamics365pdf: true
ms.openlocfilehash: c17e88c2230b029c1bea5520ef10a824593a1056
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079799"
---
# <a name="agent-productivity-enhancements-to-knowledge-capabilities"></a><span data-ttu-id="3d94e-103">ナレッジ機能に対するエージェントの生産性強化</span><span class="sxs-lookup"><span data-stu-id="3d94e-103">Agent productivity enhancements to knowledge capabilities</span></span>
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| <span data-ttu-id="3d94e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3d94e-104">Enabled for</span></span>    |  <span data-ttu-id="3d94e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3d94e-105">Public preview</span></span> | <span data-ttu-id="3d94e-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="3d94e-106">Early access</span></span> | <span data-ttu-id="3d94e-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="3d94e-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="3d94e-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="3d94e-108">End users, automatically</span></span>|-|<span data-ttu-id="3d94e-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3d94e-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3d94e-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="3d94e-110">Feb 3, 2020</span></span>| <span data-ttu-id="3d94e-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="3d94e-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3d94e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3d94e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3d94e-113">ナレッジ記事をすばやく見つけて共有する機能は、顧客が質問や問題を解決することを支援するためにエージェントが使用できる重要な資産です。</span><span class="sxs-lookup"><span data-stu-id="3d94e-113">The ability to quickly find and share knowledge articles is a key asset that agents can use to help customers resolve questions and issues.</span></span> <span data-ttu-id="3d94e-114">一般的な問題に対処するナレッジ記事を顧客に紹介することにより、エージェントは効率を向上させ、より複雑な問題や独自の問題の解決に集中できます。</span><span class="sxs-lookup"><span data-stu-id="3d94e-114">By referring customers to knowledge articles that address common issues, agents can improve their efficiency and focus on resolving more complex or unique issues.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3d94e-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3d94e-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3d94e-116">このリリースでは、エージェントが次のことを実行できるように、エージェントによるナレッジ記事のアクセスと使いやすさが向上しました。</span><span class="sxs-lookup"><span data-stu-id="3d94e-116">In this release, we're enhancing agent access to and usability of knowledge articles so that agents can:</span></span>

- <span data-ttu-id="3d94e-117">ナレッジ検索結果の改善されたレイアウトを使用して、スキャン、読み取り、アクションを簡素化できます。</span><span class="sxs-lookup"><span data-stu-id="3d94e-117">Use an improved layout of knowledge search results to simplify scanning, reading, and action.</span></span>
- <span data-ttu-id="3d94e-118">別の全画面でナレッジ記事を確認できます。</span><span class="sxs-lookup"><span data-stu-id="3d94e-118">Review knowledge articles in a separate, full screen.</span></span>
- <span data-ttu-id="3d94e-119">顧客事例のコンテキスト外でサポート情報を検索できます。</span><span class="sxs-lookup"><span data-stu-id="3d94e-119">Search the knowledge base outside the context of a customer case.</span></span> <span data-ttu-id="3d94e-120">(ナレッジ検索は、いつでもアクセスできるように顧客サービス ハブ アプリのナビゲーションで利用できるようになりました。)</span><span class="sxs-lookup"><span data-stu-id="3d94e-120">(Knowledge search is now available in the Customer Service Hub app navigation for anytime access.)</span></span>
- <span data-ttu-id="3d94e-121">より幅広いフォントを選択可能で、Word や Excel などの Office ドキュメントから書式設定されたコンテンツを書式設定を維持したままカット アンド ペーストできる最新のツールバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="3d94e-121">Use a modern toolbar with more font choices and the ability to cut and paste formatted content from Office documents such as Word and Excel while maintaining formatting.</span></span> <span data-ttu-id="3d94e-122">テーブルをすばやく作成して行と列の追加や削除を実行できる、強化されたインラインテーブル機能も使用できます。</span><span class="sxs-lookup"><span data-stu-id="3d94e-122">Meanwhile, use the enhanced inline table capabilities that allow quick tables and adding or deleting rows and columns.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="3d94e-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="3d94e-123">See also</span></span>

<span data-ttu-id="3d94e-124">[サポート情報検索コントロール](https://docs.microsoft.com/dynamics365/customer-service/search-knowledge-articles-csh#knowledge-base-search-control) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3d94e-124">[Knowledge Base Search control](https://docs.microsoft.com/dynamics365/customer-service/search-knowledge-articles-csh#knowledge-base-search-control) (docs)</span></span>

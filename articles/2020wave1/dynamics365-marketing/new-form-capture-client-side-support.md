---
title: 新しいフォームの取得とクライアント側サポート
description: サード パーティ Web サイトからのフォームの取得が、Dynamics 365 Marketing で一般提供されます。
author: relnotes
ms.reviewer: alfergus
ms.date: 05/13/2020
ms.assetid: d3b79bae-f579-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: defnea
dynamics365pdf: true
ms.openlocfilehash: c9ee46c545149146d9f15c778693241d482e18eb
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3380905"
---
# <a name="new-form-capture-and-client-side-support"></a><span data-ttu-id="f431d-103">新しいフォームの取得とクライアント側サポート</span><span class="sxs-lookup"><span data-stu-id="f431d-103">New form capture and client-side support</span></span>


| <span data-ttu-id="f431d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f431d-104">Enabled for</span></span>    |  <span data-ttu-id="f431d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f431d-105">Public preview</span></span> | <span data-ttu-id="f431d-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="f431d-106">Early access</span></span> | <span data-ttu-id="f431d-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="f431d-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="f431d-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f431d-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="f431d-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f431d-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f431d-110">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f431d-110">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f431d-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f431d-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f431d-112">直感的なフォームの取得ウィザードにより、サード パーティ Web サイトからの送信フォームの取得が簡単になり、マーケティング担当者の時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="f431d-112">An intuitive form capture wizard saves marketers time by enabling straightforward submission form capture from third-party websites.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f431d-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f431d-113">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="f431d-114">**新しいフォームの取得ウィザード**: JavaScript コードをサード パーティ Web サイトに配置する最初の手順と、フォーム取得の残りのエクスペリエンスが組み合わされています。</span><span class="sxs-lookup"><span data-stu-id="f431d-114">**New form capture wizard**: Combines the initial step of placing a JavaScript code into your third-party website with the rest of the form capture experience.</span></span> <span data-ttu-id="f431d-115">このウィザードのガイドに従うことで、ページの検出、以前のトラッキング スクリプトの確認、スクリプトの追加、ページ上の既存のフォームの検索、フォーム フィールドのマッピングなどの各手順を実行できます。</span><span class="sxs-lookup"><span data-stu-id="f431d-115">The wizard guides you through each step, including detecting the page, checking for previous tracking scripts, adding a script, finding existing forms on the page, and mapping the form fields.</span></span>
- <span data-ttu-id="f431d-116">**UX の改善**: ボタン コントロールとアクセシビリティが改善された、直感的でモダンなデザイン。</span><span class="sxs-lookup"><span data-stu-id="f431d-116">**UX improvements**: Intuitive, modern design with improved button control and accessibility.</span></span> 
- <span data-ttu-id="f431d-117">**クライアント側フォーム サポート**: スクリプトによって動的に挿入されるフォームをサポートすることにより、フォームの取得エクスペリエンスを強化します。</span><span class="sxs-lookup"><span data-stu-id="f431d-117">**Client-side form support**: Enhances the form capture experience by supporting forms that are injected dynamically by scripts.</span></span> <span data-ttu-id="f431d-118">フォームの取得の改善は、クライアント側のスクリプト機能によって拡張されます。</span><span class="sxs-lookup"><span data-stu-id="f431d-118">Form capture improvements are extended with the capability of client-side scripting.</span></span>
- <span data-ttu-id="f431d-119">**新しいフォームとページ テンプレート**: 新しい、モダンなフォームとページ テンプレートのデザイン。</span><span class="sxs-lookup"><span data-stu-id="f431d-119">**New forms and pages templates**: New, modern forms and page template designs.</span></span>
<!--feature detail end -->

<span data-ttu-id="f431d-120">![新しいフォームの取得ウィザードの UX](media/new-form-capture-wizard.jpg "新しいフォームの取得ウィザードの UX")</span><span class="sxs-lookup"><span data-stu-id="f431d-120">![New Form Capture Wizard UX](media/new-form-capture-wizard.jpg "New Form Capture Wizard UX")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="f431d-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="f431d-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="f431d-122">[新規外部フォームの取得](https://docs.microsoft.com/dynamics365/marketing/embed-forms#capture-a-new-external-form) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="f431d-122">[Capture a new external form](https://docs.microsoft.com/dynamics365/marketing/embed-forms#capture-a-new-external-form) (docs)</span></span>
<!--docs end-->

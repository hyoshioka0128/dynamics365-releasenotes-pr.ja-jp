---
title: データへのメモとリンクの追加
description: Business Central のデータに関連するメモとリンク
author: kotelko
ms.reviewer: sgroespe
ms.date: 09/12/2019
ms.assetid: a22f5f6d-957c-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 3756e0eda483b89e600bf7d5608678c6fe30d35b
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140768"
---
# <a name="add-notes-and-links-to-data"></a><span data-ttu-id="e7d4e-103">データへのメモとリンクの追加</span><span class="sxs-lookup"><span data-stu-id="e7d4e-103">Add notes and links to data</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="e7d4e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e7d4e-104">Enabled for</span></span>    |  <span data-ttu-id="e7d4e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e7d4e-105">Public preview</span></span> | <span data-ttu-id="e7d4e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e7d4e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e7d4e-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="e7d4e-107">Users, automatically</span></span>|<span data-ttu-id="e7d4e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e7d4e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e7d4e-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e7d4e-109">Aug 1, 2019</span></span>| <span data-ttu-id="e7d4e-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="e7d4e-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="e7d4e-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e7d4e-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e7d4e-112">最近のビジネス アプリケーションでは、従来よりもさらに構造化されていないデータを表すメモを追加する機能が不可欠です。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-112">An ability to add notes that represent slightly more unstructured data is essential in modern business applications.</span></span> <span data-ttu-id="e7d4e-113">メモとリンクは Business Central のオンプレミス展開で既に使用できるようになっていますが、これらの機能をオンライン環境にもデプロイし、データをクラウドに格納できるように強化しています。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-113">Notes and links are already available for on-premises deployments of Business Central, and now we bring these capabilities to the online world as well, enriching its capabilities to store data in the cloud.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e7d4e-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e7d4e-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e7d4e-115">Business Central オンラインとオンプレミスでキャプチャおよび処理されたビジネス データに内部メモを追加できます。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-115">Users can add internal notes to business data that is captured and processed in Business Central online and on-premises.</span></span> <span data-ttu-id="e7d4e-116">メモは、[情報ボックス] ペイン内のスタイルが刷新されたパネルのデータの横に表示されます。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-116">Notes are shown next to the data in a restyled panel inside the FactBox pane.</span></span>

<span data-ttu-id="e7d4e-117">そこにあるすべての情報ボックスは現在、**詳細** (すべてのビジネス関連の情報ボックスを含む) と**添付ファイル**(メモ、リンク、ドキュメントの添付ファイルを含む) の 2 つのグループに分けられています。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-117">All the FactBoxes there are now divided into two groups: **Details** (which includes all business-related FactBoxes) and **Attachments** (which includes notes, links, and document attachments).</span></span> <span data-ttu-id="e7d4e-118">グループは必要な場合にのみ表示されるため、画面が乱雑になりません。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-118">The groups are shown only when needed so there is no clutter on the screen.</span></span>

<span data-ttu-id="e7d4e-119">![メモを使用する](media/notes.png "メモを使用する")</span><span class="sxs-lookup"><span data-stu-id="e7d4e-119">![Working with notes](media/notes.png "Working with notes")</span></span>

<span data-ttu-id="e7d4e-120">次の特別な機能に注目してください。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-120">Notice the following special capabilities:</span></span>

- <span data-ttu-id="e7d4e-121">Alt + O キーのキーボード ショートカットを使用すると、**メモ**情報ボックスにフォーカスが合っていないときでも、画面上のどこからでもメモを追加できます。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-121">You can add a note using the Alt+O keyboard shortcut from anywhere on the screen, even when the **Notes** FactBox is not in view.</span></span>
- <span data-ttu-id="e7d4e-122">Alt + Shift + F2 キーボード ショートカットを使用すると、情報ボックス ペインのグループ間のフォーカスを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-122">You can switch focus between groups in the FactBox pane with the Alt+Shift+F2 keyboard shortcut.</span></span>
- <span data-ttu-id="e7d4e-123">画面には、メモやリンクを含むすべての添付ファイルを示すカウンターがあります。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-123">There is a counter on the screen showing all attachments, including notes and links.</span></span>
- <span data-ttu-id="e7d4e-124">新しく追加されたノートは常に最初に配置され、フォーカスがそこに保持されます。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-124">A newly added note is always placed first and the focus is preserved there.</span></span>
- <span data-ttu-id="e7d4e-125">メモはより長く、複数の行を入力できるようになり、十分なスペースがある場合は画面上にそのように表示されます。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-125">The notes can be longer and have multiple lines, and they are displayed like that on the screen if there’s enough space.</span></span>

<span data-ttu-id="e7d4e-126">**リンク**部分では、ユーザーはカードやドキュメント ページからオンライン コンテンツへのハイパーリンクを追加できるようになり、各種高度なシナリオにも対応します。</span><span class="sxs-lookup"><span data-stu-id="e7d4e-126">With the **Links** part, users can add hyperlinks to online content from card and document pages, opening up for various advanced scenarios.</span></span>
<!--feature detail end -->












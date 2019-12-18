---
title: データへのメモとリンクの追加
description: Business Central のデータに関連するメモとリンク
author: kotelko
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: a22f5f6d-957c-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: c6f4803a12e0d3b62467e3b6d1df71a9d7d6b230
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892308"
---
# <a name="add-notes-and-links-to-data"></a><span data-ttu-id="783b8-103">データへのメモとリンクの追加</span><span class="sxs-lookup"><span data-stu-id="783b8-103">Add notes and links to data</span></span>


| <span data-ttu-id="783b8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="783b8-104">Enabled for</span></span>    |  <span data-ttu-id="783b8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="783b8-105">Public preview</span></span> | <span data-ttu-id="783b8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="783b8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="783b8-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="783b8-107">End users, automatically</span></span>|<span data-ttu-id="783b8-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="783b8-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="783b8-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="783b8-109">Aug 1, 2019</span></span>| <span data-ttu-id="783b8-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="783b8-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="783b8-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="783b8-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="783b8-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="783b8-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="783b8-113">最近のビジネス アプリケーションでは、従来よりもさらに構造化されていないデータを表すメモを追加する機能が不可欠です。</span><span class="sxs-lookup"><span data-stu-id="783b8-113">An ability to add notes that represent slightly more unstructured data is essential in modern business applications.</span></span> <span data-ttu-id="783b8-114">メモとリンクは Business Central のオンプレミス展開で既に使用できるようになっていますが、これらの機能をオンライン環境にもデプロイし、データをクラウドに格納できるように強化しています。</span><span class="sxs-lookup"><span data-stu-id="783b8-114">Notes and links are already available for on-premises deployments of Business Central, and now we bring these capabilities to the online world as well, enriching its capabilities to store data in the cloud.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="783b8-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="783b8-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="783b8-116">Business Central オンラインとオンプレミスでキャプチャおよび処理されたビジネス データに内部メモを追加できます。</span><span class="sxs-lookup"><span data-stu-id="783b8-116">Users can add internal notes to business data that is captured and processed in Business Central online and on-premises.</span></span> <span data-ttu-id="783b8-117">メモは、[情報ボックス] ペイン内のスタイルが刷新されたパネルのデータの横に表示されます。</span><span class="sxs-lookup"><span data-stu-id="783b8-117">Notes are shown next to the data in a restyled panel inside the FactBox pane.</span></span>

<span data-ttu-id="783b8-118">そこにあるすべての情報ボックスは現在、**詳細** (すべてのビジネス関連の情報ボックスを含む) と**添付ファイル**(メモ、リンク、ドキュメントの添付ファイルを含む) の 2 つのグループに分けられています。</span><span class="sxs-lookup"><span data-stu-id="783b8-118">All the FactBoxes there are now divided into two groups: **Details** (which includes all business-related FactBoxes) and **Attachments** (which includes notes, links, and document attachments).</span></span> <span data-ttu-id="783b8-119">グループは必要な場合にのみ表示されるため、画面が乱雑になりません。</span><span class="sxs-lookup"><span data-stu-id="783b8-119">The groups are shown only when needed so there is no clutter on the screen.</span></span>

<span data-ttu-id="783b8-120">![メモを使用する](media/notes.png "メモを使用する")</span><span class="sxs-lookup"><span data-stu-id="783b8-120">![Working with notes](media/notes.png "Working with notes")</span></span>

<span data-ttu-id="783b8-121">次の特別な機能に注目してください。</span><span class="sxs-lookup"><span data-stu-id="783b8-121">Notice the following special capabilities:</span></span>

- <span data-ttu-id="783b8-122">Alt + O キーのキーボード ショートカットを使用すると、**メモ**情報ボックスにフォーカスが合っていないときでも、画面上のどこからでもメモを追加できます。</span><span class="sxs-lookup"><span data-stu-id="783b8-122">You can add a note using the Alt+O keyboard shortcut from anywhere on the screen, even when the **Notes** FactBox is not in view.</span></span>
- <span data-ttu-id="783b8-123">Alt + Shift + F2 キーボード ショートカットを使用すると、情報ボックス ペインのグループ間のフォーカスを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="783b8-123">You can switch focus between groups in the FactBox pane with the Alt+Shift+F2 keyboard shortcut.</span></span>
- <span data-ttu-id="783b8-124">画面には、メモやリンクを含むすべての添付ファイルを示すカウンターがあります。</span><span class="sxs-lookup"><span data-stu-id="783b8-124">There is a counter on the screen showing all attachments, including notes and links.</span></span>
- <span data-ttu-id="783b8-125">新しく追加されたノートは常に最初に配置され、フォーカスがそこに保持されます。</span><span class="sxs-lookup"><span data-stu-id="783b8-125">A newly added note is always placed first and the focus is preserved there.</span></span>
- <span data-ttu-id="783b8-126">メモはより長く、複数の行を入力できるようになり、十分なスペースがある場合は画面上にそのように表示されます。</span><span class="sxs-lookup"><span data-stu-id="783b8-126">The notes can be longer and have multiple lines, and they are displayed like that on the screen if there’s enough space.</span></span>

<span data-ttu-id="783b8-127">**リンク**部分では、ユーザーはカードやドキュメント ページからオンライン コンテンツへのハイパーリンクを追加できるようになり、各種高度なシナリオにも対応します。</span><span class="sxs-lookup"><span data-stu-id="783b8-127">With the **Links** part, users can add hyperlinks to online content from card and document pages, opening up for various advanced scenarios.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="783b8-128">関連項目</span><span class="sxs-lookup"><span data-stu-id="783b8-128">See also</span></span>

<span data-ttu-id="783b8-129">[カードやドキュメントで添付ファイル、リンク、メモを管理する](https://docs.microsoft.com/dynamics365/business-central/ui-how-add-link-to-record) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="783b8-129">[Manage Attachments, Links, and Notes on Cards and Documents](https://docs.microsoft.com/dynamics365/business-central/ui-how-add-link-to-record) (docs)</span></span>

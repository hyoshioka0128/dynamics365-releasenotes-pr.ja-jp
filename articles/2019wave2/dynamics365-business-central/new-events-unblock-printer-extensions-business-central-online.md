---
title: Business Central オンラインでプリンター拡張機能のブロックを解除する新しいイベント
description: 更新プログラム 15.3 では、2 つの新しいイベントが追加され、開発者が Business Central オンラインの直接印刷シナリオ (SetupPrinters と OnDocumentPrintReady) のブロックを解除できるようになります。
author: relnotes
ms.reviewer: jswymer
ms.date: 01/06/2020
ms.assetid: 021aa213-651b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: f1def5cf4ffc6061857890c7949f5a0b1da22a35
ms.sourcegitcommit: ba5b15c33dc3669937bf5219b1b38995cffb661b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947659"
---
# <a name="new-events-to-unblock-printer-extensions-in-business-central-online"></a><span data-ttu-id="bbac5-103">Business Central オンラインでプリンター拡張機能のブロックを解除する新しいイベント</span><span class="sxs-lookup"><span data-stu-id="bbac5-103">New events to unblock printer extensions in Business Central online</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="bbac5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bbac5-104">Enabled for</span></span>    |  <span data-ttu-id="bbac5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bbac5-105">Public preview</span></span> | <span data-ttu-id="bbac5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bbac5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bbac5-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="bbac5-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="bbac5-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="bbac5-108">Jan 2020</span></span>| <span data-ttu-id="bbac5-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="bbac5-109">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="bbac5-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bbac5-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bbac5-111">開発者は、これらのイベントを使って、クラウド印刷プロバイダーのサポートを実装する拡張機能を作成できます。</span><span class="sxs-lookup"><span data-stu-id="bbac5-111">Using these events, developers can create extensions that implement support for cloud-printing providers.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bbac5-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bbac5-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bbac5-113">開発者は、SetupPrinters を使って、レポート用のプリンター選択ページ (プリンター仮想テーブル内) で使用される可能性のあるプリンターを挿入できます。</span><span class="sxs-lookup"><span data-stu-id="bbac5-113">Using SetupPrinters, a developer can insert possible printers to be used in the printer selection page for reports (in the printer virtual table).</span></span> <span data-ttu-id="bbac5-114">各プリンターには、表示名のほか、両面印刷、部数、カラー、用紙トレイなどのプロパティの仕様を指定できます。</span><span class="sxs-lookup"><span data-stu-id="bbac5-114">Each printer can be given a display name as well as a specification of properties such as duplex, number of copies, color, and paper trays.</span></span> <span data-ttu-id="bbac5-115">用紙トレイでは、[PaperSourceKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.papersourcekind?view=netframework-4.8)、[PaperKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.paperkind?view=netframework-4.8)、横向きなどのプロパティを設定できます。</span><span class="sxs-lookup"><span data-stu-id="bbac5-115">In a paper tray, properties such as [PaperSourceKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.papersourcekind?view=netframework-4.8), [PaperKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.paperkind?view=netframework-4.8), and landscape can be set.</span></span>

<span data-ttu-id="bbac5-116">開発者は、OnDocumentPrintReady を使って、印刷されるレポートに反応し、プリンター仮想テーブルの情報を使ってドキュメントをプリンターに送信できます。</span><span class="sxs-lookup"><span data-stu-id="bbac5-116">Using OnDocumentPrintReady, a developer can react on reports being printed and use information in the printer virtual table to send the document to a printer.</span></span>
<!--feature detail end -->










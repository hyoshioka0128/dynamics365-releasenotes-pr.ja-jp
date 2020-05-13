---
title: Business Central online でプリンター拡張機能のブロックを解除する新しいイベント
description: 更新プログラム 15.3 では、2 つの新しいイベントが追加され、開発者が Business Central online の直接印刷シナリオ (SetupPrinters と OnDocumentPrintReady) のブロックを解除できるようになります。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/02/2020
ms.assetid: 021aa213-651b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 47958926fd2e54aedb89edf2885f0b7e7cb8270a
ms.sourcegitcommit: db53421debc891ea407773d0e9b39feb7a01fef3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "3110943"
---
# <a name="new-events-to-unblock-printer-extensions-in-business-central-online"></a><span data-ttu-id="ec899-103">Business Central online でプリンター拡張機能のブロックを解除する新しいイベント</span><span class="sxs-lookup"><span data-stu-id="ec899-103">New events to unblock printer extensions in Business Central online</span></span>


| <span data-ttu-id="ec899-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ec899-104">Enabled for</span></span>    |  <span data-ttu-id="ec899-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ec899-105">Public preview</span></span> | <span data-ttu-id="ec899-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ec899-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ec899-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ec899-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="ec899-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ec899-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ec899-109">2020 年 2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="ec899-109">Feb 26, 2020</span></span>| <span data-ttu-id="ec899-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ec899-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ec899-111">2020 年 3 月 2 日</span><span class="sxs-lookup"><span data-stu-id="ec899-111">Mar 2, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ec899-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ec899-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ec899-113">開発者は、これらのイベントを使って、クラウド印刷プロバイダーのサポートを実装する拡張機能を作成できます。</span><span class="sxs-lookup"><span data-stu-id="ec899-113">Using these events, developers can create extensions that implement support for cloud-printing providers.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ec899-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ec899-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ec899-115">開発者は、SetupPrinters を使って、レポート用のプリンター選択ページ (プリンター仮想テーブル内) で使用される可能性のあるプリンターを挿入できます。</span><span class="sxs-lookup"><span data-stu-id="ec899-115">Using SetupPrinters, a developer can insert possible printers to be used in the printer selection page for reports (in the printer virtual table).</span></span> <span data-ttu-id="ec899-116">各プリンターには、表示名のほか、両面印刷、部数、カラー、用紙トレイなどのプロパティの仕様を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ec899-116">Each printer can be given a display name as well as a specification of properties such as duplex, number of copies, color, and paper trays.</span></span> <span data-ttu-id="ec899-117">用紙トレイでは、[PaperSourceKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.papersourcekind?view=netframework-4.8)、[PaperKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.paperkind?view=netframework-4.8)、横向きなどのプロパティを設定できます。</span><span class="sxs-lookup"><span data-stu-id="ec899-117">In a paper tray, properties, such as [PaperSourceKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.papersourcekind?view=netframework-4.8), [PaperKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.paperkind?view=netframework-4.8), and landscape can be set.</span></span>

<span data-ttu-id="ec899-118">開発者は、OnDocumentPrintReady を使って、印刷されるレポートに反応し、プリンター仮想テーブルの情報を使ってドキュメントをプリンターに送信できます。</span><span class="sxs-lookup"><span data-stu-id="ec899-118">Using OnDocumentPrintReady, a developer can react on reports being printed and use information in the printer virtual table to send the document to a printer.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ec899-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="ec899-119">See also</span></span>

<span data-ttu-id="ec899-120">[Business Central でのプリンター拡張機能の開発](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reports-printing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ec899-120">[Developing Printer Extentions in Business Central](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reports-printing) (docs)</span></span>

---
title: 埋め込みビューアー コントロールを使用してドキュメントをプレビューする
description: 埋め込みビューアーを使用してビジネス ドキュメントをプレビューします
author: relnotes
ms.reviewer: sericks
ms.date: 10/04/2019
ms.assetid: 8dd380ac-206d-e911-a95f-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: c7815c65c69b3c9b3c2455adc5074e14ecd2a9e6
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668183"
---
# <a name="preview-documents-using-embedded-viewer-control"></a><span data-ttu-id="6f483-103">埋め込みビューアー コントロールを使用してドキュメントをプレビューする</span><span class="sxs-lookup"><span data-stu-id="6f483-103">Preview documents using embedded viewer control</span></span>


| <span data-ttu-id="6f483-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6f483-104">Enabled for</span></span>    |  <span data-ttu-id="6f483-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6f483-105">Public preview</span></span> | <span data-ttu-id="6f483-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6f483-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6f483-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="6f483-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6f483-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6f483-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6f483-109">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="6f483-109">Jul 5, 2019</span></span>| <span data-ttu-id="6f483-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6f483-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6f483-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6f483-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="6f483-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6f483-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6f483-113">高度なドキュメント操作オプションを使用して、顧客のレポート表示エクスペリエンスを向上させます。</span><span class="sxs-lookup"><span data-stu-id="6f483-113">Enhance the report viewing experience for customers with advanced document interaction options.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6f483-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6f483-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6f483-115">新しいホストされたドキュメントの**プレビュー** オプションを利用して、アプリケーション レポートを表示する際の顧客のエクスペリエンスを効率化します。</span><span class="sxs-lookup"><span data-stu-id="6f483-115">Streamline the customer experience when viewing application reports by taking advantage of the new hosted document **Preview** option.</span></span>  <span data-ttu-id="6f483-116">この埋め込みビューアー オプションにより、顧客はローカルに接続されたプリンターに直接アクセスでき、画面表示と印刷出力の間の一貫性が実現します。</span><span class="sxs-lookup"><span data-stu-id="6f483-116">The embedded viewer options give customers direct access to locally connected printers and offers consistency between the screen presentation and the printed output.</span></span> <span data-ttu-id="6f483-117">さらに、従来のソリューションと比べてレポートの表示時間が大幅に短縮されます。</span><span class="sxs-lookup"><span data-stu-id="6f483-117">In addition, report viewing times are drastically reduced when compared to legacy solutions.</span></span>

<span data-ttu-id="6f483-118">新しい**プレビュー** オプションはサポートされているすべてのデバイスで利用でき、ユーザーのデバイスにサード パーティのソフトウェアをローカルにインストールする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="6f483-118">The new **Preview** option is available on all supported devices and does not require any locally installed third-party software on the user's device.</span></span> <span data-ttu-id="6f483-119">埋め込みビューアーのツール バー オプションを使用して、ドキュメントをダウンロードし、すばやく操作することができます。</span><span class="sxs-lookup"><span data-stu-id="6f483-119">Documents can be downloaded and quickly navigated using the built-in viewer toolbar options.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6f483-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="6f483-120">See also</span></span>

<span data-ttu-id="6f483-121">[埋め込みビューアーを使用して PDF ドキュメントをプレビューする](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/preview-pdf-documents) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6f483-121">[Preview PDF documents with an embedded viewer](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/preview-pdf-documents) (docs)</span></span>

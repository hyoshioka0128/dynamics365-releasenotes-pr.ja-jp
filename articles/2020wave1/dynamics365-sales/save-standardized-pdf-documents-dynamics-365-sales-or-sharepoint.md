---
title: Dynamics 365 Sales や Microsoft SharePoint に標準化された PDF ドキュメントを保存する
description: 標準化された PDF ドキュメントを、Notes の添付ファイルとして Dynamics 365 Sales に保存するか、または Microsoft SharePoint に保存します。
author: relnotes
ms.reviewer: shujoshi
ms.date: 04/22/2020
ms.assetid: 53991d2d-22db-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: bharavar
dynamics365pdf: true
ms.openlocfilehash: 97a1a84f90419193f835739c87dc4a5b64e14320
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293249"
---
# <a name="save-standardized-pdf-documents-to-dynamics-365-sales-or-microsoft-sharepoint"></a><span data-ttu-id="bda42-103">Dynamics 365 Sales や Microsoft SharePoint に標準化された PDF ドキュメントを保存する</span><span class="sxs-lookup"><span data-stu-id="bda42-103">Save standardized PDF documents to Dynamics 365 Sales or Microsoft SharePoint</span></span>


| <span data-ttu-id="bda42-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bda42-104">Enabled for</span></span>    |  <span data-ttu-id="bda42-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bda42-105">Public preview</span></span> | <span data-ttu-id="bda42-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="bda42-106">Early access</span></span> | <span data-ttu-id="bda42-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="bda42-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="bda42-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="bda42-108">End users, automatically</span></span>|-|<span data-ttu-id="bda42-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bda42-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bda42-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="bda42-110">Feb 3, 2020</span></span>| <span data-ttu-id="bda42-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bda42-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bda42-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bda42-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="bda42-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bda42-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bda42-114">Dynamics 365 Sales では、過去数か月の作業で、販売担当者が見積やその他のエンティティ レコードに基づいて、標準 PDF ドキュメントを簡単に作成し、メール送信できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="bda42-114">Over the last few months, Dynamics 365 Sales made it easier for sellers to create and email standard PDF documents based on quotes and other entity records.</span></span> <span data-ttu-id="bda42-115">こうした PDF で生成されたドキュメントでの共同作業をさらに容易にするために、Notes の添付ファイルとして Dynamics 365 Sales に直接、または Microsoft SharePoint に PDF を保存する機能が導入されています。</span><span class="sxs-lookup"><span data-stu-id="bda42-115">To make it even easier to collaborate on these PDF-generated documents, we are introducing the ability to save the PDF directly in Dynamics 365 Sales as a Notes attachment or in Microsoft SharePoint.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bda42-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bda42-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bda42-117">この機能強化により、営業担当者は次のことができるようになります。</span><span class="sxs-lookup"><span data-stu-id="bda42-117">With this enhancement, salespeople will be able to:</span></span>

-  <span data-ttu-id="bda42-118">Word テンプレートから作成された標準化された PDF 文書を、Notes の添付ファイルとしてより迅速に保存する。</span><span class="sxs-lookup"><span data-stu-id="bda42-118">More quickly save standardized PDF documents created from Word templates as attachments in Notes.</span></span>
-  <span data-ttu-id="bda42-119">Word テンプレートに基づいて標準化された PDF ドキュメントを SharePoint に保存する。</span><span class="sxs-lookup"><span data-stu-id="bda42-119">Save standardized PDF documents based on Word templates in SharePoint.</span></span>
<!--feature detail end -->

<span data-ttu-id="bda42-120">![PDF を Dynamics 365 Sales または Microsoft SharePoint に保存するダイアログ ボックス](media/save-sharepoint-1.png "PDF を Dynamics 365 Sales または Microsoft SharePoint に保存するダイアログ ボックス")</span><span class="sxs-lookup"><span data-stu-id="bda42-120">![Dialog box to save the PDF to Dynamics 365 Sales or Microsoft SharePoint](media/save-sharepoint-1.png "Dialog box to save the PDF to Dynamics 365 Sales or Microsoft SharePoint")</span></span>
<!-- Picture 1 -->
<span data-ttu-id="bda42-121">![メモに追加された PDF ドキュメント](media/save-sharepoint-2.png "メモに追加された PDF ドキュメント")</span><span class="sxs-lookup"><span data-stu-id="bda42-121">![PDF document added to Notes](media/save-sharepoint-2.png "PDF document added to Notes")</span></span>
<!-- Picture 2 -->
<span data-ttu-id="bda42-122">![SharePoint サイトに追加された PDF ドキュメント](media/save-sharepoint-3.png "SharePoint サイトに追加された PDF ドキュメント")</span><span class="sxs-lookup"><span data-stu-id="bda42-122">![PDF documents added to the SharePoint site](media/save-sharepoint-3.png "PDF documents added to the SharePoint site")</span></span>
<!-- Picture 3 -->

> [!NOTE]
> <span data-ttu-id="bda42-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="bda42-123">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="bda42-124">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="bda42-124">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="bda42-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="bda42-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="bda42-126">[営業レコードから PDF ドキュメントを作成する](https://docs.microsoft.com/dynamics365/sales-enterprise/create-quote-pdf) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="bda42-126">[Create PDF documents from sales records](https://docs.microsoft.com/dynamics365/sales-enterprise/create-quote-pdf) (docs)</span></span>
<!--docs end-->

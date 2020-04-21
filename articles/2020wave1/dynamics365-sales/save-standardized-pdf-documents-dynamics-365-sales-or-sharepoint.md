---
title: Dynamics 365 Sales や Microsoft SharePoint に標準化された PDF ドキュメントを保存する
description: ''
author: relnotes
ms.reviewer: shujoshi
ms.date: 02/03/2020
ms.assetid: 53991d2d-22db-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: bharavar
dynamics365pdf: true
ms.openlocfilehash: 8d86ece803692e1ec43f042206a57438a4031c7d
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232354"
---
# <a name="save-standardized-pdf-documents-to-dynamics-365-sales-or-microsoft-sharepoint"></a><span data-ttu-id="2142a-102">Dynamics 365 Sales や Microsoft SharePoint に標準化された PDF ドキュメントを保存する</span><span class="sxs-lookup"><span data-stu-id="2142a-102">Save standardized PDF documents to Dynamics 365 Sales or Microsoft SharePoint</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="2142a-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="2142a-103">Enabled for</span></span>    |  <span data-ttu-id="2142a-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2142a-104">Public preview</span></span> | <span data-ttu-id="2142a-105">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="2142a-105">Early access</span></span> | <span data-ttu-id="2142a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2142a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="2142a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="2142a-107">End users, automatically</span></span>|-|<span data-ttu-id="2142a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2142a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2142a-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="2142a-109">Feb 3, 2020</span></span>| <span data-ttu-id="2142a-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="2142a-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="2142a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2142a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2142a-112">Dynamics 365 Sales では、過去数か月の作業で、販売担当者が見積やその他のエンティティ レコードに基づいて、標準 PDF ドキュメントを簡単に作成し、メール送信できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2142a-112">Over the last few months, Dynamics 365 Sales made it easier for sellers to create and email standard PDF documents based on quotes and other entity records.</span></span> <span data-ttu-id="2142a-113">こうした PDF で生成されたドキュメントでの共同作業をさらに容易にするために、Notes の添付ファイルとして Dynamics 365 Sales に直接、または Microsoft SharePoint に PDF を保存する機能が導入されています。</span><span class="sxs-lookup"><span data-stu-id="2142a-113">To make it even easier to collaborate on these PDF-generated documents, we are introducing the ability to save the PDF directly in Dynamics 365 Sales as a Notes attachment or in Microsoft SharePoint.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2142a-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2142a-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2142a-115">この機能強化により、営業担当者は次のことができるようになります。</span><span class="sxs-lookup"><span data-stu-id="2142a-115">With this enhancement, salespeople will be able to:</span></span>

-  <span data-ttu-id="2142a-116">Word テンプレートから作成された標準化された PDF 文書を、Notes の添付ファイルとしてより迅速に保存する。</span><span class="sxs-lookup"><span data-stu-id="2142a-116">More quickly save standardized PDF documents created from Word templates as attachments in Notes.</span></span>
-  <span data-ttu-id="2142a-117">Word テンプレートに基づいて標準化された PDF ドキュメントを SharePoint に保存する。</span><span class="sxs-lookup"><span data-stu-id="2142a-117">Save standardized PDF documents based on Word templates in SharePoint.</span></span>
<!--feature detail end -->

<span data-ttu-id="2142a-118">![PDF を Dynamics 365 Sales または Microsoft SharePoint に保存するダイアログ ボックス](media/save-sharepoint-1.png "PDF を Dynamics 365 Sales または Microsoft SharePoint に保存するダイアログ ボックス")</span><span class="sxs-lookup"><span data-stu-id="2142a-118">![Dialog box to save the PDF to Dynamics 365 Sales or Microsoft SharePoint](media/save-sharepoint-1.png "Dialog box to save the PDF to Dynamics 365 Sales or Microsoft SharePoint")</span></span>
<!-- Picture 1 -->

<span data-ttu-id="2142a-119">![メモに追加された PDF ドキュメント](media/save-sharepoint-2.png "メモに追加された PDF ドキュメント")</span><span class="sxs-lookup"><span data-stu-id="2142a-119">![PDF document added to Notes](media/save-sharepoint-2.png "PDF document added to Notes")</span></span>
<!-- Picture 2 -->

<span data-ttu-id="2142a-120">![SharePoint サイトに追加された PDF ドキュメント](media/save-sharepoint-3.png "SharePoint サイトに追加された PDF ドキュメント")</span><span class="sxs-lookup"><span data-stu-id="2142a-120">![PDF documents added to the SharePoint site](media/save-sharepoint-3.png "PDF documents added to the SharePoint site")</span></span>
<!-- Picture 3 -->

> [!NOTE]
> <span data-ttu-id="2142a-121">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="2142a-121">This feature is available in the Unified Interface only.</span></span> 
>
> <span data-ttu-id="2142a-122">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="2142a-122">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="2142a-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="2142a-123">See also</span></span>


<!--docs start-->
<span data-ttu-id="2142a-124">[営業レコードから PDF ドキュメントを作成する](https://docs.microsoft.com/dynamics365/sales-enterprise/create-quote-pdf) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2142a-124">[Create PDF documents from sales records](https://docs.microsoft.com/dynamics365/sales-enterprise/create-quote-pdf) (docs)</span></span>
<!--docs end-->


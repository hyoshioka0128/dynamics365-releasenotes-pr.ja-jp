---
title: Dynamics 365 Sales や Microsoft SharePoint に標準化された PDF ドキュメントを保存する
description: ''
author: relnotes
ms.reviewer: shujoshi
ms.date: 01/09/2020
ms.assetid: 53991d2d-22db-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: bharavar
dynamics365pdf: true
ms.openlocfilehash: 29f5759a80a53d59994196d81022073c94cef6da
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986731"
---
# <a name="save-standardized-pdf-documents-to-dynamics-365-sales-or-microsoft-sharepoint"></a><span data-ttu-id="ea21e-102">Dynamics 365 Sales や Microsoft SharePoint に標準化された PDF ドキュメントを保存する</span><span class="sxs-lookup"><span data-stu-id="ea21e-102">Save standardized PDF documents to Dynamics 365 Sales or Microsoft SharePoint</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="ea21e-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="ea21e-103">Enabled for</span></span>    |  <span data-ttu-id="ea21e-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ea21e-104">Public preview</span></span> | <span data-ttu-id="ea21e-105">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="ea21e-105">Early access</span></span> | <span data-ttu-id="ea21e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ea21e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="ea21e-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ea21e-107">End users, automatically</span></span>|-|<span data-ttu-id="ea21e-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="ea21e-108">Feb 2020</span></span>| <span data-ttu-id="ea21e-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="ea21e-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ea21e-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ea21e-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ea21e-111">Dynamics 365 Sales では、過去数か月の作業で、販売担当者が見積やその他のエンティティ レコードに基づいて、標準 PDF ドキュメントを簡単に作成し、メール送信できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ea21e-111">Over the last few months, Dynamics 365 Sales made it easier for sellers to create and email standard PDF documents based on quotes and other entity records.</span></span> <span data-ttu-id="ea21e-112">こうした PDF で生成されたドキュメントでの共同作業をさらに容易にするために、Notes の添付ファイルとして Dynamics 365 Sales に直接、または Microsoft SharePoint に PDF を保存する機能が導入されています。</span><span class="sxs-lookup"><span data-stu-id="ea21e-112">To make it even easier to collaborate on these PDF-generated documents, we are introducing the ability to save the PDF directly in Dynamics 365 Sales as a Notes attachment or in Microsoft SharePoint.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ea21e-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ea21e-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ea21e-114">この機能強化により、営業担当者は次のことができるようになります。</span><span class="sxs-lookup"><span data-stu-id="ea21e-114">With this enhancement, sales people will be able to:</span></span>

-  <span data-ttu-id="ea21e-115">Word テンプレートから作成された標準化された PDF 文書を、Notes の添付ファイルとしてより迅速に保存する。</span><span class="sxs-lookup"><span data-stu-id="ea21e-115">More quickly save standardized PDF documents created from Word templates as attachments in Notes.</span></span>
-  <span data-ttu-id="ea21e-116">Word テンプレートに基づいて標準化された PDF ドキュメントを SharePoint に保存する。</span><span class="sxs-lookup"><span data-stu-id="ea21e-116">Save standardized PDF documents based on Word templates in SharePoint.</span></span>
<!--feature detail end -->

<span data-ttu-id="ea21e-117">![PDF を Dynamics 365 Sales または Microsoft SharePoint に保存するダイアログ ボックス](media/save-sharepoint-1.png "PDF を Dynamics 365 Sales または Microsoft SharePoint に保存するダイアログ ボックス。")</span><span class="sxs-lookup"><span data-stu-id="ea21e-117">![Dialog box to save the PDF to Dynamics 365 Sales or Microsoft SharePoint](media/save-sharepoint-1.png "Dialog box to save the PDF to Dynamics 365 Sales or Microsoft SharePoint.")</span></span>
<!-- Picture 1 -->

<span data-ttu-id="ea21e-118">![メモに追加された PDF ドキュメント](media/save-sharepoint-2.png "メモに追加された PDF ドキュメント。")</span><span class="sxs-lookup"><span data-stu-id="ea21e-118">![PDF document added to Notes](media/save-sharepoint-2.png "PDF document added to Notes.")</span></span>
<!-- Picture 2 -->

<span data-ttu-id="ea21e-119">![SharePoint サイトに追加された PDF ドキュメント](media/save-sharepoint-3.png "SharePoint サイトに追加された PDF ドキュメント。")</span><span class="sxs-lookup"><span data-stu-id="ea21e-119">![PDF documents added to the SharePoint site](media/save-sharepoint-3.png "PDF documents added to the SharePoint site.")</span></span>
<!-- Picture 3 -->

> [!NOTE]
> <span data-ttu-id="ea21e-120">この機能は、従来の Web クライアントと統一インターフェイスの両方で使用できます。</span><span class="sxs-lookup"><span data-stu-id="ea21e-120">This feature is available in both the legacy web client and Unified Interface.</span></span><br>
> <span data-ttu-id="ea21e-121">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="ea21e-121">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







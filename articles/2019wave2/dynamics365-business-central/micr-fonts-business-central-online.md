---
title: Business Central online で利用可能な MICR フォント
description: すぐに使用できる Business Central には、MICR (磁気インク文字認識) フォントがインストールされています。 これらのフォントは、お客様が小切手を印刷する必要がある場合に、小切手レポートの特殊なレイアウトで使用できます。
author: relnotes
ms.reviewer: sgroespe
ms.date: 02/26/2020
ms.assetid: 2140d3fd-601b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: d52e1f6a2c486a598a7393bd01bac80e191dd78f
ms.sourcegitcommit: db53421debc891ea407773d0e9b39feb7a01fef3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "3110448"
---
# <a name="micr-fonts-available-in-business-central-online"></a><span data-ttu-id="aa55c-104">Business Central online で利用可能な MICR フォント</span><span class="sxs-lookup"><span data-stu-id="aa55c-104">MICR fonts available in Business Central online</span></span>


| <span data-ttu-id="aa55c-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="aa55c-105">Enabled for</span></span>    |  <span data-ttu-id="aa55c-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aa55c-106">Public preview</span></span> | <span data-ttu-id="aa55c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="aa55c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aa55c-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="aa55c-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="aa55c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="aa55c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="aa55c-110">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="aa55c-110">Feb 1, 2020</span></span>| <span data-ttu-id="aa55c-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="aa55c-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="aa55c-112">2020 年 2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="aa55c-112">Feb 26, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="aa55c-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="aa55c-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="aa55c-114">MICR フォントで小切手を印刷する必要がある場合、Business Central online で印刷できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aa55c-114">Customers needing to print checks with MICR fonts can now do so in Business Central online.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="aa55c-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aa55c-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aa55c-116">更新プログラム 15.3 では、MICR (E13-B および CMC-7) 用のフォントと小切手用のセキュリティ フォントが Business Central の運用環境とサンドボックス環境に追加されます。</span><span class="sxs-lookup"><span data-stu-id="aa55c-116">In update 15.3, we will add fonts for MICR (E13-B and CMC-7) and Security fonts for checks to the Business Central production and sandbox environments.</span></span> 

<span data-ttu-id="aa55c-117">これは、MICR およびセキュリティ フォントを使用するカスタム レイアウトが機能することを意味します。</span><span class="sxs-lookup"><span data-stu-id="aa55c-117">This means that any custom layouts using MICR and security fonts will work.</span></span>

<span data-ttu-id="aa55c-118">IDAutomation Inc. が提供するフォント パッケージのライセンスを取得しました。</span><span class="sxs-lookup"><span data-stu-id="aa55c-118">We have licensed the font packages provided by IDAutomation Inc.</span></span> 

<span data-ttu-id="aa55c-119">フォントのテストを開始できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aa55c-119">You can now start testing the fonts.</span></span> <span data-ttu-id="aa55c-120">フォントの種類とサイズについて詳しくは、次のドキュメント ページをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="aa55c-120">See these documentation pages for more information about font types and sizes:</span></span>

- [https://www.idautomation.com/micr-fonts/e13b/](https://www.idautomation.com/micr-fonts/e13b/)  
- [https://www.idautomation.com/micr-fonts/cmc7/](https://www.idautomation.com/micr-fonts/cmc7/)  
- [https://www.idautomation.com/security-fonts/](https://www.idautomation.com/security-fonts/)  

<span data-ttu-id="aa55c-121">テスト目的で、フォントのデモ バージョンを以下からダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="aa55c-121">For testing purposes, you can download demo versions of the fonts here:</span></span>

- [https://www.idautomation.com/micr-fonts/e13b/download.html](https://www.idautomation.com/micr-fonts/e13b/download.html)   
- [https://www.idautomation.com/micr-fonts/cmc7/download.html](https://www.idautomation.com/micr-fonts/cmc7/download.html)  
- [http://downloads.idautomation.com/IDAutomation_SecurityFontsDEMO.zip](http://downloads.idautomation.com/IDAutomation_SecurityFontsDEMO.zip)   
 
<span data-ttu-id="aa55c-122">レポートを設計するには、開発者環境にフォントのデモ バージョンをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="aa55c-122">You will need to install the demo versions of the fonts in your developer environments in order to design reports.</span></span>

- <span data-ttu-id="aa55c-123">Windows 環境の場合、フォントをインストールします。</span><span class="sxs-lookup"><span data-stu-id="aa55c-123">For a Windows environment, install the fonts.</span></span>  
- <span data-ttu-id="aa55c-124">サンドボックス Docker 環境の場合、デモ フォントをローカルにダウンロードしてインストールします。</span><span class="sxs-lookup"><span data-stu-id="aa55c-124">For a sandbox Docker environment, download and install the demo fonts locally.</span></span> <span data-ttu-id="aa55c-125">次に、ブログ投稿「[NavContainerHelper 0.3.1.0 および新しい Docker Generic ビルド 0.0.6.6](https://blogs.msdn.microsoft.com/freddyk/2018/09/03/navcontainerhelper-0-3-1-0-and-a-new-docker-generic-build-0-0-6-6/)」で説明されているように、Add-FontsToNavContainer PowerShell コマンドレットを使ってコンテナーにフォントを追加します。</span><span class="sxs-lookup"><span data-stu-id="aa55c-125">Then use the Add-FontsToNavContainer PowerShell cmdlet to add fonts to the container, as described in the blog post [NavContainerHelper 0.3.1.0 and a new Docker Generic build 0.0.6.6](https://blogs.msdn.microsoft.com/freddyk/2018/09/03/navcontainerhelper-0-3-1-0-and-a-new-docker-generic-build-0-0-6-6/).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="aa55c-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="aa55c-126">See also</span></span>

<span data-ttu-id="aa55c-127">[小切手 (MICR およびセキュリティ) フォント](https://docs.microsoft.com/dynamics365/business-central/ui-fonts) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="aa55c-127">[Check (MICR and Security) Fonts](https://docs.microsoft.com/dynamics365/business-central/ui-fonts) (docs)</span></span>

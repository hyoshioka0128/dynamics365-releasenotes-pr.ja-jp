---
title: BarTender ラベリング システム統合を使用して、Finance and Operations アプリをバックエンド システムに接続する
description: ラベル付けやバーコード処理などのための高度なソリューション。 Finance and Operations アプリでは、ラベルなどの生産を高速化するために設計されたドキュメント レンダリング サービスである BarTender がサポートされるようになりました。 Finance and Operations アプリでは、バーコードと MICR フォントを含むラベル、梱包票、その他のドキュメントのデザインと印刷に関して市場をリードするソリューションがサポートされるようになりました。
author: relnotes
ms.reviewer: kfend
ms.date: 01/14/2020
ms.assetid: b7402c86-b7c9-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 722b2106542c6665d78ddb594ceb95bd4725fd81
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986726"
---
# <a name="connect-your-finance-and-operations-apps-with-back-end-systems-using-bartender-labeling-system-integration"></a><span data-ttu-id="9feb0-105">BarTender ラベリング システム統合を使用して、Finance and Operations アプリをバックエンド システムに接続する</span><span class="sxs-lookup"><span data-stu-id="9feb0-105">Connect your Finance and Operations apps with back-end systems using BarTender labeling system integration</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="9feb0-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="9feb0-106">Enabled for</span></span>    |  <span data-ttu-id="9feb0-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9feb0-107">Public preview</span></span> | <span data-ttu-id="9feb0-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="9feb0-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9feb0-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9feb0-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9feb0-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="9feb0-110">Jun 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="9feb0-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9feb0-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9feb0-112">印刷が遅れると常に、ビジネスの生産性が犠牲になります。</span><span class="sxs-lookup"><span data-stu-id="9feb0-112">Every delay in printing comes at the expense of business productivity.</span></span> <span data-ttu-id="9feb0-113">BarTender サービスを使用すると、お客様は特別な高速の印刷機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="9feb0-113">The BarTender service allows customers to take advantage of special high-speed printing functions.</span></span> <span data-ttu-id="9feb0-114">その結果、従来の SQL Server Reporting Services (SSRS) ベースのソリューションと比較した場合、プリンターへの速度の違いは顕著です。</span><span class="sxs-lookup"><span data-stu-id="9feb0-114">As a result, the difference in speed to printer is significant when compared to legacy SQL Server Reporting Services (SSRS)-based solutions.</span></span> <span data-ttu-id="9feb0-115">Tech、Citizen、Zebra、Domino など、標準ラベル プラットフォーム用のシンプルでプロフェッショナルなデザイン キャンバスを使用して、カスタム フォントを参照します。</span><span class="sxs-lookup"><span data-stu-id="9feb0-115">Reference custom fonts using a simple professional design canvas for standard label platforms: Tech, Citizen, Zebra, Domino, and hundreds more.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9feb0-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9feb0-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9feb0-117">機能強化には、ローカル BarTender サービスへのアクセスに使用される接続情報を管理するための IT 管理ツールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="9feb0-117">Enhancements include IT Admin tools to manage the connection information that is used to access the local Bartender service.</span></span> <span data-ttu-id="9feb0-118">これらの拡張機能では、アプリケーションのビジネス ロジックを使用してラベル生成命令を定義する既存のプリンター デバイスに対する標準的な統合が提供されます。</span><span class="sxs-lookup"><span data-stu-id="9feb0-118">These extensions provide a standard integration for existing printer devices that use application business logic to define label generation instructions.</span></span>  

<span data-ttu-id="9feb0-119">サービスでは、デザインの定義に基づいて、プリンターのネイティブ言語で生成とレンダリングが行われます。</span><span class="sxs-lookup"><span data-stu-id="9feb0-119">The service compiles and renders in the native language of the printer based on the design definition.</span></span> <span data-ttu-id="9feb0-120">たとえば、サービスでは Zebra プリンター用の ZedPL を使用してラベルがレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="9feb0-120">For example, the service will render the label using ZedPL for Zebra printers.</span></span> <span data-ttu-id="9feb0-121">その結果、バーコードのシリアル番号の増分や反復などの命令は、Zebra プリント エンジンによって直接処理されて、最適なパフォーマンスが実現されます。</span><span class="sxs-lookup"><span data-stu-id="9feb0-121">As a result, instructions such as incremental or repeating serial numbers for barcodes will be handled directly by the Zebra print engine to achieve optimal performance.</span></span>
<!--feature detail end -->










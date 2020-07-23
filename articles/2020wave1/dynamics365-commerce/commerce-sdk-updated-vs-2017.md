---
title: Commerce SDK が Visual Studio 2017 に更新
description: Commerce SDK を Visual Studio 2015 から Visual Studio 2017 に移行します。
author: mugunthanm
ms.reviewer: rhaertle
ms.date: 05/08/2020
ms.assetid: b8f8388f-627b-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 48e807c506df9ade1f6a46ddf6a1fa53e329093c
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381937"
---
# <a name="commerce-sdk-updated-to-visual-studio-2017"></a><span data-ttu-id="752ec-103">Commerce SDK が Visual Studio 2017 に更新</span><span class="sxs-lookup"><span data-stu-id="752ec-103">Commerce SDK updated to Visual Studio 2017</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="752ec-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="752ec-104">Enabled for</span></span>    |  <span data-ttu-id="752ec-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="752ec-105">Public preview</span></span> | <span data-ttu-id="752ec-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="752ec-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="752ec-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="752ec-107">End users, automatically</span></span>|<span data-ttu-id="752ec-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="752ec-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="752ec-109">2020 年 4 月 27 日</span><span class="sxs-lookup"><span data-stu-id="752ec-109">Apr 27, 2020</span></span>| <span data-ttu-id="752ec-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="752ec-110">Jun 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="752ec-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="752ec-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="752ec-112">古い Commerce SDK に基づいて構築された拡張機能は、Visual Studio 2017 を使用して新しい SDK に移行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="752ec-112">Extensions built based on the older Commerce SDK need to be migrated to the new SDK using Visual Studio 2017.</span></span> <span data-ttu-id="752ec-113">コードの変更は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="752ec-113">No code change will be required.</span></span> <span data-ttu-id="752ec-114">移行が必要なのは、拡張機能があり、Commerce バージョン 10.0.11 以降の新しいパッケージをデプロイする場合だけです。</span><span class="sxs-lookup"><span data-stu-id="752ec-114">The migration is needed only when you have extensions and want to deploy a new package with Commerce version 10.0.11 or later.</span></span>

<span data-ttu-id="752ec-115">拡張プロジェクトのハード参照はすべて PackageReference に移行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="752ec-115">Any hard reference in the extension project must be migrated to PackageReference.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="752ec-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="752ec-116">See also</span></span>

<!--docs start-->
<span data-ttu-id="752ec-117">[Retail SDK の Visual Studio 2015 から Visual Studio 2017 への移行](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/retail-sdk/migrate-sdk) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="752ec-117">[Migrate the Retail SDK from Visual Studio 2015 to Visual Studio 2017](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/retail-sdk/migrate-sdk) (docs)</span></span>
<!--docs end-->

---
title: Commerce SDK が Visual Studio 2017 に更新
description: Commerce SDK を Visual Studio 2015 から Visual Studio 2017 に移行します。
author: mugunthanm
ms.reviewer: rhaertle
ms.date: 05/04/2020
ms.assetid: b8f8388f-627b-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 8c0c3f8191007cc7b5cac5ca2984fc58c57f78e1
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349591"
---
# <a name="commerce-sdk-updated-to-visual-studio-2017"></a><span data-ttu-id="cb719-103">Commerce SDK が Visual Studio 2017 に更新</span><span class="sxs-lookup"><span data-stu-id="cb719-103">Commerce SDK updated to Visual Studio 2017</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="cb719-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cb719-104">Enabled for</span></span>    |  <span data-ttu-id="cb719-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cb719-105">Public preview</span></span> | <span data-ttu-id="cb719-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cb719-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cb719-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="cb719-107">End users, automatically</span></span>|<span data-ttu-id="cb719-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cb719-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cb719-109">2020 年 4 月 27 日</span><span class="sxs-lookup"><span data-stu-id="cb719-109">Apr 27, 2020</span></span>| <span data-ttu-id="cb719-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="cb719-110">Jun 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="cb719-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cb719-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cb719-112">古い Commerce SDK に基づいて構築された拡張機能は、Visual Studio 2017 を使用して新しい SDK に移行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb719-112">Extensions built based on the older Commerce SDK need to be migrated to the new SDK using Visual Studio 2017.</span></span> <span data-ttu-id="cb719-113">コードの変更は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="cb719-113">No code change will be required.</span></span> <span data-ttu-id="cb719-114">移行が必要なのは、拡張機能があり、Commerce バージョン 10.0.11 以降の新しいパッケージをデプロイする場合だけです。</span><span class="sxs-lookup"><span data-stu-id="cb719-114">The migration is needed only when you have extensions and want to deploy a new package with Commerce version 10.0.11 or later.</span></span>

<span data-ttu-id="cb719-115">拡張プロジェクトのハード参照はすべて PackageReference に移行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cb719-115">Any hard reference in the extension project must be migrated to PackageReference.</span></span>
<!--feature detail end -->










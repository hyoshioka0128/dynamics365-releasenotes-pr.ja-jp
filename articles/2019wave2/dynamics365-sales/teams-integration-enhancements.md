---
title: Microsoft Teams 統合の機能拡張
description: Microsoft Teams の統合によるコラボレーションのメリットに関するフィードバックを顧客やパートナーから取得し、機能の導入をサポートするため、Dynamics 365 では統合エクスペリエンスが強化されています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 06/19/2019
ms.assetid: de61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: cindyliu
dynamics365pdf: true
ms.openlocfilehash: 4d4892ea2452c674b56818a16e18ae3c88c730c5
ms.sourcegitcommit: 0c53eb8711a7594ec968a8d531a78b6ab5b98bf6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/03/2019
ms.locfileid: "1725405"
---
# <a name="microsoft-teams-integration-enhancements"></a><span data-ttu-id="40bb8-103">Microsoft Teams 統合の機能拡張</span><span class="sxs-lookup"><span data-stu-id="40bb8-103">Microsoft Teams integration enhancements</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="40bb8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="40bb8-104">Enabled for</span></span>    |  <span data-ttu-id="40bb8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="40bb8-105">Public preview</span></span> | <span data-ttu-id="40bb8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="40bb8-106">General availability</span></span> | <span data-ttu-id="40bb8-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="40bb8-107">Early Access</span></span> |
| ---------- | ---------- |---------- |---------- |
|<span data-ttu-id="40bb8-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="40bb8-108">End users, automatically</span></span>|| <span data-ttu-id="40bb8-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="40bb8-109">October 2019</span></span>|<span data-ttu-id="40bb8-110">はい</span><span class="sxs-lookup"><span data-stu-id="40bb8-110">Yes</span></span> |


## <a name="business-value"></a><span data-ttu-id="40bb8-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="40bb8-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="40bb8-112">Dynamics 365 と Teams の統合は、2019 年 4 月に導入されました。</span><span class="sxs-lookup"><span data-stu-id="40bb8-112">Dynamics 365 integration with Teams was introduced in April 2019.</span></span> <span data-ttu-id="40bb8-113">この拡張機能では、Dynamics 365 アプリを終了することなく、Dynamics 365 レコードを Teams チャネルに接続できます。</span><span class="sxs-lookup"><span data-stu-id="40bb8-113">Enhancements help to connect Dynamics 365 records to Teams channels without leaving the Dynamics 365 app.</span></span> <span data-ttu-id="40bb8-114">販売担当者は、Dynamics 365 のアクセス権限に基づいて、接続フローの間に、チーム メンバーのレコメンデーションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="40bb8-114">Sellers will receive team member recommendations, during the connection flow, based on Dynamics 365 access privileges.</span></span> <span data-ttu-id="40bb8-115">拡張性をさらに向上させるため、Dynamics 365 と Teams の接続で、既製のエンティティとカスタム エンティティに対してファイル共有を有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="40bb8-115">To further improve the extensibility, file sharing can now be enabled for any out-of-the-box and custom entities, across Dynamics 365 and Teams connections.</span></span> <span data-ttu-id="40bb8-116">接続とは、Dynamics 365 のタブを Teams のチャネルに追加する機能のことです。</span><span class="sxs-lookup"><span data-stu-id="40bb8-116">Connections refer to the ability to add a Dynamics 365 tab to a Teams channel.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="40bb8-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="40bb8-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="40bb8-118">Dynamics 365 のレコードを Teams のチャネルに接続すると、Dynamics 365 レコードに関連付けられているユーザーに基づいて、関連するメンバーが提案されます。</span><span class="sxs-lookup"><span data-stu-id="40bb8-118">When connecting a Dynamics 365 record to a Teams channel, relevant members are suggested based on users associated with the Dynamics 365 record.</span></span> <span data-ttu-id="40bb8-119">チャネルの所有者として指定されている場合、ユーザーはメンバーの提案を使用できます。</span><span class="sxs-lookup"><span data-stu-id="40bb8-119">Member suggestions will be available to a user if designated as a channel owner.</span></span> 
- <span data-ttu-id="40bb8-120">カスタム エンティティ タイプを含むすべてのエンティティ タイプについて、Microsoft Teams の統合機能で SDK サポートを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="40bb8-120">SDK support is now available for the Microsoft Teams integration feature for any entity type, including custom entity types.</span></span> 
- <span data-ttu-id="40bb8-121">Dynamics 365 レコード ページから Teams チャネルを作成するとき、ユーザーは Dynamics 365 レコードを選択したチャネルに自動的に接続できます。</span><span class="sxs-lookup"><span data-stu-id="40bb8-121">When creating a Teams channel from the Dynamics 365 record page, users can automatically connect the Dynamics 365 record to the selected channel.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="40bb8-122">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="40bb8-122">This feature is available in the Unified Interface only.</span></span>








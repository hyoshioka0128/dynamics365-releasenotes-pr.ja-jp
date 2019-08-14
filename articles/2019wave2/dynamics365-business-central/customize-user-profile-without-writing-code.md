---
title: コードを書かずにユーザー プロファイルをカスタマイズする
description: ブラウザーまたは Windows 10 デスクトップ アプリでユーザー プロファイルを追加およびカスタマイズします。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 07/22/2019
ms.assetid: 846c8f04-e86b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: a2798c508fae179962d5077a50360013fc793499
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795804"
---
# <a name="customize-a-user-profile-without-writing-code"></a><span data-ttu-id="9a09f-103">コードを書かずにユーザー プロファイルをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="9a09f-103">Customize a user profile without writing code</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="9a09f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9a09f-104">Enabled for</span></span>    |  <span data-ttu-id="9a09f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9a09f-105">Public preview</span></span> | <span data-ttu-id="9a09f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9a09f-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="9a09f-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="9a09f-107">End users, automatically</span></span>|<span data-ttu-id="9a09f-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="9a09f-108">September 2019</span></span>| <span data-ttu-id="9a09f-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="9a09f-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="9a09f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9a09f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9a09f-111">Business Central は、企業、部門、ユーザーに固有のニーズに簡単に適応できます。</span><span class="sxs-lookup"><span data-stu-id="9a09f-111">Business Central is ready to adapt to the unique needs of the business, departments, and users.</span></span> <span data-ttu-id="9a09f-112">パワー ユーザー、部門の所有者、およびコンサルタントは、自分のユーザーが独自のロールのためにアクセスできるデータやタスクを制御する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9a09f-112">Power users, department owners, and consultants demand control over which data and tasks their users get access to for their unique roles.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9a09f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9a09f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9a09f-114">以前は Dynamics NAV Windows クライアントのプロファイル構成モードと呼ばれていた Business Central のデスクトップ エクスペリエンスでは、同じユーザー プロファイルを共有するユーザー グループに対して軽量の UI カスタマイズが可能です。</span><span class="sxs-lookup"><span data-stu-id="9a09f-114">Formerly known as profile configuration mode in the Dynamics NAV Windows client, the Business Central desktop experience allows lightweight UI customizations for groups of users that share the same user profile.</span></span> <span data-ttu-id="9a09f-115">これは、Visual Studio Code と AL をまったく使用しないで行うことができます。</span><span class="sxs-lookup"><span data-stu-id="9a09f-115">This can be done entirely without the use of Visual Studio Code and AL.</span></span> <span data-ttu-id="9a09f-116">次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9a09f-116">Capabilities include:</span></span>

  - <span data-ttu-id="9a09f-117">Business Central 内からユーザー プロファイルの追加、編集、削除を行います。</span><span class="sxs-lookup"><span data-stu-id="9a09f-117">Add, edit, or remove user profiles from within Business Central.</span></span>  
  - <span data-ttu-id="9a09f-118">プロフィールのより詳細な概要を取得し、それらのうちの 1 つに集中してカスタマイズを始めます。</span><span class="sxs-lookup"><span data-stu-id="9a09f-118">Get a more detailed overview of your profiles and focus on one of them to begin customizing it.</span></span>  
  - <span data-ttu-id="9a09f-119">デザイナーのすべての豊富な機能を活用して、そのプロファイルの軽量の UI カスタマイズを行い、設計の間にカスタマイズをテストします。</span><span class="sxs-lookup"><span data-stu-id="9a09f-119">Leverage all the rich capabilities of the designer to make lightweight UI customization of that profile and test your customization while you design.</span></span>  

<span data-ttu-id="9a09f-120">ユーザー プロファイルのカスタマイズでは、オブジェクトやデータへのアクセスはセキュリティで保護されません。</span><span class="sxs-lookup"><span data-stu-id="9a09f-120">Customization of user profiles does not secure access to objects or data.</span></span> <span data-ttu-id="9a09f-121">管理者は、関連するユーザー グループまたはアクセス許可セットを依然として適用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9a09f-121">Administrators are still required to apply the relevant user groups or permissions sets.</span></span>
<!--feature detail end -->












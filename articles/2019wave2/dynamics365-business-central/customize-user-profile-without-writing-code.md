---
title: コードを書かずにユーザー プロファイルをカスタマイズする
description: ブラウザーまたは Windows 10 デスクトップ アプリでユーザー プロファイルを追加およびカスタマイズします。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 07/01/2019
ms.assetid: 846c8f04-e86b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 44e1f8798571d9c54a39e4ecd80a1e23b057bd1a
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1723003"
---
# <a name="customize-a-user-profile-without-writing-code"></a><span data-ttu-id="96422-103">コードを書かずにユーザー プロファイルをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="96422-103">Customize a user profile without writing code</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="96422-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="96422-104">Enabled for</span></span>    |  <span data-ttu-id="96422-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="96422-105">Public preview</span></span> | <span data-ttu-id="96422-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="96422-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="96422-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="96422-107">End users, automatically</span></span>|<span data-ttu-id="96422-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="96422-108">September 2019</span></span>| <span data-ttu-id="96422-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="96422-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="96422-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="96422-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="96422-111">Business Central は、企業、部門、ユーザーに固有のニーズに簡単に適応できます。</span><span class="sxs-lookup"><span data-stu-id="96422-111">Business Central is ready to adapt to the unique needs of the business, departments, and users.</span></span> <span data-ttu-id="96422-112">パワー ユーザー、部門の所有者、およびコンサルタントは、自分のユーザーが独自のロールのためにアクセスできるデータやタスクを制御する必要があります。</span><span class="sxs-lookup"><span data-stu-id="96422-112">Power users, department owners, and consultants demand control over which data and tasks their users get access to for their unique roles.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="96422-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="96422-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="96422-114">以前は Dynamics NAV Windows クライアントのプロファイル構成モードと呼ばれていた Business Central のデスクトップ エクスペリエンスでは、同じユーザー プロファイルを共有するユーザー グループに対して軽量の UI カスタマイズが可能です。</span><span class="sxs-lookup"><span data-stu-id="96422-114">Formerly known as profile configuration mode in the Dynamics NAV Windows client, the Business Central desktop experience allows lightweight UI customizations for groups of users that share the same user profile.</span></span> <span data-ttu-id="96422-115">これは、Visual Studio Code と AL をまったく使用しないで行うことができます。</span><span class="sxs-lookup"><span data-stu-id="96422-115">This can be done entirely without the use of Visual Studio Code and AL.</span></span> <span data-ttu-id="96422-116">次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="96422-116">Capabilities include:</span></span>

  - <span data-ttu-id="96422-117">Business Central 内からユーザー プロファイルの追加、編集、削除を行います。</span><span class="sxs-lookup"><span data-stu-id="96422-117">Add, edit, or remove user profiles from within Business Central.</span></span>  
  - <span data-ttu-id="96422-118">プロフィールのより詳細な概要を取得し、それらのうちの 1 つに集中してカスタマイズを始めます。</span><span class="sxs-lookup"><span data-stu-id="96422-118">Get a more detailed overview of your profiles and focus on one of them to begin customizing it.</span></span>  
  - <span data-ttu-id="96422-119">デザイナーのすべての豊富な機能を活用して、そのプロファイルの軽量の UI カスタマイズを行い、設計の間にカスタマイズをテストします。</span><span class="sxs-lookup"><span data-stu-id="96422-119">Leverage all the rich capabilities of the designer to make lightweight UI customization of that profile and test your customization while you design.</span></span>  

<span data-ttu-id="96422-120">ユーザー プロファイルのカスタマイズでは、オブジェクトやデータへのアクセスはセキュリティで保護されません。</span><span class="sxs-lookup"><span data-stu-id="96422-120">Customization of user profiles does not secure access to objects or data.</span></span> <span data-ttu-id="96422-121">管理者は、関連するユーザー グループまたはアクセス許可セットを依然として適用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="96422-121">Administrators are still required to apply the relevant user groups or permissions sets.</span></span>
<!--feature detail end -->











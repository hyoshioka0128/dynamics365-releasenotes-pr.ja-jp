---
title: Dynamics GP からすべてまたはアクティブな仕入先マスター レコードを移行する
description: 現在の Dynamics GP クラウド移行ツールにサポートを追加して、ユーザーがすべてまたはアクティブな仕入先マスター レコードを移行する必要があるかどうかを指定して追加のアドレスを移行できるようにします。
author: relnotes
ms.reviewer: edupont
ms.date: 02/10/2020
ms.assetid: f6f2600d-ac16-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: c62f7884e7e04392150e40234a7c255a6459e9b0
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079942"
---
# <a name="migrate-all-or-only-active-vendor-master-records-from-dynamics-gp"></a><span data-ttu-id="a77e4-103">Dynamics GP からすべてまたはアクティブな仕入先マスター レコードを移行する</span><span class="sxs-lookup"><span data-stu-id="a77e4-103">Migrate all or only active vendor master records from Dynamics GP</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="a77e4-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a77e4-104">Enabled for</span></span>    |  <span data-ttu-id="a77e4-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a77e4-105">Public preview</span></span> | <span data-ttu-id="a77e4-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a77e4-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a77e4-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a77e4-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a77e4-108">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="a77e4-108">Mar 2020</span></span>| <span data-ttu-id="a77e4-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="a77e4-109">Apr 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="a77e4-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a77e4-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a77e4-111">ユーザーはこの移行ツールを使用して、すべての仕入先を移行するか、Dynamics GP でアクティブな状態の仕入先のみを移行することができます。</span><span class="sxs-lookup"><span data-stu-id="a77e4-111">The migration tool will allow the user to migrate either all vendors or only vendors who have an active status in Dynamics GP.</span></span> <span data-ttu-id="a77e4-112">この変更に加えて、仕入先のアドレスもすべて移行します。</span><span class="sxs-lookup"><span data-stu-id="a77e4-112">Along with that change, we will also migrate all vendor addresses.</span></span> <span data-ttu-id="a77e4-113">現在は Dynamics GP で仕入先カードに関連付けられたプライマリ アドレスのみを移行します。</span><span class="sxs-lookup"><span data-stu-id="a77e4-113">Currently we only migrate the primary address associated with the vendor card in Dynamics GP.</span></span>
<!--feature detail end -->










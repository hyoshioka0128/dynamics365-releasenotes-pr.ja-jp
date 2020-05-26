---
title: 外部カタログの機能強化
description: 外部カタログの機能強化により、調達組織はログ機能を有効にして、外部カタログのパラメーターの変更が必要になる可能性がある一般的な問題をキャプチャできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 61b663a5-f41d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: lcash
dynamics365pdf: true
ms.openlocfilehash: e8a47b9e9abd30e02c499f814505c069e6f73a3b
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272380"
---
# <a name="external-catalog-enhancements"></a><span data-ttu-id="befcd-103">外部カタログの機能強化</span><span class="sxs-lookup"><span data-stu-id="befcd-103">External catalog enhancements</span></span>


| <span data-ttu-id="befcd-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="befcd-104">Enabled for</span></span>    |  <span data-ttu-id="befcd-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="befcd-105">Public preview</span></span> | <span data-ttu-id="befcd-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="befcd-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="befcd-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="befcd-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="befcd-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="befcd-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="befcd-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="befcd-109">Feb 3, 2020</span></span>| <span data-ttu-id="befcd-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="befcd-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="befcd-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="befcd-111">Apr 3, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="befcd-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="befcd-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="befcd-113">調達組織は、Microsoft Dynamics 365 for Finance and Operations バージョン 7.2 で外部カタログの cXML プロトコルを利用することができました。</span><span class="sxs-lookup"><span data-stu-id="befcd-113">Procurement organizations were able to leverage the external catalogs cXML protocol in Microsoft Dynamics 365 for Finance and Operations version 7.2.</span></span> <span data-ttu-id="befcd-114">仕入先システムが異なるため、外部カタログの設定とテストではトラブルシューティングが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="befcd-114">Due to different vendor systems, setting up and testing external catalogs can involve some troubleshooting.</span></span> <span data-ttu-id="befcd-115">新しいカタログの機能強化により、調達組織はログ機能を有効にして、外部カタログのパラメーターの変更が必要になる可能性がある一般的な問題をキャプチャできます。</span><span class="sxs-lookup"><span data-stu-id="befcd-115">With the new catalog enhancements, the procurement organization can enable the logging feature that captures common issues that might require changes to external catalog parameters.</span></span> 

<!--![External catalog enhancements](media/external-catalog-enhancements-1.png "External catalog enhancements")-->

<span data-ttu-id="befcd-116">出荷バスケットから **SupplierPartIAuxiliary** ID を返して購買要求および関連する発注書でそれをキャプチャできるようにする、新しいサポートが追加されています。</span><span class="sxs-lookup"><span data-stu-id="befcd-116">We're adding additional support to allow the return of the **SupplierPartIAuxiliary** ID from the shipping basket and to capture it on the purchase requisition and the related purchase order.</span></span> <span data-ttu-id="befcd-117">この ID は、品目の固有の構成を表すために一部のサプライヤーによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="befcd-117">This identification is used by some suppliers to represent a unique configuration for an item.</span></span>
<!--feature detail end -->










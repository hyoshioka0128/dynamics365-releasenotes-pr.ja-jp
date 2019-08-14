---
title: 顧客移行ツールの機能強化
description: 顧客移行ツールの新機能により、Dynamics 365 Business Central に移行する顧客に対する移行エクスペリエンスが向上します。
author: relnotes
ms.reviewer: edupont
ms.date: 07/22/2019
ms.assetid: e6e5c71c-9475-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 69c86fbfdc194c95c036f30ccf38f210167dce83
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795771"
---
# <a name="enhancements-for-customer-migration-tools"></a><span data-ttu-id="51023-103">顧客移行ツールの機能強化</span><span class="sxs-lookup"><span data-stu-id="51023-103">Enhancements for customer migration tools</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="51023-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="51023-104">Enabled for</span></span>    |  <span data-ttu-id="51023-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="51023-105">Public preview</span></span> | <span data-ttu-id="51023-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="51023-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="51023-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="51023-107">Admins, makers, or analysts, automatically</span></span>|| <span data-ttu-id="51023-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="51023-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="51023-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="51023-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="51023-110">ISV が Business Central でソリューションをオンラインにした後の次のステップは、Dynamics 365 Business Central オンプレミス、Dynamics NAV 2018、Dynamics GP 2018 R2、Dynamics SL 2018 CU1 を使用している既存の Dynamics SMB の顧客の作業を簡素化することです。</span><span class="sxs-lookup"><span data-stu-id="51023-110">After enabling ISVs to bring their solutions to Business Central online, the next step is to simplify the journey for existing Dynamics SMB customers using Dynamics 365 Business Central on-premises, Dynamics NAV 2018, Dynamics GP 2018 R2, and Dynamics SL 2018 CU1.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="51023-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="51023-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="51023-112">既存のデータ レプリケーション ツールは Azure Data Factory に基づいており、移行を完了するために必要なテーブルを追加するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="51023-112">The existing data replication tooling is based on Azure Data Factory and is updated to add additional tables that are needed for the migration to be complete.</span></span> <span data-ttu-id="51023-113">2019 年リリース ウェーブ 2 の更新プログラムでは、Business Central オンプレミスと Dynamics NAV 2018 の移行ツールが最初に提供され、その後で Dynamics GP と Dynamics SL の機能強化が行われます。</span><span class="sxs-lookup"><span data-stu-id="51023-113">For the 2019 release wave 2 update, migration tooling for Business Central on-premises and Dynamics NAV 2018 comes first, followed later with enhancements for Dynamics GP and Dynamics SL.</span></span> <span data-ttu-id="51023-114">セットアップ プロセスは同じままですが、ブランド変更コンポーネントがあり、より合理化された移行をサポートするためにテーブルが追加されます。</span><span class="sxs-lookup"><span data-stu-id="51023-114">The setup process remains the same, but there will be a rebranding component and additional tables added to support a more streamlined migration.</span></span> <span data-ttu-id="51023-115">移行ツールでは、既定でインストール済み拡張機能からのデータの移行がサポートされるので、Dynamics NAV 2018 または Business Central オンプレミス アプリケーションを拡張機能で拡張している顧客は、追加の作業を行わなくても、それらのデータを Business Central オンラインに持ち込むことができます。</span><span class="sxs-lookup"><span data-stu-id="51023-115">The migration tool also supports migrating data from installed extension by default, so a customer who has extended their Dynamics NAV 2018 or Business Central on-premises application with extensions can bring that data with them to Business Central online without any additional effort.</span></span>

<span data-ttu-id="51023-116">このツールでは現在、ユーザーは Azure Data Factory を使用して SQL Server データベースを Business Central オンラインのテナントに接続し、データを共有することができます。</span><span class="sxs-lookup"><span data-stu-id="51023-116">This tool currently allows a user to use Azure Data Factory to connect their SQL Server database to a Business Central online tenant and bring their data across.</span></span> <span data-ttu-id="51023-117">さらに、2019 年リリース ウェーブ 2 では、移行を完了するために必要な情報のチェックリストが追加されます。</span><span class="sxs-lookup"><span data-stu-id="51023-117">In addition, the 2019 release wave 2 adds a checklist for information needed to complete the migration.</span></span>
<!--feature detail end -->












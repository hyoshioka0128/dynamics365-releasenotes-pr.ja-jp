---
title: 顧客移行ツールの機能強化
description: 顧客移行ツールの新機能により、Dynamics 365 Business Central に移行する顧客に対する移行エクスペリエンスが向上します。
author: relnotes
ms.reviewer: edupont
ms.date: 10/17/2019
ms.assetid: e6e5c71c-9475-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 0d5639ee37411aa948c627d223e1b730cd901a65
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667072"
---
# <a name="enhancements-for-customer-migration-tools"></a><span data-ttu-id="4f8bc-103">顧客移行ツールの機能強化</span><span class="sxs-lookup"><span data-stu-id="4f8bc-103">Enhancements for customer migration tools</span></span>


| <span data-ttu-id="4f8bc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4f8bc-104">Enabled for</span></span>    |  <span data-ttu-id="4f8bc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4f8bc-105">Public preview</span></span> | <span data-ttu-id="4f8bc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4f8bc-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4f8bc-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="4f8bc-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="4f8bc-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4f8bc-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4f8bc-109">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="4f8bc-109">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="4f8bc-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4f8bc-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4f8bc-111">ISV が自社ソリューションを Business Central オンラインに取り込めるようにした後の次のステップは、Dynamics 365 Business Central オンプレミス、Dynamics GP 2018 R2、Dynamics SL 2018 CU1 を使用している既存の Dynamics SMB の顧客の作業を簡素化することです。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-111">After enabling ISVs to bring their solutions to Business Central online, the next step is to simplify the journey for existing Dynamics SMB customers using Dynamics 365 Business Central on-premises, Dynamics GP 2018 R2, and Dynamics SL 2018 CU1.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4f8bc-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4f8bc-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4f8bc-113">2019 年リリース ウェーブ 2 の更新プログラムでは、Business Central オンプレミスの移行ツールが最初に提供され、その後で Dynamics GP と Dynamics SL の機能強化が行われます。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-113">For the 2019 release wave 2 update, migration tooling for Business Central on-premises comes first, followed later with enhancements for Dynamics GP and Dynamics SL.</span></span> <span data-ttu-id="4f8bc-114">既存のデータ複製ツールは、Azure Data Factory をベースとしています。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-114">The existing data replication tooling is based on Azure Data Factory.</span></span> <span data-ttu-id="4f8bc-115">この更新プログラムにより、移行を完了するために必要なテーブルが追加されます。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-115">This update adds additional tables that are needed for the migration to be complete.</span></span> <span data-ttu-id="4f8bc-116">セットアップ プロセスは同じままですが、商標が変更されるコンポーネントがあり、より合理化された移行をサポートするためにテーブルが追加されます。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-116">The setup process remains the same, but there will be a rebranding component and additional tables added to support a more streamlined migration.</span></span> <span data-ttu-id="4f8bc-117">移行ツールでは、既定でインストール済み拡張機能からのデータの移行に対応するため、Business Central オンプレミス アプリケーションを拡張機能でカスタマイズしている顧客は、追加の作業を行わなくても、それらのデータを Business Central オンラインに持ち込むことができます。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-117">The migration tool also supports migrating data from installed extensions by default, so a customer who has customized their Business Central on-premises application with extensions can bring that data with them to Business Central online without any additional effort.</span></span>

<span data-ttu-id="4f8bc-118">この更新プログラムにより、管理者は Azure Data Factory を使用して SQL Server データベースを Business Central オンラインのテナントに接続し、データを共有することができます。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-118">With this update, administrators can use Azure Data Factory to connect their SQL Server database to a Business Central online tenant and bring their data across.</span></span> <span data-ttu-id="4f8bc-119">さらに、2019 年リリース ウェーブ 2 では、移行を完了するために必要な情報のチェックリストが追加されます。</span><span class="sxs-lookup"><span data-stu-id="4f8bc-119">In addition, the 2019 release wave 2 adds a checklist for information needed to complete the migration.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="4f8bc-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="4f8bc-120">See also</span></span>

<span data-ttu-id="4f8bc-121">[Dynamics 365 Business Central を使用してオンプレミスからインテリジェント クラウドに接続する](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/about-intelligent-edge) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="4f8bc-121">[Connect to the Intelligent Cloud from On-Premises with Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/about-intelligent-edge) (docs)</span></span>

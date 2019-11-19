---
title: C/AL テーブルから AL テーブルへのパフォーマンス データのアップグレードのサポート
description: C/AL を AL コード カスタマイズに変換すると、AL アプリケーションの AppId を含むようにデータ テーブルの名前が変更され、変換されたソリューションでデータを使用できることが保証されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 10/04/2019
ms.assetid: ced261a0-2177-e911-a960-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 06b35c5ef78c827822e5e2f0b0e8c836f8582d75
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667017"
---
# <a name="support-for-performant-data-upgrade-from-cal-tables-to-al-tables"></a><span data-ttu-id="b5908-103">C/AL テーブルから AL テーブルへのパフォーマンス データのアップグレードのサポート</span><span class="sxs-lookup"><span data-stu-id="b5908-103">Support for performant data upgrade from C/AL tables to AL tables</span></span>


| <span data-ttu-id="b5908-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b5908-104">Enabled for</span></span>    |  <span data-ttu-id="b5908-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b5908-105">Public preview</span></span> | <span data-ttu-id="b5908-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b5908-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b5908-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="b5908-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="b5908-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b5908-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b5908-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b5908-109">Aug 1, 2019</span></span>| <span data-ttu-id="b5908-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b5908-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b5908-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b5908-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b5908-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b5908-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b5908-113">顧客を、オンプレミスの C/AL コードでカスタマイズされたソリューションから AL ベースのソリューションに変換するときは、アップグレード プロセスの一環として、前者から後者にデータが引き継がれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="b5908-113">When converting customers with on-premises C/AL code customized solutions to an AL-based solution, data must be carried forward from the former to the latter as part of the upgrade process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b5908-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b5908-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b5908-115">Business Central ベースのアプリケーションから AL への変換など、C/AL を AL コードのカスタマイズに変換するときは、既存の顧客のデータを "古い C/AL" テーブルから "新しい AL" テーブルに転送することが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="b5908-115">When you convert C/AL to AL code customizations, such as the conversion of the Business Central base application to AL, there will likely be a need to transfer data for existing customers from "old C/AL" tables to "new AL" tables.</span></span> <span data-ttu-id="b5908-116">これをサポートするため、テーブル名の一部として AL 拡張機能の AppId を追加することによって、テーブルの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="b5908-116">To support this, we rename tables by adding the AL extension's AppId as part of the table names.</span></span>  

<span data-ttu-id="b5908-117">PowerShell のコマンドレット Sync-NAVApp を使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。</span><span class="sxs-lookup"><span data-stu-id="b5908-117">Using the PowerShell cmdlet Sync-NAVApp, partners can convert all C/AL tables to AL tables with minimal database overhead and without the need to write any upgrade code.</span></span> <span data-ttu-id="b5908-118">コマンド `Sync-NAVApp -Mode BaseAppUpgrade` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。</span><span class="sxs-lookup"><span data-stu-id="b5908-118">The command `Sync-NAVApp -Mode BaseAppUpgrade` renames tables on the tenant database to conform to the naming convention for AL tables.</span></span> <span data-ttu-id="b5908-119">これは、テナントのテクニカル プラットフォームのアップグレードに対応し、基本アプリケーションのテーブル構造が拡張機能のテーブル構造に移行されます。</span><span class="sxs-lookup"><span data-stu-id="b5908-119">This corresponds to the technical platform upgrade for a tenant, bringing the table structure from the base application to the table structure for extensions.</span></span>
<!--feature detail end -->










---
title: C/AL テーブルから AL テーブルへのパフォーマンス データのアップグレードのサポート
description: C/AL を AL コード カスタマイズに変換すると、AL アプリケーションの AppId を含むようにデータ テーブルの名前が変更され、変換されたソリューションでデータを使用できることが保証されます。
author: relnotes
ms.reviewer: edupont
ms.date: 07/22/2019
ms.assetid: ced261a0-2177-e911-a960-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 97e6d986bd612ac712a360bd34802064d07b1ce6
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795430"
---
# <a name="support-for-performant-data-upgrade-from-cal-tables-to-al-tables"></a><span data-ttu-id="94569-103">C/AL テーブルから AL テーブルへのパフォーマンス データのアップグレードのサポート</span><span class="sxs-lookup"><span data-stu-id="94569-103">Support for performant data upgrade from C/AL tables to AL tables</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="94569-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="94569-104">Enabled for</span></span>    |  <span data-ttu-id="94569-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="94569-105">Public preview</span></span> | <span data-ttu-id="94569-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="94569-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="94569-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="94569-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="94569-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="94569-108">August 2019</span></span>| <span data-ttu-id="94569-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="94569-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="94569-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="94569-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="94569-111">顧客を、オンプレミスの C/AL コードでカスタマイズされたソリューションから AL ベースのソリューションに変換するときは、アップグレード プロセスの一環として、前者から後者にデータが引き継がれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="94569-111">When converting customers with on-premises C/AL code customized solutions to an AL-based solution, data must be carried forward from the former to the latter as part of the upgrade process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="94569-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="94569-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="94569-113">Business Central ベースのアプリケーションから AL への変換など、C/AL を AL コードのカスタマイズに変換するときは、既存の顧客のデータを "古い C/AL" テーブルから "新しい AL" テーブルに転送することが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="94569-113">When you convert C/AL to AL code customizations, such as the conversion of the Business Central base application to AL, there will likely be a need to transfer data for existing customers from "old C/AL" tables to "new AL" tables.</span></span> <span data-ttu-id="94569-114">これをサポートするため、テーブル名の一部として AL 拡張機能の AppId を追加することによって、テーブルの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="94569-114">To support this, we rename tables by adding the AL extension's AppId as part of the table names.</span></span>  

<span data-ttu-id="94569-115">PowerShell のコマンドレット Sync-NAVApp を使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。</span><span class="sxs-lookup"><span data-stu-id="94569-115">Using the PowerShell cmdlet Sync-NAVApp, partners can convert all C/AL tables to AL tables with minimal database overhead and without the need to write any upgrade code.</span></span> <span data-ttu-id="94569-116">コマンド `Sync-NAVApp -Mode BaseAppUpgrade` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。</span><span class="sxs-lookup"><span data-stu-id="94569-116">The command `Sync-NAVApp -Mode BaseAppUpgrade` renames tables on the tenant database to conform to the naming convention for AL tables.</span></span> <span data-ttu-id="94569-117">これは、テナントのテクニカル プラットフォームのアップグレードに対応し、基本アプリケーションのテーブル構造が拡張機能のテーブル構造に移行されます。</span><span class="sxs-lookup"><span data-stu-id="94569-117">This corresponds to the technical platform upgrade for a tenant, bringing the table structure from the base application to the table structure for extensions.</span></span>
<!--feature detail end -->












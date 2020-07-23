---
title: 最新の認証を使用して Common Data Service と Dynamics 365 Sales に接続する
description: OAuth 2 などの最新の認証方法を使用して、Business Central や別のアプリを Common Data Service を通じて接続できるようになりました。
author: relnotes
ms.reviewer: bholtorf
ms.date: 06/15/2020
ms.assetid: 07c59e20-dd99-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 64cfb8964097de2191975d1bea6f3d5475026812
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3547922"
---
# <a name="use-modern-authentication-to-connect-to-common-data-service-and-dynamics-365-sales"></a><span data-ttu-id="8c598-103">最新の認証を使用して Common Data Service と Dynamics 365 Sales に接続する</span><span class="sxs-lookup"><span data-stu-id="8c598-103">Use modern authentication to connect to Common Data Service and Dynamics 365 Sales</span></span>


| <span data-ttu-id="8c598-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8c598-104">Enabled for</span></span>    |  <span data-ttu-id="8c598-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8c598-105">Public preview</span></span> | <span data-ttu-id="8c598-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8c598-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8c598-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8c598-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="8c598-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8c598-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8c598-109">2020 年 6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="8c598-109">Jun 5, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8c598-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8c598-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8c598-111">多くの場合、ビジネス アプリでは複数のソースからのデータを使用します。つまり、アプリを簡単に接続できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="8c598-111">Business apps often use data from more than one source, which means that it must be easy to connect the apps.</span></span> <span data-ttu-id="8c598-112">管理者アカウントを使用して、OAuth 2 などの最新の認証方法で、Common Data Service を通じてアプリを Business Central に簡単かつ安全に接続できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8c598-112">You can now use an administrator account to simply, and securely, connect an app to Business Central with modern authentication methods, such as OAuth 2, through Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8c598-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8c598-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8c598-114">管理者アカウントのみを使用する最新の認証により、Business Central、Common Data Service、および別のビジネス アプリケーションを安全に接続します。</span><span class="sxs-lookup"><span data-stu-id="8c598-114">Connect Business Central, Common Data Service, and another business application securely with modern authentication using only an administrator account.</span></span> <span data-ttu-id="8c598-115">専用の統合ユーザーを設定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8c598-115">You do not have to set up a dedicated integration user anymore.</span></span> 

<span data-ttu-id="8c598-116">新しい Business Central テナントでは、2020 年 6 月の更新のドキュメントに記載されている機能の使用を簡単に開始できます。</span><span class="sxs-lookup"><span data-stu-id="8c598-116">New Business Central tenants can simply start using the feature as described in documentation from the June 2020 update.</span></span>

<span data-ttu-id="8c598-117">現時点では、Azure Active Directory テナントでレガシ認証セキュリティ ポリシーが無効になっている場合、既存の、およびアップグレードされた Business Central テナントへの対応は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="8c598-117">No action is required at this time for existing and upgraded Business Central tenants if the Azure Active Directory tenant has the legacy authentication security policy turned off.</span></span> <span data-ttu-id="8c598-118">詳細については、「[レガシ認証を無効にする](https://docs.microsoft.com/azure/active-directory/conditional-access/block-legacy-authentication)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8c598-118">For more information, see [Disable Legacy Authentication](https://docs.microsoft.com/azure/active-directory/conditional-access/block-legacy-authentication).</span></span> 

<span data-ttu-id="8c598-119">このセキュリティ ポリシーまたは [Multi-Factor Authentication](https://docs.microsoft.com/azure/active-directory/authentication/tutorial-enable-azure-mfa?toc=/azure/active-directory/conditional-access/toc.json&bc=/azure/active-directory/conditional-access/breadcrumb/toc.json) を有効にすると、同期ログで "ログインできない" エラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8c598-119">If you enable this security policy or [Multi-Factor Authentication](https://docs.microsoft.com/azure/active-directory/authentication/tutorial-enable-azure-mfa?toc=/azure/active-directory/conditional-access/toc.json&bc=/azure/active-directory/conditional-access/breadcrumb/toc.json), you may experience an "Unable to login" error in synchronization logs.</span></span> <span data-ttu-id="8c598-120">このエラーが発生した場合は、以下の手順に従います。</span><span class="sxs-lookup"><span data-stu-id="8c598-120">When this occurs, follow these steps:</span></span>

1. <span data-ttu-id="8c598-121">Dynamics 365 の接続の設定ページで Dynamics 365 の接続を無効にして、Common Data Service の接続の設定ページで Common Data Service を無効にします。</span><span class="sxs-lookup"><span data-stu-id="8c598-121">Disable Dynamics 365 Connection on the Dynamics 365 Connection setup page and disable Common Data Service on the Common Data Service Connection setup page.</span></span>  
2. <span data-ttu-id="8c598-122">*Microsoft Dynamics 365 Business Central Common Data Service ベース統合*ソリューションを[アンインストール](https://docs.microsoft.com/powerapps/developer/common-data-service/uninstall-delete-solution)します。Dynamics 365 Sales の接続が有効になっていた場合は、*Microsoft Dynamics 365 Business Central 統合*ソリューションをアンインストールします (必要な場合)。</span><span class="sxs-lookup"><span data-stu-id="8c598-122">[Uninstall](https://docs.microsoft.com/powerapps/developer/common-data-service/uninstall-delete-solution) the *Microsoft Dynamics 365 Business Central Common Data Service Base Integration* solution, and, optionally, if Dynamics 365 Sales connection was enabled, the *Microsoft Dynamics 365 Business Central Integration* solution.</span></span>   
3. <span data-ttu-id="8c598-123">その後、管理者資格情報を使用して、アシスト セットアップ ガイドまたは接続の設定ページから Common Data Service および Dynamics 365 接続 (必要な場合) に[再接続](https://docs.microsoft.com/dynamics365/business-central/admin-how-to-set-up-a-dynamics-crm-connection)します。</span><span class="sxs-lookup"><span data-stu-id="8c598-123">After that, [reconnect](https://docs.microsoft.com/dynamics365/business-central/admin-how-to-set-up-a-dynamics-crm-connection) to Common Data Service and, optionally, Dynamics 365 Connection using the assisted setup guide or the connection setup page using just the administrator credentials.</span></span>   

<span data-ttu-id="8c598-124">新しい最新の認証では、非インタラクティブな統合ユーザーが自動的に作成され、その資格情報を使用して Business Central と Common Data Service (および Dynamics 365 Sales) の間でデータが同期されます。</span><span class="sxs-lookup"><span data-stu-id="8c598-124">The new modern authentication will automatically create a non-interactive integration user whose credentials will be used to synchronize data between Business Central and Common Data Service (and Dynamics 365 Sales).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="8c598-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="8c598-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="8c598-126">[Common Data Service との統合](https://docs.microsoft.com/dynamics365/business-central/admin-common-data-service) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8c598-126">[Integrating with Common Data Service](https://docs.microsoft.com/dynamics365/business-central/admin-common-data-service) (docs)</span></span>
<!--docs end-->

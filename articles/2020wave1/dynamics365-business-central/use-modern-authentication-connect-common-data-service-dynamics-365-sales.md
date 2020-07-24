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
# <a name="use-modern-authentication-to-connect-to-common-data-service-and-dynamics-365-sales"></a>最新の認証を使用して Common Data Service と Dynamics 365 Sales に接続する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 6 月 5 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
多くの場合、ビジネス アプリでは複数のソースからのデータを使用します。つまり、アプリを簡単に接続できる必要があります。 管理者アカウントを使用して、OAuth 2 などの最新の認証方法で、Common Data Service を通じてアプリを Business Central に簡単かつ安全に接続できるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
管理者アカウントのみを使用する最新の認証により、Business Central、Common Data Service、および別のビジネス アプリケーションを安全に接続します。 専用の統合ユーザーを設定する必要はありません。 

新しい Business Central テナントでは、2020 年 6 月の更新のドキュメントに記載されている機能の使用を簡単に開始できます。

現時点では、Azure Active Directory テナントでレガシ認証セキュリティ ポリシーが無効になっている場合、既存の、およびアップグレードされた Business Central テナントへの対応は必要ありません。 詳細については、「[レガシ認証を無効にする](https://docs.microsoft.com/azure/active-directory/conditional-access/block-legacy-authentication)」を参照してください。 

このセキュリティ ポリシーまたは [Multi-Factor Authentication](https://docs.microsoft.com/azure/active-directory/authentication/tutorial-enable-azure-mfa?toc=/azure/active-directory/conditional-access/toc.json&bc=/azure/active-directory/conditional-access/breadcrumb/toc.json) を有効にすると、同期ログで "ログインできない" エラーが発生する場合があります。 このエラーが発生した場合は、以下の手順に従います。

1. Dynamics 365 の接続の設定ページで Dynamics 365 の接続を無効にして、Common Data Service の接続の設定ページで Common Data Service を無効にします。  
2. *Microsoft Dynamics 365 Business Central Common Data Service ベース統合*ソリューションを[アンインストール](https://docs.microsoft.com/powerapps/developer/common-data-service/uninstall-delete-solution)します。Dynamics 365 Sales の接続が有効になっていた場合は、*Microsoft Dynamics 365 Business Central 統合*ソリューションをアンインストールします (必要な場合)。   
3. その後、管理者資格情報を使用して、アシスト セットアップ ガイドまたは接続の設定ページから Common Data Service および Dynamics 365 接続 (必要な場合) に[再接続](https://docs.microsoft.com/dynamics365/business-central/admin-how-to-set-up-a-dynamics-crm-connection)します。   

新しい最新の認証では、非インタラクティブな統合ユーザーが自動的に作成され、その資格情報を使用して Business Central と Common Data Service (および Dynamics 365 Sales) の間でデータが同期されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[Common Data Service との統合](https://docs.microsoft.com/dynamics365/business-central/admin-common-data-service) (ドキュメント)
<!--docs end-->

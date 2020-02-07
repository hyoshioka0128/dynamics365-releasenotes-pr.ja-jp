---
title: Azure DevOps サービスを介した AppSourceアプリの継続的な配信のための API
description: パートナーを有効にし、Dynamics 365 Business Central アプリを構築して、顧客へのアプリの継続的な配信を実装し、Business Central online サービスで実行します。 パートナーは新しい API と Azure DevOps サービスを使用して、アプリを管理し、リリースのステップを調整します。
author: relnotes
ms.reviewer: solsen
ms.date: 12/16/2019
ms.assetid: 3d625248-2ccb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: 23a735d28ae5a56fcec3b55403f982d98b59feb4
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986834"
---
# <a name="api-for-continuous-delivery-of-the-appsource-apps-via-azure-devops-services"></a>Azure DevOps サービスを介した AppSourceアプリの継続的な配信のための API
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 4 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Business Central のパートナーは、Azure DevOps を使用して、ビルド プロセスと Business Central online へのデプロイを調整できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
一般的なグローバル パートナー コミュニティと特に Business Central パートナー コミュニティでは、継続的な統合/継続的な配信と DevOps の原則に対する熱意が高まっています。

Azure DevOps サービスでは継続的な統合のプラクティスに従ってコードを管理するための豊富な機能が Business Central 開発者に既に提供されています。 コードは Visual Studio コードで記述され、ソース管理リポジトリに保存されて、レビュー、分岐、およびマージされます。その後、ビルド パイプラインを使用してビルドおよびテストされ、Business Central Docker コンテナーにターゲットが設定されます。

次のステップは、パートナーを有効にし、Dynamics 365 Business Central アプリを構築して、顧客へのアプリの継続的な配信を実装し、Business Central online サービスで実行することです。 

パートナーは新しい API (FAME の固定アプリ管理エンドポイント) と Azure DevOps サービスを使用してアプリを管理し、リリースのステップ (リリース パイプライン) を調整します。

Business Central 2020 年リリース ウェーブ 1 では、次のフローが有効になる予定です: パートナーは Docker コンテナーでテストされ、自動化された AppSource 検証チェックに合格し、通常どおり、Microsoft パートナー センター ポータルを介して本番対応のアプリが AppSource 自動検証および追加の手動検証に送信されます。 アプリが承認されると、ISV は、以前のバージョンの ISV アプリを使用して、複数の国にわたるすべての顧客へのアプリの段階的な展開に進みます。 

お客様は、[拡張機能管理] ページでパートナー アプリの新しいバージョンにアップグレードできるようになります。これにより、お客様は適切と思われるときにインストールまたはアップグレードできます。 

Business Central 2020 年リリース ウェーブ 1 では、API の最初のバージョンが AppSource ISVs の限定的な対象ユーザーに対してプライベート プレビューとして利用可能になり、すべての Business Central AppSource ISVs がその後すぐに展開される予定です。

<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




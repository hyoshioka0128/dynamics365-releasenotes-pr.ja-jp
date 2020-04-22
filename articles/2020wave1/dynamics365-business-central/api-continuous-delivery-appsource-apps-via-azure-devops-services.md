---
title: Azure DevOps サービスを介して Business Central アプリを継続的に配信するための API
description: Business Central アプリを構築するパートナーが、Business Central Online の顧客にアプリを継続的に配信できるようにします。 パートナーは新しい API と Azure DevOps サービスを使用して、アプリを管理し、リリースのステップを調整します。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/23/2020
ms.assetid: 3d625248-2ccb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: 7645ad9614378e598cf26a9e9a7f8eec4ee3c390
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3233036"
---
# <a name="api-for-continuous-delivery-of-the-business-central-apps-via-azure-devops-services"></a>Azure DevOps サービスを介して Business Central アプリを継続的に配信するための API
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
グローバル パートナー コミュニティと Business Central パートナー コミュニティでは、特に、継続的インテグレーション/継続的配信と DevOps の原則に対する熱意が高まっています。

Azure DevOps サービスでは継続的インテグレーションのプラクティスに従ってコードを管理するための豊富な機能が開発者に既に提供されています。

- コードは Visual Studio Code で作成されます
- その後、コードはソース管理リポジトリに格納され、レビュー、分岐、マージされます
- 最後に、コードは、Business Central Docker コンテナーを対象としたビルド パイプラインを使用してビルドおよびテストされます。

次のステップは、Business Central Online サービスの顧客へのアプリの継続的配信をパートナーが実装できるようにすることです。  ソリューションは、新しい固定アプリ管理エンドポイント API です。

固定アプリ管理エンドポイント (または FAME) API は REST ベースの API です。 これは、認定 ISV であることと、アプリがマイクロソフトによって登録されていることを必要とします。 登録したら、グローバル エンドポイント (https://apps.businesscentral.dynamics.com) を使用して FAME API にアクセスします。

API は次の操作に使用できます。

- メジャー、マイナー、および修正プログラムのアプリ更新プログラムを、顧客が Business Central 管理センターからインストールできるようにします。 更新プログラムを FAME アプリ リポジトリにアップロードすることにより、更新を利用できるようにします。 新しいアプリのバージョンは、Business Central 管理の [アプリの管理] ページで利用できるようになります。
- アプリがインストールされている顧客の環境の一覧を取得します。
- 顧客の環境に合わせてアプリの修正プログラムの自動展開をスケジュールします。

FAME API を使用すると、最新の継続的インテグレーション (CI)、継続的配置 (CD)、および DevOps のプラクティスを作業に適用できます。次に例を示します。

- Microsoft Azure DevOps Services またはその他の利用可能なプロセス自動化ツールを使用して操作を自動化します。
- ロールベースのアクセス制御を整理します。
- 高度で適切に管理されたビルド、テスト、リリースのフローによってサポートされるアプリを複数の地理的な場所で大規模に管理します。

Business Central 2020 年リリース ウェーブ 1 では、FAME API への直接アクセスを利用できるのは、埋め込みアプリを使用する ISV だけです。 アドオンと Connect Apps では利用できません。 アドオンと Connect Apps を管理するには、パートナー センターを使用して、新しいアプリ バージョンを Business Central オファーにアップロードします。 次に、アプリは技術およびマーケティングの検証を受けてから、AppSource で使用可能になります。 検証に合格すると、これらのアプリをインストールしている顧客が Business Central 管理センターで新しいバージョンを利用できるようになります。
<!--feature detail end -->





## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目


<!--docs start-->
[Azure DevOps サービスを介して Business Central アプリを継続的に配信するための API](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/fame/fame-api) (ドキュメント)
<!--docs end-->


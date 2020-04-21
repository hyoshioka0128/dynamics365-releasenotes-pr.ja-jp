---
title: 拡張性のデザイン
description: ''
author: relnotes
ms.reviewer: bholtorf
ms.date: 03/19/2020
ms.assetid: bc92b8ed-4847-ea11-a812-000d3a579c33
ms.topic: article
ms.service: business-applications
ms.author: andreipa
dynamics365pdf: true
ms.openlocfilehash: 8dc39a46f487ad9c07b839d20b53194045d618ea
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232937"
---
# <a name="design-for-extensibility"></a>拡張性のデザイン
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 7 日| 2020 年 4 月|




## <a name="business-value"></a>ビジネス バリュー
マイクロソフトでは、システム アプリケーションとアプリケーション基盤を形成するシステム ロジックをモジュールに抽出することによって、コア アプリケーションの機能をさらに絞り込み、拡張の可能性を広げ、ローカライズをより簡単にするための取り組みを継続しています。 これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点を当てています。 各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。 これらによって開発サイクルがスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。 モジュールの数は構成によって異なり、各モジュールを個別に拡張することができます。 これは、マイクロソフトとパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2020 年リリース ウェーブ 1 よりはるかに早く各モジュールのソース コードを利用可能にしています。

## <a name="feature-details"></a>機能の詳細
モジュールが完成したら、ソース コードを GitHub 上の [ALAppExtensions リポジトリ](https://github.com/Microsoft/ALAppExtensions)に公開します。 それを調べ、直接フィードバックを提供し、貢献することをお勧めします。 現在、次のモジュールを使用できます。

|名前|責任|
|---|---|
|[Advanced Setting](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Advanced%20Settings)| 詳細設定と関連する統合イベントを含むページを公開します。|
|[Navigation Bar Subscribers](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Navigation%20Bar%20Subscribers)| システム イベントの既定のサブスクライバーとナビゲーション バーの対応するオーバーライド可能な統合イベントを公開します。|
|[Camera and Media Interaction](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Camera%20and%20Media%20Interaction)| カメラとクライアント デバイスに保存されたメディアへのアクセスを提供します。 [カメラ] ページを呼び出してカメラ ビューを開き、クライアント デバイスで写真を撮ります。 このページには、カメラの可用性と写真の保存の進行状況が表示されます。 [メディア アップロード] ページを呼び出して、クライアント デバイスから保存されたメディアをアップロードします。|
|Feature Key| テナントに対して有効にする機能を選択するための機能を提供します。|
|[OAuth](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/OAuth)| Oauth 1.0 認証プロトコルに関して、認証キーとシークレット、または認証ヘッダーを取得するためのヘルパー メソッドを提供します。|
|OAuth2| Oauth 2.0 認証プロトコルの認証キーとシークレット、または認証ヘッダーを取得するためのヘルパー メソッドを提供します。|
|[OAuthClientAddIn](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/OAuthClientAddIn)| コントロール アドインと、リソースを承認するための特定のメソッドを提供します。|
|Printer Management|テナントで使用可能なプリンターを管理するための機能が含まれています。|
|[Table Information](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Table%20Information)| テーブルに関する情報を表示します。|

<!--feature detail end -->










## <a name="see-also"></a>関連項目


<!--docs start-->
[システム アプリケーションの概要](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-system-application-overview) (ドキュメント)
<!--docs end-->


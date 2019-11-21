---
title: 拡張性のデザイン
description: 拡張性のデザイン
author: relnotes
ms.reviewer: edupont
ms.date: 10/21/2019
ms.assetid: 65c8ca19-be6c-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: henrikwh
dynamics365pdf: true
ms.openlocfilehash: 53e8b17e5e1473120cc57322f2f4439842392027
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667006"
---
# <a name="design-for-extensibility"></a>拡張性のデザイン


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL での Microsoft アプリケーションのソース コードの最初のリリースは、すべてのアプリケーションが拡張機能である新しい時代の幕を開くものです。これは拡張性がコードのカスタマイズに取って代わり始めたことを表します。 この変更を推進するために、より多くのシステム ロジックをモジュールに抽出し、システム アプリケーションとアプリケーション基盤を形成することによって、コア アプリケーションの機能をさらに絞り込み、拡張の可能性を広げ、ローカライズをより容易にしています。 これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点を当てています。 各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。 モジュールが小さいほど開発サイクルはスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。 モジュールの数は構成によって異なり、各モジュールを個別に更新することができます。 これは、Microsoft とパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2019 年リリース ウェーブ 2 よりはるかに早く各モジュールを利用可能にします。

モジュールが完成したら、ソース コードを [GitHub の ALAppExtensions リポジトリ](https://github.com/Microsoft/ALAppExtensions)で公開するので、直接フィードバックを提供し、貢献することができるようになります。 現在、以下のモジュールが公開されています。

|名前|責任|
|---|---|
|[Assisted Setup](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Assisted%20Setup)|Business Central のアシスト セットアップ ガイドで使用されるすべてのページが含まれています。 アシスト セットアップ ガイドでは、複雑な機能のセットアップ プロセスを簡素化するのに役立つステップバイステップのガイダンスが提供されます。|
|[Auto Format](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Auto%20Format)|テーブル、レポート、ページのフィールド内の 10 進データ型の外観を書式設定する方法を提供します。|
|[Azure AD Graph](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20AD%20Graph)|Azure AD からユーザーとテナントの情報を取得するための機能を提供します。|
|[Azure AD Licensing](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20AD%20Licensing)|登録された SKU とそれに対応するサービス プランに関する情報にアクセスする方法を提供します。 2 つのコレクションを使用します。1 つは登録された SKU を格納するコレクションで、もう 1 つはそのコレクション内で現在ポイントしている、対応する SKU のサービス プランを格納するコレクションです。|
|[Azure AD Plan](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20AD%20Plan)|Azure Active Directory でユーザー プランを取得および管理する方法を提供します。 プラン テーブルとユーザー プラン テーブルは internal としてマークされているため、このモジュールで提供されているメソッドを使用してクエリする必要があります。 |
|[Azure AD Tenant](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20AD%20Tenant)|Azure Active Directory テナントに関する情報を取得する方法を提供します。 |
|[Azure AD User Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20AD%20User%20Management)|このモジュールを使用して、データベース ユーザーを Azure AD のユーザーと同期します (新しいユーザーを作成するか、既存のユーザーを更新します)。|
|[Azure AD User](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20AD%20User)|Azure AD からユーザーの取得と更新の情報を取得するための機能を提供します。 |
|[Azure Key Vault](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Azure%20Key%20Vault)|Azure Key Vault からシークレット値を抽出する機能を公開します。 |
|[Blob Storage](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/BLOB%20Storage)|さまざまな種類のデータを格納する方法を提供します。 これは、BLOB データをメモリ内に格納する TempBlob コンテナー、セッション間で BLOB データを格納するための永続 BLOB 管理インターフェイス、およびそれぞれが BLOB データを格納する変数のシーケンスを格納するための TempBlob リスト インターフェイスから構成されます。 潜在的な用途として、イメージ、非常に長いテキスト、PDF ファイルなどの保存があります。|
|[Base64 Convert](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Base64%20Convert)|Base 64 との間でテキストを変換する機能を提供します。 サイズの大きい XML ファイル、画像などの処理に使用できます。 |
|[Caption Class](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Caption%20Class)|CaptionClass プロパティによってページとテーブルのキャプションがどのように表示されるかを定義します。 キャプションの表示方法に関するルールを定義できます。 |
|[Client Type Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Client%20Type%20Management)|このモジュールの目的は、テストを実行する対象のクライアント タイプ以外のクライアント タイプに依存するユニットをテストできるようにすることです。 これは、ユニット内のメソッド GetCurrentClientType を使用してクライアント タイプを比較し、イベント OnAfterGetCurrentClientType をサブスクライブしてテストのクライアント タイプを変更することによって実現します。 |
|[Confirm Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Confirm%20Management)|ロジックが実行されるときに確認ダイアログを表示する、またはバックグラウンド セッションや Web サービスの呼び出しなど、UI が許可されていない場合に確認ダイアログを非表示にするヘルパー メソッドを含みます。|
|[Cryptography Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Cryptography%20Management)|暗号化とハッシュ用のヘルパー関数を提供します。 オンプレミス バージョンでの暗号化の場合は、それを使用して暗号化をオンまたはオフにし、暗号化キーをインポートおよびエクスポートします。 オンライン バージョンでは暗号化が常にオンになります。|
|[Cues and KPIs](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Cues%20and%20KPIs)|Business Central でキューを管理するための設定ページとインターフェイス メソッドを提供します。|
|[Data Classification](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Data%20Classification)|機密情報が含まれている可能性があるオブジェクトについてデータを分類できるようにすることで、データのプライバシー基準を遵守するのに役立ちます。 データ機密度の分類には、標準、個人用、企業秘密、機密があります。|
|[Data Compression](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Data%20Compression)|このモジュールの目的は、バイナリ データ圧縮アーカイブを作成、更新、読み取り、破棄する機能を提供することです。|
|[Date-Time Dialog](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Date-Time%20Dialog)|日時値を入力するためのヘルパー ページです。|
|[Default Role Center](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Default%20Role%20Center)|既定のロール センターを定義する機能を公開します。|
|[DotNet Aliases](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/DotNet%20Aliases)|Business Central で使用される最も一般的な DotNet タイプのエイリアスを定義します。 エイリアスは *app.json* で宣言されている依存関係を通じて継承されるため、ここで定義されたエイリアスは他の場所で宣言する必要はありません。|
|[Environment Information](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Environment%20Information)|これが運用環境かサンドボックス環境か、またはオンライン バージョンとオンプレミス バージョンのどちらとして展開されているかの判断など、テナントや一般的な設定に関する情報を取得するためのヘルパー メソッドが含まれています。|
|[Extension Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Extension%20Management)|拡張機能とそれらの依存関係のインストールとアンインストール、ダウンロードとアップロード、公開のための機能を提供します。 拡張機能とその依存関係がインストールされているかどうかも確認できます。|
|[Field Selection](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Field%20Selection)|1 つ以上のテーブルから 1 つ以上のフィールドを検索して選択できるページを提供します。 たとえば、ロール センターで KPI を設定する場合に便利です。|
|[Filter Tokens](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Filter%20Tokens)|ユーザーが追加のフィルター トークンを入力できるようにフィルタリングを強化します。 コード フィルターまたはテキスト フィルターで %自分、%ユーザー、および %会社のフィルター トークンを使用できます。 Date、Time、および DateTime フィルターで、%今日、%作業日、%昨日、%明日、%週、%月、%四半期のフィルター トークンを使用できます。 さらに、Date フィルターでは日付式がサポートされます。 開発者は、OnResolveDateFilterToken、OnResolveTextFilterToken、OnResolveTimeFilterToken、OnResolveDateTokenFromDateTimeFilter、OnResolveTimeTokenFromDateTimeFilter の各イベントをサブスクライブすることで、フィルター トークンをさらに追加できます。|
|[Headlines](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Headlines)|ヘッドラインの機能に関連するさまざまな機能を提供します。 これには、テキストの最大許容長の定数、テキストの切り捨て、テキストの強調、およびユーザーが (挨拶のために) 最近ログインしたかどうかの確認を行う機能と、標準の挨拶メッセージが含まれます。|
|[Language](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Language)|Windows とアプリケーションの言語を変更し、言語コードを言語 ID に (またはその逆に) 変換します。 言語テーブルは、Windows 言語のサブセットです。 言語を追加したり、リスト内の翻訳や説明を編集したりできます。|
|[Manual Setup](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Manual%20Setup)|ビジネス プロセスと一般エンティティを手動で設定するために使用するページを一覧表示し、説明し、開きます。 たとえば、ビジネス プロセスの設定には、転記グループと一般会計の設定が含まれます。 一般エンティティには、通貨設定、言語設定などが含まれます。|
|[Math](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Math)|三角関数、対数関数、その他の一般的な数学関数の定数と静的メソッドを提供します。|
|[Object Selection](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Object%20Selection)|インストールされた拡張機能からのオブジェクトを含め、すべてのアプリケーション オブジェクトをページで検索します。|
|[Password Dialog](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Password%20Dialog)|ユーザーがパスワードを入力するためのダイアログを導入します。|
|[Record Link Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Record%20Link%20Management)|ユーザーは、ほぼすべてのレコードに対するメモやリンクをシステムに追加できます。 現在のモジュールは、レコードを処理するための API を開発者に提供します。たとえば、あるレコードから別のレコードへのリンクの転送/コピー、プラットフォームで期待される BLOB 形式へのテキスト入力の変換、孤立リンクのクリーンアップなどの処理です。|
|[Recurrence Schedule](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Satisfaction%20Survey)|イベントの繰り返しをスケジュールする方法を提供します。 日、週、月、または年単位の繰り返しを設定できます。 このモジュールで、次にスケジュールが発生する日時も特定できます。|
|[Satisfaction Survey](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Server%20Settings)|ユーザーに満足度調査を提示する方法を提供します。|
|[Server Settings](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Server%20Settings)|サーバー構成ファイルから設定を取得するメソッドを公開します。 たとえば、拡張機能では、Excel アドインがインストールされているかどうか、またはオンライン サービスをサーバーにインストールできるかどうかが確認されます。|
|[System Initialization](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/System%20Initialization)|アプリケーションを初期化するための機能が含まれます。|
|[Tenant License State](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Tenant%20License%20State)|ライセンスの開始日と終了日を含め、試用、有料、中止など、テナント ライセンスの現在の状態を取得します。|
|[Translation](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Translation)|このモジュールを使用すると、さまざまな地域の人々がデータを理解できるように、ユーザー データの言語の翻訳を追加および変更できます。 これはたとえば、販売する品目を説明したり、さまざまな地域にある工場での標準的な操作手順を示したりするのに役立ちます。|
|[Upgrade Tags](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Upgrade%20Tags)|アップグレード コードが 1 回だけ実行されるようにする機能を提供します。|
|[User Login Times](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/User%20Login%20Times)|ユーザーが初めてログインした日付を記録し、直近 2 回のログインを追跡します。|
|[User Permissions](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/User%20Permissions)|ユーザーのアクセス許可セットを確認および変更する機能を公開します。|
|[User Selection](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/User%20Selection)|1 人以上の登録ユーザーを検索して選択するためのページを提供します。 たとえば、これは人をドキュメント、プロセス、アイテムなどに割り当てるのに便利です。|
|[Video](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Video)|ビデオを検索して選択するためのページを提供します。 たとえば、これを使用してビデオ チュートリアルにアクセスします。|
|[Web Service Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Web%20Service%20Management)|Web サービスの管理に必要なツールを提供します。|
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Dynamics 365 のブログ](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/09/introducing-the-dynamics-365-business-central-system-application/) (ブログ)

[AL での開発](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-dev-overview) (ドキュメント)

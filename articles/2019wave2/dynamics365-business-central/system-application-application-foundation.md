---
title: 拡張性のデザイン
description: 拡張性のデザイン
author: relnotes
ms.reviewer: edupont
ms.date: 08/09/2019
ms.assetid: 65c8ca19-be6c-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: henrikwh
dynamics365pdf: true
ms.openlocfilehash: 7714bdcffc334eba40cec51bb209b5a74793b3e6
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140306"
---
# <a name="design-for-extensibility"></a>拡張性のデザイン
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL での Microsoft アプリケーションのソース コードの最初のリリースは、すべてのアプリケーションが拡張機能である新しい時代の幕を開くものです。これは拡張性がコードのカスタマイズに取って代わり始めたことを表します。 この変更を推進するために、より多くのシステム ロジックをモジュールに抽出し、システム アプリケーションとアプリケーション基盤を形成することによって、コア アプリケーションの機能をさらに絞り込み、拡張の可能性を広げ、ローカライズをより容易にしています。 

これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点を当てています。 各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。 モジュールが小さいほど開発サイクルはスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。 モジュールの数は構成によって異なり、各モジュールを個別に更新することができます。 これは、Microsoft とパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2019 年リリース ウェーブ 2 よりはるかに早く各モジュールを利用可能にします。

モジュールが完成したら、ソース コードを [GitHub の ALAppExtensions リポジトリ](https://github.com/Microsoft/ALAppExtensions)で公開するので、直接フィードバックを提供し、貢献することができるようになります。 現在、以下のモジュールが公開されています。

|名前|責任|
|---|---|
|[Auto Format](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Auto%20Format)|テーブル、レポート、またはページのフィールド内の 10 進データ型の外観を書式設定します。 たとえば、小数点以下を含む金額をロール センターのキューに表示する方法を変更できます。|
|[Blob Storage](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/BLOB%20Storage)|さまざまな種類のデータを格納する方法を提供します。 これは、BLOB データをメモリ内に格納する TempBlob コンテナー、セッション間で BLOB データを格納するための永続 BLOB 管理インターフェイス、およびそれぞれが BLOB データを格納する変数のシーケンスを格納するための TempBlob リスト インターフェイスから構成されます。 潜在的な用途として、イメージ、非常に長いテキスト、PDF ファイルなどの保存があります。|
|[Caption Class](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Caption%20Class)|CaptionClass プロパティによってページとテーブルのキャプションがどのように表示されるかを定義します。 キャプションの表示方法に関するルールを定義できます。 |
|[Confirm Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Confirm%20Management)|ロジックが実行されるときに確認ダイアログを表示する、またはバックグラウンド セッションや Web サービスの呼び出しなど、UI が許可されていない場合に確認ダイアログを非表示にするヘルパー メソッドを含みます。|
|[Cryptography Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Cryptography%20Management)|暗号化とハッシュ用のヘルパー関数を提供します。 オンプレミス バージョンでの暗号化の場合は、それを使用して暗号化をオンまたはオフにし、暗号化キーをインポートおよびエクスポートします。 オンライン バージョンでは暗号化が常にオンになります。|
|[Data Classification](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Data%20Classification)|機密情報が含まれている可能性があるオブジェクトについてデータを分類できるようにすることで、データのプライバシー基準を遵守するのに役立ちます。 データ機密度の分類には、標準、個人用、企業秘密、機密があります。|
|[Data Compression](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Data%20Compression)|このモジュールの目的は、バイナリ データ圧縮アーカイブを作成、更新、読み取り、破棄する機能を提供することです。|
|[Date-Time Dialog](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Date-Time%20Dialog)|日時値を入力するためのヘルパー ページ|
|[Environment Information](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Environment%20Information)|これが運用環境かサンドボックス環境か、またはオンライン バージョンとオンプレミス バージョンのどちらとして展開されているかの判断など、テナントや一般的な設定に関する情報を取得するためのヘルパー メソッドが含まれています。|
|[Extension Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Extension%20Management)|拡張機能とそれらの依存関係のインストールとアンインストール、ダウンロードとアップロード、公開のための機能を提供します。 拡張機能とその依存関係がインストールされているかどうかも確認できます。|
|[Field Selection](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Field%20Selection)|1 つ以上のテーブルから 1 つ以上のフィールドを検索して選択できるページを提供します。 たとえば、ロール センターで KPI を設定する場合に便利です。|
|[Filter Tokens](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Filter%20Tokens)|このモジュールは、ユーザーが追加のフィルター トークンを入力できるようにフィルタリングを強化します。 コード フィルターまたはテキスト フィルターで %自分、%ユーザー、および %会社のフィルター トークンを使用できます。 Date、Time、および DateTime フィルターで、%今日、%作業日、%昨日、%明日、%週、%月、%四半期のフィルター トークンを使用できます。 さらに、Date フィルターでは日付式がサポートされます。 開発者は、OnResolveDateFilterToken、OnResolveTextFilterToken、OnResolveTimeFilterToken、OnResolveDateTokenFromDateTimeFilter、OnResolveTimeTokenFromDateTimeFilter の各イベントをサブスクライブすることで、フィルター トークンをさらに追加できます。|
|[Language](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Language)|Windows とアプリケーションの言語を変更し、言語コードを言語 ID に (またはその逆に) 変換します。 言語テーブルは、Windows 言語のサブセットです。 言語を追加したり、リスト内の翻訳や説明を編集したりできます。|
|[Object Selection](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Object%20Selection)|インストールされた拡張機能からのオブジェクトを含め、すべてのアプリケーション オブジェクトをページで検索します。|
|[Password Dialog](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Password%20Dialog)|このモジュールは、ユーザーがパスワードを入力するためのダイアログを導入します。|
|[Record Link Management](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Record%20Link%20Management)|ユーザーは、ほぼすべてのレコードに対するメモやリンクをシステムに追加できます。 現在のモジュールは、レコードを処理するための API を開発者に提供します。たとえば、あるレコードから別のレコードへのリンクの転送/コピー、プラットフォームで期待される BLOB 形式へのテキスト入力の変換、孤立リンクのクリーンアップなどの処理です。|
 |[Server Settings](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Server%20Settings)|サーバー構成ファイルから設定を取得するメソッドを公開します。 たとえば、拡張機能では、Excel アドインがインストールされているかどうか、またはオンライン サービスをサーバーにインストールできるかどうかが確認されます。|
 |[Tenant License State](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Tenant%20License%20State)|ライセンスの開始日と終了日を含め、試用、有料、中止など、テナント ライセンスの現在の状態を取得します。|
 |[User Login Times](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/User%20Login%20Times)|ユーザーが初めてログインした日付を記録し、直近 2 回のログインを追跡します。|
 |[User Selection](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/User%20Selection)|1 人以上の登録ユーザーを検索して選択するためのページを提供します。 たとえば、これは人をドキュメント、プロセス、アイテムなどに割り当てるのに便利です。|
<!--feature detail end -->












## <a name="see-also"></a>関連項目

[AL での開発](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-dev-overview) (ドキュメント)

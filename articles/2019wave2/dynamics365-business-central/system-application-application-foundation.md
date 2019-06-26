---
title: 拡張性のデザイン
description: 拡張性のデザイン
author: relnotes
ms.reviewer: edupont
ms.date: 05/29/2019
ms.assetid: 65c8ca19-be6c-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: jannikb
dynamics365pdf: true
---
# <a name="design-for-extensibility"></a>拡張性のデザイン
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
AL での Microsoft アプリケーションのソース コードの最初のリリースは、すべてのアプリケーションが拡張機能である新しい時代であり、拡張性はコードのカスタマイズに取って代わり始めています。 この変更を容易にするために、私たちはより多くのシステム ロジックをモジュールに抽出し、システム アプリケーションとアプリケーション基盤を形成することによって、コア アプリケーションをよりシンにし、より拡張可能にし、ローカライズをより容易にするためにり組んでいます。 

これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点が当てられています。 各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。  

モジュールが小さいほど開発サイクルはスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。 モジュールの数は構成によって異なり、各モジュールを個別に更新することができます。 

これは、Microsoft とパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2019 年リリース ウェーブ 2 よりはるかに早く各モジュールを利用可能にします。 モジュールが完成したら、ソース コードを [GitHub の ALAppExtensions リポジトリ](https://github.com/Microsoft/ALAppExtensions)で公開するので、直接フィードバックを提供し、貢献することができるようになります。  
<!--feature detail end -->

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム ([https://aka.ms/bcideas](https://aka.ms/bcideas)) をご利用ください。




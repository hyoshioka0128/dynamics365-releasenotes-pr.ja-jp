---
title: C/AL テーブルから AL テーブルへのパフォーマンス データのアップグレードのサポート
description: C/AL を AL コード カスタマイズに変換すると、AL アプリケーションの AppId を含むようにデータ テーブルの名前が変更され、変換されたソリューションでデータを使用できることが保証されます。
author: relnotes
ms.reviewer: edupont
ms.date: 05/29/2019
ms.assetid: ced261a0-2177-e911-a960-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
---
# <a name="support-for-performant-data-upgrade-from-cal-tables-to-al-tables"></a>C/AL テーブルから AL テーブルへのパフォーマンス データのアップグレードのサポート
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
顧客を、オンプレミスの C/AL コードでカスタマイズされたソリューションから AL ベースのソリューションに変換するときは、アップグレード プロセスの一環として、前者から後者にデータが引き継がれる必要があります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central ベースのアプリケーションから AL への変換など、C/AL を AL コードのカスタマイズに変換するときは、既存の顧客のデータを "古い C/AL" テーブルから "新しい AL" テーブルに転送することが必要になる場合があります。 これをサポートするため、テーブル名の一部として AL 拡張機能の AppId を追加することによって、テーブルの名前を変更します。  

PowerShell のコマンドレット Sync-NAVApp を使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。 コマンド `Sync-NAVApp -Mode BaseAppUpgrade` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。 これは、テナントのテクニカル プラットフォームのアップグレードに対応し、基本アプリケーションのテーブル構造が拡張機能のテーブル構造に移行されます。
<!--feature detail end -->











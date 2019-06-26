---
title: 更新のテストと準備の改善
description: 更新のテストと準備の改善
author: relnotes
ms.reviewer: edupont
ms.date: 05/29/2019
ms.assetid: b5c1c411-b66d-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jaredha
dynamics365pdf: true
---
# <a name="improvements-in-update-testing-and-preparation"></a>更新のテストと準備の改善
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central 環境の更新プロセスをさらに効率化するいくつかの改善があります。 まず、カスタマイズの互換性検証が更新プロセスにいっそう確実に組み込まれます。 新しい更新が入手可能になると、自動検証が実行されて、テナント環境のカスタマイズが新しいバージョンと互換性があることが確認されます。 互換性がないことがツールで検出されると、環境にフラグが付けられ、カスタマイズがベース アプリケーションの新バージョンと互換性があるように更新されるまで、新しいバージョンに更新したり更新をスケジュールしたりできません。 これには、Business Central 管理センターの互換性インジケーター、および更新プロセスを通じて検証について管理者に通知する自動通知が含まれます。

2 つ目の重要な機能強化は、環境の更新が失敗したときにテナント管理者に提供されるフィードバックです。 失敗の原因の修正に管理者のアクションが必要な場合の対処可能な情報など、更新の失敗に関する詳細情報が記載されたメールを管理者は受け取ります。

3 つ目の機能強化では、AppSource 拡張機能に対する更新が利用可能かどうかを確認できます。 環境で公開されている AppSource 拡張機能に対する更新が利用可能になると、Business Central の拡張機能管理ページに管理者に対する通知が表示されます。 このオプションは、**拡張機能管理**ページから直接新しい更新を適用するためにも使用できます。
<!--feature detail end -->











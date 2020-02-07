---
title: BarTender ラベリング システム統合を使用して、Finance and Operations アプリをバックエンド システムに接続する
description: ラベル付けやバーコード処理などのための高度なソリューション。 Finance and Operations アプリでは、ラベルなどの生産を高速化するために設計されたドキュメント レンダリング サービスである BarTender がサポートされるようになりました。 Finance and Operations アプリでは、バーコードと MICR フォントを含むラベル、梱包票、その他のドキュメントのデザインと印刷に関して市場をリードするソリューションがサポートされるようになりました。
author: relnotes
ms.reviewer: kfend
ms.date: 01/14/2020
ms.assetid: b7402c86-b7c9-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 722b2106542c6665d78ddb594ceb95bd4725fd81
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986726"
---
# <a name="connect-your-finance-and-operations-apps-with-back-end-systems-using-bartender-labeling-system-integration"></a>BarTender ラベリング システム統合を使用して、Finance and Operations アプリをバックエンド システムに接続する
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 6 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
印刷が遅れると常に、ビジネスの生産性が犠牲になります。 BarTender サービスを使用すると、お客様は特別な高速の印刷機能を利用できます。 その結果、従来の SQL Server Reporting Services (SSRS) ベースのソリューションと比較した場合、プリンターへの速度の違いは顕著です。 Tech、Citizen、Zebra、Domino など、標準ラベル プラットフォーム用のシンプルでプロフェッショナルなデザイン キャンバスを使用して、カスタム フォントを参照します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
機能強化には、ローカル BarTender サービスへのアクセスに使用される接続情報を管理するための IT 管理ツールが含まれます。 これらの拡張機能では、アプリケーションのビジネス ロジックを使用してラベル生成命令を定義する既存のプリンター デバイスに対する標準的な統合が提供されます。  

サービスでは、デザインの定義に基づいて、プリンターのネイティブ言語で生成とレンダリングが行われます。 たとえば、サービスでは Zebra プリンター用の ZedPL を使用してラベルがレンダリングされます。 その結果、バーコードのシリアル番号の増分や反復などの命令は、Zebra プリント エンジンによって直接処理されて、最適なパフォーマンスが実現されます。
<!--feature detail end -->










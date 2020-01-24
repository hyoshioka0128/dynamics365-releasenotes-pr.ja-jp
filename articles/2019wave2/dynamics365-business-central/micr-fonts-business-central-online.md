---
title: Business Central オンラインで利用可能な MICR フォント
description: すぐに使用できる Business Central には、MICR (磁気インク文字認識) フォントがインストールされています。 これらのフォントは、お客様が小切手を印刷する必要がある場合に、小切手レポートの特殊なレイアウトで使用できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 12/10/2019
ms.assetid: 2140d3fd-601b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 1c034c6586f49d3f3110d953af4c515410ce13bf
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2912951"
---
# <a name="micr-fonts-available-in-business-central-online"></a>Business Central オンラインで利用可能な MICR フォント
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 2 月| 2020 年 3 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
MICR フォントで小切手を印刷する必要がある場合、Business Central オンラインで印刷できるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
更新プログラム 15.3 では、MICR (E13-B および CMC-7) 用のフォントと小切手用のセキュリティ フォントが Business Central の運用環境とサンドボックス環境に追加されます。 

これは、MICR およびセキュリティ フォントを使用するカスタム レイアウトが機能することを意味します。

IDAutomation Inc. が提供するフォント パッケージのライセンスを取得しました。 

フォントのテストを開始できるようになりました。 フォントの種類とサイズについて詳しくは、次のドキュメント ページをご覧ください。

- [https://www.idautomation.com/micr-fonts/e13b/](https://www.idautomation.com/micr-fonts/e13b/)  
- [https://www.idautomation.com/micr-fonts/cmc7/](https://www.idautomation.com/micr-fonts/cmc7/)  
- [https://www.idautomation.com/security-fonts/](https://www.idautomation.com/security-fonts/)  

テスト目的で、フォントのデモ バージョンを以下からダウンロードできます。

- [https://www.idautomation.com/micr-fonts/e13b/download.html](https://www.idautomation.com/micr-fonts/e13b/download.html)   
- [https://www.idautomation.com/micr-fonts/cmc7/download.html](https://www.idautomation.com/micr-fonts/cmc7/download.html)  
- [http://downloads.idautomation.com/IDAutomation_SecurityFontsDEMO.zip](http://downloads.idautomation.com/IDAutomation_SecurityFontsDEMO.zip)   
 
レポートを設計するには、開発者環境にフォントのデモ バージョンをインストールする必要があります。

- Windows 環境の場合、フォントをインストールします。  
- サンドボックス Docker 環境の場合、デモ フォントをローカルにダウンロードしてインストールします。 次に、ブログ投稿「[NavContainerHelper 0.3.1.0 および新しい Docker Generic ビルド 0.0.6.6](https://blogs.msdn.microsoft.com/freddyk/2018/09/03/navcontainerhelper-0-3-1-0-and-a-new-docker-generic-build-0-0-6-6/)」で説明されているように、Add-FontsToNavContainer PowerShell コマンドレットを使ってコンテナーにフォントを追加します。  
<!--feature detail end -->










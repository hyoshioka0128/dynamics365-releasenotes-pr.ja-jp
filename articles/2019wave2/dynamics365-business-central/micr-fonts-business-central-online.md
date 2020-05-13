---
title: Business Central online で利用可能な MICR フォント
description: すぐに使用できる Business Central には、MICR (磁気インク文字認識) フォントがインストールされています。 これらのフォントは、お客様が小切手を印刷する必要がある場合に、小切手レポートの特殊なレイアウトで使用できます。
author: relnotes
ms.reviewer: sgroespe
ms.date: 02/26/2020
ms.assetid: 2140d3fd-601b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: d52e1f6a2c486a598a7393bd01bac80e191dd78f
ms.sourcegitcommit: db53421debc891ea407773d0e9b39feb7a01fef3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "3110448"
---
# <a name="micr-fonts-available-in-business-central-online"></a>Business Central online で利用可能な MICR フォント


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 26 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
MICR フォントで小切手を印刷する必要がある場合、Business Central online で印刷できるようになりました。
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










## <a name="see-also"></a>関連項目

[小切手 (MICR およびセキュリティ) フォント](https://docs.microsoft.com/dynamics365/business-central/ui-fonts) (ドキュメント)

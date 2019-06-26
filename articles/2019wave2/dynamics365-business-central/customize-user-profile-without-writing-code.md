---
title: コードを書かずにユーザー プロファイルをカスタマイズする
description: ブラウザーまたは Windows 10 デスクトップ アプリでユーザー プロファイルを追加およびカスタマイズします。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 05/29/2019
ms.assetid: 846c8f04-e86b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
---
# <a name="customize-a-user-profile-without-writing-code"></a>コードを書かずにユーザー プロファイルをカスタマイズする
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、自動的|| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Business Central は、企業、部門、ユーザーに固有のニーズに簡単に適応できます。 パワー ユーザー、部門の所有者、およびコンサルタントは、自分のユーザーが独自のロールのためにアクセスできるデータやタスクを制御する必要があります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
以前は Dynamics NAV Windows クライアントのプロファイル構成モードと呼ばれていた Business Central のデスクトップ エクスペリエンスでは、同じユーザー プロファイルを共有するユーザー グループに対して軽量の UI カスタマイズが可能です。 これは、Visual Studio Code と AL をまったく使用しないで行うことができます。 次の機能が含まれます。

  - Business Central 内からユーザー プロファイルの追加、編集、削除を行います。  
  - プロフィールのより詳細な概要を取得し、それらのうちの 1 つに集中してカスタマイズを始めます。  
  - Designer のすべての豊富な機能を活用して、そのプロファイルの軽量の UI カスタマイズを行い、設計の間にカスタマイズをテストします。  

ユーザー プロファイルのカスタマイズでは、オブジェクトやデータへのアクセスはセキュリティで保護されません。 管理者は、関連するユーザー グループまたはアクセス許可セットを依然として適用する必要があります。
<!--feature detail end -->











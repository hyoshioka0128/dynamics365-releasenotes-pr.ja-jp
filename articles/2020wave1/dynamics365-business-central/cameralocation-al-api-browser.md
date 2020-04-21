---
title: ブラウザーで利用可能なカメラ/位置 AL API
description: ブラウザーで利用可能なカメラ/位置 AL API。
author: mikebcMSFT
ms.reviewer: solsen
ms.date: 04/01/2020
ms.assetid: 64e0ad63-3c36-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ddc2c04aaabef06eac83af4d51db461fae414e1c
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232959"
---
# <a name="cameralocation-al-api-available-in-the-browser"></a>ブラウザーで利用可能なカメラ/位置 AL API


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ユーザーは、カメラで写真を撮るなど、デバイス ハードウェアを最大限に活用することを最新のアプリに期待しています。 これにより、エクスペリエンスが刷新されるだけでなく、適切なシナリオに適用されると、データ入力の時間と労力も削減され、ソースにより近い情報を取得することができます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
開発者は、ブラウザーを介して Business Central にアクセスするときに、プログラムでカメラをアクティブにしたり、AL ベースの API を通じて現在位置の座標を取得したりできるようになりました。 ブラウザーとアプリの両方がサポートされるので、ユーザーのデバイスとブラウザーがこれらの機能をサポートしている限り、開発者はあらゆるフォーム ファクターでシナリオを確実に強化できます。

![カメラはブラウザーで Business Central によってアクティブ化され、写真を撮る準備ができています。](media/camera-snaps-incoming-document.png "カメラはブラウザーで Business Central によってアクティブ化され、写真を撮る準備ができています。")

### <a name="additional-details"></a>追加情報
- ユーザーはプライバシー設定を引き続き管理し、他の Web サイトと同様にカメラと位置情報へのアクセスを許可または拒否することができます。
- **CameraProvider.IsAvailable** および **LocationProvider.IsAvailable** は、ブラウザーとデバイスで機能がサポートされている場合に、True を返すようになりました。
- カメラには、ビューポートと**使用**および**撮り直し**ボタンが用意されています。
- 場所は経度と緯度の座標として返されます。

### <a name="try-it-now"></a>試してみましょう
[https://businesscentral.dynamics-tie.com/?page=30](https://businesscentral.dynamics.com/?page=30&mode=edit) でオンライン環境にログインして、写真を撮影してアイテム カードを更新してください。 
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcIdeas) をご利用ください。




## <a name="see-also"></a>関連項目


<!--docs start-->
[着信ドキュメント](https://docs.microsoft.com/dynamics365/business-central/across-income-documents) (ドキュメント)
<!--docs end-->


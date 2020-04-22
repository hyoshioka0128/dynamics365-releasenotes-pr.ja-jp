---
title: 価格計算の拡張
description: インターフェイス オブジェクトを使用して、価格計算を簡単に拡張できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/02/2020
ms.assetid: 741c5608-5272-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 97c8a961292624445342abb8d2a099782b0411b5
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232860"
---
# <a name="extend-price-calculation"></a>価格計算の拡張


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
販売と購入の特別価格と明細割引を記録すると、Business Central は販売ドキュメントと購買ドキュメント、およびジョブと品目の仕訳帳明細行の価格を自動的に計算できます。 価格は、指定された日付の最大許容明細割引での最低許容価格です。 Business Central での価格計算は多くのビジネスに適合しますが、業界またはビジネス固有の価格設定ニーズを持つ企業も多くあります。 この改善により、ビジネス ニーズに合わせて価格計算を簡単に拡張できるようにすることで、このようなニーズに対応します。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
このリリース ウェーブでは、2019 年リリース ウェーブ 2 以前のバージョンで利用できた計算の代替として利用できる価格計算の 2 番目の実装が導入されています。 この新しい実装には、たとえば新しい計算を使用して拡張するのがはるかに簡単であるという利点があります。

2019 年リリース ウェーブ 2 で利用可能だった価格計算は変更されていません。 2020 年リリース ウェーブ 1 の新しい計算は、拡張可能な追加の実装です。

現在、新しい拡張可能な価格計算機能はコードでのみ存在し、ユーザー インターフェイスは含まれていません。 今後のリリースで提供する予定です。 現時点では、新機能を使用するには独自のページを作成する必要があります。
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目


<!--docs start-->
[価格計算の拡張](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-extending-best-price-calculations) (ドキュメント)
<!--docs end-->


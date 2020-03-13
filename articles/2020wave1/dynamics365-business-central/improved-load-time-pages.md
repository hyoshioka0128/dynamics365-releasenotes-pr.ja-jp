---
title: ページの読み込み時間の向上
description: ページの読み込み時間の向上
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 02/03/2020
ms.assetid: c9b05388-851a-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 6eb528832a20e1e1b7dd709067262a0c388a2780
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031838"
---
# <a name="improved-load-time-for-pages"></a>ページの読み込み時間の向上
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ビジネス ユーザーは、タスクを完了するためにページ間を移動するとき、ページとダイアログ ボックスがすばやく読み込まれることを期待します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ユーザーは、頻繁に使用するページが前より速く開くようになったことがわかります。 技術的には、レンダリングされたページは、最初に開かれたときにキャッシュされるようになりました。 これを行うために、ビジネス データや機密情報がユーザーのデバイスに永続化されることはありません。 ページへの後続のアクセスでは、データがサービスからフェッチされている間は、すぐにページがレンダリングされます。
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目

[開発者向けのパフォーマンス トピック](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (ドキュメント)

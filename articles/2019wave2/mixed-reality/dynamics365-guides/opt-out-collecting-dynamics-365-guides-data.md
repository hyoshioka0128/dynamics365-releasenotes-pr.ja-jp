---
title: Dynamics 365 Guides データの収集をオプトアウトする
description: ''
author: relnotes
ms.reviewer: v-brycho
ms.date: 03/18/2020
ms.assetid: 8c64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: 17ddb0c5f04f020a652be2de4f654bae3ead84db
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178639"
---
# <a name="opt-out-of-collecting-dynamics-365-guides-data"></a>Dynamics 365 Guides データの収集をオプトアウトする


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
次をオプトアウトするよう選択できます。

- Microsoft への利用統計情報の送信。

- Guides Analytics のデータ収集。

## <a name="opt-out-of-sending-telemetry-data-to-microsoft"></a>Microsoft への利用統計情報の送信をオプトアウトする

PC と HoloLens の両方で、プライバシー保護のために利用統計情報を Microsoft に送信する機能を無効にできるようになりました。

![HoloLens アプリの使用状況データの送信設定](media/send-usage-data.png "HoloLens アプリの使用状況データの送信設定")

![PC アプリの使用状況データの送信設定](media/send-usage-data-pc.png "PC アプリの使用状況データの送信設定")

Microsoft は、製品の改善にこのデータを使用します。 オプトアウトを有効にすると、活動データが収集されなくなります。

## <a name="opt-out-of-data-collection-for-guides-analytics"></a>Guides Analytics のデータ収集をオプトアウトする

Power BI ダッシュボードに使用状況データが表示されないようにするために、管理者は Common Data Service から直接特定のユーザーに対してデータ収集をオフにすることができます。 このデータが Microsoft に送信されることはありません。 これは顧客のテナントに保存され、Dynamics 365 Guides がその顧客の会社でどのように使用されているかの分析情報の収集を支援します。 Guides Analytics の詳細については、「[ガイドの分析](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide)」を参照してください。

Guides Analytics のデータ収集をオプトアウトする方法の詳細については、「[Dynamics 365 Guides イベント データの Common Data Service での保存のオプトアウト](https://docs.microsoft.com/dynamics365/mixed-reality/guides/data-opt-out)」を参照してください。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Dynamics 365 Guides の使用状況データを Common Data Service に保存しないようオプトアウトする](https://docs.microsoft.com/dynamics365/mixed-reality/guides/data-opt-out) (ドキュメント)

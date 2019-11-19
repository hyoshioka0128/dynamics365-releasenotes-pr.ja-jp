---
title: Dynamics 365 Guides データの収集をオプトアウトする
description: ''
author: relnotes
ms.reviewer: v-brycho
ms.date: 10/09/2019
ms.assetid: 8c64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: f7a901953973466201882f9ecc7c595b2bba84c0
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2661264"
---
# <a name="opt-out-of-collecting-dynamics-365-guides-data"></a><span data-ttu-id="8723b-102">Dynamics 365 Guides データの収集をオプトアウトする</span><span class="sxs-lookup"><span data-stu-id="8723b-102">Opt out of collecting Dynamics 365 Guides data</span></span>


| <span data-ttu-id="8723b-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="8723b-103">Enabled for</span></span>    |  <span data-ttu-id="8723b-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8723b-104">Public preview</span></span> | <span data-ttu-id="8723b-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="8723b-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8723b-106">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8723b-106">End users, automatically</span></span>|-| <span data-ttu-id="8723b-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8723b-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8723b-108">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8723b-108">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8723b-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8723b-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8723b-110">次をオプトアウトするよう選択できます。</span><span class="sxs-lookup"><span data-stu-id="8723b-110">You can choose to opt out of:</span></span>

- <span data-ttu-id="8723b-111">Microsoft への利用統計情報の送信。</span><span class="sxs-lookup"><span data-stu-id="8723b-111">Sending telemetry data to Microsoft.</span></span>

- <span data-ttu-id="8723b-112">Guides 分析のデータ収集。</span><span class="sxs-lookup"><span data-stu-id="8723b-112">Data collection for Guides Analytics.</span></span>

## <a name="opt-out-of-sending-telemetry-data-to-microsoft"></a><span data-ttu-id="8723b-113">Microsoft への利用統計情報の送信をオプトアウトする</span><span class="sxs-lookup"><span data-stu-id="8723b-113">Opt out of sending telemetry data to Microsoft</span></span>

<span data-ttu-id="8723b-114">PC と HoloLens の両方で、プライバシー保護のために利用統計情報を Microsoft に送信する機能を無効にできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8723b-114">For privacy reasons, you can now turn off the ability to send telemetry data to Microsoft from both PC and HoloLens.</span></span>

<span data-ttu-id="8723b-115">![HoloLens アプリの使用状況データの送信設定](media/send-usage-data.png "HoloLens アプリの使用状況データの送信設定")</span><span class="sxs-lookup"><span data-stu-id="8723b-115">![Send usage data HoloLens app setting](media/send-usage-data.png "Send usage data HoloLens app setting")</span></span>

<span data-ttu-id="8723b-116">![PC アプリの使用状況データの送信設定](media/send-usage-data-pc.png "PC アプリの使用状況データの送信設定")</span><span class="sxs-lookup"><span data-stu-id="8723b-116">![Send usage data PC app setting](media/send-usage-data-pc.png "Send usage data PC app setting")</span></span>

<span data-ttu-id="8723b-117">Microsoft は、製品の改善にこのデータを使用します。</span><span class="sxs-lookup"><span data-stu-id="8723b-117">Microsoft uses this data to improve the product.</span></span> <span data-ttu-id="8723b-118">オプトアウトを有効にすると、活動データが収集されなくなります。</span><span class="sxs-lookup"><span data-stu-id="8723b-118">Opting out prevents Microsoft from collecting any activity data.</span></span>

## <a name="opt-out-of-data-collection-for-guides-analytics"></a><span data-ttu-id="8723b-119">Guides 分析のデータ収集をオプトアウトする</span><span class="sxs-lookup"><span data-stu-id="8723b-119">Opt out of data collection for Guides Analytics</span></span>

<span data-ttu-id="8723b-120">Power BI ダッシュボードに使用状況データが表示されないようにするために、管理者は Common Data Service から直接特定のユーザーに対してデータ収集をオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="8723b-120">To prevent usage data from showing in Power BI dashboards, administrators can turn off data collection for specific users directly from Common Data Service.</span></span> <span data-ttu-id="8723b-121">このデータが Microsoft に送信されることはありません。</span><span class="sxs-lookup"><span data-stu-id="8723b-121">This data is never sent to Microsoft.</span></span> <span data-ttu-id="8723b-122">これは顧客のテナントに保存され、Dynamics 365 Guides がその顧客の会社でどのように使用されているかの分析情報の収集を支援します。</span><span class="sxs-lookup"><span data-stu-id="8723b-122">It's stored in a customer's tenant to help them collect insights about how Dynamics 365 Guides is being used in their company.</span></span> <span data-ttu-id="8723b-123">Guides 分析の詳細については、「[ガイドの分析](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8723b-123">For more information on Guides Analytics, see [Analyze your guides](https://docs.microsoft.com/dynamics365/mixed-reality/guides/analytics-guide).</span></span>

<span data-ttu-id="8723b-124">Guides 分析のデータ収集をオプトアウトする方法の詳細については、「[Dynamics 365 Guides イベント データの Common Data Service での保存のオプトアウト](https://docs.microsoft.com/dynamics365/mixed-reality/guides/data-opt-out)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8723b-124">For information on opting out of data collection for Guides Analytics, see [Opt out of storing Dynamics 365 Guides events data in Common Data Service](https://docs.microsoft.com/dynamics365/mixed-reality/guides/data-opt-out).</span></span>
<!--feature detail end -->










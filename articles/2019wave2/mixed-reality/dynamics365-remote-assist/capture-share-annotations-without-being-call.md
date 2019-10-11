---
title: 通話せずに注釈を取り込んで共有する
description: 通話せずに注釈を取り込んで共有する
author: relnotes
ms.reviewer: v-brycho
ms.date: 08/02/2019
ms.assetid: 6e64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jaarmeni
dynamics365pdf: true
ms.openlocfilehash: 0f0e1b3b673adac63167ce27d5bbbd3a66ad9ca1
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142671"
---
# <a name="capture-and-share-annotations-without-being-in-a-call"></a><span data-ttu-id="7932d-103">通話せずに注釈を取り込んで共有する</span><span class="sxs-lookup"><span data-stu-id="7932d-103">Capture and share annotations without being in a call</span></span>
[!include[mixed-reality/dynamics365-remote-assist banner](../includes/mixed-reality/dynamics365-remote-assist.md)]

| <span data-ttu-id="7932d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7932d-104">Enabled for</span></span>    |  <span data-ttu-id="7932d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7932d-105">Public preview</span></span> | <span data-ttu-id="7932d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7932d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7932d-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7932d-107">Users, automatically</span></span>|-| <span data-ttu-id="7932d-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="7932d-108">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="7932d-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7932d-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7932d-110">リモート アシスタンスが必要であるものの、ネットワークの制限により通話を確立できないシナリオのサポートを求めるフィードバックがお客様からありました。</span><span class="sxs-lookup"><span data-stu-id="7932d-110">We have received feedback from customers asking us to support scenarios where remote assistance is needed, but a call can’t be established due to network limitations.</span></span> 

<span data-ttu-id="7932d-111">シナリオの例:</span><span class="sxs-lookup"><span data-stu-id="7932d-111">Example scenarios:</span></span> 

-  <span data-ttu-id="7932d-112">インターネット接続がない、または接続がビデオ通話をサポートできない場合に問題に関する情報を取り込む。</span><span class="sxs-lookup"><span data-stu-id="7932d-112">Capturing information about an issue when there's no internet connection or the connection can't support a video call.</span></span> <span data-ttu-id="7932d-113">例: 液化天然ガスを運ぶ石油会社の貨物船や、遠隔地の変電所。</span><span class="sxs-lookup"><span data-stu-id="7932d-113">Examples: oil company cargo ship carrying liquified natural gas; remote power substation.</span></span>

-  <span data-ttu-id="7932d-114">エキスパートがいないときに問題に関する情報を取り込み、チャット/メールで送信する。</span><span class="sxs-lookup"><span data-stu-id="7932d-114">Capturing information about an issue when an expert isn’t available and sending via chat/email.</span></span> <span data-ttu-id="7932d-115">例: 航空会社が FAA と通信する必要がある場合。</span><span class="sxs-lookup"><span data-stu-id="7932d-115">Example: airline company needs to communicate with the FAA.</span></span>

-  <span data-ttu-id="7932d-116">リモート検査の記録。</span><span class="sxs-lookup"><span data-stu-id="7932d-116">Recording remote inspections.</span></span> <span data-ttu-id="7932d-117">例: 工場出荷試験、安全検査、インシデント検査。</span><span class="sxs-lookup"><span data-stu-id="7932d-117">Examples: factory acceptance tests; safety inspections; incident inspections.</span></span>

-  <span data-ttu-id="7932d-118">将来のトレーニングと参照のための手順の文書化。</span><span class="sxs-lookup"><span data-stu-id="7932d-118">Documenting procedures for future training and reference.</span></span>

<span data-ttu-id="7932d-119">この機能には次のサポートが含まれます。</span><span class="sxs-lookup"><span data-stu-id="7932d-119">This feature includes support for the following:</span></span>

<span data-ttu-id="7932d-120">**通話なしの注釈**。</span><span class="sxs-lookup"><span data-stu-id="7932d-120">**No-call annotations.**</span></span> <span data-ttu-id="7932d-121">第一線の作業者は、電話をかけずにセッションを開始できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7932d-121">First-line workers will be able to begin a session without making a call.</span></span> <span data-ttu-id="7932d-122">自分が見ていることや行おうとしていることについての追加のコンテキストを提供するために自分の環境に注釈を付けられるようになるので、エキスパート (同僚、サード パーティなど) は適切な時点で効率的な支援を提供できます。</span><span class="sxs-lookup"><span data-stu-id="7932d-122">They will be able to annotate their world to provide additional context about what they’re looking at or trying to do, so an expert (colleague, third party, and so on) can provide efficient assistance at the appropriate time.</span></span> 

<span data-ttu-id="7932d-123">**通話なしの写真とビデオの取り込み。**</span><span class="sxs-lookup"><span data-stu-id="7932d-123">**No-call photo and video capture.**</span></span> <span data-ttu-id="7932d-124">写真とビデオは、問題について必要な情報と背景を伝えるのに役立つので、エキスパートが支援を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="7932d-124">Photos and videos help convey necessary information and context about an issue so an expert can provide assistance.</span></span> <span data-ttu-id="7932d-125">写真とビデオは、検査、監査、トレーニングの文書化に必要なアーティファクトとしても役立ちます。</span><span class="sxs-lookup"><span data-stu-id="7932d-125">Photos and videos also serve as required artifacts for inspections, audits, and training documentation.</span></span>    

<span data-ttu-id="7932d-126">**非同期ファイル共有。**</span><span class="sxs-lookup"><span data-stu-id="7932d-126">**Asynchronous file sharing.**</span></span> <span data-ttu-id="7932d-127">第一線の作業者は、シナリオに応じて異なる方法で、取り込まれた情報を送信することができます。</span><span class="sxs-lookup"><span data-stu-id="7932d-127">First-line workers will be able to send captured information in different ways, depending on the scenario.</span></span> <span data-ttu-id="7932d-128">デバイスに情報を保存し、それを OneDrive にアップロードするか、Microsoft Teams でだれかに送信できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7932d-128">They’ll be able to save information on the device, upload it to OneDrive, or send it to someone on Microsoft Teams.</span></span>
<!--feature detail end -->











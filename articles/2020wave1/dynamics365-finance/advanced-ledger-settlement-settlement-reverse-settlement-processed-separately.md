---
title: '詳細な元帳決済: 決済と決済取消を別個に処理する'
description: 決済プロセスに決済取消対象としてマークされたトランザクションと決済対象としてマークされたトランザクションが含まれていても、警告のみでプロセスを正常に実行できるようになりました。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/09/2020
ms.assetid: 5ecb01aa-ce42-ea11-a812-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 1a590ba713a9e2331a425d62833a5d4d8b42dddb
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294404"
---
# <a name="advanced-ledger-settlement-settlement-and-reverse-settlement-processed-separately"></a><span data-ttu-id="41992-103">詳細な元帳決済: 決済と決済取消を別個に処理する</span><span class="sxs-lookup"><span data-stu-id="41992-103">Advanced ledger settlement: Settlement and reverse settlement processed separately</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="41992-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="41992-104">Enabled for</span></span>    |  <span data-ttu-id="41992-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="41992-105">Public preview</span></span> | <span data-ttu-id="41992-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="41992-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="41992-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="41992-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="41992-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="41992-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="41992-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="41992-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="41992-110">決済プロセスに決済取消対象としてマークされたトランザクションと決済対象としてマークされたトランザクションが含まれていても、警告のみでプロセスを正常に実行できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="41992-110">The settlement process can now run successfully with only a warning, even if the process includes transactions that are marked for unsettlement and settlement.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="41992-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="41992-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="41992-112">詳細な元帳決済機能を有効にすると、決済対象レコードと決済取消対象レコードの両方をマークすることができます。</span><span class="sxs-lookup"><span data-stu-id="41992-112">When the Advanced ledger settlement feature is enabled, both settled records and unsettled records can be marked.</span></span> <span data-ttu-id="41992-113">以前は、決済対象レコードと決済取消対象レコードの両方がマークされている場合、各プロセスは別々のプロセスであるため、マークされたトランザクションの決済プロセスとマークされたトランザクションの取消プロセスの両方がエラーで失敗していました。</span><span class="sxs-lookup"><span data-stu-id="41992-113">Previously when both settled and unsettled records were marked, both the settle-marked transactions and reverse-marked transactions processes would fail with an error, because each process is separate.</span></span> 

<span data-ttu-id="41992-114">今後は、各プロセスが完了するまで実行されますが、警告が生成されます。</span><span class="sxs-lookup"><span data-stu-id="41992-114">Now, each process will run to completion but generate a warning.</span></span>  <span data-ttu-id="41992-115">たとえば、レコードの一部が決済対象としてマークされ、一部が決済取消対象としてマークされている場合にマークされたトランザクションの決済プロセスが実行されると、決済対象としてマークされたレコードが決済され、決済取消対象としてマークされたレコードが処理されなかったことを通知するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="41992-115">For example, if some records are marked to settle and some are marked to unsettle, and the settle-marked transactions process is run, the records marked for settlement will be settled, and a message will let you know that the records marked for unsettlement were not processed.</span></span>
<!--feature detail end -->










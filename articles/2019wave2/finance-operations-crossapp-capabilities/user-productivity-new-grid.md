---
title: ユーザーの生産性 - 新しいグリッド
description: ユーザーの生産性 - 新しいグリッド
author: relnotes
ms.reviewer: sericks
ms.date: 10/15/2019
ms.assetid: e662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: 503409a243eaf741dd29fea0c708f718c12abb06
ms.sourcegitcommit: 3e19a91181b001b74894328456d8da10d4f6d973
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2019
ms.locfileid: "2673831"
---
# <a name="user-productivity--new-grid"></a><span data-ttu-id="b4902-103">ユーザーの生産性 - 新しいグリッド</span><span class="sxs-lookup"><span data-stu-id="b4902-103">User productivity – New grid</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="b4902-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b4902-104">Enabled for</span></span>    |  <span data-ttu-id="b4902-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b4902-105">Public preview</span></span> | <span data-ttu-id="b4902-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b4902-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b4902-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b4902-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b4902-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b4902-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b4902-109">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="b4902-109">Aug 5, 2019</span></span>| <span data-ttu-id="b4902-110">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="b4902-110">Mar 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b4902-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b4902-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b4902-112">2019 年 10 月に (Platform update 29)、新しく改善されたグリッド コントロールのプレビューが利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="b4902-112">A preview of a new and improved grid control is available in October 2019 (Platform update 29).</span></span> <span data-ttu-id="b4902-113">新しいグリッドでは、レンダリング速度が向上し、スクロール エクスペリエンスが速くなっています。</span><span class="sxs-lookup"><span data-stu-id="b4902-113">The new grid provides improved rendering speed and a faster scrolling experience.</span></span> <span data-ttu-id="b4902-114">また、ユーザーはブラウザーに読み込まれたデータ内の特定の位置にスクロールすることもできます。</span><span class="sxs-lookup"><span data-stu-id="b4902-114">Users are also able to positionally scroll within the data that has been loaded in the browser.</span></span> <span data-ttu-id="b4902-115">さらに、新しいグリッドでは、既存のグリッドで生じていたグリッド ヘッダーとデータの位置のずれに関する問題と、スクロール中または新しいレコードの作成中にグリッドがジャンプする問題が排除されます。</span><span class="sxs-lookup"><span data-stu-id="b4902-115">Further, the new grid eliminates issues from the existing grid around misalignment of grid headers and data, as well as the grid jumping while scrolling or creating new records.</span></span> 

<span data-ttu-id="b4902-116">新しいグリッドでは、より複雑な機能を新しいグリッドに組み込むこともできます。これらのグリッドの機能強化は、今後の毎月の更新で予定されています。</span><span class="sxs-lookup"><span data-stu-id="b4902-116">The new grid also provides the ability to build more complex features into the new grid, and these enhancements to the grid are planned in subsequent monthly updates:</span></span>

- <span data-ttu-id="b4902-117">**合計**: ビジネス ユーザーは、表形式グリッドの数値列について合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="b4902-117">**Totals**: Business users can see totals for numeric columns in tabular grids.</span></span> <span data-ttu-id="b4902-118">たとえば、会計担当のユーザーは、特定の顧客に対するフィルター処理されたトランザクション セットの合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="b4902-118">For example, financial users will be able to view totals for a filtered set of transactions for a specific customer.</span></span> 

  <span data-ttu-id="b4902-119">![金額列に表示された合計](media/user-productivity-new-grid-1.png "金額列に表示された合計")</span><span class="sxs-lookup"><span data-stu-id="b4902-119">![Total shown for the Amount column](media/user-productivity-new-grid-1.png "Total shown for the Amount column")</span></span>

- <span data-ttu-id="b4902-120">**高速データ入力**: この機能を使用すると、ユーザーはグリッドにデータを可能な限りすばやく入力でき、グリッド内の別の行に移動する前にユーザーがサーバーによる行の検証を待つ必要性が最小限に抑えられます。</span><span class="sxs-lookup"><span data-stu-id="b4902-120">**Fast data entry**: This feature allows users to enter data in a grid as quickly as possible, minimizing the need for users to wait for the server to validate a row before moving to another row in the grid.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b4902-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="b4902-121">See also</span></span>

<span data-ttu-id="b4902-122">[Platform update 29 の新機能または変更点](https://docs.microsoft.com/dynamics365/unified-operations/fin-and-ops/get-started/whats-new-platform-update-29) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b4902-122">[What's new or changed in Platform update 29](https://docs.microsoft.com/dynamics365/unified-operations/fin-and-ops/get-started/whats-new-platform-update-29) (docs)</span></span>

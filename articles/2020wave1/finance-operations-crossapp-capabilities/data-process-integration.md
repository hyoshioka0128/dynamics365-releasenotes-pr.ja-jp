---
title: データとプロセスの統合
description: 独自の Azure Data Lake Storage Gen2 データ レイクですべてのデータが利用可能
author: relnotes
ms.reviewer: ''
ms.date: 04/29/2020
ms.assetid: e83944e6-75c8-e911-a968-000d3a4f3883
ms.topic: structure
ms.service: business-applications
ms.author: robadawy
dynamics365pdf: true
ms.openlocfilehash: 2c3567fe01dc754f7ed7ef6cd343330994c74ef1
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349430"
---
# <a name="data-and-process-integration"></a>データとプロセスの統合

[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

<!--structure start-->
## <a name="finance-and-operations-data-in-azure-data-lake-storage-gen2"></a>Azure Data Lake Storage Gen2 での Finance and Operations データ

Dynamics AX 2012 以前を使用しているオンプレミスのお客様は、これまでデータに直接アクセスすることができました。これらのお客様は、データに直接アクセスし、Power BI などのツールでレポートを作成することに慣れている可能性があります。 お客様は、Finance and Operations に移行し、クラウドでのデジタル変革を開始するにあたって、少なくともしばらくの間は、レポートやデータ ウェアハウスに関連する既存の資産を維持したいと考える可能性があります。 Microsoft では、すべてのデータにアクセスできるようにすることで、お客様がクラウドに簡単に移行できるようにしたいと考えています。 Finance and Operations アプリで定義された中核的なテーブル、データ エンティティ、および集計測定は、お客様のデータ レイク (Data Lake Storage Gen2) でも利用可能になります。 

管理者は、使いやすいインターフェイスを使用して、データ レイクを Finance and Operations アプリで構成できます。 データの更新は Microsoft によって管理されます。テーブル、エンティティ、および集計測定は、パワー ユーザーが選択できます。 データは更新され、最新の状態に保たれます。お客様がエクスポート スケジュールを管理する必要はありません。 

中核的なテーブル、エンティティ、集計測定は、さまざまな属性、定義、リレーションシップとともに Common Data Model で定義されます。 データ レイクにエクスポートされるデータは、Common Data Model で記述されます。 Data Lake Storage Gen2 のデータ構造は、Common Data Model のデータ定義の構成を反映したものとなります。 Data Lake Storage に格納されるデータは、Common Data Model の言語仕様で定義されたメタデータを使用して記述されます。 これにより、既存のツールでデータのセマンティクスとリレーションシップを解釈できるようになり、データ レイクのデータを処理できるようになります。 

Data Lake Storage Gen2 のテーブル、エンティティ、および集計測定が一般提供になることで、お客様は Data Lake Storage Gen2 をレポートやダウンストリーム統合のデータソースとして使用できるようになります。 現在、自分のデータベースの持ち込み (BYOD) を使用して Finance and Operations からデータをエクスポートしている場合は、Data Lake Storage Gen2 に移行することができます。お客様は、自分でデータをエクスポートすることなく、Data Lake Storage Gen2 に既に存在するデータを使用できます。
<!--structure end-->




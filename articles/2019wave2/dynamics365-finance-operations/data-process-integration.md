---
title: データとプロセスの統合
description: データとプロセスの統合
author: relnotes
ms.reviewer: sericks007
ms.date: 05/09/2019
ms.assetid: be096b69-725d-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: robadawy
dynamics365pdf: true
---
# <a name="data-and-process-integration"></a>データとプロセスの統合

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Common Data Service には、すぐに使用可能な追加エンティティ マッピングが含まれるようになります。 このリリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。 これらのエンティティにより、Microsoft Power Platform を通じてより深い拡張性シナリオが可能になります。 Dynamics 365 for Finance and Operations は、いくつかのビジネス プロセス分野 (製造、倉庫および輸送、銀行および現金管理など) のビジネス イベントと Microsoft Flow をトリガーおよび監視する機能が追加され、Finance and Operations でのワークフローの主な推進力になっています。

<!--note from editor:  In second sentence in below para should it be "Azure Data Lake Storage Gen2" or "Azure Data Lake Store Gen2" ? 
In second sentence below, is there a word missing ? "Transactional data from Finance and Operations is available in a customer’s own Azure Data Lake Storage Gen2 _______  in real time (within minutes)." ? -->

Azure Data Lake Gen2 でのエンティティ ストアの一般提供により、お客様は次世代の AI および分析プラットフォームを使用できます。 Finance and Operations からのトランザクション データは、お客様自身の Azure Data Lake Storage Gen2 でリアルタイムに (数分以内に) 利用できます。 従来のデータ ウェアハウスも Azure Data Lake に移行し、標準の Finance and Operations エンティティは Azure Data Lake Gen2 に格納されます。 


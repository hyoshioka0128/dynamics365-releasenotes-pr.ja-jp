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
# <a name="advanced-ledger-settlement-settlement-and-reverse-settlement-processed-separately"></a>詳細な元帳決済: 決済と決済取消を別個に処理する
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
決済プロセスに決済取消対象としてマークされたトランザクションと決済対象としてマークされたトランザクションが含まれていても、警告のみでプロセスを正常に実行できるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
詳細な元帳決済機能を有効にすると、決済対象レコードと決済取消対象レコードの両方をマークすることができます。 以前は、決済対象レコードと決済取消対象レコードの両方がマークされている場合、各プロセスは別々のプロセスであるため、マークされたトランザクションの決済プロセスとマークされたトランザクションの取消プロセスの両方がエラーで失敗していました。 

今後は、各プロセスが完了するまで実行されますが、警告が生成されます。  たとえば、レコードの一部が決済対象としてマークされ、一部が決済取消対象としてマークされている場合にマークされたトランザクションの決済プロセスが実行されると、決済対象としてマークされたレコードが決済され、決済取消対象としてマークされたレコードが処理されなかったことを通知するメッセージが表示されます。
<!--feature detail end -->










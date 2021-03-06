---
title: "Define a Fact Relationship and Fact Relationship Properties | Microsoft Docs"
ms.custom: ""
ms.date: "03/01/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services"
ms.service: ""
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  
ms.component: multidimensional-tabular
ms.component: data-mining
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "fact dimensions [Analysis Services]"
ms.assetid: d8e41724-da77-4ac1-bc42-956b5d91ea5d
caps.latest.revision: 10
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# Define a Fact Relationship and Fact Relationship Properties
[!INCLUDE[ssas-appliesto-sqlas](../../includes/ssas-appliesto-sqlas.md)]
  When you define a new cube dimension or a new measure group, [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] will try to detect if a fact dimension relationship exists and then set the dimension usage setting to **Fact**. You can view or edit a fact dimension relationship on the **Dimension Usage** tab of Cube Designer. The fact relationship between a dimension and a measure group has the following constraints:  
  
-   A cube dimension can have only one fact relationship to a particular measure group.  
  
-   A cube dimension can have separate fact relationships to multiple measure groups.  
  
-   The granularity attribute for the relationship must be the key attribute (such as Transaction Number) for the dimension. This creates a one-to-one relationship between the dimension and facts in the fact table.  
  
  

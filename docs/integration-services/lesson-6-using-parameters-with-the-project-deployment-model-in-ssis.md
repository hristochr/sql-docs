---
title: "Lesson 6: Using Parameters with the Project Deployment Model in SSIS | Microsoft Docs"
ms.custom: ""
ms.date: "03/01/2017"
ms.prod: sql
ms.prod_service: "integration-services"
ms.service: ""
ms.component: "tutorial"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 
  - "integration-services"
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "SQL Server 2016"
ms.assetid: 9216f18c-1762-4f2d-8c22-bd0ab7107555
caps.latest.revision: 5
author: "douglaslMS"
ms.author: "douglasl"
manager: "craigg"
---
# Lesson 6: Using Parameters with the Project Deployment Model in SSIS
SQL Server 2012 introduces a new deployment model where you can deploy your projects to the Integration Services server. The Integration Services server enables you to manage and run packages, and to configure runtime values for packages.  
  
In this lesson, you will modify the package that you created in [Lesson 5: Add SSIS Package Configurations for the Package Deployment Model](../integration-services/lesson-5-add-ssis-package-configurations-for-the-package-deployment-model.md) to use the Project Deployment Model. You replace the configuration value with a parameter to specify the sample data location. You can also copy the completed Lesson 5 package that is included with the tutorial.  
  
Using the Integration Services Project Configuration Wizard, you will convert the project to the Project Deployment Model and use a Parameter rather than a configuration value to set the Directory property. This lesson partially covers the steps you would follow to convert existing SSIS packages to the new Project Deployment Model.  
  
When you run the package again, the Integration Services service uses the parameter to populate the value of the variable, and the variable in turn updates the Directory property. As a result, the package iterates through the files in the new data folder specified by the parameter value rather than the folder that was set in the package configuration file.  
  
> [!IMPORTANT]  
> This tutorial requires the **AdventureWorksDW2012** sample database. For more information about how to install and deploy **AdventureWorksDW2012**, see [Considerations for Installing SQL Server Samples and Sample Databases](http://technet.microsoft.com/library/ms161556%28v=sql.105%29).  
  
## Lesson Tasks  
This lesson contains the following tasks:  
  
1.  [Step 1: Copying the Lesson 5 Package](../integration-services/lesson-6-1-copying-the-lesson-5-package.md)  
  
2.  [Step 2: Converting the Project to the Project Deployment Model](../integration-services/lesson-6-2-converting-the-project-to-the-project-deployment-model.md)  
  
3.  [Step 3: Testing the Lesson 6 Package](../integration-services/lesson-6-3-testing-the-lesson-6-package.md)  
  
4.  [Step 4: Deploying the Lesson 6 Package](../integration-services/lesson-6-4-deploying-the-lesson-6-package.md)  
  
## Start the Lesson  
[Step 1: Copying the Lesson 5 Package](../integration-services/lesson-6-1-copying-the-lesson-5-package.md)  
  

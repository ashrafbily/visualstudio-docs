---
title: "Registering File Name Extensions for Side-By-Side Deployments | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
helpviewer_keywords: 
  - "file extensions, registering for side-by-side"
ms.assetid: 9ab046a2-147d-4167-aa14-7d661b1eaaa5
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# Registering File Name Extensions for Side-By-Side Deployments
For VSPackages deployed in a side-by-side environment, you must register file name extensions to associate the files with the correct version of [!INCLUDE[vsprvs](../code-quality/includes/vsprvs_md.md)]. Unless you use a version-specific file name extension, registration enables users to open your project and project item files in the appropriate version of [!INCLUDE[vsprvs](../code-quality/includes/vsprvs_md.md)].  
  
## In This Section  
 [About File Name Extensions](../extensibility/about-file-name-extensions.md)  
 Discusses how file name extensions are registered.  
  
 [Specifying File Handlers for File Name Extensions](../extensibility/specifying-file-handlers-for-file-name-extensions.md)  
 Provides information about how to register the applications that can open, edit, and so on, a particular file name extension.  
  
 [Registering Verbs for File Name Extensions](../extensibility/registering-verbs-for-file-name-extensions.md)  
 Discusses how to register verbs.  
  
 [Managing Side-by-Side File Associations](../extensibility/managing-side-by-side-file-associations.md)  
 Discusses how to handle side-by-side installations in which a particular version of [!INCLUDE[vsprvs](../code-quality/includes/vsprvs_md.md)] should be invoked to open a file.  
  
## Related Sections  
 [Supporting Multiple Versions of Visual Studio](../extensibility/supporting-multiple-versions-of-visual-studio.md)  
 Describes issues related to multiple versions of [!INCLUDE[vsprvs](../code-quality/includes/vsprvs_md.md)] and your VSPackage during development and deployment to end users.
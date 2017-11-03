---
title: "Sample: Upload, retrieve, and download an attachment | MicrosoftDocs"
description: "The sample demonstrates how to upload, retrieve, and download an attachment for an annotation using the IOrganizationService.Entity) and IOrganizationService.ColumnSet) methods. "
ms.custom: ""
ms.date: 10/31/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "samples"
applies_to: 
  - "Dynamics 365 (online)"
helpviewer_keywords: 
  - "uploading; retrieving; and downloading attachments sample, sample for the annotation (note) entity"
  - "sample for uploading; retrieving; and downloading attachments, annotation (note) entity sample"
ms.assetid: a231c619-7130-43f0-b3da-fd1a87545672
caps.latest.revision: 19
author: "JimDaly"
ms.author: "jdaly"
manager: "amyla"
---
# Sample: Upload, retrieve, and download an attachment

[!INCLUDE[](../includes/cc_applies_to_update_9_0_0.md)]

This sample code is for [!INCLUDE[pn_dynamics_crm_online](../includes/pn-dynamics-crm-online.md)]. Download the complete sample from [Sample: Work with Annotations](https://code.msdn.microsoft.com/Annotation-Sample-9d797e21).  

## Prerequisites
[!INCLUDE[sdk-prerequisite](../includes/sdk-prerequisite.md)]
  
## Requirements  
[!INCLUDE[sdk_SeeConnectionHelper](../includes/sdk-seeconnectionhelper.md)]
  
## Demonstrates  
 This sample shows how to upload, retrieve, and download an attachment for an annotation using the <xref:Microsoft.Xrm.Sdk.IOrganizationService>.<xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*> and <xref:Microsoft.Xrm.Sdk.IOrganizationService>.<xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*> methods.  
  
## Example  
 [!code-csharp[Annotation#UploadAndDownloadAttachment](../snippets/csharp/CRMV8/annotation/cs/uploadanddownloadattachment.cs#uploadanddownloadattachment)]  
  
### See also  
 [Sample: CrmServiceHelper Class](org-service/helper-code-serverconnection-class.md)   
 [Annotation (Note) Entity](annotation-note-entity.md)   
<xref:Microsoft.Xrm.Sdk.IOrganizationService>   
 <xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>   
 <xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>
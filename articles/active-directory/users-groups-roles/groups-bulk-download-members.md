---
title: Bulk download group membership list - Azure Active Directory portal | Microsoft Docs
description: Add users in bulk in the Azure admin center. 
services: active-directory 
author: curtand
ms.author: curtand
manager: mtillman
ms.date: 09/11/2019
ms.topic: conceptual
ms.service: active-directory
ms.subservice: users-groups-roles
ms.workload: identity
ms.custom: it-pro
ms.reviewer: jeffsta
ms.collection: M365-identity-device-management
---

# Bulk download members of a group (preview) in Azure Active Directory

Using Azure Active Directory (Azure AD) portal, you can bulk download the members of a group in your organization to a comma-separated values (CSV) file.

> [!NOTE]
> Azure AD bulk operations are a public preview feature of Azure AD and are available with any paid Azure AD license plan. For more information about preview use terms, see [Supplemental Terms of Use for Microsoft Azure Previews](https://azure.microsoft.com/support/legal/preview-supplemental-terms/).

## Bulk download service limits

Each bulk activity to download a list of group members can run for up to one hour. This enables you to download of a list of at least 500,000 members.

## To bulk download group membership

1. Sign in to [the Azure portal](https://portal.azure.com) with a User administrator account in the organization. Group owners can also bulk download members of groups they own.
1. In Azure AD, select **Groups** > **All groups**.
1. Open the group whose membership you want to download, and then select **Members**.
1. On the **Members** page, select **Download members** to download a CSV file listing the group members.

   ![The Download Members command is on the profile page for the group](./media/groups-bulk-download-members/download-panel.png)

## Check download status

You can see the status of all of your pending bulk requests in the **Bulk operation results (preview)** page.

   ![The Bulk operations results page shows you bulk request status](./media/groups-bulk-download-members/bulk-center.png)

## Next steps

- [Bulk import group members](groups-bulk-import-members.md)
- [Bulk remove group members](groups-bulk-download-members.md)

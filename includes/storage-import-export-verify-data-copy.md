---
title: include file
description: include file
author: v-dalc
services: storage

ms.service: storage
ms.topic: include
ms.date: 12/27/2021
ms.author: alkohli
ms.custom: include file
---

Track the job to completion. Then make sure that your data has been uploaded to Azure successfully. 

Review the **Data copy details** of the completed job to locate the logs for each drive included in the job:

- Use the *verbose log* to verify each successfully transferred file.
- Use the *copy log* to find the source of each failed data copy.

[ ![Screenshot showing a completed import job in Azure Import Export. In Data Copy Details, the Copy Log Path and Verbose Log Path are highlighted.](./media/storage-import-export-verify-data-copy/completed-import-order.png) ](./media/storage-import-export-verify-data-copy/completed-import-order.png#lightbox)

For more information, see [Review copy logs from imports and exports](..\articles\import-export\storage-import-export-tool-reviewing-job-status-v1.md).

After you verify the data transfers, you can delete your on-premises data. Delete your on-premises data only after you verify that the upload was successful.

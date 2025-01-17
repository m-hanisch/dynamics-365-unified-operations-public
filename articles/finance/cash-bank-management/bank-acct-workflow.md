---
title: Bank account lifecycle management
description: This article explains how to enable an approval workflow for bank accounts in the Cash and bank management module.
author: EricWang
ms.date: 04/18/2024
ms.topic: article
audience: Application User
ms.reviewer: twheeloc
ms.search.region: 
ms.author: wangchen
ms.search.validFrom: 2024-04-29
ms.dyn365.ops.version: 
ms.custom: 
ms.search.form: 
---

# Bank account lifecycle management

[!include [banner](../../includes/banner.md)]

This article explains how to enable an approval workflow for bank accounts in the **Cash and bank management** module.

## Prerequisites

- In the **Feature management** workspace, turn on the **(Preview) Bank account lifecycle management** feature.
- In **Cash and bank management workflows**, make sure that there's an active **Workflow for proposed bank account change** workflow.

## Activate an approval workflow

To enable a bank account approval workflow, follow these steps.

1. Go to **Cash and bank management** \> **Setup** \> **Cash and bank master data change setup**.
1. Set the following parameters:

    - **Change approval on modification** – Select this parameter to enable an approval workflow when a bank account is modified.
    - **Change approval on creation** – Select this parameter to enable an approval workflow when a bank account is created.
    - **Change history** – Select this parameter to save and review the bank account change history.
    - **Data entity behavior** – Select the approval workflow to use when a bank account is imported through data entities.

1. If you selected the **Change approval on modification** parameter in the last step, the **Protected fields** page is available. The fields on this page correspond to fields on bank accounts. Activate the fields that should trigger an approval workflow if users update their value on a bank account.
1. Select **Save**.

## View the change history

To view the bank account change history, follow these steps.

1. Go to **Cash and bank management** \> **Bank accounts** \> **Bank accounts**.
1. Select **Changes**.
1. Select **Change history**.

---
# required metadata

title: Add a copyright notice
description: This topic describes how to add a copyright notice to your e-Commerce website.
author: psimolin
manager: AnnBe
ms.date: 10/01/2019
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-retail
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Application user
# ms.devlang: 
ms.reviewer: v-chgri
ms.search.scope: Operations, Retail, Core
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: 
ms.search.region: Global
# ms.search.industry: 
ms.author: psimolin
ms.search.validFrom: 2019-10-31
ms.dyn365.ops.version: Release 10.0.5

---

# Add a copyright notice

[!include [banner](includes/preview-banner.md)]
[!include [banner](includes/banner.md)]

This topic describes how to add a copyright notice to your e-Commerce website.

## Prerequisites

Before you can add a copyright notice to your site, you must have the following items:

- A template that includes a shared footer fragment.
- A page that uses that template.

## Add a copyright notice

To add a copyright notice to the bottom of every page that uses a specific template, follow these steps.

1. Go to **Fragments**, and then select **New Page Fragment**.
1. In the dialog box, select the **Footer** module, and name the fragment. For example, enter **Footer-Copyright**.
1. Select **OK**.
1. In the navigation pane, select the ellipsis button (**...**) next to **Footer**, and then select **Add Module**.
1. In the dialog box, select **Footer category**, and then select **OK**.
1. In the navigation pane, select the ellipsis button next to **Footer category**, and then select **Add Module**.
1. In the dialog box, select **Content rich block item**, and then select **OK**.
1. In the navigation pane, select **Content rich block item**.
1. In the properties pane on the right, in the **Paragraph** field, add your copyright message. For example, enter **(C) Fabrikam 2019**.
1. Select **Save**, select **Check In**, and then select **Publish**.
1. Go to **Templates**, select the template, and then select **Check Out**.
1. Under **Page Outline**, expand **Body**, and then expand **Default Page**.
1. Select the ellipsis button next to **Footer Slot**, and then select **Add Fragment**.
1. Select the fragment that you created earlier, and then select **Select**.
1. Check in the template, and publish it.

The footer that contains the copyright notice automatically appears at the bottom of all pages that use the selected template.

---
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server-ui.MessageFormResponse Class
description: Contents of the @minecraft/server-ui.MessageFormResponse class.
---
# MessageFormResponse Class
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

## Extends
- [*FormResponse*](FormResponse.md)

Returns data about the player results from a modal message form.

## Properties

### **cancelationReason**
`read-only cancelationReason?: FormCancelationReason;`

Contains additional details as to why a form was canceled.

Type: [*FormCancelationReason*](FormCancelationReason.md)

### **canceled**
`read-only canceled: boolean;`

If true, the form was canceled by the player (e.g., they selected the pop-up X close button).

Type: *boolean*

### **selection**
`read-only selection?: number;`

Returns the index of the button that was pushed.

Type: *number*

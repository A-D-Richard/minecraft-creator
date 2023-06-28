---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ItemCompleteUseAfterEvent Class
description: Contents of the @minecraft/server.ItemCompleteUseAfterEvent class.
---
# ItemCompleteUseAfterEvent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

Contains information related to a chargeable item completing being charged.

## Properties

### **itemStack**
`read-only itemStack: ItemStack;`

Returns the item stack that has completed charging.

Type: [*ItemStack*](ItemStack.md)

### **source**
`read-only source: Entity;`

Returns the source entity that triggered this item event.

Type: [*Entity*](Entity.md)

### **useDuration**
`read-only useDuration: number;`

Returns the time, in ticks, for the remaining duration left before the charge completes its cycle.

Type: *number*

---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.BlockSignComponent Class
description: Contents of the @minecraft/server.BlockSignComponent class.
---
# BlockSignComponent Class
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.
> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Extends
- [*BlockComponent*](BlockComponent.md)

Represents a block that can display text on it.

## Properties

### **location**
`read-only location: BlockLocation;`

Location of the sign.

Type: [*BlockLocation*](BlockLocation.md)

### **text**
`read-only text: string;`

Text of the sign

Type: *string*

### **typeId**
`read-only typeId: string;`

Identifier of this component. Should always be minecraft:sign.

Type: *string*

## Constants

### **componentId**
`static read-only componentId = "minecraft:sign";`

Identifier of this component. Should always be minecraft:sign.

Type: *string*

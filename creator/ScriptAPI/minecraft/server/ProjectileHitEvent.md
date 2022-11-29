---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ProjectileHitEvent Class
description: Contents of the @minecraft/server.ProjectileHitEvent class.
---
# ProjectileHitEvent Class
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.
> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

Contains information related to a projectile hitting an entity or block.

## Properties

### **blockHit**
`read-only blockHit?: BlockHitInformation;`

Contains additional information about the block that was hit by the projectile, or undefined if the projectile did not hit a block.

Type: [*BlockHitInformation*](BlockHitInformation.md)

### **dimension**
`read-only dimension: Dimension;`

Dimension where this projectile hit took place.

Type: [*Dimension*](Dimension.md)

### **entityHit**
`read-only entityHit?: EntityHitInformation;`

Contains additional information about a block that was hit.

Type: [*EntityHitInformation*](EntityHitInformation.md)

### **hitVector**
`read-only hitVector: Vector;`

Direction vector of the projectile as it hit a block/entity.

Type: [*Vector*](Vector.md)

### **location**
`read-only location: Location;`

Location where the projectile hit occurred.

Type: [*Location*](Location.md)

### **projectile**
`read-only projectile: Entity;`

Entity for the projectile that hit a block/entity.

Type: [*Entity*](Entity.md)

### **source**
`read-only source: Entity;`

Optional source entity that fired the projectile.

Type: [*Entity*](Entity.md)

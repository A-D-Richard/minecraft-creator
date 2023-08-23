---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.EntitySpawnAfterEvent Class
description: Contents of the @minecraft/server.EntitySpawnAfterEvent class.
---
# EntitySpawnAfterEvent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

Contains data related to an entity spawning within the world.

## Properties

### **cause**
`read-only cause: EntityInitializationCause;`

Initialization cause (Spawned, Born ...).

Type: [*EntityInitializationCause*](EntityInitializationCause.md)

### **entity**
`entity: Entity;`

Entity that was spawned.

Type: [*Entity*](Entity.md)
  
> [!IMPORTANT]
> This property can't be edited in read-only mode.

#### Examples
##### ***runEntitySpawnEvent.ts***
```typescript
  // register a new function that is called when a new entity is created.
  mc.world.afterEvents.entitySpawn.subscribe((entityEvent: mc.EntitySpawnAfterEvent) => {
    if (entityEvent && entityEvent.entity) {
      log(`New entity of type '${entityEvent.entity.typeId}' created!`, 1);
    } else {
      log(`The entity event didn't work as expected.`, -1);
    }
  });

  mc.system.runTimeout(() => {
    createOldHorse(log, targetLocation);
  }, 20);
```

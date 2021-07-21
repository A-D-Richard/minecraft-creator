---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/Mojang/MinecraftScriptingApiDocsGenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: mojang-minecraft.Dimension Class
description: Contents of the mojang-minecraft.Dimension class.
---
# Dimension Class
>[!IMPORTANT]
>These APIs are experimental as part of GameTest Framework. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to GameTest Framework APIs.

A class that represents a particular dimension (e.g., The End) within a world.


## Methods
- [createExplosion](#createexplosion)
- [getBlock](#getblock)
- [getEntitiesAtBlockLocation](#getentitiesatblocklocation)
- [isEmpty](#isempty)
- [spawnEntity](#spawnentity)
  
### **createExplosion**
`
createExplosion(location: Location, radius: number, explosionOptions: ExplosionOptions): void
`

Creates an explosion at the specified location.
#### Arguments
| Param | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **location** | [*Location*](Location.md) | n/a | The location of the explosion. |
| **radius** | *number* | n/a | Radius, in blocks, of the explosion to create. |
| **explosionOptions** | [*ExplosionOptions*](ExplosionOptions.md) | n/a | Additional configurable options for the explosion. |


> [!WARNING]
> This function can throw errors.

### **getBlock**
`
getBlock(location: BlockLocation): Block
`

Returns a block instance at the given location. This method was introduced as of version 1.17.10.21.
#### Arguments
| Param | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **location** | [*BlockLocation*](BlockLocation.md) | n/a | The location at which to return a block. |

Returns [*Block*](Block.md) - Block at the specified location.


### **getEntitiesAtBlockLocation**
`
getEntitiesAtBlockLocation(location: BlockLocation): Entity[]
`

#### Arguments
| Param | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **location** | [*BlockLocation*](BlockLocation.md) | n/a | - |

Returns [*Entity*](Entity.md)[]


### **isEmpty**
`
isEmpty(location: BlockLocation): boolean
`

Tests whether a particular location contains an Air (empty) block.
#### Arguments
| Param | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **location** | [*BlockLocation*](BlockLocation.md) | n/a | The location at which to check for emptiness |

Returns *boolean* - True if the block at the location is air (empty)


### **spawnEntity**
`
spawnEntity(identifier: string, location: BlockLocation): Entity
`

Creates a new entity (e.g., a mob) at the specified location. This method was introduced as of version 1.17.10.21.
#### Arguments
| Param | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **identifier** | *string* | n/a | Identifier of the type of entity to spawn. If no namespace is specified, 'minecraft:' is assumed. |
| **location** | [*BlockLocation*](BlockLocation.md) | n/a | The location at which to create the entity. |

Returns [*Entity*](Entity.md) - Newly created entity at the specified location.

> [!WARNING]
> This function can throw errors.



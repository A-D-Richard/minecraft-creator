---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IProjectileHitAfterEventSignal Class
description: Contents of the @minecraft/server.IProjectileHitAfterEventSignal class.
---
# IProjectileHitAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IProjectileHitAfterEventSignal
- [*ProjectileHitAfterEventSignal*](ProjectileHitAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires after a projectile hits a target.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ProjectileHitAfterEvent) => void): (arg: ProjectileHitAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ProjectileHitAfterEvent*](ProjectileHitAfterEvent.md)) => *void*

#### **Returns** (arg: [*ProjectileHitAfterEvent*](ProjectileHitAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ProjectileHitAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ProjectileHitAfterEvent*](ProjectileHitAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.

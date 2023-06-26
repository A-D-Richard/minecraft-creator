---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IEffectAddAfterEventSignal Class
description: Contents of the @minecraft/server.IEffectAddAfterEventSignal class.
---
# IEffectAddAfterEventSignal Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Classes that extend IEffectAddAfterEventSignal
- [*EffectAddAfterEventSignal*](EffectAddAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires when an effect is added to an entity.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: EffectAddAfterEvent) => void, options?: EntityEventOptions): (arg: EffectAddAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*EffectAddAfterEvent*](EffectAddAfterEvent.md)) => *void*
- **options**?: [*EntityEventOptions*](EntityEventOptions.md) = `null`

#### **Returns** (arg: [*EffectAddAfterEvent*](EffectAddAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: EffectAddAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*EffectAddAfterEvent*](EffectAddAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.

---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.service: minecraft-bedrock-edition
title: minecraft/server-editor.IModalToolContainer Interface
description: Contents of the @minecraft/server-editor.IModalToolContainer class.
---
# IModalToolContainer Interface

## Properties

### **currentTools**
`read-only currentTools: IModalTool[];`

Tools within this container.

Type: *IModalTool[]*

## Methods
- [addTool](#addtool)
- [focusToolInputContext](#focustoolinputcontext)
- [getSelectedToolId](#getselectedtoolid)
- [removeTool](#removetool)
- [setSelectedToolId](#setselectedtoolid)

### **addTool**
`
addTool(params: ModalToolCreationParameters, action: RegisteredAction<NoArgsAction>): IModalTool
`

Create a new tool in the modal tool container represented via button on the tool rail.

#### **Parameters**
- **params**: *ModalToolCreationParameters*
  
  Construction parameters for the new tool
- **action**: *RegisteredAction<NoArgsAction>*

**Returns** *IModalTool*

### **focusToolInputContext**
`
focusToolInputContext(): void
`

Activates input bindings for the selected tool by enabling viewport focus

**Returns** *void*

### **getSelectedToolId**
`
getSelectedToolId(): string | undefined
`

Returns identifier of the selected tool.

**Returns** *string | undefined*

### **removeTool**
`
removeTool(id: string): void
`

Remove an existing tool by id from the tool container

#### **Parameters**
- **id**: *string*
  
  Name of the tool to remove.

**Returns** *void*

### **setSelectedToolId**
`
setSelectedToolId(id: string | undefined): void
`

Selects a tool in the container.

#### **Parameters**
- **id**: *string | undefined*
  
  Identifier of the tool

**Returns** *void*

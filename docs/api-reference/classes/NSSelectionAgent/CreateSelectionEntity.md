﻿---
uid: crmscript_ref_NSSelectionAgent_CreateSelectionEntity
title: SelectionEntity CreateSelectionEntity(String targetTableName)
intellisense: NSSelectionAgent.CreateSelectionEntity
keywords: NSSelectionAgent, CreateSelectionEntity
so.topic: reference
---

Create (but do not save) a new selection entity, for the current user and the given target table; other fields populated as by CreateDefaultSelectionEntity()

**Parameters:**
 - **targetTableName** The name of the target table, such as 'contact' or 'appointment'; any table for which Selection functionality is enabled

**Returns:** The new SelectionEntity, which has not yet been saved

```crmscript
NSSelectionAgent agent;
String targetTableName;
SelectionEntity res = agent.CreateSelectionEntity(targetTableName);
```

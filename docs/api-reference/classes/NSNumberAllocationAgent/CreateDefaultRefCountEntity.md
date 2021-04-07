﻿---
uid: crmscript_ref_NSNumberAllocationAgent_CreateDefaultRefCountEntity
title: NSRefCountEntity CreateDefaultRefCountEntity()
intellisense: NSNumberAllocationAgent.CreateDefaultRefCountEntity
keywords: NSNumberAllocationAgent, CreateDefaultRefCountEntity
so.topic: reference
---
	  
Set default values into a new NSRefCountEntity.
NetServer calculates default values (e.g. Country) on the entity, which is required when creating/storing a new instance
	  
**Returns:** A new NSRefCountEntity with default values.

```crmscript
NSNumberAllocationAgent agent;
NSRefCountEntity thing = agent.CreateDefaultRefCountEntity();
thing = agent.SaveRefCountEntity(thing);
```

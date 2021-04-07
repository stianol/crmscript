﻿---
uid: crmscript_ref_NSFindAgent_CreateRestrictionGroup
title: ArchiveRestrictionGroup CreateRestrictionGroup(String storageType, String providerName, String storageKey, String context)
intellisense: NSFindAgent.CreateRestrictionGroup
keywords: NSFindAgent, CreateRestrictionGroup
so.topic: reference
---

Create a restriction group, initialized with next rank etc.

**Parameters:**
 - **storageType** Restriction storage type specification, either 'Criteria' or 'Reporter' (or possible extensions)
 - **providerName** Name of archive provider that is the intended consumer of the restrictions
 - **storageKey** Storage key to be interpreted by the restriction storage provider, when it saves the restrictions as criteria
 - **context** Optional context that can be used by FindProvider

**Returns:** The new restriction group.

```crmscript
NSFindAgent agent;
String storageType;
String providerName;
String storageKey;
String context;
ArchiveRestrictionGroup res = agent.CreateRestrictionGroup(storageType, providerName, storageKey, context);
```

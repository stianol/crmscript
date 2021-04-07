﻿---
uid: crmscript_ref_NSArchiveAgent_GetAvailableEntities
title: MDOListItemArray GetAvailableEntities(String providerName, String context)
intellisense: NSArchiveAgent.GetAvailableEntities
keywords: NSArchiveAgent, GetAvailableEntities
so.topic: reference
---

Return list of all entities supported by an archive provider. See also GetArchiveConfiguration.

**Parameters:**
 - **providerName** The name of the archive provider to use; it will be created via the ArchiveProviderFactory from a plugin
 - **context** Optional context parameter, url-encoded string context parameter for ArchiveProvider constructor

**Returns:** Array of all entity types supported by the archive provider. MDOListItem.Name = DisplayName, Tooltip = DisplayTooltip, Type = code name, StyleHint = optional/mandatory, IconHint=DefaultShow 

```crmscript
NSArchiveAgent agent;
String providerName;
String context;
MDOListItemArray res = agent.GetAvailableEntities(providerName, context);
```

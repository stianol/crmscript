﻿---
uid: crmscript_ref_NSMarketingAgent_CreateDefaultFormSubmissionEntity
title: NSFormSubmissionEntity CreateDefaultFormSubmissionEntity()
intellisense: NSMarketingAgent.CreateDefaultFormSubmissionEntity
keywords: NSMarketingAgent, CreateDefaultFormSubmissionEntity
so.topic: reference
---
	  
Set default values into a new NSFormSubmissionEntity.
NetServer calculates default values (e.g. Country) on the entity, which is required when creating/storing a new instance
	  
**Returns:** A new NSFormSubmissionEntity with default values.

```crmscript
NSMarketingAgent agent;
NSFormSubmissionEntity thing = agent.CreateDefaultFormSubmissionEntity();
thing = agent.SaveFormSubmissionEntity(thing);
```

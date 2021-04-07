﻿---
uid: crmscript_ref_NSConfigurationAgent_GetWwwUrlForSMWeb
title: String GetWwwUrlForSMWeb()
intellisense: NSConfigurationAgent.GetWwwUrlForSMWeb
keywords: NSConfigurationAgent, GetWwwUrlForSMWeb
so.topic: reference
---

Returns the URL used for the logo by the SM.web client. Uses urldispatch.aspx


**Returns:** Link to urldispatch.aspx tagged with [SOSITEURL]

```crmscript
NSConfigurationAgent agent;
String res = agent.GetWwwUrlForSMWeb();
```

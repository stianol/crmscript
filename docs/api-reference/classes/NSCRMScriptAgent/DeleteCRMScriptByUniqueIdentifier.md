﻿---
uid: crmscript_ref_NSCRMScriptAgent_DeleteCRMScriptByUniqueIdentifier
title: Void DeleteCRMScriptByUniqueIdentifier(String uniqueIdentifier)
intellisense: NSCRMScriptAgent.DeleteCRMScriptByUniqueIdentifier
keywords: NSCRMScriptAgent, DeleteCRMScriptByUniqueIdentifier
so.topic: reference
---

Delete the CRMScript

**Parameters:**
 - **uniqueIdentifier** Global unique reference to script (independent of installation)

**Returns:** This method has no return value

```crmscript
NSCRMScriptAgent agent;
String uniqueIdentifier;
Void res = agent.DeleteCRMScriptByUniqueIdentifier(uniqueIdentifier);
```

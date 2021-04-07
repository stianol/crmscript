﻿---
uid: crmscript_ref_NSMassOperationResult_SetRowStatus
title: SetRowStatus(UpsertRowStatusArray rowStatus)
intellisense: NSMassOperationResult.SetRowStatus
keywords: NSMassOperationResult, GetRowStatus
so.topic: reference
---

Array of statuses and primary keys for all rows that were specified. Populated if the 'ReturnRowStatus' parameter of 'Upsert' is set, otherwise null

**Parameter:** 
 - **rowStatus** UpsertRowStatusArray

```crmscript
NSMassOperationResult thing;
UpsertRowStatusArray rowStatus;
thing.SetRowStatus(rowStatus);
```

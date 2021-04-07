﻿---
uid: crmscript_ref_NSQuoteLine_GetStatus
title: QuoteStatus GetStatus()
intellisense: NSQuoteLine.GetStatus
keywords: NSQuoteLine, GetStatus
so.topic: reference
---

If there was a problem with for instance calculation, this field is set to warning or error. Typically shown as an icon. QuoteStatus is an enum with statuses: OK, OKWithInfo, Warning, Error.

**Returns:** QuoteStatus

     - Enum: 0 = Ok 
     - Enum: 1 = OkWithInfo 
     - Enum: 2 = Warning 
     - Enum: 3 = Error 

```crmscript
NSQuoteLine thing;
QuoteStatus status  = thing.GetStatus();
```


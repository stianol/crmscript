﻿---
uid: crmscript_ref_NSTicketStatusEntity_GetTimeCounter
title: TicketStatusTimeCounter GetTimeCounter()
intellisense: NSTicketStatusEntity.GetTimeCounter
keywords: NSTicketStatusEntity, GetTimeCounter
so.topic: reference
---

Which field in ticket we count time spent on (queue, internal, external) 

**Returns:** TicketStatusTimeCounter

     - Enum: 0 = None 
     - Enum: 1 = Internally 
     - Enum: 2 = Externally 
     - Enum: 3 = Queue 

```crmscript
NSTicketStatusEntity thing;
TicketStatusTimeCounter timeCounter  = thing.GetTimeCounter();
```


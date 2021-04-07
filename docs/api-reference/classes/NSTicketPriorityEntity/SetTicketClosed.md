﻿---
uid: crmscript_ref_NSTicketPriorityEntity_SetTicketClosed
title: SetTicketClosed(TicketPriorityEscalateEvent ticketClosed)
intellisense: NSTicketPriorityEntity.SetTicketClosed
keywords: NSTicketPriorityEntity, GetTicketClosed
so.topic: reference
---

This field indicates what to do with the escalation chain when the request is closed

**Parameter:** 
 - **ticketClosed** TicketPriorityEscalateEvent
     - Enum: -1 = None 
     - Enum: 0 = Stop 
     - Enum: 1 = Continue 
     - Enum: 2 = Restart 

```crmscript
NSTicketPriorityEntity thing;
TicketPriorityEscalateEvent ticketClosed;
thing.SetTicketClosed(ticketClosed);
```

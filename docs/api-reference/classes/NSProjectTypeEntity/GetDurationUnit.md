﻿---
uid: crmscript_ref_NSProjectTypeEntity_GetDurationUnit
title: DurationUnit GetDurationUnit()
intellisense: NSProjectTypeEntity.GetDurationUnit
keywords: NSProjectTypeEntity, GetDurationUnit
so.topic: reference
---

Units for the duration

**Returns:** DurationUnit

     - Enum: 0 = Unknown 
     - Enum: 1 = Second 
     - Enum: 2 = Minute 
     - Enum: 3 = Hour 
     - Enum: 4 = Day 
     - Enum: 5 = Week 
     - Enum: 6 = Month 
     - Enum: 7 = Quarter 
     - Enum: 8 = HalfYear 
     - Enum: 9 = Year 
     - Enum: 10 = Decade 
     - Enum: 11 = Century 
     - Enum: 12 = Millenium 

```crmscript
NSProjectTypeEntity thing;
DurationUnit durationUnit  = thing.GetDurationUnit();
```


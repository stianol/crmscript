﻿---
uid: crmscript_ref_NSPersonEntity_GetAssociate
title: Associate GetAssociate()
intellisense: NSPersonEntity.GetAssociate
keywords: NSPersonEntity, GetAssociate
so.topic: reference
---

The associate owning this person (similar to contact.Associate) - usually blank. Use the Person.Contact.Associate instead.  Intended for use when individual persons are created (i.e. when Person.Contact is blank)

**Returns:** Associate


```crmscript
NSPersonEntity thing;
Associate associate  = thing.GetAssociate();
```


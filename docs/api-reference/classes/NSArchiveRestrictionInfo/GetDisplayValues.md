---
uid: crmscript_ref_NSArchiveRestrictionInfo_GetDisplayValues
title: String[] GetDisplayValues()
intellisense: NSArchiveRestrictionInfo.GetDisplayValues
keywords: NSArchiveRestrictionInfo, GetDisplayValues
so.topic: reference
---

# String[] GetDisplayValues()

Display representation of value(s) - list ID's are decoded to display texts, other values are represented in a format suitable for decoding and display through the CultureDataFormatter.

**Returns:** String[]

```crmscript
NSArchiveRestrictionInfo thing;
String[] displayValues  = thing.GetDisplayValues();
```


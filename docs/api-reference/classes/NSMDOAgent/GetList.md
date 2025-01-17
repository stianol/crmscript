---
uid: crmscript_ref_NSMDOAgent_GetList
title: NSMDOListItem[] GetList(String name, Bool forceFlatList, String additionalInfo, Bool onlyHistory)
intellisense: NSMDOAgent.GetList
keywords: NSMDOAgent, GetList
so.topic: reference
---

# NSMDOListItem[] GetList(String name, Bool forceFlatList, String additionalInfo, Bool onlyHistory)

Method to get a MDO list.

**Parameters:**
 - **name** Conceptual name of the MDO list-
 - **forceFlatList** Force the list to be flat
 - **additionalInfo** Additional info to the MDO provider
 - **onlyHistory** If true, return only history items

**Returns:** NSMDOListItem[]

```crmscript
NSMDOAgent agent;
String name;
Bool forceFlatList;
String additionalInfo;
Bool onlyHistory;
NSMDOListItem[] res = agent.GetList(name, forceFlatList, additionalInfo, onlyHistory);
```


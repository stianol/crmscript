---
uid: crmscript_ref_NSEMailAgent_FindContactOrPersonByEmailName
title: ContactOrPersonFromEmail[] FindContactOrPersonByEmailName(String name, String emailAddress)
intellisense: NSEMailAgent.FindContactOrPersonByEmailName
keywords: NSEMailAgent, FindContactOrPersonByEmailName
so.topic: reference
---

# ContactOrPersonFromEmail[] FindContactOrPersonByEmailName(String name, String emailAddress)

**Parameters:**
 - **name** The sender name
 - **emailAddress** The sender email address

**Returns:** ContactOrPersonFromEmail[]

```crmscript
NSEMailAgent agent;
String name;
String emailAddress;
ContactOrPersonFromEmail[] res = agent.FindContactOrPersonByEmailName(name, emailAddress);
```


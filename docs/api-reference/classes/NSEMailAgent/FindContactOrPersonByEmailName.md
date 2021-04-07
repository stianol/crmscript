﻿---
uid: crmscript_ref_NSEMailAgent_FindContactOrPersonByEmailName
title: ContactOrPersonFromEmailArray FindContactOrPersonByEmailName(String name, String emailAddress)
intellisense: NSEMailAgent.FindContactOrPersonByEmailName
keywords: NSEMailAgent, FindContactOrPersonByEmailName
so.topic: reference
---



**Parameters:**
 - **name** The sender name
 - **emailAddress** The sender email address

**Returns:** Contacts and persons matching emailaddress and name

```crmscript
NSEMailAgent agent;
String name;
String emailAddress;
ContactOrPersonFromEmailArray res = agent.FindContactOrPersonByEmailName(name, emailAddress);
```

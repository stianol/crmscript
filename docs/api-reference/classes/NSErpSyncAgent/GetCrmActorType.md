﻿---
uid: crmscript_ref_NSErpSyncAgent_GetCrmActorType
title: Integer GetCrmActorType(Integer erpConnectionId, Integer erpActorType)
intellisense: NSErpSyncAgent.GetCrmActorType
keywords: NSErpSyncAgent, GetCrmActorType
so.topic: reference
---

Retrieves the CrmActorType that are mapped to a specific ErpActorType for this connection

**Parameters:**
 - **erpConnectionId** The ERP connection ID
 - **erpActorType** The ERP actor type
     - Enum: 0 = Unknown 
     - Enum: 1 = Customer 
     - Enum: 2 = Supplier 
     - Enum: 3 = Partner 
     - Enum: 4 = Person 
     - Enum: 5 = Project 
     - Enum: 6 = Employee 
     - Enum: 7 = Sale 

**Returns:** The CrmActorType

```crmscript
NSErpSyncAgent agent;
Integer erpConnectionId;
Integer erpActorType;
Integer res = agent.GetCrmActorType(erpConnectionId, erpActorType);
```

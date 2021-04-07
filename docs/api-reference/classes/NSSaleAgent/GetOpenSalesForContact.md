﻿---
uid: crmscript_ref_NSSaleAgent_GetOpenSalesForContact
title: SaleArray GetOpenSalesForContact(Integer contactId)
intellisense: NSSaleAgent.GetOpenSalesForContact
keywords: NSSaleAgent, GetOpenSalesForContact
so.topic: reference
---

Returns all open sales for the contact provided.

**Parameters:**
 - **contactId** The ID of the contact whose sales we want.

**Returns:** Aray of sales.

```crmscript
NSSaleAgent agent;
Integer contactId;
SaleArray res = agent.GetOpenSalesForContact(contactId);
```

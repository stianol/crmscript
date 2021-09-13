---
uid: crmscript_ref_NSQuoteAgent_GetAllAvailableQuoteConnections
title: NSQuoteConnection[] GetAllAvailableQuoteConnections()
intellisense: NSQuoteAgent.GetAllAvailableQuoteConnections
keywords: NSQuoteAgent, GetAllAvailableQuoteConnections
so.topic: reference
---

# NSQuoteConnection[] GetAllAvailableQuoteConnections()

Get all available connections. Some installed connections may not be available to the user. Use GetAllAvailableQuoteConnectionsWithPriceLists if you need the pricelists on the connections as well.

**Returns:** NSQuoteConnection[]

```crmscript
NSQuoteAgent agent;
NSQuoteConnection[] res = agent.GetAllAvailableQuoteConnections();
```

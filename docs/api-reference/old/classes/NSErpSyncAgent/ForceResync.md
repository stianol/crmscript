---
uid: crmscript_ref_NSErpSyncAgent_ForceResync
title: NSPluginResponse ForceResync(Integer erpConnectionId, Integer[] internalKeyIds)
intellisense: NSErpSyncAgent.ForceResync
keywords: NSErpSyncAgent, ForceResync
so.topic: reference
---

# NSPluginResponse ForceResync(Integer erpConnectionId, Integer[] internalKeyIds)

Force resync from CRM or given Erp connection to all other connections

**Returns:** NSPluginResponse

## Parameters

| Parameter | Type | Description |
|---|---|---|
| erpConnectionId | Integer | If positive, resync from the given ERP connection |
| internalKeyIds | Integer[] | The internal keys of the entities to resync, or empty to resync all |

## Example

```crmscript
NSErpSyncAgent agent;
Integer erpConnectionId;
Integer[] internalKeyIds;
NSPluginResponse res = agent.ForceResync(erpConnectionId, internalKeyIds);
```
---
uid: crmscript_ref_NSErpSyncAgent_ConnectActor
title: Void ConnectActor(Integer erpConnectionId, Integer crmRecordId, Integer crmActorType, String erpKey, Integer erpActorType, NSErpSyncFieldValue[] fieldValues)
intellisense: NSErpSyncAgent.ConnectActor
keywords: NSErpSyncAgent, ConnectActor
so.topic: reference
---

# Void ConnectActor(Integer erpConnectionId, Integer crmRecordId, Integer crmActorType, String erpKey, Integer erpActorType, NSErpSyncFieldValue[] fieldValues)

Create a link between Erp and Crm and set default values

## Parameters

| erpConnectionId | Integer | ErpConnectionId |
| crmRecordId | Integer | CrmRecordId |
| crmActorType | Integer | The Crm Actor type |
| erpKey | String | |
| erpActorType | Integer | The Erp Actor type |
| fieldValues NSErpSyncFieldValue[] | The Crm Fields |

### crmActorType

* Enum: 0 = Unknown
* Enum: 1 = Contact
* Enum: 2 = Person
* Enum: 3 = Project
* Enum: 4 = Sale

### erpActorType

* Enum: 0 = Unknown
* Enum: 1 = Customer
* Enum: 2 = Supplier
* Enum: 3 = Partner
* Enum: 4 = Person
* Enum: 5 = Project
* Enum: 6 = Employee
* Enum: 7 = Sale
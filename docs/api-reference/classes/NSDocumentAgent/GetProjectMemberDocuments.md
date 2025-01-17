---
uid: crmscript_ref_NSDocumentAgent_GetProjectMemberDocuments
title: NSDocument[] GetProjectMemberDocuments(Integer personId, DateTime startTime, DateTime endTime, Integer count)
intellisense: NSDocumentAgent.GetProjectMemberDocuments
keywords: NSDocumentAgent, GetProjectMemberDocuments
so.topic: reference
---

# NSDocument[] GetProjectMemberDocuments(Integer personId, DateTime startTime, DateTime endTime, Integer count)

Method that returns a specified number of document appointments within a time range. The document appointments belong to the project member specified. 

**Parameters:**
 - **personId** The project member's person id
 - **startTime** The start of the time interval we want appointments from. This will usually be the current time.
 - **endTime** The end of the time interval.
 - **count** The maximum number of appointments that should be returned. -1 means no count restrictions.

**Returns:** NSDocument[]

```crmscript
NSDocumentAgent agent;
Integer personId;
DateTime startTime;
DateTime endTime;
Integer count;
NSDocument[] res = agent.GetProjectMemberDocuments(personId, startTime, endTime, count);
```


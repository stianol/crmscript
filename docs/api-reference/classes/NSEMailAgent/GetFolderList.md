﻿---
uid: crmscript_ref_NSEMailAgent_GetFolderList
title: StringArray GetFolderList(EMailConnectionInfo connectionInfo, Bool includeItemCount)
intellisense: NSEMailAgent.GetFolderList
keywords: NSEMailAgent, GetFolderList
so.topic: reference
---

Retrieve all folders for the mail account. String is separated in sections by the paragraph character.  First section contains the folder delimeter char. Next is folder name. Additional sections may be unread and total items.

**Parameters:**
 - **connectionInfo** All information needed to connect to the mailserver
 - **includeItemCount** If true, unread and total items are added to the foldername separated by a comma

**Returns:** List of available folders as a string array

```crmscript
NSEMailAgent agent;
EMailConnectionInfo connectionInfo;
Bool includeItemCount;
StringArray res = agent.GetFolderList(connectionInfo, includeItemCount);
```

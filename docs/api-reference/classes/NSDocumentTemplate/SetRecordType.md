---
uid: crmscript_ref_NSDocumentTemplate_SetRecordType
title: SetRecordType(NSDocTmplType recordType)
intellisense: NSDocumentTemplate.SetRecordType
keywords: NSDocumentTemplate, GetRecordType
so.topic: reference
---

# SetRecordType(NSDocTmplType recordType)

1 = app, 2 = doc, 3 = email, 4 = fax, 5 = phone, 6 = todo - see EAppntRecordTypes

**Parameter:** 
 - **recordType** NSDocTmplType
     - Enum: 0 = Unknown 
     - Enum: 1 = Appointment 
     - Enum: 2 = Document 
     - Enum: 3 = Email 
     - Enum: 4 = Fax 
     - Enum: 5 = Phone 
     - Enum: 6 = Todo 
     - Enum: 7 = MergeDraft 
     - Enum: 8 = MergeFinal 
     - Enum: 9 = SavedReport 

```crmscript
NSDocumentTemplate thing;
NSDocTmplType recordType;
thing.SetRecordType(recordType);
```


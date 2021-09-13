---
uid: crmscript_ref_NSAppointmentEntity_SetInvitationStatus
title: SetInvitationStatus(Integer invitationStatus)
intellisense: NSAppointmentEntity.SetInvitationStatus
keywords: NSAppointmentEntity, GetInvitationStatus
so.topic: reference
---

# SetInvitationStatus(Integer invitationStatus)

Status if this appointment represents an invitation

**Parameter:** 
 - **invitationStatus** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = None 
     - Enum: 2 = Accepted 
     - Enum: 4 = Hidden 
     - Enum: 5 = Invitation 
     - Enum: 6 = Moved 
     - Enum: 7 = Seen 
     - Enum: 8 = MovedSeen 
     - Enum: 9 = Declined 
     - Enum: 10 = Cancelled 

```crmscript
NSAppointmentEntity thing;
Integer invitationStatus;
thing.SetInvitationStatus(invitationStatus);
```

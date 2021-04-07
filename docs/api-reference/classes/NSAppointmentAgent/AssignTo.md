﻿---
uid: crmscript_ref_NSAppointmentAgent_AssignTo
title: AppointmentEntity AssignTo(Integer appointmentId, ParticipantInfo participant, Integer updateMode)
intellisense: NSAppointmentAgent.AssignTo
keywords: NSAppointmentAgent, AssignTo
so.topic: reference
---

Assigning an appointment to another person.

**Parameters:**
 - **appointmentId** The appointmentId. Both master and child record ids are accepted.
 - **participant** 
 - **updateMode** Update mode for a recurring appointment.
     - Enum: 0 = Unknown 
     - Enum: 1 = OnlyThis 
     - Enum: 2 = ThisAndForward 
     - Enum: 9 = StopRecurrence 

**Returns:** Updated AppointmentEntity

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
ParticipantInfo participant;
Integer updateMode;
AppointmentEntity res = agent.AssignTo(appointmentId, participant, updateMode);
```

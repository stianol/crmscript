---
uid: crmscript_ref_NSUserAgent_ResolveUserFromInfo
title: NSResolvedUser ResolveUserFromInfo(Integer contactId, String personName, String[] phoneNumbers, String[] emails, Integer userType, NSCredential credential)
intellisense: NSUserAgent.ResolveUserFromInfo
keywords: NSUserAgent, ResolveUserFromInfo
so.topic: reference
---

# NSResolvedUser ResolveUserFromInfo(Integer contactId, String personName, String[] phoneNumbers, String[] emails, Integer userType, NSCredential credential)

Get a user from the provided information. If the user or associated person does not exist, it will be created on demand.

## Parameters

* **contactId** The contact Id of the contact which the person belongs to. Cannot be 0.
* **personName** The full name of the person to be resolved. Optional.
* **phoneNumbers** Phone numbers registered on the person. Optional.
* **emails** Email-addresses registered on the person. Optional.
* **userType** The type of user to look up or create.
* **credential** The credentials to be used for the user. Required.

**Returns:** NSResolvedUser

### Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUserAgent agent;
Integer contactId;
String personName;
String[] phoneNumbers;
String[] emails;
Integer userType;
NSCredential credential;
NSResolvedUser res = agent.ResolveUserFromInfo(contactId, personName, phoneNumbers, emails, userType, credential);
```
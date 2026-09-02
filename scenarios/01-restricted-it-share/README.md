# Ticket 01 — Restricted IT Share

## Ticket

**INC0010002 — Unable to access IT shared folder**

Daniel Ortiz reported that he could not access the IT shared folder.

## Investigation

The issue was reproduced from the domain workstation, and Daniel’s Active Directory group membership was reviewed.

Daniel belongs to `GG-Radiology`, while the IT share is restricted to members of `GG-IT`.

## Resolution

No permission changes were made because access was functioning as designed. Maya Chen, a member of `GG-IT`, successfully accessed the share. Daniel Ortiz received Access Denied as expected.

The investigation was documented with internal work notes, and the ServiceNow incident was resolved.

## Evidence

### Department OU Structure

![GHM department OU structure](../../screenshots/13-ghm-department-ou-structure.png)

### IT Shared Folder

![GHM IT shared folder](../../screenshots/18-ghm-it-share-created-and-shared.png)

### Maya Authorized Access

![Maya authorized IT share access](../../screenshots/19-maya-authorized-it-share-access.png)

### Daniel Access Denied

![Daniel denied IT share access](../../screenshots/20-daniel-it-share-access-denied.png)

### Group Membership Verification

![Daniel IT and Radiology group verification](../../screenshots/21-daniel-it-vs-radiology-group-verification.png)

### ServiceNow Investigation Notes

![Daniel ServiceNow investigation work notes](../../screenshots/22-inc0010002-investigation-work-notes.png)

### ServiceNow Resolution

![Daniel ServiceNow ticket resolution](../../screenshots/23-inc0010002-resolved.png)

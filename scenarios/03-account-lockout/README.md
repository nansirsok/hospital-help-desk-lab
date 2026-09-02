# Ticket 03 — Account Lockout

## Ticket

**INC0010005 — Account locked**

Elena Ramirez reported that she could not sign in to `GHM-PC01` because her account was locked.

## Investigation

The domain Account Lockout Policy was reviewed before testing. The lab policy was configured for five invalid logon attempts, with a 15-minute lockout duration and a 15-minute counter-reset period.

A controlled test confirmed that Elena’s account became locked after repeated invalid sign-in attempts.

## Resolution

Elena’s account was reviewed in Active Directory and unlocked by an administrator.

Elena then successfully signed in to `GHM-PC01` using her correct password. The incident was documented and resolved in ServiceNow.

## Evidence

### Account Lockout Policy

![GHM account lockout policy](../../screenshots/28-elena-account-lockout-policy.png)

### Locked Account Message

![Elena account locked message](../../screenshots/29-elena-account-locked.png)

### Locked Account in Active Directory

![Elena locked account in Active Directory](../../screenshots/30-elena-locked-account-ad.png)

### Successful Workstation Login

![Elena successfully signed in to GHM-PC01](../../screenshots/31-elena-successful-login.png)

### ServiceNow Resolution

![Elena account lockout ticket resolved in ServiceNow](../../screenshots/32-elena-account-lockout-resolved.png)

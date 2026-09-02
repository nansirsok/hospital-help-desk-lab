# Ticket 02 — Password Reset

## Ticket

**INC0010004 — Reset my password**

Marcus Lee reported that he could not sign in to `GHM-PC01` after forgetting his password.

## Investigation

Marcus’s identity was verified before making any account changes. His account was located in Active Directory under the Nursing department.

The account was not locked out. The issue was confirmed as a forgotten-password request.

## Resolution

The password was reset in Active Directory, and the account was configured to require a password change at next logon.

Marcus signed in to `GHM-PC01`, changed the temporary password, and confirmed access. The incident was documented and resolved in ServiceNow.

## Evidence

### Password Reset in Active Directory

![Marcus Lee password reset in Active Directory](../../screenshots/24-marcus-password-reset.png)

### Successful Workstation Login

![Marcus Lee successfully signed in to GHM-PC01](../../screenshots/25-marcus-successful-login.png)

### ServiceNow Assignment

![Marcus password-reset ticket assigned to GHM Service Desk](../../screenshots/26-marcus-assigned-ghm-service-desk.png)

### ServiceNow Resolution

![Marcus password-reset ticket resolved in ServiceNow](../../screenshots/27-marcus-password-reset-resolved.png)

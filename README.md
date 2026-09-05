# Gold Harbor Medical — Hospital Help Desk Home Lab

## About This Lab

Gold Harbor Medical is a fictional hospital IT environment I built as a home lab to practice help desk, service desk, system administration, and troubleshooting workflows.

This project demonstrates how common support tasks connect across Active Directory, Windows workstations, shared-folder permissions, account administration, network services, and ticket documentation.

The lab is a work in progress. New completed ticket scenarios will be added over time.

> All organization names, users, systems, and scenarios are fictional. Screenshots are sanitized before being shared.

## Lab Scope

This home lab is used to practice:

- User and account support
- Password resets and account lockouts
- Active Directory administration
- Windows workstation support
- Department organizational units and security groups
- Shared-folder permissions
- Domain user and workstation verification
- Basic DNS and network troubleshooting
- ServiceNow incident documentation
- Troubleshooting notes and resolution records
- Sanitizing technical evidence

## Environment

- Hyper-V virtual machines
- Windows Server 2025 domain controller: `GHM-DC01`
- Windows 11 workstation: `GHM-PC01`
- Active Directory domain: `ghm.test`
- Active Directory Users and Computers
- Department organizational units and security groups
- Group-based shared-folder access
- ServiceNow Personal Developer Instance

## What I Have Practiced

- Configuring a Windows Server domain controller and DNS
- Creating organizational units for hospital departments
- Creating users and department security groups
- Joining a Windows workstation to the domain
- Organizing workstations in Active Directory
- Creating and testing restricted shared folders
- Verifying authorized and denied access
- Resetting a domain user password
- Requiring a password change at next logon
- Verifying successful workstation access
- Creating, documenting, and resolving ServiceNow incidents
- Sanitizing technical screenshots for documentation
- Troubleshooting DNS and workstation network connectivity
- Diagnosing printer queues and Print Spooler issues
- Configuring and testing shared network resources

## Help Desk Workflow

Each ticket scenario follows a basic support workflow:

1. Review the reported issue
2. Verify the user’s identity
3. Reproduce or investigate the problem
4. Make the appropriate administrative change
5. Test the result
6. Document the work in ServiceNow
7. Resolve the incident
8. Add sanitized evidence to the repository

---

## Completed Ticket Scenarios

Each completed ticket has its own folder containing the ticket write-up, investigation, resolution, and evidence links.

1. [Ticket 01 — Restricted IT Share](scenarios/01-restricted-it-share/README.md)
2. [Ticket 02 — Password Reset](scenarios/02-password-reset/README.md)
3. [Ticket 03 — Account Lockout](scenarios/03-account-lockout/README.md)
4. [Ticket 04 — DNS Resolution](scenarios/04-dns-resolution/README.md)
5. [Ticket 05 — Workstation Network Connectivity](scenarios/05-network-connectivity/README.md)
6. [Ticket 06 — Printer Troubleshooting](scenarios/06-printer-troubleshooting/README.md)

---

## Documentation

This repository includes sanitized screenshots and notes documenting the hospital help desk lab as a whole:

- Domain controller and Active Directory setup
- Department organizational units
- Security-group structure
- Domain users and workstation verification
- Shared-folder creation and access testing
- Account and password-support procedures
- ServiceNow investigation notes
- ServiceNow resolution records
- Troubleshooting workflows
- Sanitized portfolio evidence

## Next Steps

- Add more Help Desk ticket scenarios
- Practice software and application troubleshooting
- Practice VPN and remote-access support
- Practice email and Microsoft 365 troubleshooting
- Add documented troubleshooting procedures
- Continue improving the lab as I learn

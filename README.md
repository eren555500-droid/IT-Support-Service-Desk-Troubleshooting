````markdown
# Lab 4 — IT Support Service Desk Troubleshooting

## Overview

A practical IT Support lab focused on troubleshooting common Windows and user-access issues using a structured Service Desk workflow.

## Troubleshooting Method

Each ticket follows:

**Priority → Questions → Scope → Investigation → Hypothesis → Actions → Verification → Result → Escalation**

---

## Ticket 001 — Windows Service Issue

### Scenario

A user reports that a Windows feature or application is not working correctly.

### Investigation

Used:

```text
services.msc
````

Checked:

* Service status
* Startup type
* Service availability

### Action

Started the required Windows service when it was stopped.

### Verification

Tested the affected Windows feature again after starting the service.

### Skills

* Windows Services
* Service troubleshooting
* Windows administration

---

## Ticket 002 — DNS & Network Troubleshooting

### Scenario

A user cannot access a resource using its hostname.

### Investigation

Used:

```cmd
ipconfig /all
ping 8.8.8.8
nslookup google.com
```

Checked:

* IP configuration
* Network connectivity
* DNS resolution

### Action

Used:

```cmd
ipconfig /flushdns
```

to clear the local DNS resolver cache.

### Verification

Retested network connectivity and hostname resolution.

### Skills

* Network troubleshooting
* DNS
* IP configuration
* `ping`
* `nslookup`
* DNS cache troubleshooting

---

## Ticket 003 — Folder Permissions

### Scenario

A user cannot access a company folder after moving to a different department.

### Investigation

Checked:

* User group membership
* NTFS permissions
* Share permissions

### Hypothesis

The user may not belong to the correct security group or may not have the required NTFS/Share permissions.

### Action

Verified the user's group membership and permissions and corrected access when required.

### Verification

The user retested access to the folder.

### Escalation

Escalate when:

* The issue affects multiple users
* Domain configuration is involved
* GPO changes are required
* Administrator/L2 privileges are required
* The issue is outside the IT Support role

### Skills

* NTFS permissions
* Share permissions
* Active Directory groups
* Access control
* User troubleshooting

---

## Key Skills Demonstrated

* Service Desk troubleshooting
* Windows administration
* Network troubleshooting
* DNS troubleshooting
* User and permission management
* NTFS and Share permissions
* Structured incident investigation
* Verification and documentation
* Appropriate escalation

## Conclusion

This lab demonstrates a structured approach to resolving common IT Support incidents from initial user questions through investigation, resolution, verification, and escalation.

```
```

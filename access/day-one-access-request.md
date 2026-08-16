# Day One Access Request

Send this to IT the day the contract is signed. Not the day before kickoff. Access is the single most common reason engagements start late.

---

## The ask, in one paragraph

> To assess the environment I need **read only** access to the systems below. I am not asking for administrative rights and I will not make changes. If a change is ever needed I will request it separately, in writing, with a reason. Where read only is not possible, a screen share with your admin works fine and I will take my own notes.

Say that up front. It removes most of the objection before it forms.

---

## The list

Adjust to what they actually run. Delete what does not apply.

### Identity

| Access | Level | Why |
|---|---|---|
| Microsoft Entra / Google Admin / Okta | Global Reader / Super Admin Read | See users, admins, MFA state, conditional access |
| Sign-in and audit logs | Read | See what normal looks like and whether logging exists |
| Group and role membership | Read | Find who has more than they need |

### Email and collaboration

| Access | Level | Why |
|---|---|---|
| Microsoft 365 / Google Workspace admin console | Read | Sharing settings, external access, forwarding rules |
| Message trace or email log | Read | Spot mail flow rules and forwarding nobody set on purpose |
| SharePoint / Drive sharing report | Read | Find anything shared publicly by accident |

### Devices

| Access | Level | Why |
|---|---|---|
| Intune / Jamf / MDM console | Read | Enrollment count, encryption state, patch level |
| Endpoint protection console | Read | Coverage gaps, alerts nobody is reading |

### Cloud

| Access | Level | Why |
|---|---|---|
| AWS / Azure / GCP | ReadOnlyAccess or Reader | Public exposure, identity sprawl, logging |
| Billing view | Read | Finds accounts and services nobody remembers |

### Network

| Access | Level | Why |
|---|---|---|
| Firewall config export | Read or a file | Inbound rules, any-any rules, VPN config |
| Network diagram | A file is fine | Faster than reverse engineering it |

### Backup

| Access | Level | Why |
|---|---|---|
| Backup console | Read | Coverage, schedule, last successful restore |

### Ticketing and documentation

| Access | Level | Why |
|---|---|---|
| Ticket system | Read | Recurring problems show up here before anywhere else |
| Internal wiki or documentation | Read | Tells you what they think is true |

---

## What to do when read only is not possible

Some systems have no read only role. That is normal. Options in order of preference:

1. **Screen share with the admin.** They drive, you watch and take notes. Slower, but zero risk
2. **They export the config and send it.** Works for firewalls and most consoles
3. **Time boxed elevated access.** Granted for a named window, logged, revoked after. Only if the first two do not work
4. **Skip it and note the gap.** Say in the report that you could not see it. Honest beats guessed

---

## Your side of the deal

Put this in the email. It makes yes easier.

- MFA is on for every account you are given
- Access is used only for the named engagement
- No data leaves their environment except notes and screenshots you need for the report
- You will send a list of every account you were given, and confirm when you are done with each
- On the last day you send a written request to disable all of them

Then actually do it. See `offboarding/handover-checklist.md`.

---

## Track it

| System | Account created | Level | Granted by | Date granted | Date revoked |
|---|---|---|---|---|---|
| | | | | | |

**Why track it:** because the day you finish, you want to hand them this table and say "please disable these seven accounts." Doing that unprompted is the single easiest way to be remembered as the professional one.

# Document Request List

Send this on day one with a single deadline. Mark each line with an owner.

Tell them up front: **"It does not exist" is a perfectly good answer and takes ten seconds to write. Please do not create anything for me.**

---

## Governance and policy

| Document | Why we need it | Owner | Status |
|---|---|---|---|
| Information security policy | Tells us what they claim to do | | |
| Acceptable use policy | The one employees actually sign | | |
| Access control policy | How accounts are meant to be granted | | |
| Incident response plan | What happens on a bad day | | |
| Business continuity or disaster recovery plan | Whether recovery has been thought about | | |
| Data retention policy | How long they keep things | | |
| Vendor or third party policy | Whether vendors are reviewed at all | | |
| Org chart | Who reports to whom, and where security sits | | |

**Watch for:** a policy set downloaded from somewhere, never adapted, never read. The giveaway is a company name that does not match, or a reference to a system they do not run.

---

## Technical

| Document | Why we need it | Owner | Status |
|---|---|---|---|
| Network diagram | Faster than reverse engineering it | | |
| Asset inventory | What they think they have | | |
| Firewall rule export | Inbound exposure, any-any rules | | |
| List of internet facing systems | What an attacker sees first | | |
| Admin account list | The shortest path to real risk | | |
| Backup schedule and last restore test result | Whether recovery is real or theoretical | | |
| Patch or vulnerability report, if one exists | What they already know is broken | | |
| Software inventory or license list | Finds shadow IT | | |

---

## Compliance and assurance

| Document | Why we need it | Owner | Status |
|---|---|---|---|
| Last audit or assessment report | Findings you do not have to rediscover | | |
| Management response to those findings | What they agreed to do | | |
| Any certification currently held | What is genuinely in place | | |
| Customer contracts with security clauses | The obligations that bite first | | |
| Customer security questionnaires received | What buyers are actually asking | | |
| Cyber insurance policy and last application | What was attested to | | |
| Penetration test reports, last two years | Real world exposure | | |

**Ask for the bad ones specifically.** People send the clean report and hold back the one that mattered. Say: "I would rather see the worst one. That is the useful one."

---

## People

| Document | Why we need it | Owner | Status |
|---|---|---|---|
| Onboarding checklist | Whether access is granted deliberately | | |
| Offboarding checklist | Whether access is ever removed | | |
| Security awareness training records | Whether it exists and who skipped it | | |
| Background check policy | For roles with sensitive access | | |
| List of leavers in the last twelve months | Cross reference against active accounts. Always finds something | | |

**The last one is the highest value document on this page.** Comparing leavers against active accounts takes twenty minutes and produces a concrete, undeniable finding almost every time.

---

## Vendors

| Document | Why we need it | Owner | Status |
|---|---|---|---|
| Vendor list, or an AP export | The real list, not the remembered one | | |
| Contracts for the top five vendors | Breach notification terms, data location | | |
| SOC 2 or ISO certificates held on file | Whether anyone reads them | | |
| MSP contract and scope | Where responsibility actually sits | | |

---

## The chase

| Day | Action |
|---|---|
| 0 | Send the list, one email, one deadline, owners marked |
| 3 | Short nudge. "Anything you want me to help with?" |
| 5 | Deadline |
| 6 | Send the gap list to the internal owner, not the sponsor |
| 10 | If still missing, it goes in the status report as blocked, with a name |

**Do not chase quietly forever.** Missing documents are a finding about how the organization runs. Say it kindly, in writing, and move on with what you have.

---

## What missing documents tell you

| Missing | What it usually means |
|---|---|
| No asset inventory | Nobody owns the environment as a whole |
| No offboarding checklist | Old accounts are definitely still active. Go look |
| No restore test | Backups are a theory |
| No vendor list | Shadow IT is significant |
| Policies exist but nobody can find them | They were written for an auditor, not for staff |
| Everything exists and is current | Rare and excellent. Say so in the report. People almost never hear what they are doing well |

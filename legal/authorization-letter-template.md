# Authorization Letter Template

Written permission before you touch anything. Verbal permission is not permission.

**Not legal advice.** Use this as a starting point and have counsel review it.

---

## When you need one

You need written authorization before:

- Any vulnerability scanning, however light
- Any penetration testing
- Any phishing or social engineering simulation
- Any physical access attempt
- Any password auditing or credential testing
- Anything that could look like an attack in a log

You do **not** need one for reading configuration, interviewing people, or reviewing documents. Read only assessment is not testing.

## Why it matters

Computer misuse laws generally turn on authorization. The person granting it must actually have the right to grant it. A well meaning IT manager cannot always authorize testing on a system owned by a landlord, a parent company, or a cloud provider.

If the system is hosted by a third party, you may need their permission too. Ask.

---

## Template

> **AUTHORIZATION TO CONDUCT SECURITY TESTING**
>
> **Date:** [date]
>
> **From:** [Client legal entity name], [address]
>
> **To:** [Consultant legal entity name], [address]
>
> ---
>
> **1. Authorization**
>
> [Client] authorizes [Consultant] to perform the security testing activities described below against the systems described below, during the window described below.
>
> **2. Authorized activities**
>
> The following, and nothing else:
> - [e.g. Unauthenticated vulnerability scanning]
> - [e.g. Authenticated configuration review using accounts provided by Client]
> - [e.g. Phishing simulation to a named list of employees]
>
> **Explicitly not authorized:** denial of service testing, destructive testing, changes to production data, social engineering of any person not on the named list, physical entry, or testing of any system not listed in section 3.
>
> **3. Systems in scope**
>
> | System or asset | Identifier (IP, domain, account) | Owner |
> |---|---|---|
> | | | |
>
> Any asset not listed here is out of scope. If [Consultant] discovers an asset that appears in scope but is not listed, testing will stop and [Client] will be contacted before proceeding.
>
> **4. Window**
>
> Start: [date and time, with timezone]
> End: [date and time, with timezone]
>
> Testing outside this window requires a new written authorization.
>
> **5. Third party systems**
>
> [Client] confirms it either owns the systems in section 3 or has obtained the necessary permission from the owner and hosting provider. [Client] will provide evidence of that permission on request.
>
> **6. Authority**
>
> The signer below confirms they have authority to grant this authorization on behalf of [Client].
>
> **7. Emergency contacts**
>
> If testing causes a problem, [Consultant] will stop immediately and contact:
>
> | Name | Role | Phone | Alternate contact method |
> |---|---|---|---|
> | | | | |
>
> [Consultant] emergency contact: [name, phone]
>
> **8. Notification**
>
> [Client] confirms it has notified its own monitoring team, managed service provider, and any relevant third parties that this testing is authorized, or has deliberately chosen not to in order to test detection. Tick one:
>
> - [ ] Defenders have been notified
> - [ ] Defenders have deliberately not been notified. [Client] accepts the operational risk of a real response being triggered
>
> **9. Handling of findings**
>
> Findings will be reported to [named contact] only. [Consultant] will not disclose findings to any third party without written permission, except where required by law.
>
> ---
>
> **Signed for [Client]**
>
> Name: ________________  Role: ________________
>
> Signature: ________________  Date: ________________
>
> **Signed for [Consultant]**
>
> Name: ________________  Role: ________________
>
> Signature: ________________  Date: ________________

---

## Carry it with you

Keep a copy reachable during testing, on your phone, not only in email. If someone stops you or an alert fires, you want to produce it in seconds. Section 7 exists for exactly that moment.

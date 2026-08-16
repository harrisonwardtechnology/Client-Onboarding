# Access Principles

Why the consultant asks for less than you expect, and how to hold that line when someone offers you more.

---

## 1. Read, not write

You are assessing, not operating. Read access answers every question an assessment asks.

**Why it matters to you:** if you never had write access, you can never be the cause of an outage. That protection is worth more than the convenience of admin.

**Why it matters to them:** a consultant with global admin is a new, temporary, unmonitored super user. That is a real risk they are taking on to hire you. Not asking for it is a gift.

## 2. Named accounts, never shared

Ask for your own account. Refuse the shared admin login, politely.

> "I would rather have my own account, even if it is slower to set up. That way the logs show what I did and what I did not do."

**Why:** attribution protects both sides. If something odd happens during your engagement, everyone wants the logs to be clear.

## 3. Time bound by default

Ask for access to expire, or set a calendar reminder to hand it back.

> "Can we set this to expire in six weeks? If we run long I will ask for an extension."

**Why:** the most common finding in every assessment is old accounts nobody removed. Do not become one.

## 4. MFA on everything, no exceptions

Turn it on for every account they give you, immediately, even if they do not require it.

**Why:** you cannot write "enforce MFA everywhere" in a report while your own account does not have it. It also means a stolen password of yours does not become their incident.

## 5. Least privilege applies to you too

If you need to see one system, ask for one system. Do not accept a bundle because it is easier for IT.

**Why:** every extra permission is something you have to justify later, and something an attacker gets if your laptop is taken. See [Least-Privilege-and-RBAC](https://github.com/HarrisonWard/Least-Privilege-and-RBAC).

## 6. Take nothing you do not need

Screenshots and notes, not exports. If you must export, agree it in writing first, say where it will be stored, and delete it at the end.

**Why:** the fastest way to become your client's breach is to carry their data around. Their data is safest in their environment.

## 7. Say what you will not do

Put it in writing before you start:

- No changes to configuration
- No scanning, probing, or testing without separate written authorization
- No accessing individual employee mailboxes or files without a named business reason and approval
- No copying data out except what is needed for the report

**Why:** ambiguity here is how consultants end up in an uncomfortable conversation about privacy or an unauthorized test. See `legal/authorization-letter-template.md`.

## 8. If they offer you more, ask why

When a client says "just take global admin, it is easier," the right answer is not thank you.

> "I appreciate that, and I would rather not. Read only covers what I need. If it turns out I need more for something specific, I will come back and ask for that thing."

**Why:** you are modelling the behaviour you are about to recommend to them. Advice you do not follow yourself is noise.

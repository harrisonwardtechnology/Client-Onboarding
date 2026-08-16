# Vendor List

Who else touches your data, your money, or your systems. Third parties show up in a large share of breaches, so this list is not admin work. It is the map of your actual attack surface.

**Owner of this form:** finance owns the payment list, IT owns the access list. Do both.

---

## The fast way to build this

Do not try to remember your vendors. Pull the list instead.

1. **Accounts payable.** Export every vendor paid in the last twelve months. This catches the ones nobody remembers
2. **Credit card statements.** This catches the ones bought on somebody's card without procurement
3. **Identity provider.** List every app connected for single sign on
4. **Browser and OAuth grants.** In Microsoft 365 or Google Workspace, list third party apps employees have granted access to
5. **DNS and email records.** Anything sending mail as you is a vendor

Steps 2 and 4 usually find the surprises.

---

## The list

| Vendor | What they do | Do they hold our data? | Do they have access to our systems? | Tier | Contract owner |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## Tiering

Do not review 200 vendors the same way. Tier them, then ask fewer, better questions of the ones that matter.

| Tier | Definition | Review depth |
|---|---|---|
| **Tier 1** | Holds sensitive data, or can reach your systems, or you cannot operate without them | Full review, annually, contract terms, evidence |
| **Tier 2** | Holds some data, or moderate business impact | Short questionnaire, every two years |
| **Tier 3** | No sensitive data, replaceable, low impact | Record it and move on |

**Rule of thumb:** if losing them stops the business, or if they can read customer data, they are Tier 1. Most companies have fewer Tier 1 vendors than they expect. Usually five to fifteen.

---

## The questions worth asking about each Tier 1

| Question | Answer |
|---|---|
| What data of ours do they hold? | |
| Where is it stored, and in which country? | |
| Do they use sub-processors? Who? | |
| Do they have a current SOC 2, ISO 27001, or equivalent? Have you read it, or just noted that it exists? | |
| Does the contract require them to notify you of a breach? Within how long? | |
| Can you get your data out if you leave? In what format? | |
| Who internally owns this relationship? | |
| When does the contract renew? | |

**Why the renewal date:** renewal is the only moment you have leverage to change terms. Knowing the date is half the work.

---

## Special cases people forget

- **Your MSP or IT provider.** Usually the single highest risk vendor. They often have admin everywhere
- **Your payroll and benefits provider.** Holds every employee's identity data
- **Your accountant and bookkeeper.** Often has banking access
- **Marketing tools.** Often hold customer lists and have wide email permissions
- **AI tools.** Anything employees paste work into. See [AI-Governance-Kit](https://github.com/HarrisonWard/AI-Governance-Kit)
- **Anything a single employee signed up for with a card.** This is where shadow IT lives

---

For the full approach, see [TPRM-RightSized](https://github.com/HarrisonWard/TPRM-RightSized).

# Data Map, Light Version

Not a full data inventory. Those take months and usually die halfway. This is the version that fits on two pages and answers the questions that actually come up.

**Owner of this form:** whoever knows the business, not just IT.

---

## 1. What sensitive data do you hold?

Tick what applies.

- [ ] Customer names and contact details
- [ ] Customer financial data (card numbers, bank details)
- [ ] Customer health data
- [ ] Customer identity documents
- [ ] Employee personal data (addresses, dependants, ID numbers)
- [ ] Employee health or benefits data
- [ ] Payroll and compensation data
- [ ] Children's data (under 13, or under 16 in some places)
- [ ] Biometric data (fingerprints, face, voice)
- [ ] Trade secrets, formulas, designs, source code
- [ ] Data belonging to your customers' customers
- [ ] Government or defense related data
- [ ] Nothing much, honestly

**Why:** what you hold decides which laws apply and what a breach would actually cost. Most companies hold more categories than they first say, usually because of employee data.

---

## 2. Where does each type live?

| Data type | Primary location | Backup location | Who can read it | Roughly how many records |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

**Include the messy places:** spreadsheets on desktops, an old file server nobody logs into, a shared mailbox, exports someone made for a report in 2023 and never deleted.

---

## 3. Where does it flow?

For each sensitive type, sketch the path in one line.

> Example: Customer card data goes browser to payment processor directly. We never touch it. Order metadata comes back to our order system.

> Example: Employee health data goes HR to benefits broker by email attachment. This is the one we should fix.

| Data type | Path in one line |
|---|---|
| | |
| | |

**Why:** the flow is where the risk is. Data sitting still is easier to protect than data moving through email attachments.

---

## 4. How long do you keep it?

| Data type | Stated retention | Actual retention | Why |
|---|---|---|---|
| | | | |

**Why:** "actual" is usually "forever." Data you deleted cannot be stolen. Retention is the cheapest security control that exists, and almost nobody uses it.

---

## 5. Three questions to finish

| Question | Answer |
|---|---|
| If a customer asked you to delete all their data, could you? How long would it take? | |
| If you had to tell people about a breach tomorrow, could you say who was affected? | |
| What is the single dataset that would hurt most if it leaked? Where exactly is it? | |

**Why:** the last one focuses everything that comes after. If you only protect one thing well, protect that.

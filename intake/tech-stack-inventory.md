# Tech Stack Inventory

What they run, who runs it, and who can turn it off. Fill in what you know. "Not sure" is a useful answer and tells us where to look.

**Owner of this form:** whoever runs IT day to day.

---

## Identity and email

| Item | Answer |
|---|---|
| What do people sign in with? (Microsoft Entra, Google, Okta, JumpCloud, on-prem AD, other) | |
| Is there more than one identity system? | |
| Where does email live? | |
| Is multi factor authentication on? For everyone, or some people? | |
| Which MFA methods are allowed? (App, SMS, hardware key, push) | |
| How many admin accounts exist? Who has them? | |
| Do admins have a separate account for admin work, or one account for everything? | |
| Are there shared logins anywhere? Be honest, most places have some | |

**Why:** identity is the front door. Most incidents start with a login, not an exploit.

---

## Devices

| Item | Answer |
|---|---|
| How many laptops and desktops? | |
| Windows, Mac, Linux, mix? | |
| Are devices company owned or personal? | |
| Is there device management? (Intune, Jamf, Kandji, other) | |
| Is disk encryption on by default? | |
| What antivirus or endpoint protection is installed? | |
| Do you know when a device is missing a patch? | |
| How many phones access company email? Managed or not? | |

---

## Network and infrastructure

| Item | Answer |
|---|---|
| Do you have offices with your own network gear? How many? | |
| Any servers still on site? What do they do? | |
| Any virtualization? (VMware, Hyper-V, Proxmox) | |
| Firewall vendor and who manages it | |
| Is there a VPN? Who can use it? | |
| Is anything reachable from the internet on purpose? List it | |
| Is anything reachable from the internet by accident? (If unknown, say unknown) | |
| Is there Wi-Fi guests can join? Is it separated from the main network? | |

---

## Cloud

| Item | Answer |
|---|---|
| Which cloud providers? (AWS, Azure, GCP, other) | |
| How many accounts, subscriptions, or projects? | |
| Who has root or global admin? | |
| Is there a bill nobody can explain? (Often a sign of shadow IT) | |
| Any infrastructure as code? Where does it live? | |

---

## Applications and data

| Item | Answer |
|---|---|
| What are your top ten business applications? | |
| Which of them hold customer data? | |
| Which are software as a service, and which do you host? | |
| Where do files live day to day? (SharePoint, Drive, a file server, all three) | |
| Any databases with customer or employee data? Where? | |
| Do you build software? Is it customer facing? Where does the code live? | |

---

## Backup and recovery

| Item | Answer |
|---|---|
| What is backed up? | |
| How often? | |
| Where do backups live? | |
| Are backups reachable with the same credentials as production? | |
| When did you last restore something on purpose? What happened? | |

**Why:** backups nobody has restored are a theory. The restore test is the whole control.

---

## Operational technology and the unusual

Skip if none apply. Do not skip if you are not sure.

| Item | Answer |
|---|---|
| Any factory, plant, or production line equipment? | |
| Any building systems? (HVAC, badge readers, cameras, elevators) | |
| Any lab or medical equipment on the network? | |
| Any vehicles, drones, or field devices? | |
| Anything running an operating system nobody supports anymore? | |
| Who is allowed to touch that equipment? | |

**Why:** this is where "normal IT security" breaks things. Turning off a protocol that looks obsolete can stop a production line. Ask first.

---

## Who runs it

| Function | Internal, MSP, or nobody | Name or vendor |
|---|---|---|
| Help desk | | |
| Servers and cloud | | |
| Network | | |
| Identity and accounts | | |
| Backup | | |
| Security monitoring | | |
| Software development | | |

**Why:** "we have an MSP" is not an answer to "who is responsible when something breaks at 2am." Find out where that line actually is, and whether it is in a contract.

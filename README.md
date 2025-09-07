## **[section 5.1](https://github.com/sherazi1214/-Given-a-scenario/edit/main/README.md)** : Analysis & Remediations and remediation

## 3.1 RBAC (Role-Based Access Control)
### What is RBAC?

**English:**
RBAC is a method of restricting system access based on a user’s role in an organization. Instead of assigning permissions individually, users are grouped into roles (e.g., Admin, HR, Finance) and each role has predefined access rights.

**Urdu:**
RBAC ka matlab hai ke system access user ke role ke hisaab se diya jata hai. Har user ko alag alag permissions dene ke bajaye, unko ek role (Admin, HR, Finance) assign karte hain jisme pehle se defined permissions hoti hain.

### Best Practices

**PoLP (Principle of Least Privilege)**

**English:** Users should only get the minimum access required to perform their job.

**Urdu:** Har user ko sirf utna hi access do jitna unke kaam ke liye zaroori hai.

**JIT (Just-in-Time Access)**

**English:** Grant elevated (admin) access only when needed and for a limited time.

**Urdu:** Admin ya sensitive access sirf jab zaroorat ho aur thode waqt ke liye do, permanent access na rakho.

**Role Reviews**

**English:** Regularly review roles and permissions to avoid privilege creep.

**Urdu:** Har kuch waqt baad roles check karo taake unnecessary rights remove ho jayein.

## 3.2 SDLC (Software Development Life Cycle)
#### What is SDLC?

**English:**
SDLC is a structured process for planning, designing, developing, testing, deploying, and maintaining software. It ensures software is built in a systematic, predictable, and secure way.

**Urdu:**
SDLC ek structured process hai jisme software ko plan, design, develop, test, deploy aur maintain kiya jata hai. Is se software systematic, predictable aur secure banta hai.

### Common Phases of SDLC

Planning & Requirement Gathering

Design (Architecture & Models)

Development (Coding)

Testing (QA, Security testing)

Deployment (Release to production)

Maintenance (Updates, bug fixes)

### Best Practices

**SCR (Secure Coding Review / Secure Code Review)**

**English:** Regularly review code for vulnerabilities (SQL injection, XSS, buffer overflow).

**Urdu:** Code ko review karo taake security flaws (jaise SQL injection, XSS) identify aur fix ho jayein.

**DevSecOps (Development + Security + Operations)**

**English:** Integrate security into every stage of SDLC (not only at the end).

**Urdu:** Sirf end par security check na karo, har stage mein security integrate karo (Dev + Sec + Ops).

**Shift Left Security**

**English:** Start security testing early (during design & coding).

**Urdu:** Security ko early stage par include karo, last step par nahi.


## 3.3 Security Policies & Compliance
#### What are Security Policies?

**English:**
Security policies are formal documents that define rules, responsibilities, and procedures to protect an organization’s information systems. They ensure compliance with laws, regulations, and best practices.

**Urdu:**
Security policies woh formal rules aur procedures hain jo organization ke systems ko protect karne ke liye banayi jati hain. Ye compliance aur best practices ko ensure karti hain.

### Examples of Security Policies

**AUP (Acceptable Use Policy)**

**English:** Defines how employees can use company resources (internet, email, devices). Prevents misuse.

**Urdu:** Yeh policy batati hai ke employees company ke systems aur internet kaise use kar sakte hain aur misuse rokne ke liye rules banati hai.

**Example:** No downloading illegal software, no personal use of company email for scams.

**IRP (Incident Response Plan)**

**English:** A structured process for detecting, responding to, and recovering from security incidents (like malware infection, data breach).

 **Urdu:** Jab koi security incident ho jaye (malware, data breach), to usay handle karne ke liye yeh step-by-step process hota hai.

**Example:** Incident handling steps → Identification → Containment → Eradication → Recovery → Lessons learned.

**DRP (Disaster Recovery Plan)**

**English:** A documented strategy to recover IT systems and data after a major disruption (like fire, flood, cyberattack).

**Urdu:** Agar koi disaster (fire, flood, cyberattack) ho jaye to system aur data ko recover karne ka plan.

**Example:** Backup systems, alternate data centers, recovery time objective (RTO) and recovery point objective (RPO).


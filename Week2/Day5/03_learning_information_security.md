# Day 5 (Friday): Information Security
## Protecting Information and Information Systems

This session covers **information security** – protecting information and information systems from unauthorized access, use, disclosure, disruption, modification, or destruction. It is essential for any organization, especially when using systems like SAP that hold critical business data.

---

## 🎯 Learning Objectives

By the end of this session, you will:
- ✅ Define information security and name its main goals (e.g. confidentiality, integrity, availability)
- ✅ Name the main components: access control, encryption, incident response, security policies
- ✅ Give a simple example of each component
- ✅ Connect security to SAP (e.g. who can see what, protecting data)

---

## Part 1: What Is Information Security?

**Information security** is **protecting information and information systems** from:
- **Unauthorized access** – only the right people/systems can access data
- **Unauthorized use, disclosure** – data is not misused or leaked
- **Disruption, modification, or destruction** – systems and data remain available and correct

It uses a mix of **practices and technologies** to ensure:

| Goal | What it means |
|------|----------------|
| **Confidentiality** | Only authorized people/systems can see the information |
| **Integrity** | Information is accurate and not altered improperly |
| **Availability** | Authorized users can access the information when they need it |

Often called **CIA** (Confidentiality, Integrity, Availability).

---

## Part 2: Components of Information Security

| Component | What it means | Simple example |
|-----------|----------------|----------------|
| **Access control** | Restricting access to information and systems to **authorized users** | User IDs, passwords, roles (e.g. only HR can see salaries) |
| **Encryption** | Converting data into a **coded format** that is unreadable without a decryption key | Encrypting data when sent over the internet or stored on disk |
| **Incident response** | **Detecting, responding to, and recovering from** security incidents (e.g. breach, malware) | Plan: detect → contain → fix → recover → learn |
| **Security policies** | **Guidelines and rules** for managing and protecting information assets | “Passwords must be strong and changed every 90 days”; “No sharing of customer data outside approved systems.” |

### Which Component?

**Scenario:** A company discovers that an ex-employee still has access to the SAP system.  
**Which security component should be checked and improved?** ___________________________________________  
*(Access control – ensuring access is removed when someone leaves.)*

---

## Part 3: Security and SAP

In SAP:
- **Access control** = **authorization** (roles, permissions) – who can run which transactions, see which data.
- **Encryption** = protecting data in transit (e.g. HTTPS, secure connections) and at rest (e.g. encrypted database or storage).
- **Incident response** = having a process when something goes wrong (e.g. suspicious login, data leak).
- **Security policies** = company and SAP security guidelines (e.g. password rules, audit logging).

SAP systems hold financial, HR, and customer data – so **information security** is a core concern for implementation and operation.

---

## 📝 Knowledge Check

1. **What are the three main goals of information security (CIA)?**
   - ___________________________________________

2. **What is “access control” in one sentence?**
   - ___________________________________________

3. **What is encryption used for?**
   - ___________________________________________

4. **What does “incident response” cover?**
   - ___________________________________________

5. **Give one example of how SAP uses access control.**
   - ___________________________________________

---

## 🎉 Key Takeaways

- **Information security** = protecting information and systems from unauthorized access, use, disclosure, disruption, modification, or destruction.
- **CIA** = Confidentiality, Integrity, Availability.
- **Components:** **access control**, **encryption**, **incident response**, **security policies**.
- In **SAP**, these appear as authorization/roles, encryption of data, incident handling, and security and compliance policies.

---

**Next:** [04_exercise_apis_cx_security.md](04_exercise_apis_cx_security.md) – APIs, CX, and security exercise.

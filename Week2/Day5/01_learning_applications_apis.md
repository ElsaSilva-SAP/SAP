# Day 5 (Friday): Applications and APIs
## How Applications Are Built and How They Communicate

Yesterday you covered business requirements, organizational alignment, operating systems, and elastic computing. **Today** we focus on **applications and APIs** – the building blocks of software and how different systems talk to each other. This is the last day of Week 2 morning content before discussions and recap.

---

## 🎯 Learning Objectives

By the end of this session, you will:
- ✅ Explain the main components of an application (front-end, back-end, middleware)
- ✅ Define APIs and why they matter for integration
- ✅ Describe in simple terms how a user request flows (e.g. user → front-end → API → back-end)
- ✅ Give one example of how SAP uses or exposes APIs for integration

---

## 📌 Recap

- **Day 1–2:** SAP product strategy, modules, technical modules, digital transformation.
- **Day 3:** Business processes, mapping, analysis, redesign.
- **Day 4:** Business requirements, organizational alignment, OS, elastic computing.
- **Today:** Applications & APIs, customer experience design, information security, then recap.

---

## Part 1: What Are Applications?

**Applications** are **software programs** that perform specific tasks for users or other programs.

### Main Components

| Component | What it is | Example |
|-----------|------------|---------|
| **Front-end** | The **user interface and experience** – what the user sees and interacts with | Screens, buttons, forms, dashboards (e.g. SAP Fiori apps) |
| **Back-end** | **Server-side logic**, databases, and infrastructure that support the application | Business rules, database, SAP core (e.g. S/4HANA backend) |
| **Middleware** | **Software that connects** different parts – e.g. web servers, application servers, databases | Integration layer, message queues, SAP Integration Suite |
| **APIs** | **Interfaces** that let different software systems **interact and share data** | REST APIs, OData; SAP exposes APIs for other systems to call |

### Simple Flow (Text Diagram)

```
User  →  Front-end (UI)  →  API / Middleware  →  Back-end (logic + database)  →  Response back to user
```

---

## Part 2: What Are APIs?

**APIs (Application Programming Interfaces)** are **sets of protocols and tools** that allow different software applications to **communicate with each other**.

- **In simple terms:** An API is like a **menu and waiter**: you (the calling system) say what you want (e.g. “get order 123”); the other system (via the API) returns the result (order details). You don’t need to know how the kitchen works – only how to ask.
- **Why they matter:** Without APIs, each system would need custom, brittle connections. With APIs, systems can **integrate** in a standard way (e.g. SAP with warehouse, CRM, or e-commerce).

### SAP and APIs

SAP systems **expose APIs** (e.g. OData, REST) so that:
- Other applications can read or update SAP data (e.g. “get customer list,” “create sales order”)
- Mobile apps, web apps, or partner systems can integrate with SAP without touching the core directly
- Integration is more controlled, documented, and secure

---

## 📝 Knowledge Check

1. **What are the four main components of an application (from the session)?**
   - ___________________________________________

2. **What is an API in one sentence?**
   - ___________________________________________

3. **Why do APIs matter for integration?**
   - ___________________________________________

4. **In the flow User → Front-end → ? → Back-end, what usually sits in the middle?**
   - ___________________________________________

5. **Give one example of how SAP uses APIs.**
   - ___________________________________________

---

## 🎉 Key Takeaways

- **Applications** have **front-end** (UI), **back-end** (logic, data), **middleware** (connectivity), and **APIs** (interfaces for other systems).
- **APIs** let different systems **communicate and share data** in a standard way; they are central to **integration**.
- **SAP** exposes APIs so other applications and systems can integrate with SAP in a controlled way.

---

**Next:** [02_learning_customer_experience_design.md](02_learning_customer_experience_design.md) – Customer experience design.

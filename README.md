# 9jaSales — Commerce & Logistics Platform

**A multi-workflow web application for online retail, operations, and delivery coordination.**

**Project:** Independent software development portfolio  
**Developer:** [Isah Abba Namnai](https://github.com/isa9ice)  
**Product website:** [9jaSales](https://9jasales.com)  
**Source:** Maintained separately in a private repository

> This repository is a **public portfolio case study**, not the complete production application. It intentionally contains no private source code, credentials, customer records, or financial data.

## Project overview

9jaSales is a web application project designed to bring together several workflows involved in running an online retail operation: product discovery, shopping, order management, inventory, delivery coordination, and business administration.

Rather than building only a storefront, I structured the application around the needs of several participants—customers, administrators, delivery riders, and operational staff.

## Functionality represented in the codebase

| Area | Application components |
| --- | --- |
| Customer shopping | Product browsing, product details, shopping cart, and checkout interface |
| Orders | Order history, tracking views, invoice generation, and order-management interfaces |
| Inventory | Inventory management, product administration, and stock-related workflows |
| Deliveries | Shipment management, rider dashboard, delivery updates, and proof-of-delivery workflow code |
| Business administration | Staff onboarding, role/permission interfaces, analytics, and operational dashboards |
| Growth | Affiliate dashboard and referral-related features |
| Mobile experience | Responsive navigation and progressive web application (PWA) support |

**Implementation note:** These are capabilities found in the inspected repository. Their deployment, completeness, and live operational status have not been independently verified. Certain financial settlement and security controls remain subject to further validation and remediation.

## Technology stack

- **Frontend:** React 19, TypeScript, Vite, Tailwind CSS, React Router
- **Backend:** Node.js, Express, TypeScript
- **Data and identity:** Firebase Authentication, Cloud Firestore, Firebase Storage
- **Additional libraries:** Recharts for data visualisation, Leaflet for maps, jsPDF for documents, and Socket.IO for real-time functionality
- **Engineering workflow:** Git and GitHub; application configuration and security-rule files are maintained in the private source repository

## Engineering contributions

I worked on the structure and iterative development of an application spanning customer-facing screens and operational workflows. The work represented in this project includes:

1. **Workflow design:** Bringing customer shopping, administrative tasks, delivery management, and staff-related views into one application.
2. **Full-stack integration:** Connecting React interfaces to Firebase-backed data and server-side application routes.
3. **Role-oriented interfaces:** Developing distinct dashboards and navigation for different kinds of users.
4. **Order and inventory flows:** Building interfaces for checkout, order tracking, product management, stock records, and delivery coordination.
5. **Product usability:** Implementing responsive navigation, loading states, user feedback, and installable web-app elements.
6. **Engineering review:** Maintaining project documentation for hardening, operational resilience, and the security issues that must be resolved before relying on financial workflows in production.

## Illustrative application workflow

```text
Customer browses products
          |
       Adds to cart
          |
       Checkout flow
          |
       Order management
          |
   Shipment / rider workflow
          |
    Delivery tracking view
```

This diagram shows a conceptual flow, **not** a guarantee that all stages are integrated or running in production.

## Architecture and documentation

See [Technical Overview](docs/TECHNICAL_OVERVIEW.md) for a high-level summary of the application's components and engineering considerations. The document intentionally omits sensitive implementation details.

## Demo and screenshots

A reviewed set of interface screenshots may be added later. Screenshots must be taken from test or anonymised data; private customer, staff, payment, and business records must never be disclosed.

If you are a recruiter or prospective collaborator, you can request a guided demonstration of the application and discuss specific engineering decisions.

## Contact

**Isah Abba Namnai**  
[GitHub](https://github.com/isa9ice) · [LinkedIn](https://www.linkedin.com/in/isah-abba-namnai-0b3623186/)

---

*This is a portfolio presentation of a continuing software project. No independent claim of production security certification, successful payment settlement, or guaranteed service availability is made here.*

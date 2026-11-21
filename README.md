# Agile Project Delivery & Backlog Management – Aurelia Retail (Jira)

## Project Overview
This repository documents an end-to-end **Agile / Scrum project management and Business Analysis case study** developed in **Atlassian Jira**. 
Starting from a stakeholder kick-off meeting for **Aurelia Retail** (an e-commerce company preparing for peak seasonal traffic), unstructured business requests were translated into a structured backlog, prioritized across sprints, and tracked through delivery.

---

## Business Objectives & Epics
The project scope was organized into **3 core Epics** to align technical execution with business priorities:

1. **Checkout Stability (`KC-13`):** Immediate resolution of critical checkout bugs affecting conversion rates and regression testing on payment methods.
2. **Aurelia Club & Customer Care (`KC-14`):** Design and rollout of a loyalty customer portal (user registration, points balance, active coupons, and real-time shipment tracking) subject to legal privacy compliance.
3. **Commercial BI Reporting (`KC-15`):** Extraction and cleaning of ERP sales/returns flows to automate margin and return-rate reporting for management.

---

## Key BA & PMO Activities Demonstrated
* **Requirements Elicitation & Breakdown:** Translated stakeholder needs into clear **Epics**, **User Stories**, **Tasks**, and **Bugs** with defined priorities (`Highest` to `Lowest`).
* **Dependency & Blocker Management:** Isolated external dependencies—such as flagging the legal approval of Privacy & Marketing texts (`KC-10`) as an active blocker before releasing user registration features (`KC-4`, `KC-11`).
* **Sequential Workflow Execution:** Completed upstream ERP data extraction (`KC-12`) prior to advancing the automated BI dashboard (`KC-3`).
* **Scope Control:** Kept non-urgent future enhancements (e.g., `KC-9` AI virtual size assistant) in the product **Backlog** at low priority to protect Sprint 1 team capacity.

---

## Jira Workspace Views

### 1. Roadmap & Epic Timeline
High-level breakdown of Epics, progress tracking, and Sprint 1 scheduling.
![Timeline](Screenshots/Kickoff%20Aurelia%20Retail%20-%20Timeline.png)

### 2. Active Sprint Board
Kanban workflow tracking (`To Do`, `In working`, `Done`) with Epic labels, priority indicators, and visual blocker flags.
![Board](Screenshots/Kickoff%20Aurelia%20Retail%20-%20Board.png)

### 3. Product Backlog & Epic Panel
Prioritized Sprint 1 backlog, Epic completion bars, and future backlog items separated to prevent scope creep.
![Backlog](Screenshots/Kickoff%20Aurelia%20Retail%20-%20Backlog.png)

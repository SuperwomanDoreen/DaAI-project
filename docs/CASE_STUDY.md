# Industry Case Study: E-Commerce Margin Compression & Customer Retention

**Industry Track:** E-Commerce  
**Stakeholder Audience:** Executive Leadership & Product Management

---

## 1. Executive Context & Problem Statement

Over the last two quarters, top-line gross merchandise value across our multi-category retail marketplace grew by 22%, yet net operating margins compressed significantly. Board-level reviews highlight two urgent commercial threats:

1. **Declining Customer Retention:** 60-day repeat purchase rates among newly acquired customers fell from 34% to 19%.
2. **Escalating Return Leakage:** Product return and refund volume surged across specific categories and regional fulfillment hubs, eroding logistics and restocking margins.

Leadership needs your cross-functional team to investigate the operational and behavioral drivers behind margin leakage and build an intelligent, production-minded solution that enables commercial and operations teams to detect high-risk orders or at-risk customers early enough to intervene.

---

## 2. Available Data Landscape

Internal operational records are distributed across fragmented systems reflecting growth across regional hubs:
* **Core Relational Store:** Historical order, customer, and fulfillment records stored in a multi-table SQLite database (`ecommerce_core.db`).
* **Regional Legacy Exports:** Unstandardized monthly fulfillment and refund spreadsheets exported from regional hub systems (CSV archives).
* **Customer Interaction Logs:** Raw post-purchase support and dispute event streams (`support_events.jsonl`).
* **External Context:** Teams are expected to identify, source, and integrate relevant external public data (such as regional economic indicators, holiday calendars, or logistics/weather disruptions) where it strengthens diagnostic or predictive accuracy.

*Access links to the internal data stores will be shared with your Team Lead upon repository setup.*

---

## 3. Expected Deliverables

Your team owns the end-to-end framing, architecture, product naming, and technical execution. Your team must deliver:

1. **Public GitHub Repository:** Clean, reproducible codebase with a clear `README.md` and setup instructions.
2. **Engineering & Analytical Decision Log (`DECISION_LOG.md`):** Documentation of data reconciliation assumptions, metric definitions, trade-offs, and limitations.
3. **Accessible Working Solution:** A live, interactive product (such as a deployed web application, executive dashboard, or interactive decision tool) that stakeholders can use directly without running local code.
4. **Executive Walkthrough (3 to 5 Minutes):** A recorded video demonstrating the business insights uncovered, the live solution in action, and concrete recommendations for leadership.
# ServiceNow Automated Enterprise Asset Provisioning System

An enterprise-grade IT Service Management (ITSM) automation application engineered on the **ServiceNow Cloud Platform** using event-driven workflows and relational database architectures.

## 📱 Application Architecture & Components

### 1. User Intake UI (Service Catalog)
* **Form Layout:** Developed a responsive data intake module titled `Employee IT Asset Request` hosted inside the native Service Catalog framework.
* **Schema Validation:** Configured granular catalog variables (`device_type` as a Select Box and `business_justification` as Multi-Line Text) to enforce system-wide data integrity.

### 2. Event-Driven Automation Engine (Flow Designer)
* **Trigger Mechanics:** Programmed an institutional execution rule listening continuously for structural Service Catalog submission events.
* **Approval Gates:** Implemented a contextual multi-stage managerial approval matrix to intercept incoming requests and calculate authorization states.
* **Contextual Task Routing:** Engineered a downstream delivery channel that dynamically instantiates a child Catalog Task (`SCTASK`) and automatically dispatches it to the appropriate fulfillment group (`Hardware` assignment group).

## 🧠 Core Engineering Principles Demonstrated
* Enterprise Workflow Choreography & Cloud Systems Infrastructure.
* Relational Database Management & Functional Data Pill Referencing.
* Automated IT Service Delivery Frameworks (ITIL Standards).
*# ServiceNow_asset_request_automation

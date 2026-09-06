<div align="center">

<img src="Architecture/CareSync 360 Logo.png" alt="CareSync 360 Logo" width="220">

# CareSync 360

### ServiceNow Patient Care Management Application

**A custom ServiceNow application for integrated patient care, clinical workflow automation, operational management, and healthcare process visibility.**

`ServiceNow` • `Scoped Application` • `Flow Designer` • `REST API` • `ACL` • `GlideRecord` • `Workspace` • `Reporting`

</div>

---

## 📌 Overview

**CareSync 360** is a custom patient care management application developed on the **ServiceNow platform**.

The application centralizes key patient-care processes including patient registration, admissions, care planning, clinical tasks, bed management, patient handoffs, AI-assisted insights, patient timeline tracking, workflow automation, security, integrations, and reporting.

The project demonstrates an end-to-end ServiceNow application development lifecycle — from requirements and architecture through implementation, REST API development, testing, documentation, and release preparation.

---

## ✨ Key Features

- 👤 Patient registration and patient profile management
- 🏥 Patient admission and discharge management
- 🏢 Department, ward, and bed management
- 🛏️ Hospital bed allocation and availability tracking
- 📋 Care plan management
- ✅ Clinical task management
- 🔄 Patient handoff management
- 🤖 AI-assisted clinical insights
- 🕒 Patient timeline tracking
- ⚙️ Automated healthcare workflows
- 🔐 Role-based access control using ServiceNow ACLs
- 🔌 Scripted REST API integration
- 📊 Reports and dashboards
- 🖥️ ServiceNow workspace experience

---

## 🏗️ System Architecture

CareSync 360 uses a modular ServiceNow architecture connecting the presentation, application, automation, security, integration, and data layers.

<div align="center">

<img src="Architecture/caresync360-architecture.png" alt="CareSync 360 System Architecture" width="900">

</div>

<br>

📄 **[View Complete CareSync 360 Documentation](Architecture/CareSync%20360%20Final%20Documentation.docx)**

---

## 🔄 Patient Care Workflow

```text
Patient Registration
        │
        ▼
Patient Admission
        │
        ▼
Department / Ward / Bed Allocation
        │
        ▼
Care Plan Creation
        │
        ▼
Clinical Task Management
        │
        ▼
Patient Handoff
        │
        ▼
AI-Assisted Insights
        │
        ▼
Patient Timeline Tracking
        │
        ▼
Patient Discharge
```

---

## 🧩 Core Application Modules

| Module | Purpose |
|---|---|
| Patients | Stores and manages patient information |
| Admissions | Manages patient hospital admissions |
| Departments | Maintains hospital department information |
| Wards | Manages wards associated with departments |
| Beds | Tracks hospital beds and their availability |
| Care Plans | Manages patient-specific care plans |
| Clinical Tasks | Tracks clinical activities and tasks |
| Patient Handoffs | Supports patient transfer and handoff workflows |
| AI Insights | Stores AI-assisted clinical insights and recommendations |
| Patient Timeline | Maintains chronological patient-care events |
| Reports | Provides operational and patient-care visibility |
| Administration | Supports application configuration and management |

---

## ⚙️ ServiceNow Development

The application demonstrates practical implementation of core ServiceNow development capabilities:

- Scoped Application Development
- Custom Tables and Fields
- Reference Relationships
- Application Menus and Modules
- Business Rules
- Client Scripts
- UI Policies
- Script Includes
- Flow Designer
- ACL Security
- Roles and User Access
- GlideRecord
- Scripted REST APIs
- REST API Explorer
- Reports and Dashboards
- Workspace Configuration
- Update Sets
- Source Control Integration
- Application Testing

---

## 🔌 REST API Integration

CareSync 360 includes custom **Scripted REST APIs** for exposing application data to external systems.

API resources were implemented and tested for major healthcare entities, including:

```text
Patients
Admissions
Departments
Wards
Beds
Care Plans
Clinical Tasks
Patient Handoffs
AI Insights
Patient Timeline
```

The APIs use structured JSON responses containing information such as:

```json
{
  "result": {
    "success": true,
    "count": 1
  }
}
```

API functionality was validated using the **ServiceNow REST API Explorer**.

---

## 🔐 Security

CareSync 360 implements role-based security using **ServiceNow Access Control Lists (ACLs)**.

Security controls are applied across application tables and operations to control:

```text
Create
Read
Write
Delete
```

The security implementation helps ensure that application data and functionality are accessible only to authorized users and roles.

---

## ⚡ Automation

ServiceNow automation is used to support patient-care processes and reduce manual operations.

The project incorporates:

- Flow Designer
- Business Rules
- Automated record processing
- Patient timeline event generation
- Admission workflow automation
- Bed allocation processing
- Patient-care lifecycle automation

---

## 📊 Reporting

CareSync 360 provides reporting capabilities for monitoring patient-care and hospital operations.

Reports can be used to analyze:

- Patient registrations
- Admissions
- Patient status
- Bed availability
- Care plans
- Clinical tasks
- Patient handoffs
- AI insights
- Patient timeline events
- Operational healthcare information

---

## 🛠️ Technology Stack

| Technology | Usage |
|---|---|
| ServiceNow | Enterprise application platform |
| JavaScript | Server-side and client-side development |
| GlideRecord | ServiceNow database operations |
| Flow Designer | Workflow automation |
| Scripted REST API | External integration layer |
| REST API Explorer | API testing |
| ACL | Application security |
| ServiceNow Workspace | User experience |
| Reports & Dashboards | Analytics and visualization |
| GitHub | Source control and project repository |

---

## 📚 Project Documentation

The repository contains detailed documentation covering the complete project lifecycle.

| # | Document | Description |
|---|---|---|
| 1 | **[Product Requirements Document (PRD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_PRD_1.docx)** | Product objectives, scope, and requirements |
| 2 | **[Business Requirements Document (BRD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_BRD_2.docx)** | Business requirements and project objectives |
| 3 | **[Functional Requirements Specification (FRS)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_FRS_3.docx)** | Functional requirements and expected behavior |
| 4 | **[Technical Requirements Document (TRD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_TRD_4.docx)** | Technical design and implementation requirements |
| 5 | **[Application Functional Design (AFD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_AFD_5.docx)** | Application functional design |
| 6 | **[UI/UX Design Brief](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_UIUX_Design_Brief_6.docx)** | User interface and user experience design |
| 7 | **[Backend Schema Design](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_Backend_Schema_Design_7.docx)** | Backend database and table structure |
| 8 | **[Entity Relationship Diagram (ERD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_ERD_8.docx)** | Entity relationships and data model |
| 9 | **[API Documentation](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_API_Documentation_9.docx)** | REST API design and endpoints |
| 10 | **[Implementation Plan](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_Implementation_Plan_10.docx)** | Implementation phases and development plan |
| 11 | **[Final Project Documentation](Architecture/CareSync%20360%20Final%20Documentation.docx)** | Consolidated CareSync 360 project documentation |

---

## 📂 Repository Structure

```text
CareSync-360/
│
├── Architecture/
│   ├── CareSync 360 Final Documentation.docx
│   ├── CareSync 360 Logo.png
│   └── caresync360-architecture.png
│
├── CareSync 360 – Project Documentation/
│   ├── CareSync_360_AFD_5.docx
│   ├── CareSync_360_API_Documentation_9.docx
│   ├── CareSync_360_BRD_2.docx
│   ├── CareSync_360_Backend_Schema_Design_7.docx
│   ├── CareSync_360_ERD_8.docx
│   ├── CareSync_360_FRS_3.docx
│   ├── CareSync_360_Implementation_Plan_10.docx
│   ├── CareSync_360_PRD_1.docx
│   ├── CareSync_360_TRD_4.docx
│   └── CareSync_360_UIUX_Design_Brief_6.docx
│
├── cbba01012fea8310a55a1d707fa4e3a1/
│   └── ServiceNow application source files
│
├── README.md
│
└── sn_source_control.properties
```

---

## 🧪 Testing

The CareSync 360 application was validated through functional and technical testing covering:

- Application modules
- Database tables
- Reference relationships
- CRUD operations
- Business Rules
- Client-side functionality
- Flow Designer automation
- ACL security
- Role-based access
- Scripted REST APIs
- REST API responses
- Patient lifecycle workflows
- Reports and dashboards
- Source control integration

Testing confirmed that the major application components and workflows operate as expected.

---

## 🚀 Project Lifecycle

The CareSync 360 project follows a structured development lifecycle:

```text
Requirements
     ↓
Functional Design
     ↓
Technical Design
     ↓
Database Design
     ↓
Application Development
     ↓
Security Configuration
     ↓
Workflow Automation
     ↓
REST API Development
     ↓
Reports & Dashboards
     ↓
Testing
     ↓
Documentation
     ↓
Release Preparation
```

---

## 🎯 Project Objective

The objective of CareSync 360 is to demonstrate how the **ServiceNow platform** can be used to build a structured healthcare workflow application that integrates patient management, clinical operations, automation, security, reporting, and external API capabilities within a single scoped application.

---

## 👨‍💻 Developer

**Senthilbalaji M**

ServiceNow Developer | Electronics & Communication Engineer

**ServiceNow Certifications**

- Certified System Administrator (CSA)
- Certified Application Developer (CAD)

---

## 📌 Project Status

```text
Application Development      ✅ Completed
Database Configuration       ✅ Completed
Security & ACLs              ✅ Completed
Workflow Automation          ✅ Completed
REST API Development         ✅ Completed
Reports & Dashboards         ✅ Completed
Functional Testing           ✅ Completed
Technical Testing            ✅ Completed
Documentation                ✅ Completed
Source Control               ✅ Completed
Release Preparation          ✅ Completed
```

**Current Status: Completed**

---

<div align="center">

### CareSync 360

**Integrated Patient Care Management on ServiceNow**

*Designed and developed as a complete ServiceNow application development project.*

</div>

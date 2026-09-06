<div align="center">

<img src="Architecture/CareSync%20360%20Logo.png" alt="CareSync 360 Logo" width="220"/>

# CareSync 360

### ServiceNow Patient Care Management Application

**A custom ServiceNow application for integrated patient care, clinical workflow automation, operational management, and healthcare process visibility.**

`ServiceNow` • `Scoped Application` • `Flow Designer` • `REST API` • `ACL` • `GlideRecord` • `Workspace` • `Reporting`

</div>

---

## 📌 Overview

**CareSync 360** is a custom patient care management application developed on the **ServiceNow platform**.

The application centralizes key patient-care processes including patient registration, admissions, care planning, clinical tasks, bed management, patient handoffs, AI-assisted insights, patient timeline tracking, workflow automation, security, integrations, and reporting.

The project demonstrates an end-to-end ServiceNow application development lifecycle — from requirements and architecture through implementation, REST API development, testing, and release preparation.

---

## ✨ Core Features

- 👤 Patient registration and management
- 🏥 Patient admission and discharge management
- 🛏️ Department, ward, and bed management
- 📋 Care plan management
- ✅ Clinical task management
- 🔄 Patient handoff management
- 🕒 Patient timeline tracking
- 🧠 AI insight management
- ⚙️ Automated workflows using Flow Designer
- 🔔 Automated notifications
- 🔐 Role-based security and ACLs
- 📊 Reports and dashboards
- 🔌 Scripted REST API integration
- 🖥️ ServiceNow workspace experience

---

## 🏗️ System Architecture

CareSync 360 uses a modular ServiceNow architecture connecting the presentation, application, automation, security, integration, and data layers.

<p align="center">
  <img src="Architecture/caresync360-architecture.png" alt="CareSync 360 System Architecture" width="900"/>
</p>

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
Care Plan
        │
        ▼
Clinical Tasks
        │
        ▼
Patient Handoff
        │
        ▼
AI Insights / Patient Timeline
        │
        ▼
Discharge & Care Completion
```

---

## 🛠️ ServiceNow Technology Stack

| Area | Implementation |
|---|---|
| Platform | ServiceNow |
| Application Model | Scoped Application |
| Data Layer | Custom Tables & Reference Relationships |
| Server-Side Logic | Business Rules, Script Includes, GlideRecord |
| Client-Side Logic | Client Scripts |
| Automation | Flow Designer |
| Security | Roles & Access Control Lists (ACLs) |
| Integration | Scripted REST APIs |
| API Testing | REST API Explorer |
| User Experience | Forms, Lists & Workspace |
| Notifications | ServiceNow Notifications |
| Analytics | Reports & Dashboards |
| Configuration Management | Update Sets |
| Source Control | GitHub |

---

## 🗃️ Application Modules

CareSync 360 includes modules supporting the major areas of the patient-care lifecycle.

Key functional areas include:

`Patients` • `Admissions` • `Care Plans` • `Clinical Tasks` • `Departments` • `Wards` • `Beds` • `Patient Handoffs` • `AI Insights` • `Patient Timeline` • `Reports`

---

## 🔌 REST API

CareSync 360 contains custom **Scripted REST APIs** for exposing application data and supporting external integrations.

API functionality was developed and validated using ServiceNow's **REST API Explorer**.

Major API resources include:

- Patients
- Admissions
- Care Plans
- Clinical Tasks
- Beds
- Patient Handoffs
- AI Insights
- Patient Timeline

📄 **[View REST API Documentation](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_API_Documentation_9.docx)**

---

## 🔐 Security

CareSync 360 implements role-based application security using ServiceNow security capabilities.

The security model includes:

- Custom application roles
- Table-level ACLs
- Record access restrictions
- Role-based module access
- Controlled CRUD operations
- REST API authorization
- Scoped application security

---

## ⚙️ Automation

ServiceNow **Flow Designer** is used to automate key patient-care and operational processes.

Automation is integrated with application records to reduce manual activities and maintain consistent workflow execution across the patient-care lifecycle.

---

## 📊 Reports & Analytics

The application includes reporting capabilities for monitoring patient-care and operational information.

Reporting areas include:

- Patient information
- Admissions
- Care plans
- Clinical tasks
- Bed availability
- Patient handoffs
- AI insights
- Patient timeline information
- Operational metrics

---

## 🧪 Testing & Validation

CareSync 360 underwent structured functional and end-to-end testing.

Testing covered:

`Tables` • `Forms` • `References` • `Roles` • `ACLs` • `Business Rules` • `Client Scripts` • `Script Includes` • `Flows` • `Notifications` • `Workspace` • `Reports` • `REST APIs`

The implemented application components were validated through the complete patient-care workflow.

---

# 📚 Project Documentation

Complete engineering and application documentation is maintained within this repository.

| # | Document | Description |
|---:|---|---|
| 01 | **[Product Requirements Document (PRD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_PRD_1.docx)** | Product objectives, scope, requirements and expected capabilities |
| 02 | **[Business Requirements Document (BRD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_BRD_2.docx)** | Business requirements and application objectives |
| 03 | **[Functional Requirements Specification (FRS)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_FRS_3.docx)** | Functional behavior and application requirements |
| 04 | **[Technical Requirements Document (TRD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_TRD_4.docx)** | Technical architecture and implementation requirements |
| 05 | **[Application Functional Design (AFD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_AFD_5.docx)** | Functional design of the CareSync 360 application |
| 06 | **[UI/UX Design Brief](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_UIUX_Design_Brief_6.docx)** | User experience and interface design guidance |
| 07 | **[Backend Schema Design](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_Backend_Schema_Design_7.docx)** | Backend tables, fields, references and data architecture |
| 08 | **[Entity Relationship Diagram (ERD)](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_ERD_8.docx)** | Application entities and database relationships |
| 09 | **[REST API Documentation](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_API_Documentation_9.docx)** | REST resources, integration design and API details |
| 10 | **[Implementation Plan](CareSync%20360%20%E2%80%93%20Project%20Documentation/CareSync_360_Implementation_Plan_10.docx)** | Application implementation and delivery plan |
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
│   ├── CareSync_360_PRD_1.docx
│   ├── CareSync_360_BRD_2.docx
│   ├── CareSync_360_FRS_3.docx
│   ├── CareSync_360_TRD_4.docx
│   ├── CareSync_360_AFD_5.docx
│   ├── CareSync_360_UIUX_Design_Brief_6.docx
│   ├── CareSync_360_Backend_Schema_Design_7.docx
│   ├── CareSync_360_ERD_8.docx
│   ├── CareSync_360_API_Documentation_9.docx
│   └── CareSync_360_Implementation_Plan_10.docx
│
├── cbba01012fea8310a55a1d707fa4e3a1/
│   └── ServiceNow application source files
│
├── sn_source_control.properties
│
└── README.md
```

> The ServiceNow-generated application source files and `sn_source_control.properties` are retained for application source-control compatibility.

---

## 🚀 Development Lifecycle

The project followed a structured ServiceNow development lifecycle covering:

```text
Requirements & Planning
        ↓
Application Architecture
        ↓
Data Model & Tables
        ↓
Roles & Security
        ↓
Forms & User Experience
        ↓
Business Logic
        ↓
Flow Automation
        ↓
Notifications
        ↓
Workspace
        ↓
Reports & Dashboards
        ↓
REST API Development
        ↓
Functional & End-to-End Testing
        ↓
Release Preparation
        ↓
Documentation & Source Control
```

---

## 🎯 Project Purpose

CareSync 360 was developed as a **portfolio and learning project** to demonstrate practical end-to-end ServiceNow application development using a healthcare-oriented use case.

It demonstrates experience across:

- ServiceNow application architecture
- Data modeling
- Business logic
- Workflow automation
- Platform security
- REST integrations
- Workspace development
- Reporting
- Testing
- Technical documentation
- Source control

> **Disclaimer:** CareSync 360 is an educational and portfolio project. It is not intended for use as a production clinical system or for making medical decisions.

---

## 👨‍💻 Developer

### Senthilbalaji M

**ServiceNow Developer | PCB & Hardware Designer | RF & Antenna Engineer | Embedded Designer**

### ServiceNow Certifications

- **Certified System Administrator (CSA)**
- **Certified Application Developer (CAD)**

---

## 🔗 Connect

<p align="left">

<a href="https://www.linkedin.com/in/senthilbalajim/">
<img src="https://img.shields.io/badge/LinkedIn-Senthilbalaji%20M-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</p>

---

<div align="center">

### CareSync 360

**Integrated • Secure • Automated • Patient-Centric**

*Built on ServiceNow*

</div>

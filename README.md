# Digital Document Verification System (DDVS)
### Software Engineering Laboratory Practical File (B.Tech Computer Science & Engineering)

[![Project Status](https://img.shields.io/badge/Status-Completed%20(Labs%2001--10)-brightgreen.svg)]()
[![Academic Standard](https://img.shields.io/badge/Standard-IEEE%20%2F%20OMG%20UML%202.5-blue.svg)]()
[![Repository](https://img.shields.io/badge/GitHub-divyakumari7%2FDigital--Document--Verification--System-17365D.svg)](https://github.com/divyakumari7/Digital-Document-Verification-System)

---

## 1. Project Overview
The **Digital Document Verification System (DDVS)** is a web-based software application designed to eliminate credential fraud, unauthorized document tampering, and protracted manual qualification checks. 

Authorized issuing organizations (universities, boards, corporate institutions) register electronic documents alongside cryptographic SHA-256 integrity hashes, generating a unique Verification ID and QR code. Verifiers (employers, academic evaluators, public users) can instantaneously verify document authenticity through:
1. Alphanumeric Verification ID lookup.
2. QR Code scanning via camera or mobile scanner.
3. Electronic document file upload with real-time SHA-256 hash comparison.

The system deterministically evaluates credentials against four definitive outcomes: **`Verified`**, **`Tampered`**, **`Invalid`**, or **`Not Found`**, while maintaining an immutable, append-only verification audit ledger.

---

## 2. Academic Project Information
- **Course**: Bachelor of Technology (B.Tech) in Computer Science and Engineering
- **Subject**: Software Engineering Laboratory
- **Institution**: Department of Computer Science and Engineering, KIET Group of Institutions (KIET Deemed to be University)
- **Project Authors**:
  - Divya Kumari (University Roll No: `202401100200133`)
  - Divyanshi Jaiswal (University Roll No: `202401100200134`)
  - Divyanshi Khemani (University Roll No: `202401100200135`)
  - Divyanshu Gupta (University Roll No: `202401100200136`)
- **Baseline Specification**: IEEE-Standard Software Requirements Specification v1.0 (Dated: August 31, 2026)

---

## 3. Practical Laboratory Experiments Index (Labs 01 – 10)

All ten software engineering laboratory experiments have been systematically completed, rigorously validated against the original SRS baseline, and documented with editable source models (`.drawio`), publication-grade vector documents (`.pdf`), and high-resolution graphics (`.png`):

| Lab # | Experiment Title | Core Focus & Methodology | Primary Deliverables | Status |
| :---: | :--- | :--- | :--- | :---: |
| **[Lab 01](Lab-01-SRS/)** | **Software Requirements Specification (SRS)** | IEEE 830/29148 Standard SRS defining 49 functional requirements, external interfaces, data dictionaries, and constraints. | [`README.md`](Lab-01-SRS/README.md), [`SRS_FINAL.pdf`](Lab-01-SRS/SRS_Digital_Document_Verification_System_FINAL.pdf) | **COMPLETED** |
| **[Lab 02](Lab-02-Use-Case-Diagram/)** | **UML Use Case Diagram** | Actor identification (`Verifier`, `Issuing Organization`, `Administrator`), 9 use cases, and `<<include>>` hash checking relationship. | [`README.md`](Lab-02-Use-Case-Diagram/README.md), [`.drawio`](Lab-02-Use-Case-Diagram/DDVS_Lab02_Use_Case_Diagram.drawio), [`.pdf`](Lab-02-Use-Case-Diagram/DDVS_Lab02_Use_Case_Diagram.pdf), [`.png`](Lab-02-Use-Case-Diagram/DDVS_Lab02_Use_Case_Diagram.png) | **COMPLETED** |
| **[Lab 03](Lab-03-Class-Diagram/)** | **Class Identification & UML Class Diagram** | 6 classes (`User`, `IssuingOrg`, `Admin`, `Document`, `VerificationRequest`, `VerificationLog`), 3 compartments, inheritance, multiplicities. | [`README.md`](Lab-03-Class-Diagram/README.md), [`.drawio`](Lab-03-Class-Diagram/DDVS_Lab03_Class_Diagram.drawio), [`.pdf`](Lab-03-Class-Diagram/DDVS_Lab03_Class_Diagram.pdf), [`.png`](Lab-03-Class-Diagram/DDVS_Lab03_Class_Diagram.png) | **COMPLETED** |
| **[Lab 04](Lab-04-Activity-Diagram/)** | **UML Activity Diagram** | Partitioned swimlanes (`Verifier` vs `DDVS System`), decision trees for record lookup, hash comparison bypass, and status check. | [`README.md`](Lab-04-Activity-Diagram/README.md), [`.drawio`](Lab-04-Activity-Diagram/DDVS_Lab04_Activity_Diagram.drawio), [`.pdf`](Lab-04-Activity-Diagram/DDVS_Lab04_Activity_Diagram.pdf), [`.png`](Lab-04-Activity-Diagram/DDVS_Lab04_Activity_Diagram.png) | **COMPLETED** |
| **[Lab 05](Lab-05-Data-Flow-Diagram/)** | **Data Flow Diagrams (Level 0 & Level 1)** | Context Diagram (Level 0) and Level 1 decomposition into 4 processes (`1.0`–`4.0`), 3 data stores (`D1`–`D3`), and formal balancing matrix. | [`README.md`](Lab-05-Data-Flow-Diagram/README.md), [Context `.drawio`/`.pdf`/`.png`](Lab-05-Data-Flow-Diagram/DDVS_Lab05_Context_Diagram.drawio), [Level 1 `.drawio`/`.pdf`/`.png`](Lab-05-Data-Flow-Diagram/DDVS_Lab05_Level1_DFD.drawio) | **COMPLETED** |
| **[Lab 06](Lab-06-Sequence-Diagram/)** | **UML Sequence Diagram** | Chronological interaction across 4 participants (`Verifier`, `Web Client`, `App Server`, `Database`) with `alt` combined fragment. | [`README.md`](Lab-06-Sequence-Diagram/README.md), [`.drawio`](Lab-06-Sequence-Diagram/DDVS_Lab06_Sequence_Diagram.drawio), [`.pdf`](Lab-06-Sequence-Diagram/DDVS_Lab06_Sequence_Diagram.pdf), [`.png`](Lab-06-Sequence-Diagram/DDVS_Lab06_Sequence_Diagram.png) | **COMPLETED** |
| **[Lab 07](Lab-07-State-Transition-Diagram/)** | **UML State Machine Diagram** | Verification request session lifecycle: 6 states, deterministic guard transitions, 4 discrete terminal outcomes, and audit commitment. | [`README.md`](Lab-07-State-Transition-Diagram/README.md), [`.drawio`](Lab-07-State-Transition-Diagram/DDVS_Lab07_State_Transition_Diagram.drawio), [`.pdf`](Lab-07-State-Transition-Diagram/DDVS_Lab07_State_Transition_Diagram.pdf), [`.png`](Lab-07-State-Transition-Diagram/DDVS_Lab07_State_Transition_Diagram.png) | **COMPLETED** |
| **[Lab 08](Lab-08-Component-Diagram/)** | **UML Component Diagram** | 7 logical subsystems across 3 architectural tiers, provided/required interfaces (`IAccountService`, `IVerificationService`, `IDataAccess`). | [`README.md`](Lab-08-Component-Diagram/README.md), [`.drawio`](Lab-08-Component-Diagram/DDVS_Lab08_Component_Diagram.drawio), [`.pdf`](Lab-08-Component-Diagram/DDVS_Lab08_Component_Diagram.pdf), [`.png`](Lab-08-Component-Diagram/DDVS_Lab08_Component_Diagram.png) | **COMPLETED** |
| **[Lab 09](Lab-09-Design-Analysis-Report/)** | **Software Design Analysis Report** | Comprehensive academic report evaluating 3-Tier Architecture, Modularity, Functional Cohesion, Loose Coupling, Scalability, and Security. | [`README.md`](Lab-09-Design-Analysis-Report/README.md), [Formal PDF Report](Lab-09-Design-Analysis-Report/DDVS_Lab09_Design_Analysis_Report.pdf), [Architecture `.drawio`/`.pdf`/`.png`](Lab-09-Design-Analysis-Report/DDVS_Lab09_Architecture_Diagram.drawio) | **COMPLETED** |
| **[Lab 10](Lab-10-Software-Metrics-and-Complexity/)** | **Software Metrics & Complexity Analysis** | McCabe Cyclomatic Complexity ($V(G) = 5$, 5 basis paths, Control Flow Graph), honest design-stage LOC analysis, CK OO metrics suite. | [`README.md`](Lab-10-Software-Metrics-and-Complexity/README.md), [Formal PDF Report](Lab-10-Software-Metrics-and-Complexity/DDVS_Lab10_Software_Metrics_Report.pdf), [CFG `.drawio`/`.pdf`/`.png`](Lab-10-Software-Metrics-and-Complexity/DDVS_Lab10_Control_Flow_Graph.drawio) | **COMPLETED** |

---

## 4. Repository Directory Structure

```
Digital-Document-Verification-System/
│
├── README.md                                          # Master Project & Laboratory Index (This Document)
│
├── Lab-01-SRS/                                        # Lab 01: Software Requirements Specification
│   ├── README.md
│   └── SRS_Digital_Document_Verification_System_FINAL.pdf
│
├── Lab-02-Use-Case-Diagram/                           # Lab 02: UML Use Case Modeling
│   ├── README.md
│   ├── DDVS_Lab02_Use_Case_Diagram.drawio
│   ├── DDVS_Lab02_Use_Case_Diagram.pdf
│   └── DDVS_Lab02_Use_Case_Diagram.png
│
├── Lab-03-Class-Diagram/                              # Lab 03: Class Identification & Classification
│   ├── README.md
│   ├── DDVS_Lab03_Class_Diagram.drawio
│   ├── DDVS_Lab03_Class_Diagram.pdf
│   └── DDVS_Lab03_Class_Diagram.png
│
├── Lab-04-Activity-Diagram/                           # Lab 04: UML Activity Modeling & Verification Flow
│   ├── README.md
│   ├── DDVS_Lab04_Activity_Diagram.drawio
│   ├── DDVS_Lab04_Activity_Diagram.pdf
│   └── DDVS_Lab04_Activity_Diagram.png
│
├── Lab-05-Data-Flow-Diagram/                          # Lab 05: Structured Analysis & Data Flow Modeling
│   ├── README.md
│   ├── DDVS_Lab05_Context_Diagram.drawio
│   ├── DDVS_Lab05_Context_Diagram.pdf
│   ├── DDVS_Lab05_Context_Diagram.png
│   ├── DDVS_Lab05_Level1_DFD.drawio
│   ├── DDVS_Lab05_Level1_DFD.pdf
│   └── DDVS_Lab05_Level1_DFD.png
│
├── Lab-06-Sequence-Diagram/                           # Lab 06: UML Interaction & Sequence Modeling
│   ├── README.md
│   ├── DDVS_Lab06_Sequence_Diagram.drawio
│   ├── DDVS_Lab06_Sequence_Diagram.pdf
│   └── DDVS_Lab06_Sequence_Diagram.png
│
├── Lab-07-State-Transition-Diagram/                   # Lab 07: UML State Machine Modeling
│   ├── README.md
│   ├── DDVS_Lab07_State_Transition_Diagram.drawio
│   ├── DDVS_Lab07_State_Transition_Diagram.pdf
│   └── DDVS_Lab07_State_Transition_Diagram.png
│
├── Lab-08-Component-Diagram/                          # Lab 08: UML Component Architecture & Interfaces
│   ├── README.md
│   ├── DDVS_Lab08_Component_Diagram.drawio
│   ├── DDVS_Lab08_Component_Diagram.pdf
│   └── DDVS_Lab08_Component_Diagram.png
│
├── Lab-09-Design-Analysis-Report/                     # Lab 09: Software Design Analysis Report
│   ├── README.md
│   ├── DDVS_Lab09_Design_Analysis_Report.pdf          # 5-Page Formal Academic Report (ReportLab)
│   ├── DDVS_Lab09_Architecture_Diagram.drawio
│   ├── DDVS_Lab09_Architecture_Diagram.pdf
│   └── DDVS_Lab09_Architecture_Diagram.png
│
└── Lab-10-Software-Metrics-and-Complexity/            # Lab 10: Software Measurement & Complexity
    ├── README.md
    ├── DDVS_Lab10_Software_Metrics_Report.pdf         # 5-Page Formal Academic Report (ReportLab)
    ├── DDVS_Lab10_Control_Flow_Graph.drawio
    ├── DDVS_Lab10_Control_Flow_Graph.pdf
    └── DDVS_Lab10_Control_Flow_Graph.png
```

---

## 5. Modeling Standards and Verification Methodology
- **UML Standard**: Strictly complies with OMG UML Specification version 2.5.
- **Structured Analysis**: Adheres to Yourdon & DeMarco / Gane & Sarson DFD balancing standards.
- **Cryptographic Grounding**: Employs industry-standard SHA-256 for deterministic, collision-resistant document integrity validation.
- **Audit Compliance**: Enforces synchronous audit trail persistence across all verification pathways prior to user verdict delivery.
- **Diagram Portability**: All `.drawio` files utilize standard, uncompressed XML compatible with [diagrams.net](https://app.diagrams.net). Vector PDFs and high-resolution 300 DPI PNGs are included for immediate academic evaluation.

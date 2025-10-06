# SOC2 IT Risk Register

This repository contains a **sample IT Risk Register** created as part of a **Governance, Risk, and Compliance (GRC) home lab**.  
It demonstrates how to identify, assess, and map IT and cloud infrastructure risks to **NIST Cybersecurity Framework (CSF)** and **SOC 2 Trust Services Criteria** — with cross-references to **NIST SP 800-53** and **ISO/IEC 27001** controls.

---

## 📂 Contents
| File | Description |
|------|--------------|
| **SOC2_Risk_Register_Sample.xlsx** | Complete IT risk register (Excel format) with risks, controls, residual risk, and framework mappings. |
| **Overview (Sheet)** | Explains scoring methodology and CSF informative references. |

---

## 🎯 Project Objectives
- Perform a **qualitative IT risk assessment** (impact × likelihood)
- Document **existing security controls** and **residual risk**
- Map risks to **NIST CSF** and **SOC 2 Trust Services Criteria**
- Demonstrate **audit readiness** and **control alignment**
- Showcase understanding of **CSF Informative References**

---

## 🧩 Key Features
| Category | Description |
|-----------|--------------|
| **Frameworks Used** | NIST Cybersecurity Framework (CSF), SOC 2 Trust Services Criteria |
| **Informative References** | NIST SP 800-53, ISO/IEC 27001 |
| **Control Mapping** | PR, ID, RS functions mapped to real IT risks |
| **Risk Analysis** | Qualitative impact and likelihood scoring |
| **Residual Risk Tracking** | Evaluates effectiveness of existing controls |

---

## 🧠 Example Risk Entries

| Risk ID | Risk Description | Framework Reference | CSF Informative Reference |
|----------|------------------|----------------------|-----------------------------|
| R-002 | Misconfigured S3 bucket may lead to exposure of sensitive data | NIST CSF PR.AC-5 / SOC 2 CC6.6 | NIST SP 800-53: AC-3, AC-6 / ISO 27001: A.9.2.3 |
| R-005 | No formal incident response plan may delay recovery | NIST CSF RS.RP-1 / SOC 2 CC7.4 | NIST SP 800-53: IR-1 / ISO 27001: A.16.1.1 |

---

## 🧮 Risk Scoring Methodology
- **Impact:** Low / Medium / High (business disruption or data loss potential)  
- **Likelihood:** Low / Medium / High (probability of occurrence)  
- **Inherent Risk:** Calculated before controls  
- **Residual Risk:** Evaluated after controls are applied  

---

## 🧰 Skills Demonstrated
- IT Risk Assessment & Documentation  
- Control Mapping (NIST CSF, SOC 2, ISO 27001)  
- Governance and Policy Alignment  
- Audit Readiness & Compliance Reporting  
- Excel-Based Data Analysis  

---

## 💻 Tools & Technologies
- Microsoft Excel  
- AWS (used in sample controls)  
- Nessus / WSUS (example tools in control column)  
- NIST CSF & 800-53 Reference Guides  

---

## 🧠 How to Use
1. Download **SOC2_Risk_Register_Sample.xlsx**  
2. Review the **Risk Register** tab  
3. Read the **Overview** sheet for methodology  
4. Customize risks and mappings for your organization or learning environment  

---

## 📈 Future Improvements
- Add Power BI visualization for risk heat map  
- Automate risk scoring via Python script  
- Integrate with a GRC platform (ServiceNow, LogicGate, or Drata)

---

## 👤 Author
**Andrei Sims**  
Cloud & Network Support Technician | GRC Practitioner  
🔗 [LinkedIn](https://linkedin.com/in/andrei-sims-ab040426/) • [GitHub](https://github.com/andreisims)

This project is provided for **educational and portfolio purposes** only and does not represent an official risk register for any organization.


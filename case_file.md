# Case Study

**Applying the NIST Cybersecurity Framework to Helios Health Analytics Inc**

---

## 1. Organizational Overview

Helios Health Analytics Inc is a privately held, growth stage software company that provides AI driven clinical risk analytics to mid sized hospitals and private healthcare providers.

The organization delivers a cloud based platform that ingests patient and operational data and produces predictive insights used by clinical and operational leaders to anticipate patient deterioration, manage ICU capacity, and reduce readmissions.

While Helios does not provide clinical care, its outputs directly influence medical decision making. As a result, the integrity, availability, and confidentiality of its systems and data are critical to both business performance and patient safety.

---

## 2. Business Context and Objectives

Helios operates under a subscription based B2B SaaS model. Its primary business objectives are:

* Maintain continuous service availability to clinical customers
* Protect sensitive patient and hospital data
* Preserve the confidentiality of proprietary AI models
* Demonstrate regulatory and contractual trustworthiness to customers

Customer retention and revenue growth are strongly tied to Helios’ reputation as a reliable and secure data processor.

---

## 3. Organizational Structure and Resources

Helios employs approximately 85 staff across engineering, data science, operations, and commercial functions. The company does not maintain a dedicated cybersecurity team. Security responsibilities are distributed between the CTO and a small cloud engineering function, alongside general engineering staff.

Security investment must therefore compete with product development and market expansion initiatives.

---

## 4. Technology Environment

Helios operates a fully cloud based environment consisting of:

* A web application used by hospital customers
* Data ingestion pipelines accepting API, SFTP, and file uploads
* A centralized data lake storing raw clinical data
* A model development and training environment
* A production inference API supporting real time clinical analytics
* CI CD pipelines supporting frequent code and model releases
* A centralized IAM platform for workforce and service identities

The platform supports both internal development users and external hospital integrations.

---

## 5. Information Assets

Helios processes and stores multiple high value information assets, including:

* Protected Health Information and Personally Identifiable Information
* Clinical and diagnostic records
* Insurance and billing data
* Hospital operational metrics
* Proprietary machine learning models and source code
* Customer contracts and audit evidence

Loss, corruption, or exposure of these assets would have significant regulatory, financial, and reputational consequences.

---

## 6. Regulatory and Contractual Environment

Although Helios is not a healthcare provider, it functions as a critical third party processor of regulated health data. Customers require adherence to:

* HIPAA privacy and security expectations
* Data breach notification obligations
* Vendor risk assessment and audit rights
* Increasingly, formal assurance such as SOC 2 or ISO 27001

At present, Helios has not achieved external security certifications.

---

## 7. Business Pressures and Constraints

Helios is in a rapid growth phase with limited discretionary budget. Engineering teams prioritize feature delivery and model performance. Leadership recognizes the importance of security but views it primarily as an enabler for sales and compliance rather than a revenue generator.

The company has allocated approximately 300,000 CAD annually for security related initiatives and process improvements.

---

## 8. Recent Risk Events

Three recent developments have increased management concern:

* A major sales opportunity was delayed due to the absence of mandatory multi factor authentication for customer and workforce access.
* An internal engineer inadvertently exposed production API credentials within a source code repository, creating potential unauthorized access risk.
* A direct competitor experienced a ransomware incident resulting in multiple days of service unavailability and loss of customer confidence.

These events highlighted weaknesses in identity management, data protection, and resilience.

---

## 9. Management Problem Statement

Executive leadership seeks to understand:

* The most significant cyber risks facing Helios
* How those risks impact business objectives
* Which controls provide the greatest risk reduction under financial and operational constraints
* Which risks should be mitigated, transferred, accepted, or avoided

The organization requires a structured, risk based security roadmap rather than a technology driven solution list.

---

## 10. Analytical Approach

This case is assessed using the NIST Cybersecurity Framework 2.0, structured across the six core functions:

* Govern
* Identify
* Protect
* Detect
* Respond
* Recover

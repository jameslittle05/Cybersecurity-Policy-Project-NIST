# Cybersecurity Policy Program utilitzing NIST Cybersecurity Framework (CSF) 2.0
**Corporate Cybersecurity Assessment Utilizing NIST Cybersecurity Framework (CSF) 2.0**

**Introduction**

For this project, I was tasked with analyzing B3SI's (fictitious company) cybersecurity posture and designing a comprehensive cybersecurity program utilizing the NIST CSF 2.0 to uplift its security maturity. I was provided with internal audit notes, which served as a simulated 'current status' report—similar to what would be compiled after initial stakeholder interviews and infrastructure analysis.

Using this information, I conducted a pass/fail assessment mapped to the NIST CSF 2.0's Core Functions: GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, and RECOVER. The goal was to identify key security gaps and propose realistic, prioritized recommendations. I began by creating a short overview presentation to explain the NIST framework to stakeholders and concluded with a summary of critical procedures and policy implementations needed to improve the organization's security standing—from Tier 1 (Partial) toward Tier 4 (Adaptive).

---
### Assessment Results (Summary Table)

| NIST CSF Function | Key Category                | Maturity Level (1-5) | Gap Identified                     | Recommendation                          |
|-------------------|-----------------------------|----------------------|------------------------------------|------------------------------------------|
| Identify          | Asset Management (ID.AM)    | 2                    | Incomplete inventory of systems    | Implement automated asset discovery      |
| Protect           | Identity Management (PR.AC) | 3                    | Weak MFA policies                  | Enforce MFA across all accounts          |
| Detect            | Anomalies and Events (DE.AE)| 2                    | No formal monitoring tools         | Deploy SIEM or log monitoring solution   |
| Respond           | Response Planning (RS.RP)   | 1                    | No incident response plan          | Create and train an IR policy            |
| Recover           | Recovery Planning (RC.RP)   | 2                    | Ad-hoc backup procedures           | Document and test backup/recovery plans  |


### Policy 1: Remote Access to Organizational Systems, Applications, and Data

**Purpose:**
To protect B3SI’s applications, systems, and data by ensuring that remote access is limited to authorized users only. This policy prevents unauthorized access, data breaches, and the exposure of company assets outside of secure networks.

**Scope:**
This policy applies to all employees, contractors, and vendors using B3SI technology, particularly during business hours and on company premises.

**Restrictions:**
1. All users must connect to the company Virtual Private Network (VPN) for remote access.
2. Remote users must confirm they are using a secure, private network. Public Wi-Fi is prohibited.
3. All data accessed remotely must be stored on B3SI servers; local storage is not permitted.
4. Multi-Factor Authentication (MFA) is required for all remote logins.
5. Access is restricted to company-issued devices. Personal devices require explicit authorization via the BYOD policy.

**Roles & Responsibilities:**

1. IT Department: Configure VPN, enforce MFA.
2. Users: Follow guidelines and report any anomalies.

**Enforcement:**
Violations may result in suspension of access privileges or disciplinary action.

**Review:**
Reviewed annually or after any security incident.

**External References:**
- Virtual Private Network Usage Policy
- Information Security Guidelines

**CSF Mapping:**
- **PROTECT:** PR.AC-3 (Remote access is managed)
- **IDENTIFY:** ID.AM-1 (Assets managed)
- **GOVERN:** GV.PO-1 (Policies established)

---

### Policy 2: Acceptable Use of Office Computing Technology

**Purpose:**
To ensure that the use of office computing resources aligns with operational and security requirements. Misuse may expose the company to risks such as data loss, decreased productivity, and legal action.

**Scope:**
Applies to all employees, contractors, and vendors using B3SI technology during business hours and on company premises.

**Restrictions:**
1. Company computers are for business use only.
2. Internet access is restricted to job-related tasks.
3. Printers are to be used only for business documents.
4. All software installations require IT department approval.
5. Suspected misuse must be reported to the IT team immediately.

**Acceptable Use:**
1. Use systems for job-related activities.
2. Secure workstations when unattended.
3. Save data only to approved locations.

**Unacceptable Use:**
1. Downloading pirated software or media.
2. Unauthorized software installation.
3. Using company devices for cryptocurrency mining, etc.

**Monitoring and Privacy:** B3SI IT team may log and monitor usage. Employees should have no expectation of privacy.

**Enforcement:** Breaches may lead to warnings, termination, or legal action.

**External References:**
- Software Installation Policy
- Internet Usage Policy

**CSF Mapping:**
- **PROTECT:** PR.PT-1 (Audit/log records)
- **GOVERN:** GV.PO-1 (Policies established)

---

### Policy 3: Acceptable Use of Personal Technology on Organizational Networks (BYOD)

**Purpose:**
To ensure that personal devices allowed on B3SI’s network meet security requirements. Improperly managed devices may introduce vulnerabilities.

**Scope:**
Applies to all employees, contractors, and vendors using personal devices to connect to B3SI systems.

**Restrictions:**
1. Only pre-approved personal devices may connect to the corporate network and must meet B3SI’s security standards.
2. Personal devices must have anti-virus software enabled.
3. Access to company systems is prohibited unless authorized.
4. Employees must safeguard all company-related information/assets on personal devices.
5. B3SI reserves the right to wipe company data from personal devices.

**Security Controls:**
1. Company may require installation of MDM (Mobile Device Management).
2. Remote wipe capability must be enabled for lost/stolen devices.

**Data Segregation:** Business data must be kept in designated apps or containers.

**Employee Consent:** Signing this policy is a prerequisite to accessing company resources via BYOD.

**Violations:** Loss of BYOD privileges or further disciplinary steps.

**External References:**
- Remote Access Policy
- Information Handling Policy

**CSF Mapping:**
- **PROTECT:** PR.AC-6 (Access to systems is restricted)
- **IDENTIFY:** ID.AM-3 (Authorization of devices/users)
- **PROTECT:** PR.IP-11 (BYOD security requirements)

---

**Conclusion:**
The implementation of these foundational policies is a significant first step in improving B3SI’s cybersecurity posture. Each policy aligns with specific CSF Core Functions and supports movement toward a Tier 4 Adaptive cybersecurity maturity level. Continued assessment and refinement, along with employee training and executive oversight, will be critical to sustaining progress.


**Next Steps:**
- Conduct a gap analysis comparing actual practices against these policies
- Launch organization-wide cybersecurity training
- Schedule periodic policy reviews and updates
- Begin integration of automated monitoring and enforcement tools

**References:**
- NIST Cybersecurity Framework 2.0: https://www.nist.gov/cyberframework

- CIS Controls v8

- B3SI Internal Audit Notes (fictional)

- Course Materials: Management of Cybersecurity – Kennesaw State University


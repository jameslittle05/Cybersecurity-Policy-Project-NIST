# Cybersecurity Policy Program Using NIST CSF 2.0

**Corporate cybersecurity assessment and policy design for B3SI (fictitious company), mapped to the NIST Cybersecurity Framework (CSF) 2.0**

## Introduction

For this project, I analyzed B3SI's cybersecurity posture and designed a foundational policy program using NIST CSF 2.0 to raise its security maturity. I was given internal audit notes that served as a simulated "current status" report, similar to what would be compiled after initial stakeholder interviews and infrastructure analysis.

Using this information, I conducted a pass/fail assessment mapped to the six CSF 2.0 Core Functions: **GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, and RECOVER**. The goal was to identify key gaps and propose realistic, prioritized recommendations. I created a short overview presentation explaining the framework to stakeholders and concluded with three core policies to move the organization from **Tier 1 (Partial)** toward **Tier 4 (Adaptive)**.

---

## Assessment Results

| CSF 2.0 Function | Category | Current Tier (1-4) | Gap Identified | Recommendation |
|---|---|---|---|---|
| Govern | Policy (GV.PO) | 1 | No formal, communicated cybersecurity policies | Establish and enforce the three policies below |
| Identify | Asset Management (ID.AM) | 2 | Incomplete inventory of systems | Implement automated asset discovery |
| Protect | Identity Management, Authentication, and Access Control (PR.AA) | 2 | Weak MFA policies | Enforce MFA across all accounts |
| Detect | Continuous Monitoring (DE.CM) | 1 | No formal monitoring tools | Deploy a SIEM or log monitoring solution |
| Respond | Incident Management (RS.MA) | 1 | No incident response plan | Create, approve, and train staff on an IR plan |
| Recover | Incident Recovery Plan Execution (RC.RP) | 2 | Ad hoc backup procedures | Document and test backup and recovery plans |

---

## Policy 1: Remote Access to Organizational Systems, Applications, and Data

**Purpose**
Protect B3SI's applications, systems, and data by limiting remote access to authorized users. This prevents unauthorized access, data breaches, and exposure of company assets outside secure networks.

**Scope**
Applies to all employees, contractors, and vendors who access B3SI systems, applications, or data from outside B3SI premises, at any time.

**Requirements**
1. All remote access must go through the company Virtual Private Network (VPN).
2. Remote users must use a secure, private network. Public Wi-Fi is prohibited.
3. Data accessed remotely must be stored on B3SI servers. Local storage is not permitted.
4. Multi-Factor Authentication (MFA) is required for all remote logins.
5. Access is limited to company-issued devices. Personal devices require explicit authorization under the BYOD policy (Policy 3).

**Roles & Responsibilities**
- **IT Department:** Configure and maintain the VPN, enforce MFA, and review remote access logs.
- **Users:** Follow this policy and report anomalies or suspected compromise immediately.

**Enforcement**
Violations may result in suspension of access privileges or disciplinary action.

**Review**
Reviewed annually or after any security incident.

**Related Policies**
- Virtual Private Network Usage Policy
- Information Security Guidelines
- BYOD Policy (Policy 3)

**CSF 2.0 Mapping**
- **GOVERN:** GV.PO-01 (Cybersecurity policy is established, communicated, and enforced)
- **PROTECT:** PR.AA-03 (Users, services, and hardware are authenticated)
- **PROTECT:** PR.IR-01 (Networks are protected from unauthorized logical access)
- **PROTECT:** PR.DS-02 (Data in transit is protected)

---

## Policy 2: Acceptable Use of Office Computing Technology

**Purpose**
Ensure office computing resources are used in line with operational and security requirements. Misuse may expose the company to data loss, reduced productivity, and legal action.

**Scope**
Applies to all employees, contractors, and vendors using B3SI technology during business hours and on company premises.

**Restrictions**
1. Company computers are for business use only.
2. Internet access is limited to job-related tasks.
3. Printers are for business documents only.
4. All software installations require IT department approval.
5. Suspected misuse must be reported to IT immediately.

**Acceptable Use**
1. Use systems for job-related activities.
2. Lock workstations when unattended.
3. Save data only to approved locations.

**Unacceptable Use**
1. Downloading pirated software or media.
2. Installing unauthorized software.
3. Using company devices for cryptocurrency mining or other non-business activity.

**Monitoring and Privacy**
The B3SI IT team may log and monitor usage. Employees should have no expectation of privacy on company systems.

**Roles & Responsibilities**
- **IT Department:** Approve software, monitor usage, investigate reported misuse.
- **Users:** Comply with this policy and report suspected misuse.

**Enforcement**
Breaches may lead to warnings, termination, or legal action.

**Review**
Reviewed annually or after any security incident.

**Related Policies**
- Software Installation Policy
- Internet Usage Policy

**CSF 2.0 Mapping**
- **GOVERN:** GV.PO-01 (Cybersecurity policy is established, communicated, and enforced)
- **PROTECT:** PR.PS-05 (Installation and execution of unauthorized software is prevented)
- **PROTECT:** PR.AT-01 (Personnel receive awareness and training)
- **DETECT:** DE.CM-03 (Personnel activity and technology usage are monitored)

---

## Policy 3: Acceptable Use of Personal Technology on Organizational Networks (BYOD)

**Purpose**
Ensure personal devices allowed on B3SI's network meet security requirements. Unmanaged devices can introduce vulnerabilities.

**Scope**
Applies to all employees, contractors, and vendors using personal devices to connect to B3SI systems.

**Requirements**
1. Only pre-approved personal devices may connect to the corporate network, and they must meet B3SI security standards.
2. Personal devices must run active anti-virus software.
3. Access to company systems is prohibited unless authorized.
4. Users must safeguard all company information and assets on personal devices.
5. B3SI reserves the right to wipe company data from personal devices.

**Security Controls**
1. B3SI may require installation of Mobile Device Management (MDM).
2. Remote wipe must be enabled for lost or stolen devices.

**Data Segregation**
Business data must be kept in designated apps or containers.

**Employee Consent**
Signing this policy is a prerequisite to accessing company resources via BYOD.

**Roles & Responsibilities**
- **IT Department:** Approve and register devices, manage MDM, execute remote wipes.
- **Users:** Keep devices patched and protected, and report loss or theft immediately.

**Violations**
Loss of BYOD privileges or further disciplinary action.

**Review**
Reviewed annually or after any security incident.

**Related Policies**
- Remote Access Policy (Policy 1)
- Information Handling Policy

**CSF 2.0 Mapping**
- **GOVERN:** GV.PO-01 (Cybersecurity policy is established, communicated, and enforced)
- **IDENTIFY:** ID.AM-01 (Hardware inventories are maintained)
- **PROTECT:** PR.AA-05 (Access permissions and authorizations are managed and enforced)
- **PROTECT:** PR.PS-01 (Configuration management practices are applied)

---

## Conclusion

These foundational policies are a significant first step in improving B3SI's cybersecurity posture. Each aligns with CSF 2.0 Core Functions and supports movement toward Tier 4 (Adaptive). Continued assessment, employee training, and executive oversight will be critical to sustaining progress.

## Next Steps
- Conduct a gap analysis comparing actual practices against these policies
- Launch organization-wide cybersecurity training
- Schedule periodic policy reviews and updates
- Integrate automated monitoring and enforcement tools

## References
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- CIS Controls v8
- B3SI Internal Audit Notes (fictional)
- Course Materials: Management of Cybersecurity, Kennesaw State University

# Botium-Toys-Internal-Security-Audit
This project is a mock internal security audit assignment written for a fictitious toy company that is part of my cybersecurity portfolio.

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
4. [Internal Security Audit Process](#process)
5. [Controls Assessment](#control-assessment)
6. [Compliance Checklist](#compliance-checklist)
7. [Stakeholder Memorandum](#stakeholder-memo)
8. [Conclusion](#conclusion)

-------
# Introduction <a name="introduction">
The following exercise is part of my cybersecurity portfolio whose completion is a requirement of Google's Cybersecurity Professional Certificate on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course .

# Scenario  <a name="scenario">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

------------------------
The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices. 

Goals for this internal IT audit exercise are:
- Assess existing assets
- Complete the controls and compliance checklist
- Establish systems that are compliant
- Ensure these systems allow Botium Toys’ to meet compliance requirements

### Internal Security Audit Process  <a name="process">
Assets will need to be assessed alongside internal processes and procedures
1. Analyze the project scope, audit goals, and risk assessment
2. Perform the audit
   - Complete Controls assessment 
     - Select and rate each control organize list based on priority (i.e. needing to be implemented immediately or in the future)
   - Complete the Compliance checklist
     - Include notes as to why selected compliance regulations and standards need to be adhered to.
3. Review results from process steps (1-2)
    - Summarize your recommendations
    - Send findings and recommendation's to stakeholders

Controls Assessment  <a name="control-assessment">
===================

Current Assets 
--------------

Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

### Administrative Controls 
| Control name | Control type and purpose | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

### Technical Controls 
| Control Name | Control type and purpose | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall |  ***implemented***  | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |

### Physical Controls
| Control Name | Control type and purpose | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attacks, potential threats | X | Medium/Low |
| Adequate lighting | Deterrent; maximize visibility | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | High/Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium |

Compliance checklist
====================
As a result of successfully assessing existing assets and and completing the controls checklist for Botium Toys, the items included below as part of the compliance checklist are not being utilized and should be implemented: 

- General Data Protection Regulation (GDPR)
- Payment Card Industry Data Security Standard (PCI DSS)
- System and Organizations Controls (SOC type 1, SOC type 2)
  
----------------

# Stakeholder memorandum <a name="stakeholder-memo">
TO: IT Manager, Stakeholders

FROM: Brittni Ahrens\
DATE: 02/01/2024\
SUBJECT: Internal IT Audit Findings and Recommendations
RE: Botium Toys

Dear Colleagues,

Please see below all documentation in relation to the Internal IT Audit performed for Botium Toys. You will find notes pertaining to the internal audit, scope, goals, critical findings, summary and a summary of all recommendations.

**Scope:**
In Scope:
- Integrated controls to ensure data integrity
- Firewall
- End point detection
- Intrusion detection system
- (SIEM) tools; event management and security information
- Accounting
- 
Systems currently in place will be evaluated for: 
Current user permissions, existing procedures and protocols
 - Ensuring that permissions, controls, procedures and protocols exist and are meeting compliance requirements.
   
**Goals:**

- Establish a better process for their systems to ensure they are compliant
- Adhere to the NIST CSF
- Establish system controls meet compliance and best practices
- Implement the concept of least permissions when it comes to user credential management
- Establish their policies and procedures (includes their playbooks)

**Recommendations:**
  **Critical** (must be addressed immediately):

 Multiple controls need to be developed and implemented to meet the audit goals, including:

- Principle of Least Privilege and Separation of duties
- Disaster recovery plans
- Password, Access control, and Account management policies
- Intrusion Detection System (IDS)
- Encryption (secure website transactions wand disk drive(s) containing sensitive information)
- Backups
- Implementation of a Password management system
- Antivirus (AV) software
- Manual monitoring, maintenance, and intervention for legacy systems
- Closed-circuit television (CCTV) surveillance
- Locks
- Locking cabinets (for network gear)
- Fire detection and prevention (fire alarm, sprinkler system, etc.)
- Policies need to be developed and implemented for the following:
  - To meet PCI DSS and GDPR compliance requirements.
  - To meet SOC1 and SOC2 guidance related to user access policies and overall data safety.

**Low Priority** (should be addressed, but no immediate need):
Physical controls
- Improved lighting
- Surveillance signage

# Conclusion  <a name="conclusion">
In conclusion though there are certain systems already in place, these are the areas that should be addressed immediately as Botium Toys accepts online payments and is expanding offerings. Therefore these critical findings will put you in compliance with PCI and GDPR ultimately strengthening your overall security posture at scale. 

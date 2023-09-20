# Botium Toys Security Audit

## Overview:
This audit is completed as part of a training excercise of the Google Cybersecurity Certificate on Coursera. It is conducted on the cybersecurity program at a fictitious company called Botium Toys.

## Scenario:
The exercise sets out a scenario in which the IT manager completed a risk assessment and established an audit scope and goals. You need to review these documents, perform an audit to complete a controls assessment and compliance checklist, analyze your findings, develop recommendations and communicate with stakeholders with the aim of improving the security posture of the organization, as well as using it to justify new hires for the security team.

## Scope:  
The entire security program at Botium Toys. The audit will assess the following:
-	Current procedures. protocols, implemented controls and user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
-	Ensure current procedures, protocols, controls and user permissions implemented align with compliance requirements.
-	Ensure current technology is accounted for hardware and system access.
 
## Goals:
-	To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF). 
-	Establish a better process for their systems to ensure they are compliant. 
-	Fortify system controls.
-	Implement the concept of least permissions when it comes to user credential management. 
-	Establish their policies and procedures, which includes their playbooks. 
-	Ensure they are meeting compliance requirements. 

---

# Control Assessment

## Current assets
Assets managed by the IT Department include:
-	On-premises equipment for in-office business needs.
-	Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
-	Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management.
-	Internet access.
-	Internal network.
-	Vendor access management.
-	Data center hosting services. 
-	Data retention and storage.
-	Badge readers.
-	Legacy system maintenance: end-of-life systems that require human monitoring.
## Administrative Controls:  
| Control Name | Control Type and explanation | Need to be Implemented (x) | Priority |
| --- | --- | :---: | --- |
|Least Privilege|Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs.|  X  |High    |
|Disaster recovery plans|Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration.|	X|	High|
|Password policies|	Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques.|	X|	High|
|Access control policies|	Preventative; increase confidentiality and integrity of data.|	X|	High |
| Account management policies|	Preventative; reduce attack surface and limit overall impact from disgruntled/former employees.|	X|	High |
| Separation of duties| Preventative; ensure no one has so much access that they can abuse the system for personal gain.|	X|	High  |

## Technical Controls:  
| Control Name | Control Type and explanation | Need to be Implemented (x) | Priority |
| --- | --- | :---: | --- |
|Firewall|	Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network.|	N/A|	N/A|
|Intrusion Detection System (IDS)	|Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly.|	X|	High|
|Encryption|	Deterrent; makes confidential information/data more secure (e.g., website payment transactions).|	X|	High/Medium|
|Backups|	Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan.|	X|	High|
|Password management system|	Corrective; password recovery, reset, lock out notifications.|	X|	High/Medium|
|Antivirus (AV) software|	Corrective; detect and quarantine known threats.|	X|	High|
|Manual monitoring, maintenance, and intervention	|Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities.	|X|	High|

## Physical Controls:  
| Control Name | Control Type and explanation | Need to be Implemented (x) | Priority |
| --- | --- | :---: | --- |
|Time-controlled safe|	Deterrent; reduce attack surface/impact of physical threats.|	X|	Medium/Low|
|Adequate lighting|	Deterrent; limit “hiding” places to deter threats.|	X|	Medium/Low|
|Closed-circuit television (CCTV) surveillance|	Preventative/detective; can reduce risk of certain events; can be used after event for investigation.|	X|High/Medium|
|Locking cabinets (for network gear)|	Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear.|	X|	Medium|
|Signage indicating alarm service provider|	Deterrent; makes the likelihood of a successful attack seem low.|	X|	Low|
|Locks|	Preventative; physical and digital assets are more secure.	|X	|High|
|Fire detection and prevention (fire alarm, sprinkler system, etc.)|	Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.|	X|	Medium|

---

# Compliance checklist

- [ ] The Federal Energy Regulatory Commission - North American Electric Reliability Corporation (FERC-NERC)
The FERC-NERC regulation applies to organizations that work with electricity or that are involved with the U.S. and North American power grid. Organizations have an obligation to prepare for, mitigate, and report any potential security incident that can negatively affect the power grid. Organizations are legally required to adhere to the Critical Infrastructure Protection Reliability Standards (CIP) defined by the FERC.<br/>
**Explanation:** N/A

- [x] General Data Protection Regulation (GDPR)
GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.<br/>
**Explanation:** *Botium Toys needs to adhere to this regulation because it conducts worldwide business and collects data from European Union Citizens.*

- [x] Payment Card Industry Data Security Standard (PCI DSS)
PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment.<br/>
**Explanation:** *Botium Toys needs to adhere to this standard because it accepts, store, process and transmit credit card information when clients use it as a payment option.*

- [ ] The Health Insurance Portability and Accountability Act (HIPAA)
HIPAA is a federal law established in 1996 to protect U.S. patients' health information. This law prohibits patient information from being shared without their consent. Organizations have a legal obligation to inform patients of a breach.<br/>
**Explanation:** N/A

- [x] System and Organizations Controls (SOC type 1, SOC type 2)
The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.<br/>
**Explanation:** *Botium Toys needs to develop and implement appropriate user access and financial controls policies to ensure data safety, reduce risk and avoid fraud.*

---

# Stakeholder memorandum

TO: IT Manager, Stakeholders  
FROM: Amaury   
DATE: 5/27/203   
SUBJECT: Internal IT Audit Findings and Recommendations   

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.

### Scope: 
The audit will assess the following:
-	Current procedures. protocols, implemented controls and user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
-	Ensure current procedures, protocols, controls and user permissions implemented align with compliance requirements.
-	Ensure current technology is accounted for hardware and system access.

### Goals:
-	To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF). 
-	Establish a better process for their systems to ensure they are compliant. 
-	Fortify system controls.
-	Implement the concept of least permissions when it comes to user credential management. 
-	Establish their policies and procedures, which includes their playbooks. 
-	Ensure they are meeting compliance requirements. 


### Critical findings (must be addressed immediately): 
-	Botium Toys needs to develop and implement policies to fulfill GPDR and PCI DSS requirements.
-	Botium Toys needs to develop and implement appropriate user access and financial controls policies to align with SOC1and SOC2 standards for ensuring data safety, reduce risk and avoid fraud.
  
The following security controls need to be implemented:
-	Access control, account Management and Password policies.
-	Password Management system.
-	Less Privilege access and separation of duties.
-	Disaster recovery plans and regular backups.
-	Encryption for website payment transactions.
-	IDS (Intrusion Detection system)
-	Antivirus software
-	Manual Monitoring, maintenance and intervention for legacy systems.
-	CCTV
-	Locks
-	Fire detection and prevention systems.

### Findings (should be addressed, but no immediate need): 
-	Adequate lighting
-	Time-Controlled safe
-	Locking cabinets
-	Signage indicating alarm provider.
  
### Summary/Recommendations:

     
As Botium Toys conducts worldwide business including Europe and process credit card payments is recommended that the company immediately develop and implement policies to comply with GPDR and PCI DSS requirements. 
Equally critical is the development and implementation of appropriate user access and financial controls policies to align with SOC1and SOC2 standards for ensuring data safety, reducing risk and avoid fraud.  It is necessary to promptly implement access control, account management, password policies, password management system, less privilege access and separation of duties. Additionally, Encryption is a way to secure customer information.
Not less important is to develop a disaster Recovery plan and perform regular backups to be prepare for a disruptive cybersecurity attack and ensure the business continuity.
The constantly monitoring of the system is critical to detect possible intrusions and mitigate risk; the implementation of IDS and AV software will address this issue and controls like locks, CCTV and fire detection system help us to secure the physical assets.
Some other measures will improve the security posture but are not immediately required such as Adequate lighting, Time-Controlled safe, locking cabinet and signage indicating alarm provider.










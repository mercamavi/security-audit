# Botium Toys Security Audit

## Overview:
This audit is completed as part of an exercise training of the Google Cybersecurity Certificate on Coursera. It is conducted on the cybersecurity program at a fictitious company called Botium Toys.

## Scenario:
The exercise set out and scenario in which the IT manager completed a risk assessment and established an audit scope and goals. You need to review these documents, perform an audit to complete a controls assessment and compliance checklist, analyze your findings, develop recommendations and communicate with stakeholders with the aim of improving the security posture of the organization, as well as using it to justify new hires for the security team.

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



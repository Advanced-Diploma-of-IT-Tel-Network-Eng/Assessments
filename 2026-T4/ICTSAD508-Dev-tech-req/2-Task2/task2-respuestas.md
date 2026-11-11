
---
1. Question

King Edward VII College became a Registered Training Organisation (RTO) in 2010 and is based in Melbourne's CBD.

It is nationally recognized for the quality of its courses in management, marketing, human resources, and international business. It currently has around 500 students. Its staff includes 24 members, 14 of whom are trainers and assessors.

The college follows the quality guidelines of the national VET Quality Framework and implements a continuous improvement system.

# Goals and objectives:

- To be leaders in quality in VET courses
- To establish and maintain high quality services (staff/platform)
- To be a profitable and high-performing organization

# Business model:

- Value proposition: high-quality, industry-ready training, competitive pricing, highly qualified, experienced training staff and innovative teaching methods.
- Target customer base: people who want to formalize and develop their skills. Also, people entering the industry, people already working in the sector.
- Delivery: classroom, blended (face-to-face/online) and online courses.
- Revenue: course fees, payment plans.
- Marketing strategy: continuous market research, information sessions, an improved website and targeted campaigns

# Business Requirements:

- Outdated ICT system: A recognized weakness
- ICT system upgrade: A system capable of scaling easily and quickly, with cloud access and access to other locations
- Moodle: All courses must be available online
- Improved website: Target increase of 10%, with a 5% market growth target
- Expansion and growth: New campuses in Sydney and Brisbane. Target of at least 10% annual increase in new students
- Security and compliance: Protection of student and staff data

# Impact on Business Infrastructure

I believe the main obstacle is the current, outdated infrastructure, considering the expansion objectives.

- vs. Objective 1: High latency and low video/audio quality in online classes. It cannot offer all courses online.

- vs. Objective 2: The current infrastructure is not capable of scaling or expanding to future campuses. It also cannot provide quality services to staff or students.

- vs. Objective 3: It is difficult to implement solutions to achieve this objective based on business requirements.

# Legislation, standards & procedures

- Privacy Act 1988: Student and staff personal information in the ICT system, the cloud and the moodle must be collected, stored and accessed under the Australian Privacy Principles. This requires security controls, such as access control and encryption, and a data breach response.
- Web accessibility standards (WCAG 2.2, Level A): The website and moodle must be accessible to all users, including students with disability, which supports the College value "Embrace difference and diversity" and it would meet the international requirement to comply with Conformance Level 2.2.
- Systems Development Life Cycle (SDLC)
This gives a structured methodology for planning, testing and implementing the three solutions.

## Procedures in the Simulation Pack:

- Purchasing Policy and Procedures: This procedure directly affects vendor selection and the implementation timeline, so the quotation steps must be built into the schedule.
- Risk Management: This supports the business case for the upgrade.
- Continuous improvement system and annual internal audit: The solutions must be reviewed and improved after implementation.

## Other applicable procedures:

- Information security and cyber security policies, including acceptable use, passwords and access control.
- Backup and disaster recovery procedure.
- Procedures for planning and implementing projects (SDLC) and change management.
- Risk management procedures for ICT projects.
- OHS policies for hardware installation and workstations.
- Documentation procedures for hardware and software solutions, such as asset registers and network diagrams.

# Hardware, software,  network and interface requirements

## Hadware
- Related to staff work
	- Workstations
	- laptops
	- classroom devices
	
- Related to the general functioning of the network
	- ISP, high bandwith
	- Redudancy network devices
	- Cloud or dedicated servers
	- WAN/VPN links
- Related to accessibility
	- Accessible interface WCAG
	- Accessible interface multilingual support
	
- Realated to Network and security
	- LAN network private/public
	- Wifi network private/public
	- Endpoints
	- Routers, switches, firewalls, access points

## Software

Operating systems
Suits (cloud, on-premise)
Liceses 
Website
Moodle

## Interface
- GUI for website
- GUI for moodle
- Responsibe desing moodle/website
- Network infrastructure digram 
- ICT infrastructure map

# Security requirements
Although no business solutions have been proposed, I believe the following essential security requirements must be met:

- Authentication and access control: strong passwords, password changes, two step authentication (MFA) and role-based access for staff and students.
- Preventing hacking, virus and malware: firewalls, endpoint protection, and regular patching and updates.
- Encryption: HTTPS (SSL/TLS) for the website and moodle, VPN (IPSec) between campuses, and encryption of data at rest in the cloud.
- Privacy and confidentiality: protection of student and staff personal information under the Privacy Act 1988, including a data breach response plan.
- Backup and disaster recovery: regular, tested backups, both cloud and offsite, to protect against data corruption and hardware failure.
- Web and web server security: secure configuration of the website, moodle and servers.
- Workstation and physical security: screen locks, physical locks on server and network rooms, and asset tagging.
- Internal security breaches: an information security policy, logging and monitoring, and staff security awareness training.
---

2. Question

# Draft Business Solutions:
The draft business solutions shown to Alex are:

1. ICT Infrastructure Upgrade:
Upgrade the ICT infrastructure to make it faster, more efficient, scalable, and enable cloud access and inter-campus connectivity.

This also includes security aspects such as access controls, data protection, backups, and recovery.

2. Moodle:
Implement a Moodle platform that allows for offering all courses online and supports blended learning. It should also facilitate access for students and faculty. Ensuring the availability of services such as digital resource management and assessments is crucial.

3. Website Improvement:
Improve the website to present clear information about the courses and the College. Also, offer accessible and multilingual UX/UI features. Finally, enhance features to improve marketing.


# Meeting Notes:
Hi teacher, to create this section, I first developed a draft and then researched the topic to improve it and align it with the College's objectives.

## Identification of College and user needs
Alex was initially sent the document with the provisional "Hardware, software, network and interface requirements" (see Section 1). The needs of the College and those involved were also discussed and identified, leading to the following conclusion:

Alex summarized the needs as faster, more efficient, sustainable, and secure for staff and students, emphasizing the importance of "Strategic Objectives" (case study).

Alex summarized the needs as faster, more efficient, sustainable and secure for staff and students.

## Discussion and feedback
Alex confirmed that the three proposed business solutions generally align with the College’s objectives. He requested more precise descriptions of the security requirements.

Alex clarified that the College already uses a Moodle-based online learning platform provided by a third party. Implementing a new Moodle platform is not required. The preferred approach is to modernise the existing platform through its provider, which would avoid the substantial cost and risk of acquiring a new product and migrating data. Alex also suggested developing APIs to integrate the online learning platform with the College website.

## Agreed business solutions

1. ICT Infrastructure Upgrade and Security:
Upgrade the College’s ICT infrastructure to make it faster, more efficient and sustainable, support cloud access, and connect the College’s campuses. The solution must include defined security controls: 
- role-based access
- multi-factor authentication
- firewalls
- endpoint protection
- regular security updates
- encryption of data in transit and at rest
- security monitoring
- and tested backup and disaster recovery procedures. 

Secure network connections must also be established between campuses.

2. Modernisation and Integration of the Existing Moodle:
Modernise the moodle currently used by the College through its existing third-party provider, rather than implementing a new product. Confirm the required features with the provider, including support for all courses, online and blended delivery learning resources and assessments. 

This approach would avoid the substantial cost and risk associated with moving to a new product and migrating existing data. Develop secure APIs to integrate the platform with the College website, using appropriate authentication, encrypted connections and access controls.

3. Website Improvement:
Improve the website information to attract more students and support the College’s marketing objectives. The website would provide accessible, user-friendly information about the College and its courses, with responsive and multilingual features as identified in the initial requirements. Integrate it with the existing online learning platform through the proposed secure APIs.


## Agreements

1. Alex set the maximum budget at $500,000.

2. The project, including the three business solutions, is expected to be completed within a maximum of 12 months.
3. Alex expects to receive technical support from us for the first 6 months after the end of the project.
4. It was agreed to present the budget and timeline next week.
---

3. Question

Find presentation on "presentation.pptx" or "presentation.md"

---

4. Question

## UPDATED Hardware, software,  network, interface requirements and Professional Services

## Hardware
- Related to staff work (Solution 1: faster, more efficient and sustainable ICT system)
	- Workstations
	- Laptops
	- Classroom devices

- Related to infrastructure (Solution 1: cloud access and links between campuses)
	- Cloud or dedicated servers
	- Backup storage (cloud and offsite)

- Related to network and security devices (Solution 1: defined security controls)
	- Firewalls at each campus
	- Routers, switches, access points
	- Redundant network devices
	- Endpoints

## Software
- Related to the ICT infrastructure (Solution 1)
	- Operating systems
	- Suites (cloud, on-premise)
	- Licences

- Related to security (Solution 1)
	- Identity and access management (role-based access, MFA)
	- Endpoint protection
	- Security monitoring and logging tools
	- Backup and disaster recovery software
	- Encryption of data at rest

- Related to online learning (Solution 2)
	- Existing Moodle, modernised through the current third-party provider (all courses, online and blended delivery, learning resources and assessments)
	- Secure APIs for Moodle and website integration

- Related to the website (Solution 3)
	- Website CMS

## Network
- Related to connectivity (Solution 1: cloud access and links between campuses)
	- ISP, high bandwidth, with redundant connection
	- Secure WAN/VPN (IPSec) links between campuses

- Related to local networks (Solution 1: defined security controls)
	- LAN network, private/public (segmented)
	- Wi-Fi network, private/public (segmented)

- Related to secure access (Solutions 2 and 3)
	- Encrypted connections (HTTPS/TLS) for the website and Moodle
	- Secure network access for API integration between Moodle and website

## Interface
- GUI for website (accessible information about the College and its courses, Solution 3)
- GUI for Moodle (Solution 2)
- Responsive design for Moodle and website
- Accessible interface (WCAG 2.2)
- Multilingual support on the website
- Secure API interface between Moodle and website (authentication, encrypted connections, access controls; Solutions 2 and 3)
- Access for external parties (students, prospective students) and internal users (staff)

## Security requirements
Based on the agreed business solutions, the following security requirements must be met:

- Authentication and access control: strong passwords, password changes, multi-factor authentication (MFA) and role-based access for staff and students.
- Preventing hacking, virus and malware: firewalls, endpoint protection, and regular security updates.
- Encryption: HTTPS (SSL/TLS) for the website and Moodle, VPN (IPSec) between campuses, and encryption of data at rest in the cloud.
- Secure APIs: authentication, encrypted connections and access controls for the Moodle and website integration.
- Security monitoring: logging and monitoring of systems and network activity.
- Privacy and confidentiality: protection of student and staff personal information under the Privacy Act 1988, including a data breach response plan.
- Backup and disaster recovery: regular, tested backups, both cloud and offsite, to protect against data corruption and hardware failure.
- Web and web server security: secure configuration of the website, Moodle and servers.
- Workstation and physical security: screen locks, physical locks on server and network rooms, and asset tagging.
- Internal security breaches: an information security policy and staff security awareness training.

## Professional Services

- IT Manager (me): project lead. Plans, coordinates and controls the three solutions, manages vendors and the budget, reports to the CEO and obtains approvals and sign-off.
- Finance & Administration Manager: budget control, and purchasing approvals under the Purchasing Policy and Procedures. Also, process for purchasing.
- Academic Manager: Moodle requirements (courses, online and blended delivery, assessments) and user acceptance testing (UAT) with trainers.
- Compliance & QA Officer: checks privacy, accessibility (WCAG 2.2), RTO compliance requirements and head of QA office. Also, provide trainning staff
- Marketing Manager and Marketing Assistant: website content and multilingual information.
- Technician engineer: Network, security, cloud and monitoring
- Developer: Website and APIs design


# COST x Units x Time

Total Time: 12 months + 6 months (technical support)

Quantity | Cost/unit | Total cost

## Hardware

- Workstations: 12 | $1,600 | $19,200
- Laptops: 12 | $2,000 | $24,000
- Classroom devices: 30 | $1,200 | $36,000
- Cloud or dedicated servers: 12 months | $900/month | $10,800
- Backup storage: 1 set (local and offsite) | $4,000 | $4,000
- Firewalls at each campus: 3 | $4,500 | $13,500
- Routers, switches, access points: 6 switches, 15 access points (routing on firewalls) | $2,500 / $700 | $25,500
- Redundant network devices: 2 (HA firewall, spare switch) | $4,500 / $2,500 | $7,000
- Endpoints: 54 | Included in workstations, laptops and classroom devices | $0

* Hardware subtotal: $140,000

## Software

- Operating systems: 54 | Included in device price (OEM) | $0
- Suites: 24 users | $36/user/month | $10,368
- Licences: 24 users | Included in suites | $0
- Identity and access management: 24 users | Included in suites (role-based access, MFA) | $0
- Endpoint protection: 54 endpoints | Included in suites | $0
- Security monitoring and logging tools: 54 endpoints | $80/year | $4,320
- Backup and disaster recovery software: 1 annual subscription | $3,496 | $3,496
- Encryption of data at rest: 1 | Included in cloud services | $0
- Existing Moodle: 1 modernisation (third-party provider) | $20,000 | $20,000
- Secure APIs for Moodle and website integration: 1 integration | Included in Developer | $0
- Website CMS: 1 (theme, multilingual and accessibility plugins) | $2,100 | $2,100

* Software subtotal: $40,284

## Network

- ISP, high bandwidth, with redundant connection: 3 campuses | $4,800/year | $14,400
- Secure WAN/VPN links between campuses: 2 | Included in firewalls (IPSec) | $0
- LAN network: 3 campuses | Included in switches and Technician engineer | $0
- Wi-Fi network: 3 campuses | Included in access points and Technician engineer | $0
- Encrypted connections for the website and Moodle: 2 SSL/TLS certificates | $250/year | $500
- Secure network access for API integration between Moodle and website: 1 | Included in firewalls and Developer | $0

* Network subtotal: $14,900

## Interface

- GUI for website: 1 | Included in Website CMS and Developer | $0
- GUI for Moodle: 1 | Included in Moodle modernisation | $0
- Responsive design for Moodle and website: 2 | Included in Moodle modernisation and Developer | $0
- Accessible interface: 2 (WCAG 2.2) | Included in Moodle modernisation, Developer and Compliance & QA Officer | $0
- Multilingual support on the website: 1 | Included in Website CMS and Marketing | $0
- Secure API interface between Moodle and website: 1 | Included in Developer | $0
- Access for external parties and internal users: 1 | Included in suites (IAM) and Moodle | $0

* Interface subtotal: $0 (costed in Hardware, Software and Professional Services)

## Security requirements

- Authentication and access control: 24 users | Included in suites (MFA, role-based access) | $0
- Preventing hacking, virus and malware: 1 set of testing tools (vulnerability scan, load and accessibility testing) | $5,800 | $5,800
- Encryption: 1 | Included in cloud services, firewalls and SSL/TLS | $0
- Secure APIs: 1 | Included in Developer | $0
- Security monitoring: 1 | Included in security monitoring and logging tools | $0
- Privacy and confidentiality: 1 (data breach response plan) | Included in Compliance & QA Officer | $0
- Backup and disaster recovery: 1 | Included in backup storage and backup and DR software | $0
- Web and web server security: 1 | Included in Technician engineer and Developer | $0
- Workstation and physical security: 54 endpoints | Included in suites and Technician engineer | $0
- Internal security breaches: 1 set of staff security awareness training materials | $3,000 | $3,000

* Security subtotal: $8,800

## Professional Services

- IT Manager: 418 hours (22 weeks at 0.5 FTE) | $92/hour | $38,456
- Finance & Administration Manager: 80 hours | $82/hour | $6,560
- Academic Manager: 120 hours | $79/hour | $9,480
- Compliance & QA Officer: 160 hours | $59/hour | $9,440
- Marketing Manager and Marketing Assistant: 80 hours / 120 hours | $76 / $46 per hour | $11,600
- Technician engineer: 760 hours (20 weeks) | $95/hour | $72,200
- Technician engineer support 1000 hours (6 months):  (Block of Hours) | $50/hour | $50,000
- Developer: 380 hours (10 weeks) | $100/hour | $38,000

* Professional Services subtotal: $185,736

---
* Subtotal: $439,720
* Contingency (10%): $43,972
* Total project budget: $483,692



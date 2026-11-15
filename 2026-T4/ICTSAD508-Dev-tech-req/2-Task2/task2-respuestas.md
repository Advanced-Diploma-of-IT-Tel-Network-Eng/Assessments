
# Section 1: Planning

King Edward VII College became a Registered Training Organisation (RTO) in 2010 and is based in Melbourne's CBD.

It is nationally recognised for the quality of its courses in management, marketing, human resources, and international business. It currently has around 500 students. Its staff includes 24 members, 14 of whom are trainers and assessors.

The college follows the quality guidelines of the national VET Quality Framework and implements a continuous improvement system.

# Goals and objectives:

- To be leaders in quality in VET courses
- To establish and maintain high quality services (staff/platform)
- To be a profitable and high-performing organisation

# Business model:

- Value proposition: high-quality, industry-ready training, competitive pricing, highly qualified, experienced training staff and innovative teaching methods.
- Target customer base: people who want to formalise and develop their skills. Also, people entering the industry, people already working in the sector.
- Delivery: classroom, blended (face-to-face/online) and online courses.
- Revenue: course fees, payment plans.
- Marketing strategy: continuous market research, information sessions, an improved website and targeted campaigns

# Business Requirements:

- Outdated ICT system: A recognised weakness
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

- Information security and cybersecurity policies, including acceptable use, passwords and access control.
- Backup and disaster recovery procedure.
- Procedures for planning and implementing projects (SDLC) and change management.
- Risk management procedures for ICT projects.
- OHS policies for hardware installation and workstations.
- Documentation procedures for hardware and software solutions, such as asset registers and network diagrams.

# Hardware, software,  network and interface requirements

## Hardware
- Related to staff work
	- Workstations
	- laptops
	- classroom devices
	
- Related to the general functioning of the network
	- ISP, high bandwidth
	- Redundancy network devices
	- Cloud or dedicated servers
	- WAN/VPN links
- Related to accessibility
	- Accessible interface WCAG
	- Accessible interface multilingual support
	
- Related to Network and security
	- LAN network private/public
	- Wi-Fi network private/public
	- Endpoints
	- Routers, switches, firewalls, access points

## Software

Operating systems
Suits (cloud, on-premise)
Licenses 
Website
Moodle

## Interface
- GUI for the website
- GUI for moodle
- Responsible design moodle/website
- Network infrastructure digram 
- ICT infrastructure map

# Security requirements
Although no business solutions have been proposed, I believe the following essential security requirements must be met:

- Authentication and access control: strong passwords, password changes, two-step authentication (MFA) and role-based access for staff and students.
- Preventing hacking, virus and malware: firewalls, endpoint protection, and regular patching and updates.
- Encryption: HTTPS (SSL/TLS) for the website and moodle, VPN (IPSec) between campuses, and encryption of data at rest in the cloud.
- Privacy and confidentiality: protection of student and staff personal information under the Privacy Act 1988, including a data breach response plan.
- Backup and disaster recovery: regular, tested backups, both cloud and offsite, to protect against data corruption and hardware failure.
- Web and web server security: secure configuration of the website, moodle and servers.
- Workstation and physical security: screen locks, physical locks on server and network rooms, and asset tagging.
- Internal security breaches: an information security policy, logging and monitoring, and staff security awareness training.
---

# Section 2: Meeting

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
The College prioritises a secure and scalable infrastructure. After reviewing the provisional hardware, software, network, and interface requirements and discussing stakeholder needs, Alex concluded that the system must be faster, more efficient, sustainable, and secure for both staff and students, while aligning with the College's strategic objectives.


## Discussion and feedback
Alex confirmed that the 3 proposed business solutions generally align with the College's objectives, though he requested clearer descriptions of the security requirements. Since the College already uses a third-party Moodle platform, he advised modernising the existing system through the current provider rather than replacing it—avoiding high costs and data migration risks—and suggested developing APIs to integrate it with the College website.

## Agreed business solutions

1. ICT Infrastructure Upgrade and Security:
Upgrade the College’s ICT infrastructure to make it faster, more efficient and sustainable, support cloud access, and connect the College’s campuses. The solution must include defined security controls: 
- role-based access
- multifactor authentication
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


## AFTER MEETING: 1 WEEK

In a follow-up meeting a week later, Alex was presented with the budget and timeline, along with all the cost and technical details as agreed. The project now includes technical support for the six months following its completion.

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

- Authentication and access control: strong passwords, password changes, multifactor authentication (MFA) and role-based access for staff and students.
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
- Compliance & QA Officer: checks privacy, accessibility (WCAG 2.2), RTO compliance requirements and head of QA office. Also, provide training staff
- Marketing Manager and Marketing Assistant: website content and multilingual information.
- Technician engineer: Network, security, cloud and monitoring
- Developer: Website and APIs design

# COST x Units x Time

Total Time: 12 months + 6 months (technical support)

Quantity | Cost/unit | Total cost

## Hardware

- ThinkPad E14_Gen7 (AMD7_250): 100x3campuses| $1,649 | $49,470
- Classroom devices: 300 | $1,200 x3campuses | $360,000

*Hardware subtotal: $136,490 (each campus)

## Software

- Suite Google Workspace plus: 1 year/100 users | $1,545 | $1,545
- Identity and access management: 300 staff | Included in suite/Cloud (role-based access, MFA) | $0
- Endpoint protection: Cloud endpoints | Included in Cloud | $0
- Security monitoring and logging tools | Included FortiNet | $0
- Backup and disaster recovery software | included Cloud | $0
- Encryption of data at rest: 1 | Included in cloud | $0
- Moodle Cloud upgrade plan Standard: 1 modernisation | $1,300 | $1,300
- Secure APIs for Moodle and website integration: 1 integration | Included in Developer | $0
- TALKK Website CMS: 1 (theme, multilingual and accessibility plugins) | $25,000 | $25,000
- Endpoint FortiClient EPP/ATP Cloud FC3-10-EMS05-428: 2000 pack- 1 year | $21,060 | $21,060

*Software subtotal: $16,301  (each campus)

## Network

- ISP Telstra Small Business, pro ultra fast nbn: 3 campuses | $1,908/campus | $5,724
- Secure WAN/VPN links between campuses: 2 | Included in firewalls | $0
- LAN network: 3 campuses | Included in switches and Technician engineer | $0
- Wi-Fi network: 3 campuses | Included in access points and Technician engineer | $0
- Encrypted connections for the website and Moodle: included Cloud/Moodle/Web | $0 | $0
- Secure network access for API integration between Moodle and website: 1 | Included in Developer | $0
- HUB-Firewall FortiGate 200G: 1 | $17,165 | $17,165
- Campus Firewall FortiGate 70G: 3 | $2,337 | $7,011
- Distributed switch Ubiquiti UniFi Pro Max 48: 6x3campuses | $1,435 | $25,830
- Wi-fi 7 Ubiquiti UniFi U7 Pro: 30x3campuses | $568 | $51,200

*Network subtotal: $188,976  (each campus)

## Interface

- GUI for the website: 1 | Included in Website CMS and Developer | $0
- GUI for Moodle: 1 | Included in Moodle modernisation | $0
- Responsive design for Moodle and website: 2 | Included in Moodle modernisation and Developer | $0
- Accessible interface: 2 (WCAG 2.2) | Included in Moodle modernisation, Developer and Compliance & QA Officer | $0
- Multilingual support on the website: 1 | Included in Website CMS and Marketing | $0
- Secure API interface between Moodle and website: 1 | Included in Developer | $0
- Access for external parties and internal users: 1 | Included in suites (IAM) and Moodle | $0

*Interface subtotal: $0 (costed in Hardware, Software and Professional Services)

## Security requirements

- Authentication and access control: 100 users | Included in Software (MFA, role-based access) | $0
- Hardening: vulnerability scan, load and accessibility testing | $1,995 | $1,995
- Encryption: 1 | Included in cloud services, firewalls and SSL/TLS | $0
- Secure APIs: 1 | Included in Developer | $0
- Backup and disaster recovery: 1 | Included Cloud | $0
- Web and web server security: 1 | Included TALKK | $0
- Workstation and physical security | Included Technician engineer/FortiNet | $0
- Internal security breaches: 1 set of staff security awareness training materials | icluded PS| $0

*Security subtotal: $1,995

## Professional Services

- IT Manager: 960 hours | $83/hour | $XXX
- Finance & Administration Manager: 80 hours | $83/hour | $XXX
- Compliance & QA Officer: 160 hours | $35/hour | $XXX
- Marketing Manager and Marketing Assistant: 80 hours / 120 hours | $34 / $39 per hour | $4,680
- Technician engineer: 960 hours | $41/hour | $XXX
- Technician engineer support: 1000 hours (6 months, Block of Hours) | $41/hour | $41,000
- APIs Developer: 96 hours | $80/hour | $XXX

*Professional Services subtotal: $184,640


## Cost Analysis
- Discount: 25% (by Bulk purchasing on Hardware and network devices)
- Fixed: $245,595 ($327,461)
- Variable: $200,941
- Budget: $446,536

## NEW Meeting Summary
Alex accepted the budget and timeline. He also accepted the updated hardware, software, network, interface requirements and professional services document.

The project begins immediately.

---

# Section 3: Technical requirements 

Find presentation on "presentation.pptx" or "presentation.md"

---


# Section 4: Impact statement

Fin the document on "Impact-statement.md"

# Meeting Notes Impact statement: 

## Attendees:
- Selina Garcia - Academic Manager
- Nomthandazo Adebayo - Finance Manager
- Chandra Singh - Marketing Manager


## General concerns
Each service provider has its own T support team, so if it's not one of our services, you should contact them directly.

Costs and renewals associated with licenses purchased from providers are managed directly with them after the first year of service with us.

The cost of licenses, services, and equipment is covered by an SLA, so the agreed-upon prices will not increase, regardless of the city to which the equipment needs to be shipped; these costs are already included in the total equipment cost.

The cost of the project with us will be handled by the finance team, so they will contact your finance team directly to discuss the details.

The cost of licenses and services is for one year, so you don't need to worry about additional costs in the first year.

All employees at all College locations will receive basic cybersecurity training.

Each division will receive training focused on its area of ​​work. For example, the marketing team will receive special marketing training under the new provider.

All equipment is new and therefore under direct warranty with the provider. All equipment will be delivered with the secure configuration required by the College. In addition, two of the computers have Antonio Neville features, so you shouldn't worry about whether your equipment will run the new software without problems; the equipment is designed to last up to 10 years.

All providers comply with data protection regulations under the Copyright Act 1968.

## Moodle. Selina Garcia - Academic Manager
An agreement has been reached with MoodleCloud to upgrade the subscription to a higher version, so no student will lose their progress, and no administrator will lose their system configuration.

Moodle will not require migration, as we will continue with the same provider. Therefore, the change will be transparent for everyone and will take effect immediately the day after the license upgrade is authorized with Moodle.

The new MFA security measures will be automatically applied by the provider, and the user will be notified to update their password and authentication method.

## MARKETING. Chandra Singh's concerns

From now on, all marketing guidelines will be managed through the TALKK CMS. An API is being developed to integrate Moodle and the College's current functions, so all current marketing will work on the new site. The domain will remain the same, as the College owns its web domain.

All accessibility content will be verified by TALKK to comply with WCAG 2.2.


## Meeting Notes

## 1. General items (all attendees)

| Concern raised | Response / agreement |
|---|---|
| Who provides support | Each supplier provides its own IT support for its service. For third-party services, staff contact the supplier directly. IT supports College-owned systems. |
| Licence costs and renewals | Licences and services are paid for the first year. No additional costs in year one. From year two, renewals are managed directly with each supplier. |
| Price increases and campus locations | Licences, services and equipment are covered by an SLA. Agreed prices will not increase, and delivery to any campus (Melbourne, Sydney, Brisbane) is included in the total equipment cost. |
| Project cost details | IT will work directly with the Finance team on the project cost details and payment schedule. |
| Training | All staff at all campuses will complete basic cyber security training. Each division will also receive training focused on its area (e.g. Marketing on the new CMS). |
| Equipment | All equipment is new, covered by direct supplier warranty and delivered with the College's secure configuration. Specifications are high-end, so devices will run the new software without issues and are designed for a long service life. |
| Data protection | All suppliers comply with data protection requirements under the Privacy Act 1988. |

## 2. Moodle (Selina Garcia)

| Concern raised | Response / agreement |
|---|---|
| Loss of student progress or admin settings | The MoodleCloud subscription will be upgraded to a higher plan with the same provider. No student progress or administrator configuration will be lost. |
| Migration and downtime | No migration is required. The change is transparent and takes effect the day after the licence upgrade is authorised. |
| MFA impact on users | MFA is applied automatically by the provider. Each user will be notified to update their password and authentication method. |

## 3. Website (Chandra Singh)

| Concern raised | Response / agreement |
|---|---|
| Marketing campaigns and current functions | All marketing campaigns will be managed through the TALKK CMS. APIs are being developed to integrate Moodle and current College functions, so all current marketing will work on the new site. |
| Domain and online presence | The domain stays the same, as the College owns its web domain. |
| Accessibility | TALKK will verify all content for WCAG 2.2 compliance. |

## 4. Outcome
Stakeholder concerns were addressed. The initial recommendations were maintained, with no changes to the accepted budget or timeline.

## 5. Actions

| Action | Owner | Due |
|---|---|---|
| Meet Finance on project cost details and payment schedule | Manuel Perez / Nomthandazo Adebayo |
| Schedule cyber security and division-specific training | Manuel Perez / Roy Ayoade |
| Authorise MoodleCloud licence upgrade and notify users about MFA | Manuel Perez / Selina Garcia |
| Confirm TALKK CMS training and WCAG 2.2 review plan | Manuel Perez / Chandra Singh |



---
# Section 4: File Upload page

Source of research: 
I was a PS (technical) engineer, so I'm developing the assessment from that perspective, which is why it's the most expensive part of the project. I used Seek to determine the hourly rate for a PS in Australia. I used my experience developing a bank platform modernisation project and a bank transactional switch modernisation project to develop the three business proposals.

Find Email evidence on "email-1.txt", "email-2.txt" and "email-3.txt"

---


# Section 5: Planning for implementation

---

# Section 6: Finalisation


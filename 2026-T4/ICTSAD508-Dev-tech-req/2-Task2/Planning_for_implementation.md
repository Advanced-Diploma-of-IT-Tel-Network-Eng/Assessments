# Planning for implementation 

## Business solutions: 

1. ICT Infrastructure Upgrade and Security 

2. Modernisation and Integration of the Existing Moodle 

3. Website Improvement 

## Testing Setup 

|**Business Solution**|**Test Environment**|**What**|**Responsible**|
|---|---|---|---|
|**ICT Infrastructure Upgrade and**<br>**Security**|Pilot on campus|- All network: VPN, LAN, VLAN, WLAN, Wi-Fi.<br>Testing software GNS3<br>- Internet Telstra<br>- Laptops ThinkPad<br>- classroom devices<br>- FortiGate 200G (hub) y FortiGate 70G<br>(campus) with test VPN IPSec<br>- Switches UniFi y access points Wi-Fi 7<br>- Google Workspace features<br>- FortiClient<br>- MFA<br>- Web filtering<br>- Backup|Technician<br>engineer|
|**Modernisation and Integration of the**<br>**Existing Moodle**|MoodleCloud|- Access to all courses<br>- Trial course<br>- Student and trainer trial accounts<br>- Check data integrity: students and staff<br>- MFA<br>- Secure API connection|Academic<br>Manager / APIs<br>Developer|
|**Website Improvement**|Website developed<br>by TALKK +<br>CMS|- multilingual and accessibility features<br>- API Moodle<br>- Marketing|APIs<br>Developer /<br>Marketing<br>Manager|



### Performance Benchmarks: 

#### Business Benchmarks: 

|**Business Solution**||**Benchmark**|**Source**||
|---|---|---|---|---|
|**ICT Infrastructure Upgr**|**ade and Security**|Does the ICT system meet the needs of staff<br>and students?|ICT Test Environ|ment|
|**ICT Infrastructure Upgr**|**ade and Security**|Can data be retrieved via cloud access?|ICT Test Environ|ment|
|**Modernisation and Inte**<br>**Existing Moodle**|**gration of the**|Are all courses offered online?<br>Did the number of students increase by 12%?|Website Moodle|and Website Test|
|**Website Improvement**||10% more students, 5% higher market share|Website Test||
|echnical Benchmarks:<br>**Area**||**Benchmark**||**Source**|
|**Network speed**|nbn 100<br>975 Mbps Download<br>350 Mbps Uploading|<br>||Vendor<br>performance<br>statement<br>(Telstra)|
|**Firewall (campus)**|FortiGate 70G: IPse<br>threat protection up t<br>Real speeds are limi|c VPN 7.1 Gbps<br>o 1.3 Gbps.<br>ted by internet bandwidth||Vendor<br>performance<br>statement<br>(FortiGate)|



Technical Benchmarks: 

||UniFi U7 Pro||
|---|---|---|
|**Wi-Fi**|- **6 GHz**: 2 x 2 (DL/UL MU-MIMO): **5.8 Gbps** (up to 5,765 Mbps in earlier<br>datasheets): Up to **320 MHz** (BW320)<br>- **5 GHz**: 2 x 2 (DL/UL MU-MIMO): **4.3 Gbps** (2,882 Mbps in earlier datasheets): Up<br>to **240 MHz** (BW240)<br>- **2.4 GHz**: 2 x 2 (DL/UL MU-MIMO):**688 Mbps**: Up to**40 MHz**(BW40)|Vendor<br>performance<br>statement<br>(Ubiquiti)|
|**Classroom devices**|Online trial class with uninterrupted audio and video|Vendor<br>Performance|
|**Website speed**|Loading landing page in 2.5 seconds|Google Core<br>Web Vitals|
|**Load**|500 students and Staff|IC Test<br>environment|
|**Accessibility**|Website<br>Moodle WCAG 2.2 Level A|Website<br>Test<br>Environment|
|**Security**|MFA<br>role-based access<br>Hardening: 0 critical vulnerabilities|IC Test<br>environment|
|**Backup**|Backup restored|IC Test<br>environment|



## Test Plan and Results: 

### ICT Infrastructure Upgrade and Security 

|**Test**|**Expected Benchmark**|**Result**|**Outcome**|
|---|---|---|---|
|**Speed test**<br>**(nbn)**|Downloading 975<br>Uploading 350|Downloading 900<br>Uploading 340<br>Ping 5ms|The average results are lower than<br>the reference values but are within<br>the acceptable range.|
||200G - 36<br>Tunnelling speed IPSec|35.4Gbps<br>76.98Gpbs||
|**VPN hub -**<br>**campus**<br>**(IPSec)**|70G – 7.1<br>Tunnelling speed IPSec<br>Ping<br>tunnel uptime 30min<br>Traceroute|20/20 and 30/30  packages<br>0% loss<br>avg 9ms<br>min 8 – max 12<br>3 hops: 10.20.1.1 (70G) to<br>10.255.0.1 (tunnel IPsec) to<br>10.10.0.1 (200G hub), 8 ms|The result is less than 3%.<br>Accepted.|
|**Remote**<br>**VPN (staff)**|Private network Staff<br>Private network Students<br>Public Network|Accessible, stable session<br>Accessible, stable session<br>Accessible, stable session|Accepted|
|**Wi-Fi**<br>**coverage**|Wi-Fi coverage~100m|98m – inside<br>12ms<br>-10% internet speed at 100m|Results are better than 10% under<br>adverse conditions. Accepted|



|**Laptops**|Secure configuration<br>Hardening<br>pre-installed software|Checked<br>Approved, secure<br>Checked by staff|Accepted|
|---|---|---|---|
|**Classroom**<br>**devices**|Online Clase, video, audio, files|All devices working|Accepted|
|**Cloud**<br>**access**|Backup restored from Google Workspace|Restored, no file issues, integrity<br>checked|Accepted|
|**MFA and**<br>**role-based**<br>**access**|MFA<br>Role base|MFA working, SMS, email, app|Accepted|
|**Endpoint**<br>**protection**|FortiClient runs antimalware<br>advance-protection<br>Monitoring<br>Reporting<br>Blocking|EICAR file detected, blocked,<br>deleted and/or quarantine and<br>reported<br>Endpoint: Online<br>Real-time protection: on<br>DB updated|Accepted|
|**Web**<br>**filtering**|Blocking<br>news<br>Gambling<br>Games<br>Adult|Website blocked and reported<br>Endpoint: Online<br>Real-time protection: on|Approved|
|**Vulnerabilit**<br>**y scan**|0 critical vulnerabilities|No threats|Approved|
|**Backup and**<br>**restore**|Test file is recoverable|Restored, no file issues, MD5<br>integrity checked|Approved|



### Modernisation and Integration of the Existing Moodle 

|**Test**|**Expected Benchmark**|**Result**|**Outcome**|
|---|---|---|---|
|**Existing data**<br>**after upgrade**|No missing information|No missing information|Approved|
|**Course**<br>**access**<br>**(functionality)**|Students and trainers have access to and use courses,<br>resources, and assessments.|Students and trainers<br>have access to and use<br>courses, resources, and<br>assessments.|Approved|
|||Notification received by<br>the MFA app|Approved|
|**MFA**|Sent notification to setting up MFA|||
|**Responsive**<br>**design**<br>**(compatibility**<br>**)**|All work and classroom devices are working|All devices working|Approved|
|**Load**|Load test with 500 students+staff, no issues|Downloading avg<br>1.7Mbps<br>Uploading avg 168Mbps<br>less than 32ms<br>Packet loss less tan<br>0.4%|For 500+ people, the<br>download speed drops<br>considerably; however, it<br>is sufficient for tasks<br>within Moodle and<br>audio/video.|



||||Approved|
|---|---|---|---|
|**Accessibility**|Comply WCAG 2.2 Level A|Comply WCAG 2.2<br>Level A|Approved|
|**User**||Passed all test courses|Approved|
|**acceptance**<br>**testing (UAT)**|Testing course approved|||



### Website Improvement 

|**Test**|**Expected Benchmark**|**Result**|**Outcome**|
|---|---|---|---|
|**Functionality**<br>**and**<br>**navigation**|<br>Landing page<br>Links<br>Moodle<br>Marketing|2s<br>All links working<br>Moodle accessible<br>Marketing is showing as<br>excepted|Approved|
|**Content**<br>**checking**|Courses information|The course, title,<br>information, and content<br>are reproduced<br>correctly.|Approved|
|||The content changes<br>language|Approved|
|**Multilingual**|Language change available|||



|||Comply WCAG 2.2<br>Level A|Approved|
|---|---|---|---|
|**Accessibility**|Comply WCAG 2.2 Level A|||
|||Avg 2s|Approved|
|**Performance**|Loading lading page in less than 2.5s|||
|**Interface**<br>**(API)**|Login to Moodle and APIs working|Moodle, API to Moodle,<br>API to Marketing<br>working|Approved|
||HTTPS (SSL/TLS)|valid and functional<br>certificates<br>0 threats|Approved|
|**Security**|0 critical vulnerabilities|||
|**W3C**<br>**validation**|0 critical errors|0 critical errors|Approved|



## Trainning Sessions 

|**Staff/Group**|**Skill required**|**Current GAP**|**Training**|**Delivery**|**Responsible**|
|---|---|---|---|---|---|
|**All**<br>**campuses**<br>**staff**|Cybersecurity<br>awareness, MFA<br>usage, and VPN|MFA and mandatory<br>VPN are new|Basic<br>Cybersecurity<br>Training|Online|Manuel Perez / Roy<br>Ayoade|
|**All staff**|New laptops and<br>Google<br>Workspace|New operating<br>system, 100% cloud-<br>based|Introduction to<br>Workspace and<br>Laptops|Workshop and User Guide|Technician engineer|
|**Trainers**<br>**and**<br>**assessors**|Classroom<br>devices|New audio and video<br>equipment|Short Classroom<br>Session|Workshop|Technician engineer|
|**Trainers**<br>**and**<br>**assessors**|Improved Moodle<br>(courses,<br>assessments)|New features in the<br>enhanced plan|Moodle Training|Workshop|Academic Manager|
|**Students**|Moodle login with<br>MFA|MFA is new|User Guide and<br>Vendor Notice|Online Guide|Academic Manager|



|**Marketing**<br>**team**|TALKK CMS and<br>multilingual<br>content|New campaign tool|CMS Training|Vendor (TALKK)|Marketing Manager /<br>TALKK|
|---|---|---|---|---|---|
|**Compliance**<br>**& QA**<br>**Officer**|WCAG 2.2 review|Content accessibility<br>review|Accessibility<br>Review Training|Vendor (TALKK)|Compliance & QA<br>Officer|
|**Finance**<br>**team**|License renewal<br>from year 2|New process with<br>each vendor|SLA and Renewal<br>Briefing|Meeting|Manuel Perez /<br>Finance &<br>Administration<br>Manager|
|**IT team**|Firewall, VPN,<br>and monitoring|New Fortinet and<br>UniFi equipment|Fortinet and UniFi<br>Administration|Vendor / Vendor<br>Documentation|Technician engineer|



## Implementation Schedule 

|**No**|**Task**|**Solution**|**Duration**<br>**(Months)**|**Milestone**|
|---|---|---|---|---|
|1|Quotations and purchases<br>according to the Purchasing<br>Policy and Procedures.|All|1|Purchase orders approved|
|2|Pilot setup and testing.|ICT<br>Infrastructure<br>Upgrade and<br>Security|1|Pilot results approved|
|3|MFA guide and basic<br>cybersecurity training.|||Users notified|
|||All|1||
|4|MoodleCloud upgrade, MFA,<br>and Moodle UAT.|Modernisation<br>and<br>Integration of<br>the Existing<br>Moodle|1|Moodle improved and approved|



|5|Network and security<br>deployment in Melbourne.|ICT<br>Infrastructure<br>Upgrade and<br>Security|2|Melbourne campus live|
|---|---|---|---|---|
|6|Website design and content<br>(TALKK).|Website<br>Improvement|4|Staging site approved|
|7|Network and security<br>deployment in Sydney and<br>Brisbane.|ICT<br>Infrastructure<br>Upgrade and<br>Security|3|All campuses connected|
|8|Secure Moodle API - website.|Modernisation<br>and<br>Integration of<br>the Existing<br>Moodle<br>Website<br>Improvement|2|API tested|
|9|Final testing: accessibility,<br>security, and load.|All|2|Test report approved|



|10|Staff training (TNA).|||All staff trained|
|---|---|---|---|---|
|||All|8||
|11|Website go-live.|Website<br>Improvement|0|New website live|
|12|Final review and sign-off.|All|0|Project sign-off|
|13|Technical support.|All|5|Support period ended|



## Resources 

### Human Resources 

|**Role**|**Responsibility**|**Hours**|
|---|---|---|
|**IT Manager**|Project lead, vendors, budget, approvals and sign-off|960|
|**Finance &**<br>**Administration**<br>**Manager**|Budget control and purchasing approvals|80|
|**Academic**<br>**Manager**|Moodle requirements and UAT||
|**Compliance &**<br>**QA Officer**|Privacy, WCAG 2.2, RTO compliance, staff training|160|
|**Marketing**<br>**Manager and**<br>**Marketing**|Website content and multilingual information|80 /<br>120|



|**Assistant**|||
|---|---|---|
|**Technician**<br>**engineer**|Network, security, cloud and monitoring|960|
|**Technician**<br>**engineer**<br>**support**|Technical support (6 months)|1,000|
|**APIs**<br>**Developer**|Website and API design|96|



### Physical Resources & Costs by Category 

#### Hardware 

|**Item**|**Quantity**|**Cost/Unit**|**Total**|
|---|---|---|---|
|ThinkPad E14_Gen7 (AMD7_250)|100 x 3 campuses|$1,649|$49,470|
|Classroom devices|300 (3 campuses)|$1,200|$360,000|
|**Subtotal Hardware**|**136490 (each campus)**|||



Software 

|**Item**|**Quantity**|**Cost/Unit**|**Total**|**Detail**|
|---|---|---|---|---|
|Suite Google Workspace plus|1 year / 100 users|$1,545|$1,545||
|Identity and access management|300 staff|Included|$0|Included in<br>suite/Cloud (role-<br>based access, MFA)|
|Endpoint protection|Cloud endpoints|Included|$0|Included in Cloud|
|Security monitoring and logging<br>tools|-|Included|$0|Included FortiNet|
|Backup and disaster recovery<br>software|-|Included|$0|Included Cloud|



|Encryption of data at rest|1|Included|$0|Included in cloud|
|---|---|---|---|---|
|Moodle Cloud upgrade plan<br>Standard|1 modernisation|$1,300|$1,300||
|Secure APIs for Moodle and<br>website integration|1 integration|Included|$0|Included in<br>Developer|
|TALKK Website CMS|1|$25,000|$25,000|Theme, multilingual<br>and accessibility<br>plugins|
|Endpoint FortiClient EPP/ATP<br>Cloud FC3-10-EMS05-428|2000 pack - 1 year|$21,060|$21,060||
|**Subtotal Software**|**16301 (each campus)**||||



#### Network 

|**Item**|**Quantity**|**Cost/Unit**|**Total**|**Detail**|
|---|---|---|---|---|
|ISP Telstra Small Business, pro<br>ultra-fast nbn|3 campuses|$1,908 / campus|$5,724||
|Secure WAN/VPN links between<br>campuses|2|Included|$0|Included in firewalls|
|LAN network|3 campuses|Included|$0|Included in switches<br>and Technician<br>engineer|
|Wi-Fi network|3 campuses|Included|$0|Included in access<br>points and<br>Technician engineer|
|Encrypted connections for the<br>website and Moodle|-|Included|$0|Included<br>Cloud/Moodle/Web|
|Secure network access for API<br>integration between Moodle and<br>website|1|Included|$0|Included in<br>Developer|
|HUB-Firewall FortiGate 200G|1|$17,165|$17,165||
|Campus Firewall FortiGate 70G|3|$2,337|$7,011||
|Distributed switch Ubiquiti UniFi<br>Pro Max 48|6 x 3 campuses|$1,435|$25,830||



|Wi-fi 7 Ubiquiti UniFi U7 Pro|30 x 3 campuses|$568|$51,200|
|---|---|---|---|
|**Subtotal Network**|**188976 (each campus)**|||



#### Interface 

|**Item**|**Quantity**|**Cost/Unit**|**Total**|**Detail**|
|---|---|---|---|---|
|GUI for the website|1|Included|$0|Included in Website<br>CMS and Developer|
|GUI for Moodle|1|Included|$0|Included in Moodle<br>modernisation|
|Responsive design for Moodle and<br>website|2|Included|$0|Included in Moodle<br>modernisation and<br>Developer|
|Accessible interface|2 (WCAG 2.2)|Included|$0|Included in Moodle<br>modernisation,<br>Developer and<br>Compliance & QA<br>Officer|
|Multilingual support on the website|1|Included|$0|Included in Website<br>CMS and Marketing|



|Secure API interface between|1<br>Included|$0|Included in|
|---|---|---|---|
|Moodle and website|||Developer|
|Access for external parties and|1<br>Included|$0|Included in suites|
|internal users|||(IAM) and Moodle|
|**Subtotal Interface**|**$0 Costed in Hardware, Software and Pr**|**ofessional Services**||



#### Security Requirements 

|**Item**|**Quantity**|**Cost/Unit**|**Total**|**Detail**|
|---|---|---|---|---|
|Authentication and access control|100 users|Included|$0|Included in Software<br>(MFA, role-based<br>access)|
|Hardening|1|$1,995|$1,995|Vulnerability scan,<br>load and accessibility<br>testing|
|Encryption|1|Included|$0|Included in cloud<br>services, firewalls<br>and SSL/TLS|
|Secure APIs|1|Included|$0|Included in<br>Developer|
|Backup and disaster recovery|1|Included|$0|Included Cloud|
|Web and web server security|1|Included|$0|Included TALKK|
|Workstation and physical security|-|Included|$0|Included Technician<br>engineer/FortiNet|
|Internal security breaches|1 set|Included|$0|Staff security<br>awareness training<br>materials (Included<br>PS)|
|**Subtotal Security**|**$1,995**||||



#### Professional Services 

|**Rol**|**Time**|**Rate**|**Total**|**Detail**|
|---|---|---|---|---|
|IT Manager|960 hours|$83|$79,680||
|Finance & Administration Manager|80 hours|$83|$6,640||
|Compliance & QA Officer|160 hours|$35|$5,600||
|Marketing Manager and Marketing<br>Assistant|80 hrs / 120 hrs|$34 / $39|$4,680||
|Technician engineer|960 hours|$41|$39,360||
|Technician engineer support|1000 hours|$41|$41,000|6 months, Block of<br>Hours|
|APIs Developer|96 hours|$80|$7,680||
|**Subtotal Professional Services**|**$184,640**||||



## Cost Analysis 

|**Item**|**Amount**|**Detail**|
|---|---|---|
|Discount|25%|By Bulk purchasing on Hardware and network devices|
|Fixed|$245,595|($327,461)|
|Variable|$200,941||
|**Budget**|**$446,536**||




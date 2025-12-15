# Cyberdyne Systems Corporation - Scenario Overview

## Company Profile

**Company Name:** Cyberdyne Systems Corporation  
**Industry:** AI and Robotics Manufacturing  
**Headquarters:** California, United States  
**Manufacturing Facility:** Taiwan  
**Employee Count:** 400 employees  
**Revenue Status:** Mid-sized enterprise  
**Government Vendor:** Yes (local, state, and potentially federal contracts)

---

## Business Operations

### Primary Business Activities

- **AI and Robotics Development:** Research and development of artificial intelligence systems and robotic technologies
- **Microprocessor Manufacturing:** Production of advanced microprocessors for AI applications
- **Government Solutions:** Vendor for government entities providing IT services, hardware, and software solutions
- **Customer Data Analysis:** Engineers work with high volumes of customer data for research and product development

### Geographic Operations

**California Location (Headquarters)**

- Administrative functions
- Research & Development center
- Engineering teams
- Executive offices
- Sales team base (primarily remote)
- IT operations center

**Taiwan Location (Manufacturing)**

- Production facility in densely populated industrial park
- Factory floor operations
- Local manufacturing workforce
- Quality control and testing
- International supply chain hub

---

## Organizational Structure

### Employee Distribution (400 Total)

| Department/Role | Count | Location |
|----------------|-------|----------|
| Engineers | 150 | Primarily California (R&D) |
| Sales Team | 50 | Remote (home-based) |
| Factory Workers | 50 | Taiwan |
| IT Staff | 45 | California |
| Executives | 10 | California |
| Managers | 25 | Both locations |
| HR/Administrative | 15 | Primarily California |
| Accounting | 20 | California |
| Administrative Staff | 20 | Both locations |
| Contract Workers | 15 | Various |

---

## Technology Infrastructure

### Device Inventory

**Desktop Workstations (200 units)**

- Operating System: Ubuntu 10.04 (End-of-Life April 2015)
- Processor: Dual Core CPU
- RAM: 2GB
- USB Ports: 8 ports
- Network: Ethernet connectivity
- **Security Issue:** Severely outdated OS, excessive USB ports, insufficient RAM

**Laptop Computers (300 units)**

- Operating System: Windows 10 Version 1607 (End-of-Life April 2018)
- Processor: Quad Core CPU
- RAM: 4GB
- USB Ports: 4 ports
- Network: Wi-Fi + Ethernet
- **Security Issue:** Outdated Windows version, travel internationally with sensitive data

**Android Tablets (150 units)**

- Operating System: Android 10 (Released 2019, 6 versions behind current)
- Use Case: Mobile workforce, field operations
- **Security Issue:** Outdated mobile OS lacking security patches

**iPad Tablets (Multiple units)**

- Operating System: iOS 13 (Released 2019, 13 versions behind current)
- Use Case: Executive mobile devices
- **Security Issue:** Severely outdated iOS with 5 years of missing security patches

**Windows Servers (100 units)**

- Operating System: Windows Server 2016 Standard
- Processor: Quad Core CPU
- RAM: 4GB
- **Security Issue:** Approaching end-of-life, insufficient RAM for modern server workloads

**Linux Servers (50 units)**

- Operating System: Ubuntu 14.04 LTS (End-of-Life 2019)
- Processor: Quad Core CPU
- RAM: 4GB
- **Security Issue:** 5+ years without security patches, insufficient resources

---

## Current Security Challenges

### Critical Issues

**1. End-of-Life Operating Systems**

- 200 desktops running Ubuntu 10.04 (10+ years old)
- 50 servers running Ubuntu 14.04 LTS (5+ years without patches)
- 300 laptops running Windows 10 v1607 (7+ years of missing updates)
- 150 Android tablets running Android 10 (3 years without patches)
- iPads running iOS 13 (5 years without security updates)

**2. Absence of Security Infrastructure**

- No corporate antivirus deployment
- No centralized identity management (Active Directory)
- No VPN for remote access
- No encryption for data transportation
- No centralized logging or SIEM
- No mobile device management

**3. Data Protection Gaps**

- Sensitive data transported via USB drives between locations
- Customer data emailed without encryption
- Laptops traveling internationally with unencrypted data
- Lost/stolen devices without remote wipe capability

**4. Access Management Weaknesses**

- Passwords shared and reused across accounts
- Local accounts on all systems (no centralized authentication)
- Multiple password requirements creating user frustration
- No multi-factor authentication

**5. Hardware Security Vulnerabilities**

- 8 USB ports on desktop workstations (excessive attack surface)
- 4 USB ports on traveling laptops (data exfiltration risk)
- Insufficient RAM preventing modern security tool deployment
- Dual-core processors unable to support real-time security scanning

### Operational Challenges

**High Employee Turnover**

- Frequent hiring required across all departments
- Employees report "exhaustion, dismay, and potentially negative attitudes"
- Onboarding time is minimal
- Security awareness training inadequate

**IT Skills Gap**

- IT staff "suffer from skills gap in picking up new technology"
- Versed in older systems but struggle with modern security technologies
- Difficulty deploying new systems and security controls

**Shadow IT**

- Employees using personal devices for ease of use
- Developing security shortcuts without IT knowledge
- Executives using personal machines instead of corporate devices

**Geographic Complexity**

- Data transfer between California and Taiwan facilities
- International travel with laptops containing sensitive data
- Taiwan factory experiences wireless interference from industrial park
- Regulatory compliance across multiple jurisdictions

---

## Compliance Requirements

### Regulatory Obligations

**California Consumer Privacy Act (CCPA)**

- Cyberdyne operates in California
- Handles customer personal information
- Requires encryption, access controls, breach notification
- Non-compliance: Fines up to $7,500 per violation

**Taiwan Personal Data Protection Commission (PDPC)**

- Taiwan manufacturing facility
- Employee data and local operations
- Consent management requirements
- Data protection impact assessments

**Government Vendor Requirements**

- Vendor for local and state governments
- Likely NIST 800-171 compliance required (CUI protection)
- Federal Acquisition Regulation (FAR) clauses
- Potential DFARS requirements if DoD contracts exist
- Possible ITAR/EAR compliance for technology export

### Compliance Gaps

Management reports being "often unaware of specific requirements for the regions they reside in for IT business practices," indicating:

- No formal compliance program
- Lack of regulatory requirement mapping
- No data protection impact assessments
- Inadequate breach notification procedures
- Missing contractual security obligations

---

## Business Risk Factors

**Revenue Risk**

- Loss of government contracts due to security failures
- Competitive disadvantage ("products from competitors seem to beat them on the market")
- Intellectual property theft (proprietary algorithms, AI research)

**Operational Risk**

- Device loss/theft without recovery capability
- Data breaches triggering regulatory penalties
- Ransomware potential with no backup strategy

**Reputational Risk**

- Customer data exposure
- Government client data breach
- Loss of vendor status
- Media coverage of security incidents

**Legal/Regulatory Risk**

- CCPA violation lawsuits and fines
- Government contract termination
- Suspension and debarment from future contracts
- Taiwan regulatory enforcement actions

---

## Assessment Objectives

This security assessment aims to:

1. **Identify Critical Vulnerabilities** - Document all security weaknesses across technology, policy, and human factors
2. **Recommend Technical Controls** - Provide specific, implementable security solutions
3. **Develop Policy Framework** - Create governance structure for sustainable security program
4. **Design Training Programs** - Address human layer through security awareness and specialized training
5. **Ensure Compliance** - Map recommendations to regulatory requirements (CCPA, PDPC, NIST 800-171)
6. **Create Implementation Roadmap** - Prioritize remediation activities based on risk
7. **Establish Defense-in-Depth** - Build multilayered security architecture resistant to single points of failure

---

## Success Criteria

A successful security program implementation will achieve:

- **All devices running current, supported operating systems**  
- **Enterprise endpoint protection deployed across all systems**  
- **Encryption for all data at rest and in transit**  
- **Centralized identity management with Active Directory**  
- **SIEM implementation providing security visibility**  
- **VPN with MFA for all remote access**  
- **Mobile Device Management for tablets and BYOD**  
- **Comprehensive policy framework documented and enforced**  
- **Security awareness training for all employees**  
- **Regulatory compliance verification (CCPA, PDPC, government contracts)**  
- **Incident response capability with defined procedures**  

---

*This scenario represents a realistic mid-sized enterprise security challenge requiring comprehensive assessment and multilayered remediation strategy.*

# Creating a Company Culture for Security - Design Document

# Security Infrastructure Design for Artisanal Widget Retailer

---

## 1. Authentication System:
- **External Website:** Use **MFA** and **OAuth 2.0** for secure customer logins.
- **Internal Website:** Implement **SSO** with **MFA** for employee access, managed by **Active Directory (AD)**.

## 2. External Website Security:
- Enforce **HTTPS** using **SSL/TLS** certificates.
- Deploy a **Web Application Firewall (WAF)** to protect against common attacks.
- Regularly scan for vulnerabilities (e.g., **OWASP Top 10**).

## 3. Internal Website Security:
- Apply **role-based access control (RBAC)** for limited employee access.
- Use **SSL/TLS** encryption for internal communications.
- Implement **network segmentation** to isolate sensitive systems.

## 4. Remote Access Solution:
- Use a **VPN** with **MFA** for secure remote access.
- Require **SSH key-based authentication** for engineers accessing internal systems remotely.

## 5. Firewall and Basic Rules:
- **External Firewall:** Block unnecessary inbound traffic; allow only HTTP/HTTPS.
- **Internal Firewall:** Use **VLANs** for segmentation and limit outgoing traffic from sensitive systems.

## 6. Wireless Security:
- Use **WPA3 encryption** for Wi-Fi security.
- Set up a **guest Wi-Fi network** isolated from internal systems.
- Use **802.1X** for secure access point authentication.

## 7. VLAN Configuration:
- Segment networks into **VLANs** (e.g., departments, guest devices).
- Isolate **payment systems** on a separate VLAN for security.

## 8. Laptop Security Configuration:
- Use **full-disk encryption (FDE)** on all laptops.
- Install **antivirus/anti-malware** software and enable **remote wipe** capabilities.
- Use **MDM** to enforce security policies.

## 9. Application Policy Recommendations:
- Use **application whitelisting** to ensure only approved software is installed.
- Establish a **patch management** policy to ensure timely updates.

## 10. Security and Privacy Policies:
- Create a **privacy policy** to inform customers of data usage and storage practices.
- Implement **data retention** and **secure disposal** policies.
- Conduct regular **security awareness training** for employees.

## 11. Intrusion Detection or Prevention:
- Implement an **IDS/IPS** to monitor and block malicious activities.
- Use **database activity monitoring (DAM)** to protect customer data.
- Enable **logging** for audit trails and **encrypt** sensitive data at rest.

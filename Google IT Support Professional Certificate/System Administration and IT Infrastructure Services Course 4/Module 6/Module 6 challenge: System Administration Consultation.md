# Module 6 challenge: System Administration Consultation

Scenario 1: Network Funtime Company
Problem: Network Funtime Company’s current IT infrastructure is disorganized and inefficient, especially regarding hardware management, employee onboarding, and IT support processes. The lack of standardized laptops for employees, absence of an inventory system, and poor password management practices are key areas of concern. Additionally, employees must rely on HR for both tech-related and office-related needs, which strains HR’s time and creates delays in onboarding. The reliance on a variety of Linux distributions and the absence of standardized setups result in unnecessary time spent by engineers setting up their machines. Furthermore, there is no password retrieval system for employees who forget their login credentials.

Proposed Improvements:

Standardize Hardware Procurement:

The company should establish a standard laptop configuration for all employees, balancing performance with cost. This reduces compatibility issues, streamlines setup processes, and makes it easier to manage and troubleshoot devices.
Rationale: Standardization simplifies IT support and reduces time spent troubleshooting different models. Additionally, bulk purchasing could offer cost savings.
Implement an Inventory Management System:

The company should implement a system like an asset management tool (e.g., Spiceworks, or any open-source option) to track all devices and software licenses.
Rationale: This helps keep track of assets, identify lost or stolen items quickly, and maintain better control over company hardware.
Implement a Centralized Authentication System:

Set up an Active Directory or an LDAP-based directory service to centralize employee logins, ensuring easy password management and recovery. HR should not handle logins directly.
Rationale: Centralized authentication improves security, reduces HR’s workload, and gives employees an easy way to reset forgotten passwords.
Automate Employee Onboarding Process:

Implement a script-based approach to automate the installation of necessary software (e.g., Ansible, Chef, or Puppet for Linux setup), which would allow software engineers to get a ready-to-use machine with all the necessary tools.
Rationale: Automation speeds up the process and reduces errors, giving employees quicker access to the tools they need to be productive.
Enforce Stronger Password Policies:

The company should enforce a minimum password length and complexity requirement for all users, ensuring that security is maintained.
Rationale: Strong password policies protect against unauthorized access and reduce the chances of password-related security breaches.
Scenario 2: W.D. Widgets
Problem: W.D. Widgets is facing challenges in hardware provisioning, software installation, backup management, and scalability due to their current manual processes. The company’s use of a single file server for customer data without backups is a major concern. Additionally, the manual installation of sales-specific applications is time-consuming and inefficient. The growing employee base further exacerbates these challenges, as the IT infrastructure cannot scale with the company’s rapid growth.

Proposed Improvements:

Implement Automated Software Deployment:

Use Microsoft System Center Configuration Manager (SCCM) or a similar tool to automate the installation and management of sales-specific applications across all devices.
Rationale: This reduces the time spent installing software manually and ensures consistency across all devices, allowing IT to focus on higher-priority tasks.
Implement Cloud Services for Scalability:

Migrate email, instant messaging, and customer data to cloud-based services (e.g., Microsoft 365 for email and collaboration tools, Google Workspace, or a cloud backup solution for customer data).
Rationale: Cloud services can scale quickly as the company grows, reducing the burden on the IT team and providing a more reliable infrastructure for critical services.
Implement Regular Backup Procedures for Customer Data:

Implement a daily backup of customer data and store it in a secure offsite or cloud-based location to prevent data loss in case of server failure.
Rationale: Regular backups ensure that data is protected from loss due to system failure, human error, or malicious activity.
Transition to Role-Based Access Control (RBAC) for File Permissions:

Use Active Directory to enforce RBAC on file shares, ensuring that only authorized employees can access sensitive customer data and reducing the risk of data leaks or accidental deletions.
Rationale: RBAC ensures that employees only have access to the data necessary for their job functions, improving security and preventing unauthorized access.
Implement IT Service Management (ITSM) Platform:

Implement an ITSM tool, such as ServiceNow or Jira Service Management, to streamline IT requests, track issues, and improve communication with employees.
Rationale: An ITSM platform allows for better tracking of IT requests and helps prioritize tasks, ensuring faster response times and improving overall efficiency.
Scenario 3: Dewgood
Problem: Dewgood is struggling with a lack of scalability, inefficient manual processes for onboarding, and inadequate IT systems to support their growing needs. The company uses a single server for all services, which poses a risk to system availability and reliability. Additionally, their ticketing system is difficult to use, leading to employees bypassing it and relying on the IT person for support. The company’s backup strategy is also manual, with the IT administrator personally taking backup disks home, which is inefficient and risky.

Proposed Improvements:

Migrate to Cloud Services for Scalability and Reliability:

Migrate the email, file storage, and ticketing systems to cloud-based services (e.g., Google Workspace or Microsoft 365 for email and file storage, and a cloud-based helpdesk solution like Zendesk).
Rationale: Cloud services offer better scalability and reliability, reducing the risk of system failure due to a single server and providing access to critical tools remotely.
Implement a More Intuitive Ticketing System:

Upgrade to a user-friendly ticketing system like Jira Service Desk or Freshdesk, which offers better reporting, automation, and communication features.
Rationale: A better ticketing system will reduce the number of direct requests to the IT admin, improving efficiency and allowing employees to handle issues more independently.
Automate Employee Onboarding and Software Installation:

Implement a system to automate the setup of new employee devices, including software installation and server mapping. This could involve using Windows Deployment Services (WDS) or an open-source alternative like FOG.
Rationale: Automation reduces setup time, ensures consistent configurations across devices, and allows the IT team to scale operations more easily.
Implement Offsite Backups and Redundancy:

Set up an automated backup solution that stores backups both offsite and in the cloud, ensuring that critical data is protected and easily recoverable in case of a disaster.
Rationale: Automated backups reduce the risk of data loss and free up the IT administrator from manually taking backups home.
Set Up Role-Based Access Control (RBAC) and Network Segmentation:

Implement RBAC and segment the network for better security and easier management. Assign appropriate permissions based on employee roles and ensure sensitive data is protected.
Rationale: RBAC improves security by ensuring that only authorized employees have access to sensitive data. Network segmentation limits exposure in case of a breach and enhances overall security.

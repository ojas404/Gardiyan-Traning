# Active Directory Security & Administration Project

This folder contains a complete lifecycle implementation of **Microsoft Active Directory** in a Windows Server 2022 environment.  
The project integrates **identity management, security hardening, Group Policy engineering, auditing, backup/recovery, and delegated administration** into a cohesive enterprise-ready deployment.

---

## Project Overview

The Active Directory (AD) Project was executed as an **end-to-end enterprise security exercise**, covering all aspects from **initial provisioning** to **advanced monitoring and disaster recovery**.  
Tasks were completed using a combination of **PowerShell automation** and GUI-based administration tools, ensuring both operational efficiency and visibility.

---

## Key Implementations

- **User & Group Provisioning** – Automated account creation, enforced strong password policies, disabled inactive accounts, and assigned users to role-based security groups.
- **Group Policy Objects (GPOs)** – Applied targeted security baselines, workstation restrictions, drive mapping, logon banners, and firewall enforcement.
- **Advanced Auditing** – Configured SACLs on privileged groups, enabled directory service change auditing, and monitored Event IDs **4732, 5136, and 4663** for high-value object and file access tracking.
- **Backup & Recovery** – Performed system state backups with **wbadmin**, enabled the AD Recycle Bin, and executed **authoritative restores** in DSRM to recover deleted OUs.
- **Delegation of Control** – Applied least-privilege delegation to distribute administrative tasks securely across IT staff.
- **Security Hardening** – Restricted RDP access, enforced account lockout policies, and applied auditing across sensitive file systems.
- **Disaster Recovery Validation** – Tested restore operations to ensure environment resilience and data integrity.

---

## Tools & Technologies

| Category             | Tools & Technologies                                           |
|----------------------|----------------------------------------------------------------|
| **OS & Directory**   | Windows Server 2022, Active Directory Domain Services (AD DS)  |
| **Management**       | Active Directory Users & Computers (ADUC), Group Policy Management Console (GPMC) |
| **Automation**       | PowerShell (ActiveDirectory module), wbadmin                   |
| **Auditing**         | Event Viewer, SACL configuration, auditpol, ntdsutil           |
| **Security**         | Group Policy security settings, firewall rules                 |
| **Backup/Recovery**  | Windows Server Backup, Directory Services Restore Mode (DSRM)  |

---

## Achievements

- Delivered a **secure, role-based identity infrastructure** aligned to enterprise standards.
- Implemented **centralized policy control** for consistent security enforcement across clients.
- Established **real-time monitoring and audit logging** for privileged changes and file access.
- Validated **full disaster recovery workflow**, ensuring rapid restoration after critical failures.
- Reduced administrative risk via **delegated control** with least privilege.

---

## Recommendations

- Maintain strict **naming conventions** for AD objects.
- Schedule **regular system state backups** with off-site storage.
- Integrate audit logs into a **centralized SIEM** for correlation and alerting.
- Periodically **review group memberships** to prevent privilege creep.
- Continuously refine GPOs for security–usability balance.

---

## Conclusion

This Active Directory deployment demonstrates **enterprise-grade identity and access management**, combining operational efficiency with strong security governance.  
The implementation not only hardened the AD environment against internal and external threats but also ensured **operational continuity** through tested recovery procedures.

---

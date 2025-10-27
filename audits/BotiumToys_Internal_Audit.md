# Botium Toys – Internal Security Audit Report

## 1. Overview
Botium Toys is a U.S.-based company developing and selling toys both in-store and online.  
This internal audit evaluates the company's security posture, identifies gaps in access controls, policies, backups, and compliance with PCI DSS and GDPR.

**Overall Risk:** 8/10 (High)  

---

## 2. Controls Assessment Checklist

### Security Controls
- [ ] Least Privilege – All employees currently have access to critical data; implement role-based access control (RBAC)
- [ ] Disaster Recovery Plans – No plan exists; create a documented and tested DRP
- [ ] Password Policies – Weak policy; implement strong and centralized password management
- [ ] Separation of Duties – Not implemented; essential to minimize fraud
- [x] Firewall – Properly configured and updated
- [ ] Intrusion Detection System (IDS) – IDS missing; implement monitoring
- [ ] Backups – None in place; establish regular backup plan and testing
- [x] Antivirus Software – Present and monitored, maintain updates
- [ ] Manual Monitoring for Legacy Systems – No schedule defined; implement regular maintenance
- [ ] Encryption – Credit card and PII data not encrypted; implement encryption at rest and in transit
- [ ] Password Management System – Missing; implement centralized management
- [x] Locks (office, storefront, warehouse) – Adequate
- [x] CCTV Surveillance – Functional and updated
- [x] Fire Detection/Prevention – Functional and updated

---

## 3. Compliance Checklist

### PCI DSS
- [ ] Only authorized users have access to customers’ credit card information
- [ ] Credit card information is stored, accepted, processed, and transmitted securely
- [ ] Implement data encryption procedures for credit card data
- [ ] Adopt secure password management policies

### GDPR
- [x] E.U. customers’ data is kept private/secured
- [x] Notify E.U. customers within 72 hours in case of a data breach
- [ ] Ensure data is properly classified and inventoried
- [x] Enforce privacy policies and procedures

### SOC Type 1 & 2
- [ ] User access policies are established
- [ ] Sensitive data (PII/SPII) is confidential/private
- [x] Data integrity is ensured
- [ ] Data is available only to authorized individuals

---

## 4. Recommendations

1. **Full Encryption:** Encrypt credit card and PII data at rest and in transit.
2. **Access Control & Separation of Duties:** Apply least privilege, multi-factor authentication (MFA), and centralized password management.
3. **Disaster Recovery & Backups:** Create a formal DRP, perform regular backups, and test restoration.
4. **Intrusion Detection & Monitoring:** Implement IDS/IPS and central log monitoring (SIEM).
5. **Policy Review & Employee Training:** Update policies and train staff on GDPR and security best practices.
6. **Asset Classification & Inventory:** Catalog all critical assets and assess loss impact.
7. **Ongoing Compliance:** Monitor adherence to PCI DSS and GDPR; update processes as regulations evolve.

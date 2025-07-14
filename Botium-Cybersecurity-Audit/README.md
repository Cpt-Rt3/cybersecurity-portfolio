# 🔍 Botium Cybersecurity Audit

**Company**: Botium Toys  
**Industry**: eCommerce (toys)  
**Scope**: PCI-DSS, GDPR Compliance  
**Audit Framework**: NIST Cybersecurity Framework (CSF)

---

## 🧩 Identify (ID)

Understand the business context, assets, and risk:

| Asset | Risk | Status |
|-------|------|--------|
| Customer PII | Data theft | ⚠️ Moderate |
| Payment gateway | PCI-DSS failure | ✅ Secured |
| Vendor access | Phishing/insider threat | ⚠️ Low |

✅ Mapped digital assets  
✅ Interviewed key stakeholders  
✅ Created baseline of known vulnerabilities  

---

## 🛡️ Protect (PR)

Safeguard assets with appropriate controls:

- ✅ Multi-Factor Authentication enabled
- ✅ SSL certificates updated
- ⚠️ Outdated CMS plug-ins (needs update)
- ✅ Data backups encrypted

**Tools Used**:  
🛠️ Nessus, Bash scripts, firewall logs

---

## 🧭 Detect (DE)

Monitor systems to identify potential threats:

| Tool | Function |
|------|----------|
| Nmap | Network discovery and open port scanning |
| Wireshark | Traffic analysis (packet sniffing) |
| OSSEC | Host-based intrusion detection |

✅ Alert thresholds reviewed  
⚠️ No centralized SIEM — recommend deploying Wazuh or Splunk Lite

---

## 🧯 Respond (RS)

Response planning & incident handling:

- ✅ Drafted Incident Response Playbook  
- ✅ Created phishing response drill  
- ⚠️ No formal IR tabletop tests conducted  

**Recommendation**: Monthly IR tabletop training  

---

## ♻️ Recover (RC)

Post-incident recovery plans:

- ✅ Daily encrypted cloud backups  
- ✅ Service-level agreements with cloud vendors  
- ⚠️ No documented Disaster Recovery Plan (DRP)

---

## 📦 Summary & Recommendations

- Patch CMS vulnerabilities ASAP  
- Implement centralized SIEM  
- Document a Disaster Recovery Plan  
- Perform quarterly tabletop drills  

---

## 🧰 Tools Used

- **Nmap** – Port & service discovery  
- **Wireshark** – Packet sniffing  
- **Nessus** – Vulnerability scanning  
- **OWASP ZAP** – Web app security testing  
- **Bash & Python** – Automation scripts  
- **GitHub** – Repo tracking and version control  

---

> “Cybersecurity isn’t just code — it’s a mindset.” — RT3

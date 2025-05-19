## Parking Lot USB Exercise – Security Awareness Activity

**Scope:** This activity involved the analysis of an unencrypted USB drive discovered on Rhetorical Hospital grounds. The primary focus was to examine the contents of the drive, understand how a malicious actor could potentially exploit the exposed information, and assess the resulting security risks to the hospital and its employees. The analysis was conducted from a defensive perspective to identify vulnerabilities and inform security recommendations.

**Objectives:**

- **Analyze Found USB Contents:** Examine the data present on the USB drive.
- **Identify Potential Exploitation:** Determine how an attacker could misuse the discovered data.
- **Assess Security Risks:** Evaluate the vulnerabilities exposed by the unencrypted data.

---

## 🗂️ Contents of the USB Drive

The discovered USB drive contained a mix of **personal and work-related sensitive data**, including:

- 📷 Personal identifiable information (PII) for **Jorge**, including family photos and his resume
- 🗂️ Sensitive work files:
  - Staff schedules
  - New hire offer letters
  - Employee budget documents

⚠️ **None of the data on the USB was encrypted**, meaning anyone with access to the device could view and misuse the information.

![image](https://github.com/user-attachments/assets/8069a4fe-7fec-4644-bf0a-498f0bc637a9)

---

## 🎯 Attacker Mindset

A malicious actor could exploit this unprotected USB drive in several ways:

* **Social engineering opportunities:** Use photos and wedding invite details to impersonate relatives or build trust with Jorge or his family for further attacks (e.g., phishing, vishing).
* **Targeted phishing:** Use destination/travel plans and personal themes from the documents to craft convincing phishing emails aimed at Jorge or individuals mentioned in the work documents.
* **Insider exploitation:** Accessing employee offers or schedules could enable further attacks on staff or HR systems, potentially revealing sensitive salary information or organizational changes.
* **USB baiting:** While the contents themselves aren't malicious in this scenario, a similar drive could be planted with malicious code to be reintroduced into the network environment for further exploitation.
---

## 🛡️ Risk Analysis & Security Recommendations

The lack of encryption on this USB drive exposes Rhetorical Hospital and its employees to several significant security risks:

* **Data Breach and Confidentiality Loss:** The unencrypted PII and sensitive work files are readily accessible, violating confidentiality and potentially leading to a data breach if the drive falls into the wrong hands.
* **Identity Theft:** Jorge's PII could be used for identity theft or other malicious purposes.
* **Targeted Attacks:** The personal and work-related details provide attackers with valuable intelligence for launching highly targeted social engineering or phishing attacks.
* **Insider Threats:** The exposure of employee-related information could be exploited by malicious insiders or external actors who gain access to the drive.
* **Reputational Damage:** A data breach involving employee or potentially patient-related (if hinted at in schedules or offer letters) information could severely damage Rhetorical Hospital's reputation.

**Security Recommendations:**

* Use a safe environment (e.g., sandbox) to inspect unknown or found USB devices.
* Separate personal and professional data — avoid storing both on the same removable device.
* **Encrypt USB drives** to ensure data is not accessible if lost or stolen. This is a critical control to mitigate the risks identified in this scenario.
* Implement separation of duties for documents and access control to prevent unauthorized editing or misuse of sensitive work files.
* Educate employees on USB baiting threats and how to respond appropriately when unknown devices are found, emphasizing that even seemingly legitimate drives can pose a risk if not properly handled.

---

> _“Convenience should never come at the cost of security.”_

# ⭐ 🔐 Remote IT Support — Executive Travel Security & Tenable Ops
 
> ## > I am Jose G. (IT Specialist), responsible for securing CEO Alexander Pierce’s personal Windows 10 laptop during a business trip. In this simulation, I am building a secure work profile, running Tenable credentialed scans, hardening the system, configuring remote access, setting up a portable printer, reviewing hotel Wi-Fi security, and ensuring a secure work environment. I am performing this scenario to practice real-world IT security tasks and to protect sensitive executive data during travel. By creating a secure work profile, I isolate business activities from personal use, reducing the risk of accidental data leaks. Running credentialed Tenable scans allows me to identify and remediate vulnerabilities, ensuring the laptop meets a strong security baseline. Hardening the system and configuring remote access guarantees that only authorized connections are possible, while setting up a portable printer and assessing hotel Wi-Fi ensures the CEO can work efficiently and safely in any environment. This simulation helps me anticipate risks, apply security best practices, and document procedures professionally for a comprehensive IT portfolio.


<p align="center">
  <img src="https://github.com/user-attachments/assets/b55b42e2-53eb-4da6-966b-cd1e9825b04a" width="426" height="471" alt="5EUG6FD" />
</p>

# 🎫 **TICKET 1 — CEO Travel Laptop Intake & Security Requirements**

<img width="677" height="281" alt="TMA3lY9" src="https://github.com/user-attachments/assets/80e40663-6ec7-4a39-a399-d7c0df458231" />

> ### I collect all essential system and security information from the CEO’s personal laptop so I can prepare it for secure remote work and vulnerability scanning.

> ### 🖥️ I gather system information such as hostname, OS version, IP settings, and architecture.  
> ### 🔍 I review installed software and check for outdated programs.  
> ### 🛡️ I verify what antivirus, VPN, and remote-access tools are present.  
> ### 👑 I confirm whether the CEO has admin rights on the device.  
> ### 📶 I determine if the laptop will use hotel Wi-Fi or a mobile hotspot.  
> ### 🖨️ I check how the travel printer connects (USB or Wi-Fi Direct).  
> ### 🔐 I confirm BitLocker, RDP, and SSH requirements.

---

# 🎫 **TICKET 2 — Creation & Security of CEO-Work Windows Account**

<img width="655" height="280" alt="NXW5cUj" src="https://github.com/user-attachments/assets/3c5f9814-41cd-418e-8016-5ca9e4a11d21" />

> ### I build a secure, isolated work-only user account so the CEO’s business tasks stay protected and separate from personal activity.

> ### 👤 I create a **CEO-Work** standard account with restricted privileges.  
> ### 🔧 I set up an optional local admin account for IT maintenance.  
> ### 🔑 I enforce a strong password policy with complexity and length.  
> ### 📁 I organize a clean folder structure for work documents and logs.  
> ### 🚫 I ensure personal apps and data are not accessible inside the work account.  
> ### 🧹 I disable unnecessary startup programs within the work profile.

---

# 🎫 **TICKET 3 — Device Preparation for Tenable Credentialed Scan**

<img width="664" height="280" alt="c9rhfUJ" src="https://github.com/user-attachments/assets/1de1f877-98a2-4cc8-85c8-c056e8337f9b" />

> ### I ensure the laptop can be credential-scanned by Tenable by enabling required services, verifying credentials, and confirming network accessibility.

> ### 🔑 I test admin credentials needed for authenticated scans.  
> ### 🧰 I enable Remote Registry and other required Windows services.  
> ### 🌐 I confirm the laptop can be reached through VPN or hotspot.  
> ### 🚫 I check if hotel Wi-Fi uses client isolation that blocks scanning.  
> ### 🔥 I identify firewall rules that may interrupt the credentialed scan.  
> ### 🛡️ I review UAC and security software to ensure nothing blocks Tenable.

---

# 🎫 **TICKET 4 — Add Asset to Tenable & Create Scan Policies**

<img width="633" height="283" alt="HEQbTLR" src="https://github.com/user-attachments/assets/91b58f75-582f-4178-a0f0-cc6cefe00736" />

> ### I add the CEO’s laptop to Tenable and configure multiple scan templates to perform a complete vulnerability assessment.

> ### ➕ I register the laptop as a Windows asset with hostname and IP.  
> ### 🔑 I apply the correct Windows credential set for authenticated scans.  
> ### 📊 I build scans such as Basic Network Scan, Advanced Scan, and Patch Audit.  
> ### ⚙️ I enable checks for patches, weak configurations, and compliance gaps.  
> ### 🗓️ I save and schedule the scans manually for the lab environment.

---

# 🎫 **TICKET 5 — Execute the Tenable Scan and Review Results**

<img width="633" height="277" alt="fM5mWOn" src="https://github.com/user-attachments/assets/8b9ebc8f-7772-4c11-9bd9-fc84ef3507e3" />

> ### I run the full scan, analyze the findings, categorize vulnerabilities, and document everything for later remediation.

> ### ▶️ I start the scan and monitor its progress.  
> ### 📄 I export the complete scan report after it finishes.  
> ### 🔥 I categorize issues by severity (Critical, High, Medium, Low).  
> ### 🧭 I identify missing patches, outdated software, firewall issues, weak RDP, and insecure authentication settings.  
> ### 📸 I capture screenshots of the Tenable dashboard and findings.

---

# 🎫 **TICKET 6 — Vulnerability Remediation for CEO Laptop**

<img width="673" height="286" alt="PEQtzVw" src="https://github.com/user-attachments/assets/1651a6ba-e943-4c03-962c-65cb4e31ccc4" />

> ### I fix the weaknesses identified by Tenable and harden the laptop to meet the organization’s baseline security posture.

> ### ⬆️ I apply Windows Updates and reboot if required.  
> ### 🔄 I update all third-party software including browsers and PDF tools.  
> ### 🛡️ I ensure Defender real-time protection is active and functional.  
> ### 🔥 I enforce firewall profiles across Public, Private, and Domain modes.  
> ### 🔧 I address insecure registry settings for RDP encryption, NTLM, AutoRun, and network hardening.  
> ### 🚫 I disable unnecessary Windows services and risky startup items.  
> ### 🔁 I perform a follow-up scan to confirm vulnerabilities were resolved.

---

# 🎫 **TICKET 7 — Registry Security Audit Checklist**

<img width="680" height="280" alt="eS78Wqs" src="https://github.com/user-attachments/assets/c6642ce9-a26c-450d-b763-5558cae3b3be" />

> ### I audit key registry paths related to remote access, firewall behavior, authentication, and startup entries to ensure the system is aligned with security best practices.

> ### 🔐 I review registry keys controlling RDP and Remote Assistance.  
> ### 🔥 I verify firewall configuration keys for all profiles.  
> ### 🛡️ I check antivirus and SmartScreen registry values.  
> ### 🚫 I inspect LLMNR, SMB signing, and startup entry keys.  
> ### 📄 I document any registry entries that require further remediation.

---

# 🎫 **TICKET 8 — Windows Security Review & Hardening Validation**

<img width="681" height="282" alt="KK5yHs4" src="https://github.com/user-attachments/assets/48f56e9d-43b5-4a8a-b3f9-cacc69afba9b" />

> ### I perform a full inspection of Windows Security features to confirm that the laptop is protected at all layers.

> ### 🧭 I review each Windows Security dashboard section for compliance.  
> ### 🛡️ I verify Defender real-time and cloud protection are active.  
> ### 🔥 I confirm that all firewall profiles are enabled.  
> ### 🚫 I ensure SmartScreen and exploit protections are configured.  
> ### 🌐 I validate browser security settings in Edge and Chrome.  
> ### 📸 I note any warnings or missing features for documentation.  
> ### 🔐 I recommend enabling BitLocker if not already set up.

---

# 🎫 **TICKET 9 — Remote Access Validation (RDP & SSH)**

<img width="675" height="284" alt="AStJvYU" src="https://github.com/user-attachments/assets/b69672f6-4781-4f9c-b3b9-e229e6938b27" />

> ### I verify that remote access methods are secure and functional so the CEO can access corporate systems while traveling.

> ### 🔐 I restrict RDP usage to VPN-only connections.  
> ### 🔧 I confirm RDP encryption levels meet security standards.  
> ### 🔥 I ensure RDP firewall rules apply only to Private networks.  
> ### 💻 I set up an SSH server for secure remote PowerShell management if needed.  
> ### 🌐 I test remote connectivity from the laptop to the admin workstation.

---

# 🎫 **TICKET 10 — Hotel Wi-Fi & Network Security Assessment**

<img width="664" height="274" alt="fXD5fwP" src="https://github.com/user-attachments/assets/51360573-7e5f-44cf-b508-1e338bd4d85c" />

> ### I review the hotel network the CEO is using to ensure it is safe, and I identify any potential risks while advising secure alternatives.

> ### 📶 I check whether the hotel Wi-Fi is open, captive portal, or WPA2 secured.  
> ### 🚫 I determine if client isolation is active on the network.  
> ### 🌐 I identify the DNS servers and network behavior.  
> ### 🔐 I recommend a VPN if the network appears untrusted.  
> ### 🧭 I monitor for suspicious devices or ARP behavior.  
> ### 📉 I evaluate the network speed and latency for remote work.  
> ### 🔒 I ensure the laptop is set to **Public** network mode.

---

# 🎫 **TICKET 11 — Printer Setup for CEO on Work Trip**

<img width="682" height="277" alt="uifNwBc" src="https://github.com/user-attachments/assets/ba07e27c-ecf3-477d-9cde-6334172b199f" />

> ### I configure the CEO’s portable printer so it functions reliably while traveling.

> ### 🖨️ I identify the printer model and connection type.  
> ### 🔌 For USB mode, I install the driver and print a test page from the CEO-Work account.  
> ### 📡 For Wi-Fi Direct, I ensure the printer connects directly to the laptop and not the hotel Wi-Fi.  
> ### 🧾 I capture screenshots and document the full setup.

---

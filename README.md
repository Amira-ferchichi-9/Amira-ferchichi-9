<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="banner-light.png">
    <img src="banner-dark.png" alt="Amira Ferchichi, Telecommunications Engineering Student" width="100%">
  </picture>
</p>

<p align="center">
  <b>Security-minded telecom engineer. Cloud & AI curious.</b><br>
  Tunis, Tunisia<br><br>
  <a href="https://linkedin.com/in/amira-ferchichi">linkedin.com/in/amira-ferchichi</a> ·
  <a href="mailto:amira.ferchichi@etudiant-enit.utm.tn">amira.ferchichi@etudiant-enit.utm.tn</a>
</p>

---

## A little about me

I'm Amira, a final-year Telecommunications engineering student at **ENIT** (École Nationale d'Ingénieurs de Tunis), specializing in **Converged Infrastructures, Cloud & Cybersecurity (I3C)**.

I like projects where security meets automation: from CI/CD pipelines and threat modeling to cloud-native detection systems.

- 🔍 **Currently exploring**: DevSecOps, cloud security, LLM/RAG applied to security
- 🎯 **Looking for**: an international PFE (end-of-studies internship) in cybersecurity / cloud / DevSecOps
- 🏃‍♀️ **Beyond the keyboard**: I love sports and nature. I run marathons and go hiking.

## Experience

### 🛡️ Security Engineering Intern · Tunisian Engineers Order (OIT) · Jun–Aug 2026
*Security team, new core platform (Spring Boot / React) migrated from a legacy PHP application*

- **Secured the CI/CD pipeline**: integrated SAST (Semgrep) into GitLab through a Merge Request. Found that the GitLab template silently skipped every analyzer in Merge Request pipelines (a green pipeline with no scan) and fixed it with the right pipeline variable.
- **Made scan results actionable**: classified alerts by area and CWE category, verified a false positive by reading the code, and proposed a roadmap (legacy code exclusion, custom Semgrep rules, a progressive security gate).
- **Threat modeling and hardening**: applied STRIDE to the sensitive flows (authentication, access control, payment), reviewed the findings of a static security review by severity and level of evidence, and delivered hardening for the network edge (Traefik) and the Spring Boot production profile.
- **Wrote a prioritized remediation plan** (impact vs. effort) and assessed residual risk.

`GitLab CI/CD` `Semgrep` `STRIDE` `OWASP` `Traefik` `Spring Boot` `Helm`

### 📣 Marketing Manager · ENIT Junior Entreprise
- Lead the digital presence of the junior enterprise: Instagram strategy and content creation.

### 📡 Intern · One Tech Group (TTEI) · 2024–2025
*1st-year industrial placement, enterprise WiFi*

- Built a **virtual WiFi lab** around a Cisco vWLC (OVA import on VMware Workstation, then deployment on vSphere) and configured the controller (IP addressing, RF group, SSH access).
- Connected a **physical access point** over CAPWAP and verified SSID and radio provisioning.
- Studied enterprise WLAN security (WPA2/WPA3, 802.1X/RADIUS, VLAN segmentation) and started forwarding controller logs to Wazuh (SIEM).

`Cisco vWLC` `CAPWAP` `VMware vSphere` `Wazuh` `SSH`

## Selected projects

### 📧 [ThreatIntel](https://github.com/Amira-ferchichi-9/threatintel) · Final-Year Project 2 (ENIT, 2025/2026)
Cloud-native, **multi-agent pipeline** that analyzes incoming emails and returns a Safe / Suspicious / Dangerous verdict through a REST API.

- 5 specialized agents: sender authentication (SPF/DKIM/DMARC), URL reputation (VirusTotal), NLP and BEC detection (RoBERTa, DistilBERT), attachment sandbox (ephemeral Azure Container Instances), and ensemble scoring (Random Forest / XGBoost).
- Resilience and speed: circuit breaker with a local blocklist fallback, and a Redis cache that brings a repeated analysis from 2.3 s down to 15 ms.
- Built as a team of two on Azure (Functions, Cosmos DB, Service Bus, Key Vault), containerized with Docker.

`Python` `FastAPI` `Azure` `Docker` `Redis` `Transformers`

### 🔧 [gitlab-sast-demo](https://github.com/Amira-ferchichi-9/gitlab-sast-demo)
Minimal, reproducible demo of SAST in GitLab Merge Request pipelines, showing the pitfall where analyzers are silently skipped and how to detect and fix it. Based on a problem I diagnosed during my internship, rebuilt on a toy project.

`GitLab CI/CD` `Semgrep`

### 🔓 [wifi-mitm-lab](https://github.com/Amira-ferchichi-9/wifi-mitm-lab) · Final-Year Project 1 (ENIT, 2024/2025)
Educational study of a Man-in-the-Middle attack in an **isolated virtual lab** (Kali Linux against a Windows target): ARP spoofing with Bettercap, traffic redirection with iptables, interception and modification of HTTP responses with mitmproxy, and packet analysis with Ettercap and Wireshark. Also documents why the attack fails against HTTPS/HSTS, client isolation and WPA3.

`Kali Linux` `Bettercap` `mitmproxy` `Wireshark`

### 🤖 [rl-intrusion-detection](https://github.com/Amira-ferchichi-9/rl-intrusion-detection)
Reinforcement learning agent for network intrusion detection.

`Python` `Reinforcement Learning`

<!-- TODO: replace the links once each repo is public, and remove any project you don't publish -->

## Toolkit

| Focus | Technologies |
|---|---|
| **Security** | SAST (Semgrep) · STRIDE · OWASP · Wireshark · Kali Linux |
| **Cloud & DevOps** | Azure · GCP · Docker · GitLab CI/CD · VMware vSphere |
| **Programming** | Python · C / C++ · C# · Bash · JavaScript · React · Node.js · MongoDB |
| **Networks & systems** | TCP/IP · DNS · Firewalls · Cisco Packet Tracer · Linux · Arduino · STM32 |
| **AI** | RAG · prompt engineering · LLM output evaluation |

## Certifications

NVIDIA LLM Customization · Cisco CCNA: Introduction to Networks · Hedera Hashgraph Developer

---

<p align="center"><i>Let's talk security, cloud or AI. I'd be happy to connect.</i></p>

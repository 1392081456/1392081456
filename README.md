## Hi, I'm Colorful White 👋

Independent security researcher focused on **adversarial machine learning**, **detection engineering**, and **defense-oriented CVE research**.

### 🔬 Research

- **Black-box adversarial attacks on ML models** — First author, peer-reviewed publication in *Computer Engineering and Applications* (《计算机工程与应用》, 2025).
  DOI: [10.3778/j.issn.1002-8331.2311-0227](https://doi.org/10.3778/j.issn.1002-8331.2311-0227)
  Journal indexed in the Peking University Core Journals catalogue and the CSCD. The DOI page resolves to both Chinese full text and the journal's officially-translated English abstract and keywords.

### 🛡 Detection Engineering & CVE Defense

- Maintain a [`labs/`](https://github.com/1392081456/ctf-notes/tree/main/labs) chapter that reproduces published CVEs in isolated vulhub Docker containers and produces canonical SOC artifacts for each: **Sigma YAML rule**, **Suricata SID**, **structured IOC table**, and **hunting queries in multiple SIEM dialects** (Splunk SPL, Microsoft Sentinel KQL, Elastic ES|QL).
- Five CVE writeups already published (Shiro, ActiveMQ, Jenkins, Grafana, TeamCity); Log4Shell and Spring4Shell planned next.
- Public [Use of AI Assistants statement](https://github.com/1392081456/ctf-notes#use-of-ai-assistants) and [Authorization-and-Targets table](https://github.com/1392081456/ctf-notes#authorization-and-targets) describe the defensive orientation of all work in this portfolio.

### 🎯 CTF Practice

- Active CTF player — member of team **APWN** ([CTFtime](https://ctftime.org/user/colorfulwhitez))
- ~70 in-depth writeups across **pwn**, **reverse engineering**, **cryptography**, **web exploitation**, and **forensics**: [`ctf-notes`](https://github.com/1392081456/ctf-notes)
- Writeups privilege "why each step works" over "what each step does" — failed paths and traps are documented as much as successes, so the lessons remain useful to defenders building detection logic.

### 🛠 Stack

**Offensive understanding** — `x86-64 pwn` · `glibc heap exploitation` · `ARM/MIPS RE` · `Python (pwntools / sage)` · `Frida / Ghidra / IDA Pro`

**Defensive output** — `Sigma` · `Suricata` · `YARA` · `Splunk SPL` · `Sentinel KQL` · `Elastic ES|QL` · `vulhub` · `Falco`

### 📫 Contact

- CTFtime: [@colorfulwhitez](https://ctftime.org/user/colorfulwhitez)
- Email: colorfulwhitez@gmail.com
---

> All research conducted on (a) public CTF challenge binaries distributed by event organizers, (b) vulhub Docker images of vendor-patched CVEs run on 127.0.0.1 in isolation, (c) virtual machines I own on hardware I own, or (d) academic research code I author. No production system, third-party service, or unauthorized network is involved. The intent of this work is consistently defensive — understanding offensive techniques deeply enough to detect them, patch them, and write durable security controls.

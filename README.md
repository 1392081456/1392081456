## Hi, I'm Colorful White 👋

Independent security researcher focused on **adversarial machine learning**, **detection engineering**, and **defense-oriented CVE research**.

### 🔬 Research

- **Black-box adversarial attacks on ML models** — First author, peer-reviewed publication in *Computer Engineering and Applications* (《计算机工程与应用》, 2025).
  DOI: [10.3778/j.issn.1002-8331.2311-0227](https://doi.org/10.3778/j.issn.1002-8331.2311-0227)
  Journal indexed in the Peking University Core Journals catalogue and the CSCD. The DOI page resolves to both Chinese full text and the journal's officially-translated English abstract and keywords.

### 🛡 Detection Engineering & CVE Defense

- Maintain a [`labs/`](https://github.com/1392081456/ctf-notes/tree/main/labs) chapter that reproduces published CVEs in isolated vulhub Docker containers and produces canonical SOC artifacts for each: **Sigma YAML rule**, **Suricata SID**, **structured IOC table**, and **hunting queries in multiple SIEM dialects** (Splunk SPL, Microsoft Sentinel KQL, Elastic ES|QL).
- **Twenty-three CVE writeups** now follow this structure, including the canonical advisories Log4Shell (CVE-2021-44228), Spring4Shell (CVE-2022-22965), Shiro RememberMe (CVE-2016-4437), ActiveMQ Jolokia (CVE-2026-34197), ActiveMQ OpenWire (CVE-2023-46604), Fastjson 1.2.24 AutoType (CVE-2017-18349), Jenkins CLI (CVE-2024-23897), Grafana DuckDB (CVE-2024-9264), TeamCity auth bypass (CVE-2024-27198), GNU InetUtils telnetd (CVE-2026-24061), Chartbrew MongoDB RCE (CVE-2026-25887), Metabase (CVE-2023-38646), GeoServer (CVE-2024-36401), Nexus traversal (CVE-2024-4956), Next.js middleware bypass (CVE-2025-29927), Langflow pre-auth RCE (CVE-2025-3248), DataEase JWT (CVE-2025-49001), and others (ComfyUI-Manager, OpenClaw, Tomcat Tribes, JimuReport, Redis unauth, ZeroShell).
- Public [Use of AI Assistants statement](https://github.com/1392081456/ctf-notes#use-of-ai-assistants) and [Authorization-and-Targets table](https://github.com/1392081456/ctf-notes#authorization-and-targets) describe the defensive orientation of all work in this portfolio.

### 🎯 CTF Practice

- Active CTF player — member of team **APWN** ([team page](https://ctftime.org/team/435891), [my profile](https://ctftime.org/user/261101))
- ~30 highlighted deep writeups plus ~344 catalogued entries across **pwn**, **reverse engineering**, **cryptography**, **web exploitation**, **forensics**, and **labs**: [`ctf-notes`](https://github.com/1392081456/ctf-notes)
- Writeups privilege "why each step works" over "what each step does" — failed paths and traps are documented as much as successes, so the lessons remain useful to defenders building detection logic.

### 🛠 Stack

**Offensive understanding** — `x86-64 pwn` · `glibc heap exploitation` · `ARM/MIPS RE` · `Python (pwntools / sage)` · `Frida / Ghidra / IDA Pro`

**Defensive output** — `Sigma` · `Suricata` · `YARA` · `Splunk SPL` · `Sentinel KQL` · `Elastic ES|QL` · `vulhub` · `Falco`

### 📫 Contact

- CTFtime: [@colorfulwhitez](https://ctftime.org/user/261101)
- Email: colorfulwhitez@gmail.com
---

> All research conducted on (a) public CTF challenge binaries distributed by event organizers, (b) vulhub Docker images of vendor-patched CVEs run on 127.0.0.1 in isolation, (c) virtual machines I own on hardware I own, or (d) academic research code I author. No production system, third-party service, or unauthorized network is involved. The intent of this work is consistently defensive — understanding offensive techniques deeply enough to detect them, patch them, and write durable security controls.

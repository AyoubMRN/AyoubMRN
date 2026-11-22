# Hi, I'm Ayoub Mernissi 👋

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AyoubMRN&label=PROFILE+VIEWS&color=00c8d4&style=flat-square" alt="Profile views">
  <br>
  <a href="https://www.linkedin.com/in/ayoub-mernissi"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://tryhackme.com/p/mernissi.ayoub13"><img src="https://img.shields.io/badge/TryHackMe-Top%205%25-212C42?style=flat-square&logo=tryhackme&logoColor=red" alt="TryHackMe"></a>
</p>

I'm a fourth-year engineering student at **ESIEE Paris**, specializing in **cybersecurity**. I practise through security labs and personal projects, alongside my coursework in systems, networks and programming.

## Looking for an internship

I'm looking for a **3–3.5 month cybersecurity internship starting from 10 May 2027**, with a minimum duration of 12 weeks and an end date before 3 September 2027.

I'm open to a range of cybersecurity missions, including security monitoring, system and network security, and vulnerability analysis.

## Projects

### [Home SOC Lab — Wazuh](https://github.com/AyoubMRN/home-soc-lab-wazuh)

An **ongoing personal project** that I continue to extend with new scenarios, detection tests and Python tools. The lab runs on three VMs: a Wazuh server, a Windows endpoint and an Ubuntu endpoint.

- **V1 foundation:** eight documented scenarios, Sysmon and PowerShell logging on Windows, file integrity and SSH authentication monitoring on Ubuntu.
- **V2 detection work:** five custom XML/PCRE2 rules — four discovery rules and one Windows correlation rule — plus controlled PowerShell and scheduled-task registration tests.
- **SSH validation:** repeated-failure correlation checked through a recorded replay on the real Wazuh engine using `wazuh-logtest`.
- **Python tools:** evidence validation, XML checks, a local HTML report and an SSH replay runner; **46 unit tests** for the tools and automated checks with **GitHub Actions**.
- **Documentation:** selected evidence, MITRE ATT&CK mappings, observed results and [explicit limitations](https://github.com/AyoubMRN/home-soc-lab-wazuh/blob/main/docs/results-and-limits.md). Unit tests and file checks are distinct from live detection tests.

The published V2 is a documented milestone; the lab remains in continuous development.

### [Breast Cancer Detection and Risk Prediction](https://github.com/AyoubMRN/breast-cancer-detection-and-risk)

Academic project with a team of six students (ESIEE Paris): a web application that combines mammography and ultrasound detection with long-term breast cancer risk prediction, built with a Flask backend and three AI models. I worked on the risk prediction module (AsymMirai with a multimodal extension combining imaging and clinical data), an RSNA benchmark, and the ultrasound classifier together with a teammate.

- **Responsible release:** before the repository was made public, it was reviewed for secrets, personal data and patient data; third-party licenses and model-weight provenance were checked, and weights whose redistribution rights were unclear were left out.
- **Honest evaluation:** reported figures are traced to their source, limits are documented (for example, imaging models at chance level in the RSNA benchmark), and the project is clearly labelled a student prototype, not a medical device.
- **Security awareness:** the README states that the Flask development server runs in debug mode with open CORS and must only be used locally.

## Tools and practice

- **Security:** Wazuh, Sysmon, MITRE ATT&CK, Burp Suite and Metasploit.
- **Systems and networks:** Linux, Windows, TCP/IP, Wireshark and Nmap.
- **Programming and scripting:** Python, C, Java, SQL and Bash; basic PowerShell knowledge.

I practise through [TryHackMe](https://tryhackme.com/p/mernissi.ayoub13) labs and challenges (**Top 5% worldwide**). I've completed the **Cyber Security 101** learning path and am currently working through **Jr Penetration Tester**.

On PortSwigger Web Security Academy, I practise SQL injection and server-side vulnerability labs.

## Education

- Fourth year at ESIEE Paris; ranked second in my class during my third year.
- Exchange semester at the University of Bologna.

## Contact

[LinkedIn](https://www.linkedin.com/in/ayoub-mernissi) · [TryHackMe](https://tryhackme.com/p/mernissi.ayoub13)

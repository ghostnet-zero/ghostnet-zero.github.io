# ghostnet-zero.github.io
# 🕶️ Ghostnet-Zero: A Self-Taught Red + Blue Team Lab

> _“This lab is my playground and my proving ground. I built it to teach myself how real adversaries behave—and how defenders detect them.”_

Ghostnet-Zero is a modular cybersecurity lab built from the ground up to explore both red team and blue team operations. Every container in this project is a focused, hands-on lesson—designed, broken, rebuilt, and refined through trial and error.

---

## 🧠 What This Lab Is

- A place to simulate real-world attacks using tools like Nmap, Impacket, and Metasploit  
- A space to detect and investigate those attacks using Zeek, Suricata, Wazuh, and Osquery  
- A framework for learning by doing—automated with Ansible, orchestrated with Docker Compose, and built on NixOS for reproducibility  
- A way to challenge myself with AI-driven adversaries (RedAI) and guided detection prompts (SOCai)

---

## 🧱 Modular Design

Each module is a self-contained lab environment:

| Module | Tool | RedAI Attack | SOCai Focus |
|--------|------|--------------|-------------|
| `blue-zeek-net` | Zeek | SYN scan, banner grab | Network metadata analysis |
| `blue-suricata-exfil` | Suricata | DNS tunneling | Signature tuning and alerting |
| `blue-osquery-persistence` | Osquery | Registry keys, cron jobs | Endpoint hunting |
| `red-impacket-lateral` | Impacket | SMB relay | Lateral movement simulation |

---

## ⚙️ Tech Stack

- 🧠 AI: LangChain + GPT for log parsing and guided learning  
- 🔧 Automation: Ansible for orchestration and attack toggles  
- 🧱 Infrastructure: NixOS + Docker Compose for modular, reproducible builds  
- 🧪 Targets: VulnHub VMs and custom RedAI scripts  
- 🧰 Tools: Zeek, Suricata, Osquery, Wazuh, Metasploit, NetExec, and more

---

## 🧭 Why I Built This

I wanted to understand cybersecurity from both sides—attacker and defender. I didn’t want to just follow tutorials or passively consume content. I wanted to build, break, detect, and learn through doing.

This lab is the result of that mindset. No classroom. No instructor. Just curiosity, iteration, and a relentless drive to understand.

---

> _“Each container is a lesson I gave myself.”_

# SOC Analyst Training Simulator

An interactive browser-based game for practising defensive Security Operations Centre (SOC) skills. Built to simulate real Tier 1 SOC analyst work — log analysis, alert triage, and incident classification.

## 🎮 Live Demo

> **[▶ Play the Simulator](https://ibrahimiyawa.github.io/soc-analyst-simulator)**

---

## 📋 What It Covers

The simulator presents 8 real-world alert scenarios drawn from common SOC investigations:

| Scenario | Concept |
|----------|---------|
| Brute Force — Domain Account | Windows Event IDs 4624 / 4625 / 4740 |
| Suspicious PowerShell Execution | Malware / LOLBins / C2 Communication |
| Multiple Failed SSH Logins | Linux Auth Logs / SSH Hardening |
| After-Hours Admin Login | Behavioural Anomaly Detection |
| Firewall Port Scan Detected | Network Reconnaissance |
| Phishing Email — Credential Harvester | SPF / DKIM / DMARC / Email Security |
| Scheduled AV Scan Alert | False Positive Identification / Alert Fatigue |
| Lateral Movement — Pass-the-Hash | NTLM vs Kerberos / Credential Attacks |

---

## 🕹️ How to Play

1. Select a difficulty level — **Rookie**, **Analyst**, or **Senior**
2. Pick an alert from the queue on the left
3. Read the event logs and answer the investigation questions
4. Make your triage decision: **Escalate**, **Resolve**, or **False Positive**
5. Review your score and lesson recap at the end of the shift

**Difficulty levels:**
- **Rookie** — No time limit, focus on learning
- **Analyst** — 120 second response timer per incident
- **Senior** — 60 second response timer, maximum pressure

---

## 🧠 Skills Practiced

- Reading Windows Security Event Logs
- Identifying brute force, lateral movement, and C2 patterns
- Email header and authentication analysis (SPF/DKIM/DMARC)
- Linux `/var/log/auth.log` interpretation
- Network traffic and firewall log analysis
- Alert triage: escalate vs resolve vs false positive
- Reducing alert fatigue through accurate classification

---

## 🚀 Running Locally

No installation required. Just open the file in any browser:

```bash
git clone https://github.com/ibrahimiyawa/soc-analyst-simulator.git
cd soc-analyst-simulator
open index.html
```

Or simply download `index.html` and double-click it.

---

## 🛠️ Built With

- HTML5
- CSS3 (custom HUD/terminal aesthetic, no frameworks)
- Vanilla JavaScript (no dependencies)

---

## 👤 Author

**Ibrahim Aminu Iyawa**
Network Support Technician → SOC Analyst
- GitHub: [github.com/ibrahimiyawa](https://github.com/ibrahimiyawa)
- LinkedIn: [linkedin.com/in/ibrahim-iyawa-90b729352](https://www.linkedin.com/in/ibrahim-iyawa-90b729352)

---

## 📄 License

MIT License — free to use and modify.

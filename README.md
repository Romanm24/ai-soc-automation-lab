\# AI SOC Automation Lab



Automated SOC pipeline with AI-powered threat analysis, escalation logic, and real-time Discord alerting.



\## What This Is

This is the automation and agent layer of the Delta Force AI SOC Platform. It monitors incoming logs, analyzes threats using Claude AI, and dispatches structured incident reports to Discord.



\## How It Works

Incoming log → auto\_soc.py → Claude AI analysis → Incident report saved → Discord alert fired



\## Tech Stack

| Layer | Tool |

|-------|------|

| AI Analysis | Claude AI (Anthropic) |

| Automation | Python, n8n |

| Alerting | Discord webhooks |

| Tracking | JSON database, text logs |



\## Part of Delta Force SOC

👉 \[View the full platform](https://github.com/Romanm24/deltaforce-soc-ai)



Built by Roman Mares — Cybersecurity Engineer \& AI SOC Builder  

📧 roman@deltaforcesecurity.io


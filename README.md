# Enterprise-Level SIEM with Elastic Security (ELK Stack)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Elastic Version](https://img.shields.io/badge/Elastic-8.x-blue)](https://www.elastic.co/)

A hands-on, enterprise-relevant Security Information and Event Management (SIEM) project built using **Elastic Security** on the Elastic Stack. This lab demonstrates real-time log ingestion, threat detection, custom dashboards, prebuilt and custom detection rules, timelines for investigations, and simulated attacks in an isolated environment.

## 🎯 Project Goals
- Implement centralized logging and security monitoring
- Enable threat hunting with MITRE ATT&CK mappings
- Create custom detection rules and alerts
- Simulate real-world attacks (e.g., port scans, brute force) for testing
- Demonstrate compliance features (NIST/ISO 27001 alignment)
- Build a portfolio-ready project showcasing defensive cybersecurity skills

## 🏗️ Architecture Overview

elastic-siem-home-lab/
├── README.md                  # Main project overview (most important!)
├── architecture/              # Diagrams
│   └── architecture.png       # High-level diagram (we'll add later)
├── screenshots/               # Kibana dashboards, alerts, timelines
│   ├── overview-dashboard.png
│   ├── detection-alert.png
│   └── timeline-investigation.png
├── config/                    # Config files (safe versions, no secrets)
│   ├── elastic-agent-policy.md
│   └── custom-detection-rules.ndjson
├── scripts/                   # Attack simulation scripts
│   ├── generate-nmap-scans.sh
│   └── atomic-red-team-simulations.sh
├── docs/                      # Detailed write-ups
│   ├── setup-guide.md
│   ├── threat-simulations.md
│   └── lessons-learned.md
├── .gitignore
└── LICENSE

- **Elastic Cloud Deployment** (or self-hosted Docker option)
- **Elastic Agents** on endpoint VMs (Kali Linux, Windows, Ubuntu)
- **Fleet Server** for agent management
- Simulated attacks from Kali Linux using safe tools (Nmap, Atomic Red Team)

## 🚀 Quick Start
1. Sign up for Elastic Cloud free trial: https://cloud.elastic.co/
2. Create a Security deployment
3. Deploy Elastic Agents on lab VMs
4. Generate events and watch detections fire!

(Full setup guide in `/docs/setup-guide.md`)

## 📸 Screenshots


## 🛠️ Technologies Used
- Elastic Stack (Elasticsearch, Kibana, Fleet, Elastic Security)
- Elastic Agent with Sysmon integration
- VirtualBox/VMware for lab VMs
- Kali Linux for attack simulation

## 📚 Resources & Inspiration
- Official Elastic Security Guide
- Great community labs: [SreeRaj-K0](https://github.com/SreeRaj-K0/Elastic-SIEM-Home-Lab-And-Elastic-Defend-EDR), [ryuk27](https://github.com/ryuk27/elastic-siem)

## 📄 License
MIT License

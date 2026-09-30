# CyberWar-Tool-Directory
Open for Contribution
⚠️ For Education purposes only!

🧭 Overall Website Architecture

```bash
                         CYBERWAR
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
       DISCOVER            LEARN             USE
          │                 │                 │
          │                 │                 │
       Categories        Roadmaps           Tools
       Search            Concepts           Commands
       Comparisons       Guides             Examples
          │                 │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                       COMMUNITY
                            │
                 ┌──────────┼──────────┐
                 ▼          ▼          ▼
              Contribute  Verify    Update
```

---

Webpage Structure:

```bash
CyberWar Tool Directory
│
├── 🏠 HOME
│
├── 🧰 TOOLS
│   │
│   ├── OSINT
│   │   ├── Phone Number
│   │   ├── Email
│   │   ├── Username
│   │   ├── Social Media
│   │   ├── Domain
│   │   ├── IP / Network
│   │   ├── Images / Metadata
│   │   ├── Search Engines
│   │   └── Archives
│   │
│   ├── 🔴 PENTESTING
│   │   ├── Reconnaissance
│   │   ├── Network
│   │   ├── Web
│   │   ├── Enumeration
│   │   ├── Vulnerability Scanning
│   │   ├── Password / Hash
│   │   └── Exploitation
│   │
│   ├── 🌐 NETWORKING
│   │   ├── Discovery
│   │   ├── Packet Analysis
│   │   ├── DNS
│   │   ├── HTTP
│   │   ├── Traffic
│   │   └── Network Utilities
│   │
│   ├── 🔬 FORENSICS
│   │   ├── Disk
│   │   ├── Memory
│   │   ├── File Analysis
│   │   ├── Metadata
│   │   └── Incident Response
│   │
│   ├── 📡 WIRELESS
│   │   ├── Wi-Fi
│   │   ├── Bluetooth
│   │   └── Wireless Analysis
│   │
│   ├── ☁️ CLOUD / DEVSECOPS
│   │   ├── Cloud
│   │   ├── Containers
│   │   ├── Kubernetes
│   │   └── CI/CD Security
│   │
│   └── ⚙️ MISC
│       ├── Cryptography
│       ├── Encoding
│       ├── Automation
│       ├── Wordlists
│       └── Utilities
│
├── 🗺️ ROADMAPS
│   ├── Absolute Beginner
│   ├── Cybersecurity Fundamentals
│   ├── OSINT Investigator
│   ├── Web Pentester
│   ├── Network Pentester
│   ├── Bug Bounty
│   ├── Blue Team
│   ├── Digital Forensics
│   └── CTF Beginner
│
├── ⚔️ COMPARISONS
│   ├── Tool vs Tool
│   ├── Which Tool?
│   ├── Feature Comparisons
│   └── Alternatives
│
├── 📚 LEARNING HUB
│   ├── Cyber Concepts
│   ├── Beginner Guides
│   ├── Practice Labs
│   ├── CTF Resources
│   ├── Certifications
│   └── Resources
│
├── 📋 CHEATSHEETS
│   ├── Nmap
│   ├── Linux
│   ├── Bash
│   ├── PowerShell
│   ├── Wireshark
│   ├── tcpdump
│   ├── Networking
│   └── Regex
│
├── 👥 COMMUNITY
│   ├── Contributors
│   ├── Recently Updated
│   ├── Add Tool
│   ├── Request Tool
│   ├── Suggest Edit
│   ├── Report Outdated Info
│   └── GitHub
│
└── ℹ️ ABOUT
    ├── About
    ├── Verification
    ├── Sources
    ├── Contribution Guide
    ├── Privacy
    ├── Terms
    └── Disclaimer
```

🏠 Homepage Architecture

```bash
┌─────────────────────────────────────────────────────────┐
│ NAVBAR                                                  │
│                                                         │
│ Logo | Tools | Roadmaps | Comparisons | Learning | ... │
│                                      Search | Theme | ☰ │
└─────────────────────────────────────────────────────────┘

                         HERO

             Cybersecurity Tools.
             Commands. Knowledge.

      Curated tools, commands, setup guides
           and practical resources.

        ┌─────────────────────────────────┐
        │ 🔎 Search tools, commands...    │
        └─────────────────────────────────┘


                     QUICK STATS

       ┌────────┐ ┌────────┐ ┌────────┐ ┌────────┐
       │ 250+   │ │ 3000+  │ │ 50+    │ │ Open   │
       │ Tools  │ │ Cmds   │ │ Topics │ │ Source │
       └────────┘ └────────┘ └────────┘ └────────┘


                 EXPLORE CATEGORIES

 ┌─────────┐ ┌────────────┐ ┌────────────┐
 │  OSINT  │ │ Pentesting │ │ Networking │
 └─────────┘ └────────────┘ └────────────┘

 ┌───────────┐ ┌──────────┐ ┌────────────┐
 │ Forensics │ │ Wireless │ │ Cloud/etc. │
 └───────────┘ └──────────┘ └────────────┘


                   POPULAR TOOLS

   Nmap   Burp   Wireshark   ffuf   Sherlock
    │       │        │         │        │


                  LEARNING PATHS

 ┌──────────────┐ ┌──────────────┐
 │ Beginner     │ │ OSINT        │
 │ Fundamentals │ │ Investigator │
 └──────────────┘ └──────────────┘

 ┌──────────────┐ ┌──────────────┐
 │ Web          │ │ Bug Bounty   │
 │ Pentester    │ │              │
 └──────────────┘ └──────────────┘


                RECENTLY UPDATED

      Nmap     Sherlock     Wireshark


                       ↓

                    FOOTER

```


🧰 Tools Architecture:
- When someone clicks Tools

```bash
TOOLS
 │
 ├── Category navigation
 │
 ├── Search
 │
 ├── Filters
 │    ├── Category
 │    ├── Platform
 │    ├── Difficulty
 │    └── Purpose
 │
 └── Tool Cards
```


📄 Individual Tool Page

This is the most important page template.

```bash
┌───────────────────────────────────────────────┐
│ ← Tools / OSINT / Username                   │
│                                               │
│ 🔵 Sherlock                                  │
│ Hunt down social media accounts by username   │
│                                               │
│ [GitHub] [Official] [Copy Link]               │
│                                               │
│ ✓ Verified     v0.x     Linux / Win / macOS  │
└───────────────────────────────────────────────┘

┌──────────────┐ ┌─────────────────────────────┐
│ PAGE NAV     │ │ CONTENT                     │
│              │ │                             │
│ Overview     │ │ Overview                    │
│ Installation │ │ What is Sherlock?           │
│ Commands     │ │                             │
│ Examples     │ │ Installation                │
│ Use Cases    │ │ ─────────────               │
│ Errors       │ │ Windows | Linux | macOS     │
│ Alternatives │ │                             │
│ References   │ │ Commands                    │
│              │ │ ┌─────────────────────────┐ │
│              │ │ │ command                 │ │
│              │ │ │                    Copy │ │
│              │ │ └─────────────────────────┘ │
│              │ │                             │
│              │ │ Example                     │
│              │ │                             │
│              │ │ Common Errors               │
│              │ │                             │
│              │ │ Related Tools               │
└──────────────┘ └─────────────────────────────┘
```

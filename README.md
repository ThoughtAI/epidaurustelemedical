# Epidaurus Telemedical — Thought Seeing

> **AI-powered telemedicine platform** by [Mosae Zorg Industries](https://mosaezorg.com)

---

## Overview

**Epidaurus Telemedical** is a next-generation telehealth platform built around **Thought Seeing** — our proprietary AI-assisted diagnostic engine that helps clinicians surface critical insights during remote consultations.

Named after the ancient Greek sanctuary of Epidaurus, where the sick travelled in search of healing, we carry that mission into the digital age: **world-class healthcare, accessible from anywhere.**

## Key Features

| Feature | Description |
|---------|-------------|
| 🧠 **Thought Seeing AI** | Synthesises patient history, symptoms, and behavioural cues to support clinical decision-making |
| 📹 **HD Video Consultations** | Low-latency video visits with screen sharing, annotations, and auto-generated summaries |
| 📊 **Continuous Monitoring** | Wearable & IoT integration with intelligent alerts for out-of-range vitals |
| 🔒 **End-to-End Encryption** | HIPAA, GDPR, SOC 2 Type II compliant — data encrypted in transit and at rest |
| 💊 **Smart Prescriptions** | E-prescribing with drug-interaction checks and pharmacy integration |
| 🌐 **Multi-language** | Real-time translation across 40+ languages |

## How It Works

1. **Describe** — Patient shares symptoms via AI-guided intake forms  
2. **Match** — Algorithm selects the best-fit specialist  
3. **Consult** — Live video visit with real-time AI diagnostic assistance  
4. **Follow-up** — Automated care plans, prescription delivery, and check-in reminders

## Tech Stack

- **Frontend:** Static site (HTML/CSS/JS) hosted on GitHub Pages  
- **Domain:** [epidaurustelemedical.com](https://epidaurustelemedical.com)  
- **DNS:** IONOS (A records → GitHub Pages IPs, CNAME `www` → `thoughtai.github.io`)  
- **CI/CD:** GitHub Pages auto-deploy from `main` branch

## Deployment

This site is deployed via **GitHub Pages**:

```
Branch: main
Path:   / (root)
Domain: epidaurustelemedical.com (custom domain via CNAME file)
HTTPS:  Enforced
```

### DNS Configuration (IONOS)

| Type  | Host | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | thoughtai.github.io    |

## Local Development

```bash
# Clone the repo
git clone https://github.com/ThoughtAI/epidaurustelemedical.git
cd epidaurustelemedical

# Open in VS Code
code .

# Serve locally (Python)
python -m http.server 8000

# Or with Node
npx serve .
```

Then open [http://localhost:8000](http://localhost:8000)

## Project Structure

```
epidaurustelemedical/
├── index.html    # Main website (Thought Seeing landing page)
├── CNAME         # Custom domain for GitHub Pages
└── README.md     # This file
```

## License

© 2026 Epidaurus Telemedical · Mosae Zorg Industries. All rights reserved.

## Contact

- 📧 hello@epidaurustelemedical.com  
- 📍 Mosae Zorg Industries, The Netherlands

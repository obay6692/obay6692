# ☁️ Greetings From Production ☁️

```python
from enum import Enum
from dataclasses import dataclass


class University(Enum):
    UNIVERSITY_OF_AGDER = "UiA — Grimstad, Norway"


@dataclass
class Engineer:
    name:        str
    location:    str
    university:  University
    field:       str
    role:        str
    stack:       dict
    currently:   str
    looking_for: str


def main():
    me = Engineer(
        name        = "Obay bin Khadra",
        location    = "Norway 🇳🇴",
        university  = University.UNIVERSITY_OF_AGDER,
        field       = "Data Engineering & Software Development — graduated 2025",
        role        = "Software Architect & DevOps Engineer",

        stack = {
            "cloud":      ["Kubernetes", "ArgoCD", "Sealed Secrets", "OpenStack"],
            "iac":        ["Terraform", "Ansible", "Vagrant", "Docker", "cloud-init"],
            "backend":    ["FastAPI", "ASP.NET Core", "Flask", "Go", "SQLAlchemy", "EF Core"],
            "frontend":   ["React", "React Router", "Axios", "Recharts"],
            "ai_vision":  ["OpenCV", "Ollama", "feature matching", "face recognition"],
            "data":       ["Streamlit", "Plotly", "Monte Carlo", "Pandas", "NumPy"],
            "embedded":   ["Mbed OS", "STM32", "I²C", "WiFi", "RTOS", "Thingsboard"],
            "security":   ["OAuth 2.0", "TOTP 2FA", "bcrypt", "JWT", "OWASP basics"],
            "languages":  ["Python", "C", "C++", "C#", "Go", "JavaScript", "Bash"],
        },

        currently   = "Maintaining Virtual CFO — a production-grade fintech SaaS for Norwegian SMBs",
        looking_for = "DevOps · Software Architecture · Cloud Engineering · IoT roles",
    )

    print(f"Hello, I'm {me.name} 👋")


if __name__ == "__main__":
    main()
```

---

## 🎓 Bachelor's Graduation Project

### [🏦 Virtual CFO](https://github.com/obay6692/virtual-cfo)

A full-stack financial management platform for Norwegian SMBs.

```
FastAPI  +  React  +  Ollama  +  Docker  +  Nginx (HTTPS)
   │         │         │          │         │
   └─ JWT, TOTP 2FA, bcrypt, rate limiting, account lockout
             │
             └─ Dashboard · Invoices · Cash-flow forecast · Payment prioritization · AI advisor · GDPR export
```

---

## 🚀 Featured Projects

| | Project | Stack |
|---|---------|-------|
| ☸️ | [**k8s-mastodon-monitoring-stack**](https://github.com/obay6692/k8s-mastodon-monitoring-stack) | Mastodon + ArgoCD + Sealed Secrets + Prometheus/Grafana/Loki |
| 🔧 | [**mbed-stm32-embedded-projects**](https://github.com/obay6692/mbed-stm32-embedded-projects) | STM32 · Mbed OS · I²C · WiFi · RTOS · IoT telemetry |
| 🛠️ | [**ikt114-it-orchestration-devops**](https://github.com/obay6692/ikt114-it-orchestration-devops) | Bash · Docker · Vagrant · Ansible · Terraform · OpenStack |
| 🔐 | [**flask-2fa-oauth-app**](https://github.com/obay6692/flask-2fa-oauth-app) | Flask · GitHub OAuth · TOTP 2FA · bcrypt · lockout |
| 📊 | [**us_election_simulation_project**](https://github.com/obay6692/us_election_simulation_project) | Streamlit · Monte Carlo · Plotly · Pandas |
| 👁️ | [**ikt213-computer-vision-assignments**](https://github.com/obay6692/ikt213-computer-vision-assignments) | OpenCV · ORB · feature matching · face recognition |

---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Obay_bin_Khadra-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/obay-bin-khadraa-61452b1a1/)
[![GitHub](https://img.shields.io/badge/GitHub-obay6692-181717?style=for-the-badge&logo=github)](https://github.com/obay6692)
[![Location](https://img.shields.io/badge/Norway-🇳🇴-EF2B2D?style=for-the-badge)](https://www.google.com/maps/place/Norway)

> Open to **DevOps**, **Software Architecture**, **Cloud Engineering**, and **IoT** roles.

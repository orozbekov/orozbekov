# Timur Suerkulov

**Infrastructure Engineer · SysAdmin → DevOps** · Bishkek, Kyrgyzstan

I keep systems alive, secure, and observable — then automate everything I just did manually.
Currently managing full-stack corporate IT infrastructure while building toward a dedicated DevOps role.

---

## Infrastructure I Own

| Layer | Tools |
|---|---|
| **OS & Server** | Windows Server (AD, DC, GPO, DHCP, DNS), Linux (Ubuntu/Debian) |
| **Networking** | MikroTik RouterOS — routing, firewall, VLANs, VPN (L2TP/IPSec, WireGuard) |
| **Security & Access** | Proxy server, AD group policies, RDP, AnyDesk, TeamViewer |
| **Monitoring & CI/CD** | Netdata, Sentry, Grafana, Prometheus, Kubernetes, Jenkins, GitLab CI, GitHub Actions, Nginx |
| **Containers** | Docker, Docker Compose |
| **Automation** | Bash, PowerShell, Python |
| **VCS** | Git, GitHub, GitLab |

---

## What I Actually Do Day-to-Day

```bash
# Morning
$ check-netdata-alerts && review-sentry-errors

# Infrastructure
$ configure-mikrotik --vlan=new-office --firewall=strict
$ deploy-service --docker-compose up -d
$ New-ADUser -Name "..." -Path "OU=Staff,DC=corp,DC=local"

# When things break at 2am
$ ssh root@server "journalctl -u nginx --since '10 min ago'"
$ tail -f /var/log/syslog | grep -i "error\|crit"

# Automation (so it doesn't break at 2am again)
$ vim automate-this.sh
```

---

## Background in Backend Dev

Before going deep into infra, I spent time building backends — which means I actually understand what I'm deploying.

```
Python · Django · DRF      PostgreSQL · Redis      Docker
REST API design             JWT Auth                Celery
C# · ASP.NET Core           Entity Framework        Git workflows
```

Interned at **TimelySoft** (2023) — built a CRM API and authorization service in production.

---

## Roadmap

```
2026 ████████████░░░░░░  SysAdmin + DevOps practices    ← now
2026 ░░░░████████████░░  Kubernetes, Terraform, CI/CD
2027 ░░░░░░░░████████░░  Full DevOps Engineer role
```

**Studying next:**
- `kubernetes` — CKA certification path
- `terraform` — infrastructure as code
- `github-actions` / `gitlab-ci` — CI/CD pipelines
- `prometheus` + `grafana` — proper observability stack
- `ansible` — configuration management at scale

---

## Education

```yaml
- institution: IT Academy
  program: Backend Developer (Python, C#)
  period: 2021 – 2023

- institution: ATEK College
  program: Technician
  period: 2019 – 2022
```

---

## Languages

`Kyrgyz` native · `Russian` fluent · `English` technical · `Turkish` conversational

---

## Reach Me

[![Email](https://img.shields.io/badge/-tiima.orozbekov@gmail.com-black?style=flat-square&logo=gmail)](mailto:tiima.orozbekov@gmail.com)
&nbsp;&nbsp;
`+996 505 73-27-73`

---

<sub>Infrastructure doesn't lie. Logs don't either.</sub>

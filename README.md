# Hi, I'm Rey

I'm a self-taught DevOps and cloud engineer. I also build **AI agents** — backend systems that use LLMs (like Google Gemini) to handle real tasks such as answering customer questions, qualifying leads, and booking appointments.

I like to learn by building real projects, deploying them, and writing down what actually happened — including the errors I hit and how I fixed them.

## What I know

- **Cloud & Infrastructure:** AWS (EKS, ECR, CloudShell, IAM), Terraform, eksctl, Kubernetes, Docker, Ansible
- **CI/CD:** GitHub Actions, Jenkins, GitLab CI
- **AI Agents & Backend:** Python, FastAPI, Google Gemini API, PostgreSQL, SQLite, Node.js
- **Other:** Basic security/detection engineering, Linux troubleshooting

## Projects

### FINTECH-CLOUD-EKS
A fintech API deployed to AWS using Kubernetes. Built two ways — with eksctl and with Terraform — with autoscaling, health checks, CI/CD, and notes on cost and security.

```
api-service/   → Flask app, Dockerfile, k8s manifests
infra/         → Terraform (EKS cluster)
.github/       → CI/CD workflows
```

**Future plans:** add Prometheus/Grafana monitoring, container vulnerability scanning (Trivy), and Network Policies.
🔗 https://github.com/rey26341-sudo/FINTECH-CLOUD-EKS

---

### devops-stack
A full DevOps pipeline: Terraform builds the infrastructure, Ansible configures the server, and Jenkins handles build-and-deploy automatically on every push.

```
terraform/     → infrastructure provisioning
ansible/       → server configuration
jenkins/       → CI/CD pipeline config
```

**Future plans:** add automated rollback on failed deploys and a staging environment.
🔗 https://github.com/rey26341-sudo/devops-stack

---

### yellamma-bot
An AI agent that acts as a receptionist for multiple businesses from one backend — answers questions and books appointments using Google Gemini.

```
app/           → FastAPI backend + Gemini agent logic
db/            → PostgreSQL models
Dockerfile
```

**Future plans:** add WhatsApp integration and a business owner dashboard.
🔗 https://github.com/rey26341-sudo/yellamma-bot

---

### bilingual-tour-ops-agent
An AI agent that reads travel enquiries in Chinese or English, extracts key details (dates, budget, group size), and flags incomplete ones for human review.

```
app/           → FastAPI backend + Gemini agent logic
models/        → Pydantic schemas
db.sqlite
```

**Future plans:** add a human-review web dashboard and CRM export.
🔗 https://github.com/rey26341-sudo/bilingual-tour-ops-agent

---

### SOC-Evaluation-Lab
A small security project that detects repeated failed login attempts and generates alerts, similar to what a SOC analyst would monitor.

```
detectors/     → detection logic (brute-force login)
alerts/        → JSON alert output
```

**Future plans:** add more detection rules and a simple alert dashboard.
🔗 https://github.com/rey26341-sudo/SOC-Evaluation-Lab

---

### ENVIRONMENT-ACCESS-VALIDATION
A script that checks whether a system is ready for deployment — server access, repo structure, pipeline status, and logs — built and tested on real AWS CloudShell.

```
scripts/       → validation checks
.github/       → CI workflow
```

**Future plans:** turn checks into a reusable CI/CD pre-deploy gate.
🔗 https://github.com/rey26341-sudo/ENVIRONMENT-ACCESS-VALIDATION

---

### SYSTEM-TROUBLESHOOTING-CASE-STUDY
A write-up of a real problem I debugged: a dual-boot laptop with a frozen screen and dead touchpad. The cause turned out to be a hardware key, not the software I'd spent hours checking.

```
README.md      → full case study write-up
```

**Future plans:** turn this into a general troubleshooting checklist for dual-boot systems.
🔗 https://github.com/rey26341-sudo/SYSTEM-TROUBLESHOOTING-CASE-STUDY

## How I work

- I write down real errors and how I fixed them, not just the finished result.
- I test things end-to-end and keep proof (screenshots, logs, output) instead of just describing what should work.
- I'm comfortable working across infrastructure (Terraform, Kubernetes, CI/CD) and AI-driven backend systems (FastAPI + agents).

## Contact

Open an issue on any of my repos, or find me at [github.com/rey26341-sudo](https://github.com/rey26341-sudo).

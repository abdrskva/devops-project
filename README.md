#  DevOps Infrastructure Repository

Lab done by : Salima Abdyrasakova 
Group : COMCEH-23 
Course : DevOps 

This repository contains infrastructure and automation configurations created as part of the Week 2 DevOps assignment.

---

## 📂 Project Structure
devops-project/
├── infrastructure/
│   ├── terraform/
│   │   ├── main.tf
│   │   └── variables.tf
│   ├── ansible/
│   │   └── playbook.yml
│   ├── kubernetes/
│   │   ├── deployment.yaml
│   │   └── service.yaml
│   ├── docker/
│   │   └── Dockerfile
│   └── monitoring/
│       └── prometheus.yml
├── .github/workflows/
│   └── ci.yml
├── .gitignore
└── README.md
---

## Technologies Used

- **Git & GitHub**
- **Terraform** (Infrastructure as Code)
- **Ansible** (Configuration Management)
- **Docker** (Containerization)
- **Kubernetes** (Container Orchestration)
- **GitHub Actions** (CI/CD)
- **Prometheus** (Monitoring)

---

##  Features Implemented

- ✔ Feature branch workflow
- ✔ Multiple Pull Requests
- ✔ Merge commits
- ✔ Git conflict resolution
- ✔ Infrastructure as Code structure
- ✔ CI/CD workflow configuration
- ✔ Proper `.gitignore` setup

---

##  Git Workflow

1. Created feature branches
2. Implemented infrastructure components
3. Committed changes with meaningful messages
4. Opened Pull Requests
5. Performed merges into `main`
6. Verified CI execution

---

##  CI/CD

GitHub Actions workflow:

- Triggered on push and pull request
- Basic validation step
- Repository checkout

Workflow file:
.github/workflows/ci.yml
---

##  Best Practices Applied

- Descriptive commit messages
- Structured branching strategy
- Clean project organization
- Secrets excluded via `.gitignore`
- Merge-based integration

---

##  How to Clone

```bash
git clone https://github.com/<your-username>/devops-project.git
cd devops-project

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2196F3&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Bhargav+Patel+%F0%9F%91%8B;DevOps+%26+Cloud+Engineer;GitOps+%7C+AWS+EKS+%7C+CI%2FCD+Pipelines;DevSecOps+%7C+Observability+%7C+IaC)](https://git.io/typing-svg)

---

### 🚀 DevOps Engineer · AWS EKS · GitOps · DevSecOps · Observability

DevOps Engineer with hands-on experience building end-to-end CI/CD pipelines on **AWS EKS** using **Jenkins**, **ArgoCD**, and **Kubernetes**. Implemented GitOps workflows with integrated DevSecOps tooling (Trivy, OWASP, SonarQube) and live observability via **Prometheus + Grafana**. Brings a quality-first mindset from 3 years in QA automation — strong cross-team incident communication.

---

</div>

## 🛠️ Tech Stack

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=flat&logo=kubernetes&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-%23EF7B4D.svg?style=flat&logo=argo&logoColor=white)

**CI/CD & GitOps**

![Jenkins](https://img.shields.io/badge/Jenkins-%232C5263.svg?style=flat&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white)

**Cloud — AWS**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-%23FF9900.svg?style=flat&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-%23569A31.svg?style=flat&logo=amazon-s3&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-%23DD344C.svg?style=flat&logo=amazon-aws&logoColor=white)

**DevSecOps & Observability**

![SonarQube](https://img.shields.io/badge/SonarQube-%234E9BCD.svg?style=flat&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-%231904DA.svg?style=flat&logo=aqua&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white)

**IaC & Scripting**

![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat&logo=terraform&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 🌟 Featured Projects

### 🧳 WanderLust — Full GitOps CI/CD Pipeline on AWS EKS

> `Jenkins` · `ArgoCD` · `Docker` · `AWS EKS` · `Trivy` · `OWASP` · `SonarQube` · `Prometheus` · `Grafana` · `Redis` · `MongoDB`

A production-grade travel platform showcasing a complete GitOps-driven delivery pipeline with end-to-end DevSecOps and observability baked in.

- **CI Pipeline:** Parameterized Jenkins pipeline — Git checkout → Trivy filesystem scan → OWASP Dependency Check → SonarQube quality gate → parallel frontend/backend env setup → multi-stage Docker builds → tagged DockerHub push — zero manual steps.
- **CD Pipeline:** Tag-driven Jenkins pipeline auto-updates Kubernetes manifests, commits to GitHub, and triggers ArgoCD GitOps sync to AWS EKS with zero manual deployment steps.
- **Observability:** Deployed Prometheus + Grafana on EKS with live dashboards tracking CPU, memory, and pod health; configured automated HTML email alerts per build.
- **DevSecOps shift-left:** Trivy scans pre-build; OWASP checks pre-push — broken or vulnerable code never becomes a deployable image.

---

### 🗺️ Jerney — 3-Tier Blog Platform on AWS EKS

> `Docker` · `Kubernetes` · `AWS EKS` · `EBS CSI Driver` · `Minikube` · `PostgreSQL` · `React` · `Node.js`

A fully containerized 3-tier blog platform (React + Node.js + PostgreSQL) deployed on AWS EKS with stateful persistence and full CI/CD automation.

- **Containerization:** Custom Dockerfiles and Docker Compose for local dev parity; validated inter-service networking on Minikube before EKS promotion.
- **Stateful persistence:** Provisioned EBS CSI Driver with PV/PVCs on EKS — zero-data-loss PostgreSQL persistence across pod restarts and node failures.
- **Kubernetes manifests:** Authored complete set — Deployments, Services, PV/PVCs, Secrets — for full-stack orchestration.
- **Automated delivery:** Every git push triggers Docker build → DockerHub push → manifest update → `kubectl apply` → EKS rolling update → rollout verification.
- **Ingress & webhooks:** Configured ALB Ingress Controller and GitHub Webhooks for event-driven pipelines; enforced build-number image tagging (not `latest`) for guaranteed rolling update detection.

---

## 📌 Other Projects

| Project | Stack | Highlights |
|---|---|---|
| **3-Tier To-Do App on EKS** | Docker · K8s · EKS · NGINX · NLB · MongoDB | Kubernetes Secrets management, namespace isolation, NGINX Ingress + AWS NLB |
| **Two-Tier Flask + MySQL on K8s** | Docker (multi-stage) · K8s · Flask · MySQL · ConfigMaps | Multi-stage builds to reduce image footprint; ConfigMaps for DB config decoupling |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bhargav-patel3&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhargav-patel3&layout=compact&theme=default&hide_border=true" height="165" />

</div>

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=bhargav-patel3&theme=default&hide_border=true)

</div>

---

## 🏆 GitHub Achievements

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=bhargav-patel3&theme=flat&no-frame=true&column=6&margin-w=10)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 💼 Experience

**MOBA Mobile Automation Pvt Ltd** — QA Engineer *(Jul 2023 – Present)*
Designed TestNG-Maven automation framework cutting repetitive QA effort by 80%. Security testing with Burp Suite; REST API testing with Postman; defect tracking in JIRA within Agile sprints.

**Nevina Infotech Pvt Ltd** — QA Engineer *(May 2022 – Jun 2023)*
Functional, regression, and cross-browser testing for PWA and event organizer apps. Bug tracking via Trello/Mantis; daily Scrum standups.

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/bhargav-patel-devops)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:bhargavpatel3027@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat&logo=github&logoColor=white)](https://github.com/bhargav-patel3)

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=bhargav-patel3.bhargav-patel3)

</div>

---

<div align="center">
  <i>Open to DevOps, Cloud, and Platform Engineering roles · Ahmedabad, Gujarat · Available for full-time opportunities</i>
</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8B5CF6,6366F1,4F46E5&height=150&section=header&text=Rohit&fontSize=50&fontColor=ffffff&fontAlignY=45" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=A855F7&center=true&vCenter=true&width=500&height=50&lines=Cloud+%26+DevSecOps+Engineer;AWS+Cloud+Architect;Security+%26+Automation+Engineer" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Education-Cloud%20%26%20DevSecOps-8B5CF6?style=flat-square&logo=gitbook&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-India-6366F1?style=flat-square&logo=googlemaps&logoColor=white" />
  <a href="https://rohitdevdas.github.io"><img src="https://img.shields.io/badge/Portfolio-Explore-4F46E5?style=flat-square&logo=visualstudiocode&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/rohitdevdas"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:rohitdevdas240205@gmail.com"><img src="https://img.shields.io/badge/Email-rohitdevdas240205%40gmail.com-D11141?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Rohit24-devOp"><img src="https://img.shields.io/badge/GitHub-Rohit24--devOp-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>
<p align="center">
  <img src="https://komarev.com/ghvc/?username=Rohit24-devOp&color=8B5CF6&style=flat-square&label=Profile+Views" />
  <img src="https://img.shields.io/github/followers/Rohit24-devOp?color=6366F1&label=Followers&style=flat-square" />
  <img src="https://img.shields.io/github/stars/Rohit24-devOp?color=4F46E5&label=Stars&style=flat-square" />
</p>

---

## 🌌 About Me

I am an enterprise-focused Cloud & DevSecOps Engineer dedicated to building high-availability, highly secure, and automated cloud systems. With a strong software engineering foundation, I design production-grade Infrastructure as Code (IaC) solutions, optimize continuous delivery pipelines, and enforce strict defense-in-depth cloud security controls. 

Driven by a product engineering mindset, I bridge the gap between application code and cloud architecture, incorporating analytics and interactive diagnostic consoles to monitor health, security, and costs.

* 🚀 **Core Expertise:** Cloud Networking, Infrastructure as Code, CI/CD Automation, DevSecOps.
* 🤖 **AI/ML & Automation:** Designing anomaly-detection algorithms for WAF logs and deploying scalable model architectures.
* 🛡️ **Security First:** Implementing stateless network filters, least-privilege IAM, and static application security testing (SAST).
* 💼 **Open To:** Senior DevSecOps Engineer, Cloud Infrastructure Architect, or Cloud Security Consultant positions.

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,terraform,python,bash,githubactions,docker,kubernetes,linux,git,postgres,mongodb,react,nodejs,html,css" />
</p>

### 🛠️ Core Technologies

* **Languages:** Python, Bash, HTML/CSS, JavaScript
* **Frontend & Visualization:** React, Streamlit (for dashboards)
* **Backend & Databases:** Node.js, PostgreSQL, MongoDB
* **Cloud & DevOps:** AWS, Terraform, Docker, Kubernetes, Linux, GitHub Actions, Git

---

## 🤖 AI / ML & Automation Expertise

| Domain | Proficiency | Details |
|---|---|---|
| **Log Anomaly Detection** | Advanced | Developed custom Python scripts to parse, extract patterns, and identify security anomalies in AWS WAF JSON logs. |
| **Model Scaling & Deployment** | Intermediate | Implemented elastic architectures using AWS Auto Scaling Groups (ASG) and Application Load Balancers for model endpoints. |
| **Automated Security Pipelines** | Advanced | Integrated automated scanning tools (Trivy) into CI/CD workflows to prevent insecure package and base-image deployments. |

---

## 🏆 Featured Projects

<details>
<summary><b>🛡️ AWS DevSecOps Control Center</b></summary>
<br />

> **Enterprise-grade AWS security dashboard and attack simulation suite.**

### Project Overview
A comprehensive DevSecOps control center consisting of a Terraform-provisioned AWS environment, an automated attack simulator (Python/Streamlit), and an interactive metrics dashboard that parses and visualizes WAF traffic.

| Parameter | Specification |
|---|---|
| **Stack** | Terraform, Python, AWS WAF, Streamlit, Trivy, GitHub Actions |
| **Scale** | Multi-AZ security testing across simulated workloads |
| **Performance** | Real-time log ingestion and dashboard updating < 1.2s |
| **Security** | Automated vulnerability scans (Trivy SAST/DAST) in runner |
| **Impact** | Reduced security verification time by 80% through automated reporting |
| **Repository** | [AWS-DevSecOps-Control-Center](https://github.com/Rohit24-devOp/AWS-DevSecOps-Control-Center) |

#### Technical Deep-Dive
* Built an end-to-end testing platform to execute simulated network attacks (SQL Injection, XSS, Path Traversal) and verify AWS WAF rule enforcement.
* Generated automated compliance audit reports in PDF/CSV format with full attack logs and vulnerability breakdown.
* Built a modern, glassmorphic Streamlit dashboard that runs alongside the pipeline to display network metrics and threat intelligence.

</details>

<br />

<details>
<summary><b>🏗️ Enterprise AWS Multi-Tier VPC Architecture</b></summary>
<br />

> **Production-ready, highly-available networking and compute infrastructure.**

### Project Overview
A multi-tier AWS network environment designed for security, scalability, and high-availability across multiple Availability Zones, provisioned entirely as Infrastructure as Code.

| Parameter | Specification |
|---|---|
| **Stack** | Terraform, AWS VPC, EC2, Application Load Balancer, CloudWatch, IAM |
| **Scale** | Dual Availability Zones, 3-tier subnets (Public, Private App, Private DB) |
| **Performance** | Elastic scaling (2 to 6 EC2 instances) matching real-time traffic |
| **Security** | Bastion host jump server, stateless NACLs, stateful Security Groups |
| **Impact** | High-availability design ensuring 99.99% infrastructure uptime |
| **Repository** | [AWS-Enterprise-VPC](https://github.com/Rohit24-devOp/AWS-DevSecOps-Control-Center/tree/main/AWS%20VPC%20project) |

#### Technical Deep-Dive
* Segmented the VPC using a 3-tier subnet architecture to enforce strong network isolation between web, application, and database layers.
* Provisioned NAT Gateways to grant secure outbound internet access for patching and package installation in the private tiers without exposing them to incoming traffic.
* Configured CloudWatch dashboards, alarms, and SNS email alerts to automatically notify administrators of elevated CPU usage or elevated 5xx error rates on the ALB.

</details>

---

## 💼 Professional Experience

### Cloud & DevSecOps Engineer
**Self-Employed / Open Source Contributor** | *June 2025 - Present*
* Architected and built complete Infrastructure as Code templates for AWS web applications.
* Engineered CI/CD pipelines incorporating static code analysis, security scanning (Trivy), and automated infrastructure deployment.
* Authored comprehensive documentation, deployment validation scripts, and troubleshooting runbooks.
* **Skills:** `Terraform` · `AWS` · `GitHub Actions` · `Python` · `Bash` · `DevSecOps` · `Network Security`

### Associate Cloud Infrastructure Engineer
**Contract** | *January 2024 - May 2025*
* Maintained multi-zone network configurations and performed regular updates on VPC subnets and routing policies.
* Monitored compute nodes, optimized auto-scaling threshold conditions, and configured CloudWatch metric monitors.
* Implemented and managed Bastion hosts and IAM roles ensuring compliance with the principle of least privilege.
* **Skills:** `AWS VPC` · `EC2` · `IAM` · `CloudWatch` · `Terraform` · `Systems Manager`

---

## 🏆 Key Achievements

<p align="center">

| Recognition | Details |
|---|---|
| **Infrastructure Optimizer** | Reduced development infrastructure run costs by 35% through optimal NAT Gateway and scaling policies. |
| **DevSecOps Champion** | Achieved 100% automated security compliance gates on test repositories using Trivy scan integrations. |
| **Open Source Contributor** | Maintained active repositories showcasing production-grade AWS modules utilized by peer engineers. |

</p>

---

## 📜 Certifications

### 🌐 Amazon Web Services (AWS)
* <img src="https://img.shields.io/badge/AWS-Certified%20Solutions%20Architect--Associate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />
* <img src="https://img.shields.io/badge/AWS-Certified%20SysOps%20Administrator--Associate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />

### 🛢️ Database & Systems
* <img src="https://img.shields.io/badge/Oracle-Certified%20Associate%20Java%20SE%208-F80000?style=flat-square&logo=oracle&logoColor=white" />

### 🎓 Academic & Networking
* <img src="https://img.shields.io/badge/NPTEL-Cloud%20Computing--Elite%20Gold-blue?style=flat-square&logo=google-scholar&logoColor=white" />
* <img src="https://img.shields.io/badge/Cisco-CCNA%20Routing%20and%20Switching-049FD9?style=flat-square&logo=cisco&logoColor=white" />

---

## 💻 Coding Profiles

<p align="center">
  <a href="https://leetcode.com/Rohit24-devOp"><img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <a href="https://auth.geeksforgeeks.org/user/Rohit24-devOp"><img src="https://img.shields.io/badge/GeeksforGeeks-Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" /></a>
  <a href="https://www.hackerrank.com/Rohit24-devOp"><img src="https://img.shields.io/badge/HackerRank-Profile-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" /></a>
  <a href="https://www.codechef.com/users/Rohit24-devOp"><img src="https://img.shields.io/badge/CodeChef-Profile-5B4636?style=for-the-badge&logo=codechef&logoColor=white" /></a>
</p>

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rohit24-devOp&theme=violet&show_icons=true&hide_border=true&count_private=true" height="180px" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Rohit24-devOp&theme=violet&hide_border=true" height="180px" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rohit24-devOp&theme=violet&layout=compact&hide_border=true" height="180px" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Rohit24-devOp&theme=violet&no-bg=true&no-frame=true&margin-w=15&margin-h=15" />
</p>

---

## 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Rohit24-devOp&bg_color=0D1117&color=A855F7&line=8B5CF6&point=6366F1&area=true&hide_border=true" width="100%" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Rohit24-devOp/Rohit24-devOp/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" width="100%" />
</p>

---

## 🎯 Current Focus

```yaml
learning: "Advanced EKS Security & Multi-Cluster Mesh Architecture"
building: "AWS Event-Driven GuardDuty & Security Hub Automations"
exploring: "Generative AI for Cloud Infrastructure Threat Detection"
openTo: "Senior DevSecOps Engineer & Cloud Infrastructure Architect roles"
```

---

## 🤝 Connect With Me

<p align="center">
  <a href="mailto:rohitdevdas240205@gmail.com"><img src="https://img.shields.io/badge/Gmail-rohitdevdas240205%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/rohitdevdas"><img src="https://img.shields.io/badge/LinkedIn-Rohit%20Devdas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Rohit24-devOp"><img src="https://img.shields.io/badge/GitHub-Rohit24--devOp-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://rohitdevdas.github.io"><img src="https://img.shields.io/badge/Portfolio-Explore%20Site-4F46E5?style=for-the-badge&logo=visualstudiocode&logoColor=white" /></a>
</p>

---

<p align="center">
  <i>"Security is not an afterthought, it is the foundation of modern cloud scalability."</i>
</p>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4F46E5,6366F1,8B5CF6&height=100&section=footer&text=Automate%20Everything&fontSize=20&fontColor=ffffff&fontAlignY=55" width="100%" />
</p>

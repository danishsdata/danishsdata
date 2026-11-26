<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,100:2C5364&height=180&section=header&text=Danish%20Shaikh&fontSize=48&fontColor=ffffff" alt="Danish Shaikh" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=2E9EF7&center=true&vCenter=true&width=650&lines=AWS+DBA+%7C+Data+Engineer+%7C+DevOps+Engineer;RDS+%26+Aurora+PostgreSQL+at+scale;Redshift+DR+in+under+30+minutes;CloudFormation+%7C+Python+%7C+SQL" alt="Typing animation" />
</div>

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=danishsdata&color=0e75b6&style=flat)
![GitHub followers](https://img.shields.io/github/followers/danishsdata?style=flat&color=0e75b6)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danish1488)
![Open to Work](https://img.shields.io/badge/Open_to_Work-Full--time-2ea043?style=flat)

</div>

## 👋 About Me

I'm a data platform and cloud infrastructure engineer with 10+ years of experience keeping production databases and platforms fast, available, and observable — from Samsung service centers to Goldman Sachs and Prudential Financial. I work where data meets infrastructure: PostgreSQL and RDS at scale, production Kubernetes, infrastructure as code, and CI/CD automation.

- 🔭 Currently working at **Prudential Financial** as an AWS DBA / IaC Developer
- 🌱 Currently working toward **AWS Certified Solutions Architect – Associate**
- 💼 Open to full-time **AWS DBA, Data Engineer, DevOps, and Cloud/Platform** roles — remote US, or hybrid/onsite in Jersey City and New York City
- 📍 Based in Jersey City, NJ — authorized to work in the US, no sponsorship required

---

## 🛠️ Technologies & Tools

<div align="center">

![PostgreSQL](https://skillicons.dev/icons?i=postgres)
![AWS](https://skillicons.dev/icons?i=aws)
![Kubernetes](https://skillicons.dev/icons?i=kubernetes)
![Jenkins](https://skillicons.dev/icons?i=jenkins)
![Python](https://skillicons.dev/icons?i=python)
![Bash](https://skillicons.dev/icons?i=bash)
![Linux](https://skillicons.dev/icons?i=linux)
![Git](https://skillicons.dev/icons?i=git)

![Amazon RDS](https://img.shields.io/badge/Amazon_RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![Amazon Aurora](https://img.shields.io/badge/Amazon_Aurora-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Amazon_Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![AWS CloudFormation](https://img.shields.io/badge/AWS_CloudFormation-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white)
![Amazon SNS](https://img.shields.io/badge/Amazon_SNS-FF9900?style=for-the-badge&logo=amazonsns&logoColor=white)
![AWS KMS](https://img.shields.io/badge/AWS_KMS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

</div>

**Databases:** PostgreSQL · Amazon RDS · Amazon Aurora · Amazon Redshift · SQL · query tuning · indexing · replication · backup & recovery

**Cloud & DevOps:** AWS · AWS CloudFormation · CI/CD · Jenkins · Kubernetes · AWS Lambda · Bash · Python · SQL automation

---

## 💼 Featured Work

**RDS Observability Pipeline — Prudential Financial**
Built self-service automation to upgrade Aurora PostgreSQL from 15.x to 16.6, including global clusters, using CloudFormation, Lambda, and Jenkins. It runs pre-upgrade checks, validates the upgrade, and rolls back if needed. Cut manual DBA work by 40%. Designed and built an RDS observability pipeline: RDS event subscriptions send alerts to an SNS topic encrypted with a KMS key, deployed with CloudFormation and tested end to end in QA.

**Disaster Recovery & Security — Prudential Financial**
Built Redshift disaster recovery with Step Functions and Python — snapshot, check, restore to a DR cluster, and fail back to the primary when done. Failback removes the failover tag and pauses the DR cluster only if pausing was opted in, after a wait you choose. Brought recovery time from hours to under 30 minutes. Locked down write access to the Redshift audit-log S3 buckets with IAM and CloudFormation.

**ServiceNow Archival — Prudential Financial**
Helped design the ServiceNow-to-S3 archival solution for moving ticket data from ServiceNow to S3.

**Production Kubernetes Platform — Goldman Sachs**
Ran production-grade Kubernetes clusters at 99.9%+ uptime, built reusable Terraform and CloudFormation templates for Redshift, Aurora, and DocumentDB (cut environment setup time 60%), and migrated 10+ applications from Azure to AWS with zero unplanned downtime.

**Infrastructure as Code & Automation**
Set up IaC provisioning for RDS and IAM resources with CloudFormation, cutting time to deploy a new database environment by over 80%, from days to under 2 hours. Built least-privilege Level 1 support roles and documentation for Aurora PostgreSQL, and wrote runbooks and training for the support team. First-level escalations to the DBA team dropped by 60%.

---

## 🚀 Projects

| | |
|---|---|
| [![rds-observability-pipeline](https://github-readme-stats.vercel.app/api/pin/?username=danishsdata&repo=rds-observability-pipeline&theme=dark)](https://github.com/danishsdata/rds-observability-pipeline) | [![redshift-dr-automation](https://github-readme-stats.vercel.app/api/pin/?username=danishsdata&repo=redshift-dr-automation&theme=dark)](https://github.com/danishsdata/redshift-dr-automation) |
| [![aws-data-infrastructure](https://github-readme-stats.vercel.app/api/pin/?username=danishsdata&repo=aws-data-infrastructure&theme=dark)](https://github.com/danishsdata/aws-data-infrastructure) | [![sql-automation-toolkit](https://github-readme-stats.vercel.app/api/pin/?username=danishsdata&repo=sql-automation-toolkit&theme=dark)](https://github.com/danishsdata/sql-automation-toolkit) |
| [![kubernetes-platform-jenkins](https://github-readme-stats.vercel.app/api/pin/?username=danishsdata&repo=kubernetes-platform-jenkins&theme=dark)](https://github.com/danishsdata/kubernetes-platform-jenkins) | |

- [rds-observability-pipeline](https://github.com/danishsdata/rds-observability-pipeline) — RDS event subscriptions to a KMS-encrypted SNS topic, plus a scheduled Lambda health check for RDS/Aurora PostgreSQL.
- [redshift-dr-automation](https://github.com/danishsdata/redshift-dr-automation) — Step Functions disaster recovery: snapshot, verify, restore to a DR cluster, notify — plus failback to the primary.
- [aws-data-infrastructure](https://github.com/danishsdata/aws-data-infrastructure) — Parameterized CloudFormation templates for Aurora PostgreSQL, Redshift, and DocumentDB.
- [sql-automation-toolkit](https://github.com/danishsdata/sql-automation-toolkit) — Python/SQL DBA tools: slow queries, index usage, backup checks.
- [kubernetes-platform-jenkins](https://github.com/danishsdata/kubernetes-platform-jenkins) — Kubernetes manifests, Jenkins pipeline, and a runbook for the failures that come up most.

---

## 📊 GitHub Stats

<div align="center">

![Danish's GitHub stats](https://github-readme-stats.vercel.app/api?username=danishsdata&show_icons=true&theme=dark)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=danishsdata&layout=compact&theme=dark)

</div>

---

## 📜 Certifications

- Microsoft Certified: Azure Data Engineer Associate
- AWS Certified Solutions Architect – Associate (in progress)
- AWS re/Start Graduate — Per Scholas (Nov 2024)

## 🎓 Education

- **M.S. Computer Science — University of Colorado Boulder** (Feb 2026 – Present, pursuing; via Coursera)
- **Bachelor of Commerce (BCom), Banking & Finance — Sangai International University** (Mar 2017 – Mar 2020)
- **AWS re/Start Training — Per Scholas** (Aug 2024 – Nov 2024; 500-hour hands-on AWS training)
- **Certification, Azure Data Engineer — Microsoft** (Jan 2023 – Dec 2023)

---

## 🤝 Let's Connect!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danish1488)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:danishsdata@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/danishsdata)

</div>

## ⚡ Fun Fact

I've spent 10+ years keeping production databases and platforms running — and I still enjoy the moment a slow query finally explains itself.

![GitHub last commit](https://img.shields.io/github/last-commit/dev-chulbuji/resume.svg)

---

# RESUME

## Introduce
- Name: 김동진(dj.kim)
- Email: ladmusician.kim@gmail.com
- Github: https://github.com/dev-chulbuji

## Experience
- [카카오뱅크](https://www.kakaobank.com/) (19.04 - )
- [Flitto](https://www.flitto.com/) (18.11 - 19.02)
- [개인카페 창업 & 플리랜서](https://www.instagram.com/__zipdri/) (17.10 - 18.10)
- [Vingle](https://vingle.com) (17.06 - 17.10)
- [Goqual](https://www.goqual.com/) (15.02 - 17.04)
- ClasseStudio( 13.07 - 14.07)

## Skill Stack
- docker container
- kubernetes
- nodejs
- python
- bash
- yaml

## Activity
- Fastcampus Devops 강의 (CI/CD, Monitoring, AWS Security)
- [Kubernetes Scheduler - Open Infrastructure & Cloud Native Days Korea 2019 발표](https://drive.google.com/file/d/1bqkUrXOEUvNZxf0iXghlPZ5DSJhRZ85t/view?usp=sharing)
- [Kakaobank - Kubernetes 사내 발표](https://docs.google.com/presentation/d/1kOCsAngKGZpHvFVeS227cXsfFfPVlNWdtjaq5S1NDsg/edit#slide=id.g51229b7dc5_2_967)
- AWS KRUG - Kubernetes 보안 발표
- [Flitto - Terraform 도입 사내 발표](https://docs.google.com/presentation/d/1VZvGsXjXc2EcJL6P_j0jUiUqF55HLvLwGNzLG00DIOw/edit?usp=sharing)

## Project
>**Building & operation Kubernetes echo system suitable for financial environment | 카카오뱅크**
- Implement and operate a Kubernetes CI/CD platform
  - Continuous Integration with Gitlab & gitlab-runner
  - Continuous Deployment with ArgoCD(GitOps)
	- configManagementPlugin for external Helm chart registry
    - argo-rollout for advanced deployment capabilities
	- argocd-notifications for notifying CD events
	- dex for SSO & RBAC
- Operate AWS EKS(Elastic Kubernetes Service)
  - Managed by Hashicorp Terraform
  - IRSA(Iam Role Service Account) for setting AWS IAM Role to pod
  - Traefik for Kubernetes Ingress Controller
  - Taint, Affinity and labels for scheduling strategy
  - Admission Controller for controlling deployed docker image (security)
  - kube-bench(open source) with AWS Security Hub for checking vulnerability EKS nodes
- Kubernetes & workload monitoring
  - prometheus & grafana (metric)
  - fluentbit & elasticsearch & kibana (logging)
  - jaeger & elasticsearch & (kafka) (tracing)
- Built and deploy Kubernetes cluster that complies with financial sector compliance
  - Create provisioning script based on Ansible
  - Create operation/user guide

---

>**Establish public cloud for financial enviroment | 카카오뱅크**
- Create automation environment using Terraform(Atlantis), Ansible, Packer
  - terraform private provider registry for closed network env
  - AWS EC2 AMI pipeline
  - AWS lambda CI/CD pipeling
- Design multi account environment (AWS Organization, AWS SSO)
- Design and operate the AWS Network architecture
  - Design VPC, subnet CIDR
  - AWS TGW(Transit G/W) for central hub 
  - DX(Direct connect) for secure connection with on-premise
  - VPN for secure connection with on-premise
- Build governance for secure AWS Cloud use
  - operate MITM proxy for controlling connection with AWS console
  - forward proxy with LB for L4 firewall

---

>**Building & upgrading Docker echo system suitable for financial environment | 카카오뱅크**
- Actively manage, improve and monitor Docker container CI/CD platform
  - Improve deployment based on Ansible
  - Built and deploy BLUE/GREEN deployment feature
- Maintain Docker container registry
  - Harbor v2.0.0
  - Harbor custom prometheus exporter for robot account
- Control Docker cli for regulation
  - Improve Docker authz plugin(opensource :: hbm)
- Improve Docker container monitoring
  - prometheus & grafana (metric)
  - elasticsearch & kibana (logging)
  - consul (service discovery)
  
---

>**Improve in-house management system & manage kubernetes cluster | 플리토**
- Manage in-house management system
- Change framework
  - tsed framework -> nestjs framework
  - sequelize orm -> typeorm
  - unit test
- Improve e2e test environment
- Create automation environment
  - Automated AWS nacl(terraform, slack, jenkins)
- Diet Docker image
  - Alpine linux
  - multi-stage docker build

---

>**Manage & Update Android client application | 빙글**
- Involve application update TF (involve 33%)
- Improve CI/CD jenkinsfile for android application deployment
- Change android project design pattern
  - MVC -> MVP pattern
  - Presenter layer unit test(JUnit)

---

>**Remote control smart switch software | 고퀄**
- Develope Firmware BLE(bluetooth) communication feature(c++, cc2540)
- Switch control android client application development
- Switch control back-end server development
  - api server (nodejs, express, ec2, RDS, S3, ELB)
  - mqtt server (mosquito, ec2, rdis, ELB)

---

Thank you for reading so far. If you have any questions, please contact ladmusician.kim@gmail.com.
Thank you :)

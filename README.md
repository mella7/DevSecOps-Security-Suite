# DevSecOps Security Suite

This project was created by team MHAF as a part of our University project, where we're focusing on a secure DevSecOps deployment. 
#MHAF: M = Med Ali Mellah, H = Hyba Ayeshi, A = Ala Eddine Largat, F = Fyras Mabrouki

## Project Overview

The DevSecOps Security Suite focuses on embedding security into every phase of the software development lifecycle. This project utilizes Terraform to set up and manage infrastructure on AWS, integrates multiple security tools into a Jenkins CI/CD pipeline, and ensures compliance and security through automated checks and balances.

### Key Features

- **Infrastructure as Code (IaC) with Terraform:** Automated and consistent environment setups.
- **Code Quality and Security Analysis:** Using SonarQube.
- **Dependency Management and Security Scanning:** Comprehensive scanning with OWASP Dependency-Check.
- **Container Security Assessments:** Utilizing Trivy.
- **Dynamic Security Testing:** Real-time testing with OWASP ZAP.
- **Enhanced Security for Open-Source Dependencies:** Managed with Snyk.
- **Secrets Management:** Secure handling of sensitive data with HashiCorp Vault.
- **Detailed Reporting and Alerts:** For security vulnerabilities.

### Project Overview

**Objective:** To create a secure CI/CD pipeline that integrates static code analysis, dependency scanning, container security, and dynamic application security testing (DAST).

### Tools Used

- **Jenkins:** For CI/CD orchestration.
- **SonarQube:** For static code analysis.
- **OWASP Dependency-Check:** For dependency vulnerability scanning.
- **Trivy:** For container image scanning.
- **OWASP ZAP:** For dynamic application security testing (DAST).
- **Snyk:** For open-source dependency and container security.
- **HashiCorp Vault:** For secrets management.

### Steps to Create the Project

**1. Set Up Jenkins Pipeline**

- Install Jenkins and necessary plugins (Git, Pipeline, SonarQube, OWASP Dependency-Check, etc.).
- Create a new Jenkins pipeline job.

**2. Integrate Static Code Analysis with SonarQube**

- Set up SonarQube server and create a project.
- Configure Jenkins to use SonarQube for code quality analysis.
- Add a SonarQube scan stage to your Jenkinsfile.

### Additional Resources

- [Securing the CI/CD Pipeline on Microsoft Learn](https://docs.microsoft.com/en-us/learn/)
- [8 Tips for Securing Your CI/CD Pipeline with Snyk](https://snyk.io/blog/securing-your-cicd-pipeline/)
- [Building a Secure CI/CD Pipeline with GitHub Actions](https://github.com/actions)

This comprehensive project setup ensures multiple layers of security are integrated into the CI/CD pipeline, providing thorough scanning and testing at various stages of development and deployment.

## GuardianX

As the first step in our University project, we created [GuardianX](https://github.com/mella7/GuardianX). GuardianX is a comprehensive web URL vulnerability scanner designed to enhance cybersecurity measures by providing extensive URL analysis. It integrates with VirusTotal to scan URLs for vulnerabilities and potential threats, ensuring a safer browsing experience for users. GuardianX serves as the foundation for the broader DevSecOps Security Suite project, where it will be deployed as part of a secure, integrated system.


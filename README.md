# Change Firewall Rules Using Terraform and Cloud Shell

## Objective

The **Change Firewall Rules Using Terraform and Cloud Shell** lab focused on automating cloud infrastructure deployment using **Infrastructure as Code (IaC)** with Terraform. The primary objective was to clone a Terraform repository, provision a Virtual Private Cloud (VPC) network and firewall rules, and verify the deployed resources within Google Cloud. This hands-on exercise strengthened my understanding of infrastructure automation, firewall management, and cloud resource provisioning.

### Skills Learned

- Understanding of Infrastructure as Code (IaC) concepts.
- Experience using Terraform to provision cloud infrastructure.
- Knowledge of automated firewall rule deployment.
- Proficiency with Google Cloud Shell and Terraform CLI.
- Ability to deploy and verify VPC networks using reusable configuration files.
- Understanding of version-controlled cloud infrastructure management.

### Tools Used

- Google Cloud Platform (GCP)
- Google Cloud Shell
- Terraform
- Google Cloud CLI
- Virtual Private Cloud (VPC)
- Google Cloud Firewall
- GitHub Repository

## Steps

### Step 1: Clone the Terraform Repository

Activated Google Cloud Shell and cloned the Terraform example repository containing predefined infrastructure configuration files. Reviewed the project structure and inspected the `main.tf` configuration file to understand the resources that would be deployed.

---

### Step 2: Analyze the Terraform Configuration

Examined the Terraform configuration to identify the VPC network and firewall resources defined in the script. Verified that the firewall configuration would allow **ICMP** traffic along with **TCP ports 80, 8080, and 1000–2000**, demonstrating how infrastructure can be managed through code.

---

### Step 3: Initialize the Terraform Environment

Configured the Google Cloud project and initialized the Terraform working directory using `terraform init`. This downloaded the required provider plugins and prepared the environment for infrastructure deployment.

---

### Step 4: Deploy Cloud Infrastructure

Executed `terraform apply` to automatically provision the VPC network and firewall rules. Terraform created the required cloud resources based on the configuration file while ensuring a consistent and repeatable deployment process.

---

### Step 5: Verify the Deployment

Navigated to the Google Cloud Console to verify that the new VPC network and firewall rules had been successfully created. Confirmed that the deployed firewall configuration matched the rules defined within the Terraform configuration file.

---

### Step 6: Complete the Lab

Successfully automated the deployment of networking infrastructure using Terraform, verified the deployed resources, and completed all required lab objectives.

## Lab Completion

**Ref 1: Google Cloud Skills Boost Lab Completion**

![Lab Completion](images/lab-completion.png)

*Assessment Score: **100%** — Successfully deployed and verified Google Cloud networking infrastructure using Terraform and Cloud Shell.*

## Key Takeaway

This lab provided practical experience with **Infrastructure as Code (IaC)** by using Terraform to automate the deployment of Google Cloud networking resources. Automating firewall and VPC configurations improves consistency, reduces manual configuration errors, and enables scalable, repeatable cloud infrastructure management—an essential skill for Cloud Security Engineers, DevSecOps professionals, and Cloud Infrastructure Engineers.
```

Dominique Cargle 
Trotwood Ohio 
Email: domcargle@gmail.com  
Phone: 937-825-1811  
LinkedIn: https://www.linkedin.com/in/dominique-cargle-118527229/
GitHub: https://github.com/Dcargle1020  

---

## SUMMARY

Entry-Level DevOps Engineer with a strong foundation in cloud technologies, automation, and Linux-based system reliability. Transitioning from a healthcare background into tech, bringing excellent communication, problem-solving, and adaptability skills. Hands-on experience with AWS fundamentals, scripting, CI/CD workflows, and deploying infrastructure using modern DevOps tools. Actively building real-world cloud projects and pursuing AWS certifications to accelerate growth in cloud engineering. Motivated self-learner with a collaborative mindset and a commitment to contributing to high-performing engineering teams.

---

## SKILLS

- **Languages:** Bash, PowerShell, Python (boto3 primarily)  
- **DevOps & Cloud:** AWS (EC2, S3, IAM, Lambda, CloudFormation, CloudWatch), GitHub Actions, Terraform (IaC), Docker (basic), AWS CLI, EventBridge  
- **CI/CD & Automation:** GitHub Actions, Git, GitHub, CodePipeline (familiar), YAML  
- **Monitoring & Logging:** AWS CloudWatch, EC2 Logs  

---

## PROJECTS

### Prompt Deployment Pipeline | Amazon Bedrock + S3 + GitHub Actions  
*Use Case: Automate AI-powered content creation and publishing for static sites.*

- Created a GitHub-based CI/CD workflow to process prompt templates and config files  
- Built a Python script (`process_prompt.py`) that:  
  - Loads and renders prompt templates using variables from config files  
  - Sends structured prompts to Amazon Bedrock for content generation  
  - Saves outputs as `.html` or `.md` files and uploads to S3 for static website hosting  
- Used environment-specific prefixes (`beta/`, `prod/`) to separate test and live content  
- Managed workflow triggers using PRs and merges, with secrets securely handled in GitHub Actions  

### Multilingual Audio Pipeline | Amazon Transcribe + Translate + Polly + S3 + GitHub Actions  
*Use Case: Automate voice-to-voice translation for .mp3 content.*

- Developed a Python script (`process_audio.py`) to:  
  - Upload input .mp3 files to S3  
  - Transcribe English audio using Amazon Transcribe  
  - Translate text into other languages with Amazon Translate  
  - Generate multilingual speech using Amazon Polly  
  - Save outputs to structured S3 paths for `transcripts/`, `translations/`, and `audio_outputs/`  
- Automated processing via GitHub Actions workflows for both PR (beta) and main (prod) branches  
- Used GitHub Secrets to securely manage AWS credentials and environment variables  

### Two-Tier Web Architecture on AWS | EC2 + RDS + VPC  
*Use Case: Deploy a secure and scalable content management website.*

- Launched a custom VPC with public and private subnets, configured routing tables and Internet Gateway  
- Deployed CMS on an Ubuntu EC2 instance (web tier), with MySQL database hosted on Amazon RDS (database tier)  
- Hardened networking using security groups and subnet isolation (EC2 in public, RDS in private)  
- Verified application connectivity and documented the benefits of two-tier architecture  

### EC2 Shutdown Automation | AWS Lambda + GitHub Actions + CloudFormation  
*Use Case: Reduce unnecessary EC2 runtime costs for non-production environments.*

- Built a Python Lambda function using `boto3` to identify and stop EC2 instances based on state and tags  
- Scheduled shutdowns via Amazon EventBridge  
- Created an S3-hosted deployment package and used CloudFormation templates to deploy the Lambda with IAM roles  
- Automated deployment using separate GitHub Actions workflows for beta and prod environments  
- Managed environment-specific parameters and AWS credentials using GitHub Secrets  

---

## EXPERIENCE

### 
** Dsnp Case manager 
**Untied healthcare ** — Trotwood Ohio  
*06/2022 - 09/2025*

- - Communicated with cross-functional teams and documented complex cases with high accuracy, supporting consistent workflows.
- Resolved high-priority issues under pressure by analyzing root causes and collaborating with internal and external stakeholders.
- Improved documentation and internal processes, reducing errors and enhancing efficiency through system-based solutions.

---

## EDUCATION

**High School Diploma**  
Meadowdale Highschool, Dayton, Ohio — 2009

---

## CERTIFICATIONS

- AWS Certified Cloud Practitioner – *In Progress or Completed*  
- AWS Certified Developer – Associate – *In Progress*  
- Certified AI Practitioner (CAIP) – *In Progress*  
- HashiCorp Certified: Terraform Associate – *Planned*  


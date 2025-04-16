# DevOps Git Project

This is a version-controlled DevOps practice project showcasing Git fundamentals like branching, pull requests, tagging, and collaboration using GitHub.

## 📌 Project Modules

- `terraform-docker/`: A Terraform module to provision a Docker container locally.
- `docs/`: Markdown notes explaining Git workflows and key commands used.

## 🛠 Tools Used

- Git
- GitHub
- Terraform
- Docker

## 🔀 Git Workflow Followed

1. **Branches Created**
   - `main`: Stable production branch
   - `dev`: Development branch
   - `feature/terraform-docker`: For the Terraform + Docker task

2. **Pull Requests**
   - Feature branches merged into `dev` via PRs
   - `dev` merged into `main` after approval

3. **Tags**
   - Tagged `v1.0` after completing Docker provisioning task

## 📁 .gitignore

Files and folders ignored from version control, like:

```
*.log
*.tfstate
.terraform/
.env
```

### ✅ How to Run Terraform Project (if applicable)

```bash
cd terraform-docker
terraform init
terraform apply
```

---



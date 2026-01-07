# ExamPrepEmpire Infrastructure

This repository manages the infrastructure and deployment automation
for ExamPrepEmpire digital products.

## Purpose
- Store infrastructure-as-code (Terraform)
- Manage ebook and exam assets
- Enable automated deployment via Jenkins
- Upload and distribute content through AWS S3 and CloudFront

## Structure
- `terraform/` – AWS infrastructure definitions
- `ebooks/` – Source ebook and exam files before upload

## Workflow (Planned)
1. Add or update ebook content
2. Commit and push to GitHub
3. Jenkins triggers automatically
4. Terraform uploads content to AWS S3
5. CloudFront serves content globally

This repository is part of the ExamPrepEmpire DevOps pipeline.

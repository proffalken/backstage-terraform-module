# Backstage Terraform Module Template

This Backstage template scaffolds a new Terraform module repository with a standard structure.

## Overview

Use this template to create a new Terraform module under your GitHub account. It will:

- Create a new GitHub repository with a standard Terraform module layout
- Pre-populate `main.tf`, `variables.tf`, and `outputs.tf`
- Set up a `README.md` and documentation scaffold
- Register the module in the Backstage catalog automatically

## Usage

1. Navigate to **Create** in the Backstage sidebar
2. Select **Terraform Module**
3. Fill in the module name, provider, and description
4. Choose a repository location
5. Click **Create**

## Module Structure

```
.
├── main.tf         # Main Terraform configuration
├── variables.tf    # Input variable definitions
├── outputs.tf      # Output value definitions
├── README.md       # Module documentation
└── docs/           # TechDocs source
```

## Supported Providers

- AWS
- Azure
- Google Cloud
- Kubernetes

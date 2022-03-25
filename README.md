# Backstage Terraform Module

This repository provides a template for new Terraform Modules.

## Usage

Update your `app-config.yaml` and add the following to your catalog locations:

```yaml
    - type: url
      target: https://github.com/proffalken/backstage-terraform-module/blob/main/template.yaml
      rules:
        - allow: [Template]

```

The Template should then appear in your options to create a new entity

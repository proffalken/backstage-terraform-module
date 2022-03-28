# Backstage Terraform Module

This repository provides a template for new Terraform Modules, including CI/CD workflows for Github.

## Installation

Update your `app-config.yaml` and add the following to your catalog locations:

```yaml
    - type: url
      target: https://github.com/proffalken/backstage-terraform-module/blob/main/template.yaml
      rules:
        - allow: [Template]

```

The Template should then appear in your options to create a new entity

## Usage

In your Backstage installation, create a new entity and fill in the prompts.

Once the installer has completed, you will see a new git repo listed in your catalog with all the files from the `templates` dir automatically added and content generated where appropriate.

## CI/CD for generated code

This module uses the Hashicorp `setup-terraform` module and will *automatically* deploy on merge to `main`.

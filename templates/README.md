# ${{ values.name }}

${{ values.description }}

## Documentation

Documentation for this module is managed via [mkdocs](https://www.mkdocs.org) so it can be read by Backstage.

In order to add new documentation, simply update the files in the `docs/docs/` directory and push your changes - Backstage will build them on the fly.

## CI/CD

This module uses the Hashicorp `setup-terraform` github actions module and will *automatically* deploy on merge to `main`.

If you want to link it into Terraform Cloud or Terraform Enterprise, this is easy to do.  Simply edit `.github/workflows/terraform.yml` and add [the approprate
configuration](https://github.com/hashicorp/setup-terraform#usage).

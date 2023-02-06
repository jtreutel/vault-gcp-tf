# vault-gcp-tf
Deploys Vault to a GCP instance.  Copied from the [terraform-google-modules](https://github.com/terraform-google-modules/terraform-google-vault/blob/v6.2.0/examples/vault-on-gce/main.tf) repo.  Good for deploying a throwaway Vault instance for quick testing.

## How to Use

1. Auth with gcloud
2. Copy `terraform.tfvars.example` to `terraform.tfvars` and fill out the values
3. Run `terraform apply`
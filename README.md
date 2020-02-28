# Terraform API Helper Script

This repo contains a shell script that facilitates pushing Terraform plans to a previously created workspace. It can be used as an example/introduction to the TFE API.

## Usage

```
export TOKEN=token_generated_from_tfe
./terraform-enterprise-push.sh ./target-plan-folder org/workspace
```

The token can be of type user, group, or organization (see [here](https://www.terraform.io/docs/cloud/api/index.html#authentication)).

Full write up can be found on the [Terraform API Docs](https://www.terraform.io/docs/cloud/run/api.html)

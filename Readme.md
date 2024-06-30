# About
Example showing how to connect from a GitHub Workflow to Azure with OpenId Connect (OIDC) using a managed identity. 


# Prerequisites

- A Created Azure Container registry without an user-assigned identity (this is done in the Demo)
- Provided Secrets

# Demo
## Introduction

The repository contains a gitHub workflow which is triggered by pushes to the main branch or manually in the UI and a simple Dockerfile which uses a simple bash script. 

## Without OIDC
Go to 




# Resources
- [GitHub Permission Setting with OpenId Connect](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-azure#adding-permissions-settings)
- [Configure a user-assigned managed identity to trust an external identity provider](https://learn.microsoft.com/en-us/entra/workload-id/workload-identity-federation-create-trust-user-assigned-managed-identity?pivots=identity-wif-mi-methods-azp)
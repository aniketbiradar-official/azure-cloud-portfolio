# Backend applications on Azure

> Connect backend design decisions to Azure-managed services.

[← Back to the learning resource index](./README.md)

## Overview

For developers familiar with Django and REST APIs, this guide introduces hosting choices and secure service-to-service identity without asserting that any existing application is deployed on Azure.

## Recommended official resources

### [Azure App Service overview](https://learn.microsoft.com/en-us/azure/app-service/overview?wt.mc_id=studentamb_688610)

**Best for:** Backend developers. Understand managed web hosting and how it differs from hosting on a virtual machine.

### [Managed identities in Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/overview-managed-identity?wt.mc_id=studentamb_688610)

**Best for:** Application developers. Learn the secret-reduction benefits and limitations of managed identities.

### [Azure Functions documentation](https://learn.microsoft.com/en-us/azure/azure-functions?wt.mc_id=studentamb_688610)

**Best for:** Backend and cloud learners. Explore event-driven compute as an alternative to a continuously running web backend.

## Recommended learning sequence

1. Describe the runtime and data requirements of a Django REST API.
2. Compare managed web hosting with event-driven functions for relevant workloads.
3. Review managed identity and least-privilege resource access.
4. Consider logging, operational cost, and secrets management before choosing a host.

## Practical learning

Write a deployment decision record for a hypothetical Django service: target hosting option, authentication boundary, database handling, secrets strategy, and monitoring plan. A design document is not evidence of an actual deployment.

---

*Curated for Azure learning · Microsoft Learn is the official source · Reviewed 18 November 2026. The `wt.mc_id` parameter indicates a contributor referral; it does not guarantee program attribution.*

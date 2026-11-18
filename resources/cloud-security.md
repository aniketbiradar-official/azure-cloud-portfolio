# Cloud security

> Identity, authorization, and separation of responsibility.

[← Back to the learning resource index](./README.md)

## Overview

These resources explain security foundations for administrators and developers. Microsoft Entra directory roles and Azure resource RBAC are related but distinct authorization models.

## Recommended official resources

### [Azure identity management security overview](https://learn.microsoft.com/en-us/azure/security/fundamentals/identity-management-overview?wt.mc_id=studentamb_688610)

**Best for:** Security beginners. Orient yourself to identity controls for Azure services and applications.

### [Microsoft Entra role-based access control](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/?wt.mc_id=studentamb_688610)

**Best for:** Identity administrators. Study role management for Microsoft Entra resources.

### [Azure roles vs. Microsoft Entra roles](https://learn.microsoft.com/en-us/azure/role-based-access-control/rbac-and-directory-admin-roles?wt.mc_id=studentamb_688610)

**Best for:** AZ-104 learners. Clarify the boundary between directory roles and Azure resource-management roles.

## Recommended learning sequence

1. Start with core identity concepts and the principle of least privilege.
2. Contrast Microsoft Entra roles with Azure resource roles.
3. For a sample web app, separate human administrator permissions from application identities.
4. List security controls you would verify before a real deployment.

## Practical learning

Write an access-control matrix for Student, Teacher, and Admin roles in a hypothetical service, then separately identify what Azure RBAC would control in its hosting environment. App-level RBAC and Azure RBAC are not interchangeable.

---

*Curated for Azure learning · Microsoft Learn is the official source · Reviewed 18 November 2026. The `wt.mc_id` parameter indicates a contributor referral; it does not guarantee program attribution.*

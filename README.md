# HR-Driven IAM Lifecycle Automation Lab

This project is a hands-on Identity and Access Management lab focused on HR-driven Joiner, Mover and Leaver lifecycle automation.

The lab uses Microsoft Entra ID as the central identity platform and is designed to demonstrate user lifecycle management, group-based access control, Microsoft Graph API automation, SAML Single Sign-On and SCIM provisioning to AWS IAM Identity Center.

## Project Status

Current phase: Phase 1 – Project foundation

Completed so far:

- Local project workspace created
- GitHub repository created
- Repository structure created
- Git initialized locally
- Git configured with GitHub noreply email
- Branch renamed to main
- Remote origin connected
- First push to GitHub completed
- Initial .gitignore created
- Placeholder folders created for documentation, diagrams, source code, sample data and logs

Not implemented yet:

- Microsoft Entra ID tenant setup
- App Registration
- Microsoft Graph API authentication
- Joiner/Mover/Leaver automation
- SAML SSO to AWS IAM Identity Center
- SCIM provisioning
- Functional IAM test cases

## Planned Architecture

```text
HR.csv
  ↓
PowerShell JML Engine
  ↓
Microsoft Graph REST API
  ↓
Microsoft Entra ID
  ↓
Enterprise Application: AWS IAM Identity Center
  ↓
SAML SSO + SCIM Provisioning
  ↓
AWS IAM Identity Center
  ↓
Permission Sets / AWS Access Portal


iam-lifecycle-entra-aws/
├── .gitignore
├── docs/
├── diagrams/
├── src/
├── sample-data/
│   └── hr-sample.csv
├── logs/
│   └── sanitized-example-run.log
└── README.md
# Bitbucket (bitbucket)
Bitbucket is a Git-based source code repository hosting service owned by Atlassian offering both commercial plans and free accounts with unlimited private repositories, along with CI/CD pipelines, code reviews via pull requests, and code collaboration tools for development teams.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bitbucket/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Atlassian, CI/CD, Code Collaboration, Code Review, DevOps, Git, Pull Requests, Repository Hosting, Version Control

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Bitbucket Cloud REST API
The REST API for Bitbucket Cloud allows you to build apps using any language, exposing operations on repositories, pull requests, commits, pipelines, workspaces, projects, webhooks, issues, and users.

**Human URL:** [https://developer.atlassian.com/bitbucket/api/2/reference/](https://developer.atlassian.com/bitbucket/api/2/reference/)

#### Tags:

 - Commits, Pipelines, Pull Requests, Repositories, REST, Webhooks, Workspaces

#### Properties

- [Documentation](https://developer.atlassian.com/bitbucket/api/2/reference/)
- [Authentication](https://developer.atlassian.com/cloud/bitbucket/rest/intro/#authentication)
- [OpenAPI](openapi/bitbucket-cloud-rest-api-openapi.json)
- [JSONSchema](json-schema/bitbucket-cloud-rest-api-repository-schema.json)
- [JSONSchema](json-schema/bitbucket-cloud-rest-api-pullrequest-schema.json)
- [JSONSchema](json-schema/bitbucket-cloud-rest-api-pipeline-schema.json)
- [JSONSchema](json-schema/bitbucket-cloud-rest-api-commit-schema.json)
- [JSONStructure](json-structure/bitbucket-cloud-rest-api-repository-structure.json)
- [JSONStructure](json-structure/bitbucket-cloud-rest-api-pullrequest-structure.json)
- [JSONStructure](json-structure/bitbucket-cloud-rest-api-pipeline-structure.json)
- [JSONStructure](json-structure/bitbucket-cloud-rest-api-commit-structure.json)
- [Example](examples/bitbucket-cloud-rest-api-repository-example.json)
- [Example](examples/bitbucket-cloud-rest-api-pullrequest-example.json)
- [Example](examples/bitbucket-cloud-rest-api-pipeline-example.json)
- [Example](examples/bitbucket-cloud-rest-api-commit-example.json)

## Common Properties

- [Portal](https://developer.atlassian.com/)
- [StatusPage](https://status.atlassian.com/)
- [TermsOfService](https://www.atlassian.com/legal/cloud-terms-of-service)
- [PrivacyPolicy](https://www.atlassian.com/legal/privacy-policy)
- [SignUp](https://bitbucket.org/account/signup/)
- [Blog](https://bitbucket.org/blog/)
- [GitHubOrganization](https://github.com/atlassian)
- [Support](https://support.atlassian.com/bitbucket-cloud/)

## Features

| Name | Description |
|------|-------------|
| Git Repository Hosting | Host unlimited private and public Git repositories with fine-grained access controls. |
| Pull Requests | Code review workflows with inline comments, approvals, and merge checks. |
| Bitbucket Pipelines | Integrated CI/CD service for building, testing, and deploying code. |
| Branch Permissions | Enforce branch restrictions and merge requirements. |
| Webhooks | Receive real-time notifications about repository events. |
| Issue Tracking | Built-in issue tracker for managing bugs and feature requests. |
| Deployment Environments | Track deployments across multiple environments. |
| Code Search | Search across repositories, code, and pull requests. |
| Snippets | Share code snippets with version history. |

## Use Cases

| Name | Description |
|------|-------------|
| Code Review Workflows | Enforce code quality through structured pull request reviews with required approvals. |
| CI/CD Automation | Automate build, test, and deployment pipelines triggered by code changes. |
| Team Collaboration | Enable distributed development teams to collaborate on code with workspaces and projects. |
| Release Management | Manage releases with deployment tracking and environment promotion. |
| Security Scanning | Integrate security scanning into CI/CD pipelines for vulnerability detection. |

## Integrations

| Name | Description |
|------|-------------|
| Jira Software | Deep integration with Jira for issue tracking and project management. |
| Trello | Connect Bitbucket with Trello for visual project management. |
| Slack | Receive Bitbucket notifications in Slack channels. |
| Confluence | Link documentation in Confluence with code in Bitbucket. |
| AWS | Deploy to AWS services using Bitbucket Pipelines. |
| Azure | Deploy to Azure services using Bitbucket Pipelines. |
| Google Cloud | Deploy to Google Cloud using Bitbucket Pipelines. |
| Docker | Build and push Docker images using Bitbucket Pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Bitbucket Cloud REST API](openapi/bitbucket-cloud-rest-api-openapi.json)

### JSON Schema

- [Repository](json-schema/bitbucket-cloud-rest-api-repository-schema.json)
- [Pullrequest](json-schema/bitbucket-cloud-rest-api-pullrequest-schema.json)
- [Pipeline](json-schema/bitbucket-cloud-rest-api-pipeline-schema.json)
- [Commit](json-schema/bitbucket-cloud-rest-api-commit-schema.json)

### JSON Structure

- [Repository](json-structure/bitbucket-cloud-rest-api-repository-structure.json)
- [Pullrequest](json-structure/bitbucket-cloud-rest-api-pullrequest-structure.json)
- [Pipeline](json-structure/bitbucket-cloud-rest-api-pipeline-structure.json)
- [Commit](json-structure/bitbucket-cloud-rest-api-commit-structure.json)

### JSON-LD

- [Bitbucket Cloud REST API Context](json-ld/bitbucket-cloud-rest-api-context.jsonld)

### Examples

- [Repository](examples/bitbucket-cloud-rest-api-repository-example.json)
- [Pullrequest](examples/bitbucket-cloud-rest-api-pullrequest-example.json)
- [Pipeline](examples/bitbucket-cloud-rest-api-pipeline-example.json)
- [Commit](examples/bitbucket-cloud-rest-api-commit-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Bitbucket Cloud REST API](capabilities/shared/cloud-rest-api.yaml) — 13 operations for repository, pull request, and pipeline management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Code Collaboration](capabilities/code-collaboration.yaml) | Bitbucket Cloud REST API | 13 | Developer, DevOps Engineer |

## Vocabulary

- [Bitbucket Vocabulary](vocabulary/bitbucket-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 11 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Bitbucket Spectral Rules](rules/bitbucket-spectral-rules.yml) — 19 rules across 7 categories enforcing Bitbucket API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

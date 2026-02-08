# Jira Service Management Checklist Templates

This repository contains reusable checklist templates for common **Jira Service Management** request types, such as employee onboarding, offboarding, access removal, and compliance-related processes.

The templates are designed to help teams standardize their service desk work and reduce the risk of missed steps, especially in high-pressure or audit-sensitive scenarios.

---

## What problem do these templates solve?

In Jira Service Management, many teams rely on:
- free-text descriptions
- SOPs stored in Confluence
- tribal knowledge

As a result:
- critical steps are skipped
- processes are applied inconsistently
- audit evidence is incomplete or missing

Checklists help break complex processes into explicit, repeatable steps that agents can follow ticket by ticket.

---

## How to use these checklists in Jira (without add-ons)

These templates can be used **without any Jira apps**, for example by:

1. Creating a **multi-line custom field** (e.g. “Checklist”)
2. Copying one of the templates from this repository
3. Setting it as a **default value** for a request type
4. Asking agents to manually check off items as they work

This approach works for simple setups and small teams.

---

## Limitations of manual checklist approaches

While custom fields and templates can help, manual approaches have important limitations:

- Checklist completion cannot be enforced
- No visibility into progress or skipped steps
- No audit trail of who completed which task
- Easy to forget or partially apply under pressure
- Difficult to scale across many request types

For teams operating under compliance requirements (ISO 27001, SOC 2, ITIL) or with higher ticket volume, these limitations often become critical.

---


## When a dedicated checklist app makes sense

For teams that need **enforced processes, visibility, and audit readiness**, dedicated checklist apps exist.

**Service Desk Checklists** is a Jira Service Management app that enforces consistent, auditable processes using mandatory checklists. It allows teams to:

- Define checklists per request type
- Enforce task completion before ticket resolution
- Track progress directly on the ticket
- Maintain a full audit trail for compliance purposes

- Atlassian Marketplace listing: https://marketplace.atlassian.com/apps/1219608/service-desk-checklists  
- Product documentation: https://js-factory.io/service-desk-checklists/

This repository focuses on **templates and concepts**. The app focuses on **execution, enforcement, and scale**.

---

## Available templates

The repository includes checklist templates for common service desk scenarios, such as:

- Employee onboarding
- Employee offboarding
- IT access removal
- Laptop provisioning
- Account deactivation
- Security incident response
- ISO / SOC 2 evidence requests

Each template is provided as plain text or Markdown for easy reuse.

---

## Who maintains this repository?

This repository is maintained by **JS Factory**, the team behind *Service Desk Checklists*, an Atlassian Marketplace app for Jira Service Management.

The goal is to share practical process templates and document common patterns teams use when running service desks in Jira.

---

## License

All templates in this repository are provided under an open license and can be freely reused and adapted.

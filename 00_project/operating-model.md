# Operating Model

## Purpose

Define where project knowledge, delivery activity and exploratory solution development are managed.

## Tool responsibilities

| Tool | Role | Authority |
|---|---|---|
| Confluence | Project context, agreed scope, decisions, stakeholder outcomes and endorsed artefacts | Project source of truth |
| Jira | Delivery activity, ownership, sequencing, blockers and progress | Delivery-management system |
| Bitbucket | Private hypotheses, experiments, prototypes, patterns and technical exploration | Working environment |
| Other organisational systems | Original records, controlled material and operational data | Relevant organisational system of record |

## Core rule

> Confluence records what the project has agreed. Bitbucket explores what the project could become.

## Promotion rule

Material moves conceptually through:

**Hypothesis → Experiment → Evidence → Working-group decision → Agreed project direction**

A Bitbucket artefact does not become an organisational standard simply because it has been implemented technically.

## Bitbucket status labels

Use these labels in working documents where useful:

- Hypothesis
- Exploring
- Prototype
- Testing
- Evidence recorded
- Candidate
- Rejected
- Superseded

Avoid using `Approved` or `Endorsed` unless the corresponding decision exists in Confluence.

## Confluence relationship

Bitbucket may contain links to relevant Confluence pages.

Do not maintain independent copies of stakeholder-approved project documentation unless a future publishing experiment explicitly tests that model.

## Jira relationship

Jira should track work required to progress experiments.

Do not use repository issues, commits or pull requests as the primary project delivery-management system while Jira is the agreed delivery layer.
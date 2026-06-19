# Workflow Diagrams

These diagrams explain the public Black2Africa workflow without exposing source
code, credentials, private queues, internal prompts, deployment systems, or
protected owner records.

## Workflow Overview

Source: `assets/diagrams/workflow-overview.mmd`

Rendered asset:

![Workflow overview](../assets/diagrams/workflow-overview.svg)

```mermaid
flowchart LR
  visitor["Visitor or partner"] --> public["Public project surface"]
  github["GitHub public repo"] --> public
  wordpress["FaithCheltenham.com WordPress page"] --> public
  public --> intake["Reviewed intake"]
  intake --> review["Human/admin review point"]
  review --> directory["Public-safe opportunity or profile output"]
  review --> private["Private owner workspace"]
  private --> packet["Preparation packet"]
  packet --> handoff["Owner-controlled portal or professional handoff"]
  handoff --> receipt["Receipt archive"]
```

## Public / Private Boundary

Source: `assets/diagrams/public-private-boundary.mmd`

Rendered asset:

![Public private boundary](../assets/diagrams/public-private-boundary.svg)

```mermaid
flowchart TB
  subgraph public["Public-safe surface"]
    readme["README and docs"]
    page["FaithCheltenham.com draft"]
    visuals["Public brand visuals"]
    policy["Ownership and commercial-use policy"]
  end

  subgraph guarded["Guarded review layer"]
    intake["Intake review"]
    approval["Owner approval"]
    claims["Claim and privacy review"]
  end

  subgraph private["Private engine"]
    source["Source code"]
    prompts["Private prompts and agent instructions"]
    secrets["Credentials and account settings"]
    records["Customer, legal, admin, family, and owner records"]
    deploy["Deployment and production config"]
  end

  public --> guarded
  guarded --> private
  private -. excluded from repo .-> public
```

## Safety Notes

- The diagrams describe workflow categories, not implementation architecture.
- The public workflow explicitly connects the GitHub public repo and
  FaithCheltenham.com WordPress draft to the same public project surface.
- They intentionally omit server paths, API routes, schemas, credentials, and
  production adapters.
- They are suitable for README, GitHub social review, and a public WordPress
  project page.

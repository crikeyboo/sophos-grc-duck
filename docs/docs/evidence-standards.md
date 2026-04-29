# Evidence Standards

This document defines what evidence may be used to support Sophos product, service and capability mappings to cybersecurity frameworks.

## Purpose

The purpose of evidence standards is to ensure that all mappings are traceable, reviewable and defensible.

Duck must not rely on unsupported assumptions, generic product claims or sales language when producing framework mappings.

## Evidence Quality Levels

## Level 5: Authoritative Technical Evidence

Use this where the mapping is supported by technical, implementation-level evidence.

Examples include:

- Product documentation
- Configuration guides
- API documentation
- Detection logic
- Supported integration lists
- Architecture diagrams
- Admin guides
- Service runbooks
- Product owner confirmation

## Level 4: Strong Product Evidence

Use this where the mapping is supported by published or internally approved product material, but where the control outcome depends on deployment, configuration, integration or operation.

Examples include:

- Product feature descriptions
- Release notes
- Technical white papers
- Service descriptions
- Approved support knowledge base articles
- Approved enablement material

## Level 3: Reasonable Inference

Use this where a capability appears relevant to a control outcome, but the evidence does not fully prove the mapping.

Mappings at this level must be marked for review before publication.

## Level 2: Weak or Indirect Evidence

Use this where the source only indirectly supports the mapping.

Examples include:

- High-level marketing pages
- Sales slides
- Unverified enablement notes
- Non-specific claims
- Outdated product material

Mappings at this level must not be used externally without review and stronger evidence.

## Level 1: Speculative

Use this where the mapping is based mainly on assumption.

Speculative mappings must not be published. They may only be used as research leads.

## Level 0: No Evidence

Use this where no reliable evidence has been found.

The correct output is either Not Covered or Evidence Required.

## Approved Evidence Source Types

- Public product documentation
- Internal product documentation
- Git repository
- Detection rule, query or content pack
- API specification
- Configuration guide
- Architecture diagram
- Service runbook
- Support knowledge base article
- Product owner confirmation
- GRC reviewer confirmation
- Customer implementation evidence, where authorised and anonymised

## Weak Evidence Source Types

These may be useful as discovery leads but must not be treated as authoritative evidence without review:

- Sales claims
- Marketing headlines
- Unverified slides
- Anecdotal knowledge
- Old enablement material
- Unsourced internal notes
- AI-generated summaries without citations

## Required Evidence Fields

Every mapping should include:

- Evidence title
- Evidence source type
- Evidence URL or repository path
- Publication or last updated date, where available
- Product or service version, where relevant
- Extracted evidence statement
- Reviewer name or role
- Review date
- Confidence score

## Evidence Handling Rules

Duck must:

- Cite every product capability claim.
- Prefer technical evidence over marketing material.
- Flag stale or undated evidence.
- Separate evidence of product capability from evidence of customer implementation.
- Separate Sophos managed service activity from customer-owned process activity.
- Mark unsupported claims as Evidence Required.
- Avoid converting sales language into compliance claims.

## Prohibited Evidence Behaviour

Duck must not:

- Treat marketing claims as control satisfaction.
- Invent product capabilities.
- Assume a feature is enabled by default unless evidenced.
- Assume customer configuration is correct.
- Assume a managed service is in scope unless evidenced.
- State or imply that evidence of tool capability equals evidence of customer compliance.

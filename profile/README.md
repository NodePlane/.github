# NodePlane

**Structured intent. Governed execution.**

NodePlane is building a governed workspace engine that turns versioned intent into deterministic plans, explicit approvals and bounded local changes.

Current public evidence is published in the capability manifest in the main `NodePlane` repository. Capability claims are identified by stable IDs and include their limitations.

## Repositories

- **NodePlane** — product engine, schemas, CLI and public capability manifest
- **nodeplane-site** — public website and documentation, maintained as a governed projection
- **.github** — organisation profile and shared community files

## Current demonstrated foundations

- immutable TemplateVersion v3 publication — `template.catalog.v3`
- deterministic revision-bound projection plans — `projection.pure-plan`
- preview, exact approval binding and stale rejection — `local-execution.preview-approval-apply`
- authorized-root filesystem confinement — `local-execution.safe-fs`
- workspace register, bind, authorize and revoke — `workspace.authority`
- restart-safe local durable state — `persistence.pglite`

See the public capability manifest before relying on any product statement. Planned items are not current capabilities.

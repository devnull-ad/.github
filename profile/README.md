# Dev Null SLU

Andorran owner-operator IT ([devnull.ad](https://devnull.ad)). Contact: [info@devnull.ad](mailto:info@devnull.ad) · GitHub notices: [github@devnull.ad](mailto:github@devnull.ad).

## Repository policy

**Private is the default.** This org holds company intellectual property. New repositories should be created **private** unless there is an explicit reason to publish.

### Private (typical)
Product code, Workers/infra, internal tools, customer data plumbing, internal MCP/server implementations, and anything not meant for end customers to clone.

- Treat as all rights reserved (no open-source license) unless a repo says otherwise.
- Do not change visibility to public without an owner decision.
- Do not fork private repos outside this org.

### Public (intentional only)
Thin **customer-facing** surfaces: public MCP/API contracts, SDKs, examples, changelogs, and docs that end consumers need.

- Prefer **Apache-2.0** or **MIT** on those repos.
- Keep proprietary implementation and secrets in **private** repos (or in published packages that do not ship sensitive source).
- Name clearly so the lane is obvious (e.g. public contract vs private implementation).

### Free-plan note
GitHub Free cannot enforce “private-only creation”, org-wide 2FA require, or org/repo rulesets. Discipline: create private by default; only owners publish. Team unlocks rulesets + 2FA require.

### Security baseline (org)
Dependabot alerts/updates, dependency graph, secret scanning + push protection for new repos; web commit signoff required; base permission none; private forks off.

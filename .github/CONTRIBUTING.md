# Contributing to Aptitude

Thanks for contributing to Aptitude.

Aptitude is split into clear product surfaces:

- `aptitude-server` owns the authoritative registry contract
- `aptitude-client` owns runtime orchestration, solving, and execution planning
- `.github` owns the org profile, shared docs, and community health files

Before opening a larger change, read:

- [Start Here](./START-HERE.md)
- [Aptitude Stack Overview](./docs/project/overview.md)
- [Repository Map](./docs/project/repository-map.md)
- [Scope and Ownership Boundary](./docs/project/scope.md)

## How to Contribute

1. Open an issue first for larger changes, cross-repo refactors, or boundary changes.
2. Keep changes scoped to one concern and one repository when possible.
3. Update docs when behavior, contracts, or repo boundaries change.
4. Add or update tests for behavior changes.
5. Keep PRs small enough to review quickly.

## Pull Request Expectations

- Explain the problem and the boundary you changed.
- Link the relevant issue or design doc.
- Call out any API, schema, or workflow changes.
- Include verification steps.

## Quality Bar

For product repos, changes should generally include:

- passing tests
- lint-clean changes
- type-check clean changes where type checking is configured
- updated docs for contract or workflow changes

## Boundary Rules

- Do not move runtime decision logic into `aptitude-server`.
- Do not couple `aptitude-client` directly to server persistence internals.
- Do not use `.github` as a substitute for product implementation docs inside the product repos.

## Security

Do not open public issues for security vulnerabilities.

Use the process in [SECURITY.md](./SECURITY.md).

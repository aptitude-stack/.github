# Start Here

If you are new to Aptitude, start with these pages in order:

1. [Aptitude Stack Overview](./docs/project/overview.md)
2. [Repository Map](./docs/project/repository-map.md)
3. [Scope and Ownership Boundary](./docs/project/scope.md)
4. [Server API Contract](./docs/project/api-contract.md)

## Repositories

- [`aptitude-server`](https://github.com/aptitude-stack/aptitude-server): authoritative registry backend and public HTTP API
- [`aptitude-client`](https://github.com/aptitude-stack/aptitude-client): Python runtime client for MCP, CLI, solving, and execution planning
- [`aptitude-docs`](https://github.com/aptitude-stack/aptitude-docs): longer-form product and architecture documentation
- [`.github`](https://github.com/aptitude-stack/.github): org profile, shared docs, and community health files

## What Aptitude Is

Aptitude is a versioned, dependency-aware ecosystem for AI skills.

It separates:

- publishing and release flows
- authoritative registry behavior
- runtime selection and execution planning

That split keeps the registry small and stable while allowing runtime behavior to evolve independently.

## Where To Go Next

- Want the big picture: [Aptitude Stack Overview](./docs/project/overview.md)
- Want repo boundaries: [Repository Map](./docs/project/repository-map.md)
- Want API details: [Server API Contract](./docs/project/api-contract.md)
- Want contribution guidance: [CONTRIBUTING.md](./CONTRIBUTING.md)
- Want support or reporting info: [SUPPORT.md](./SUPPORT.md)

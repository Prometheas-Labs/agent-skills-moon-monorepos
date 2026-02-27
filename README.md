# Moon Monorepo Skills

Agent skills for working with [Moon](https://moonrepo.dev/) v2 monorepo configurations.

## Installation

```bash
npx skills add prometheas-labs/agent-skills-moon-monorepos
```

## Included Skills

| Skill | Description |
|-------|-------------|
| `moonrepo-workspace` | Workspace configuration, toolchains, caching, CI pipelines, and affected detection |
| `moonrepo-project-config` | Project `moon.yml` files, tasks, file groups, and task options |
| `moonrepo-languages` | Language-specific patterns for PHP, TypeScript, Python, and mobile apps |

## What These Skills Cover

- **Moon v2 syntax** — Updated field names, CLI flags, and configuration patterns
- **Task configuration** — `command` vs `script`, inputs/outputs, caching, presets
- **Workspace setup** — Project discovery, toolchains, CI commands
- **Language patterns** — Idiomatic configurations for common project types

## Compatibility

These skills target **Moon v2**. Key differences from v1 include:

- `type` → `layer`
- `runner` → `pipeline`
- `vcs.manager` → `vcs.client`
- `.moon/toolchain.yml` → `.moon/toolchains.yml` (plural)
- CLI flags use kebab-case

## License

MIT

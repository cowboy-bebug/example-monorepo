# Example Monorepo

Minimal pnpm workspace with Nx release and conventional commits.

## Setup

```bash
pnpm install
```

## Release

```bash
pnpm release:dry-run    # Preview
pnpm release            # Bump versions, changelogs, git tags
```

## Commit Format

```
feat(pack-1): add feature    # minor bump
fix(pack-2): fix bug         # patch bump
```

Scopes: `release`, `pack-1`, `pack-2`, `serve-1`, `serve-2`

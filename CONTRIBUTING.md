# Contributing

## Commit messages

This repo uses [Conventional Commits](https://www.conventionalcommits.org/).

```
<type>(#<issue>): <short description>
```

No issue? Drop the `(#n)`:

```
<type>: <short description>
```

| Type | Use for |
|------|---------|
| `feat` | New composition or feature |
| `fix` | Bug fix |
| `chore` | Maintenance, deps, tooling |
| `docs` | Documentation only |
| `refactor` | Code restructure, no behaviour change |
| `test` | Adding or fixing tests |
| `style` | Formatting, whitespace (no logic change) |
| `perf` | Performance improvement |
| `ci` | CI/CD config changes |
| `build` | Build system changes |

**Rules:**
- Description is lowercase, imperative mood — `add` not `adds` or `added`
- No period at the end
- Keep under 72 characters total

## Branch naming

```
<type>/<issue-number>-<short-description>
```

Examples: `feat/42-intro-card`, `fix/87-ticker-fps`

## PRs

- One thing per PR
- Link the issue if there is one
- The CI render job must pass before merging

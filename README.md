# Slate CLI

Usage: `slate <command> [flags] [args]`

## Commands

| Command | Description |
|---------|-------------|
| `run <file>` | Execute a Slate file |
| `check [file]` | Type-check a file; `--workspace` to check all files |
| `build` | Compile to native binary |
| `new` / `init` | Scaffold a new project |
| `add` / `remove` / `sync` | Dependency management |
| `docs` | Built-in documentation |
| `help` | Show all commands |

## Flags

Applies to `run` and `build`:
| Flag | Description |
|------|-------------|
| `--verbose` | Per-file progress output |
| `--quiet`   | Errors and results only |

Applies to `build`:
| Flag | Description |
|------|-------------|
| `--debug`       | Build with debug info |
| `--release`     | Optimized release build (default) |
| `--release-fast`| Aggressively optimized |
| `--target <arch>` | Cross-compile target |

See `slate help <command>` for usage details.
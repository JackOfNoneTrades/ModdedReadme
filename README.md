# ModdedReadme

Transforms GitHub READMEs for Modrinth/CurseForge by converting local image paths to raw GitHub URLs.

Tries to guess raw URLs from current folder git info.

## Usage

```bash
python3 transform_readme.py [input] [-o output] [-b branch] [--repo owner/repo]
```

## Flags

| Flag | Description |
|------|-------------|
| `input` | Input file (default: `README.md`) |
| `-o, --output` | Output file (default: stdout) |
| `-b, --branch` | Git branch (default: auto-detect) |
| `--repo` | Override repo as `owner/repo` |

## Example

```bash
python3 transform_readme.py README.md -o README_MODRINTH.md
```

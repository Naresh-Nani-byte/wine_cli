[[![YOLO](https://img.shields.io/badge/YOLO-100%25-red?style=flat-square![YOLO](https://img.shields.io/badge/YOLO-0%25-brightgreen?style=flat-square&logo=github)](https://github.com/YOUR_USERNAME/wine_cli)logo=github)](https://github.com/Naresh-Nani-byte/wine_cli)

# wine_cli

A CLI tool for wine — built with Go.

## Getting Started

```bash
go run main.go
```

## GitHub Actions

| Workflow | Trigger | Purpose |
|---|---|---|
| **Merge PR** | PR labelled `merge` | Auto-squash-merges the PR via `peter-evans/enable-pull-request-automerge` |
| **YOLO Badge** | Push to `main`/`master` | Recalculates the % of commits that bypassed a PR and updates the badge above |

## How to auto-merge a PR

1. Open a pull request.
2. Add the **`merge`** label.
3. The workflow approves and squash-merges it automatically.

> **Tip:** Enable "Allow auto-merge" in your repo settings (*Settings → General → Pull Requests*).

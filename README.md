# flockr

Small Go tool: declutter ~/Downloads in one command

Built for my own use; public in case it helps someone.

## Installation

```bash
go build -o bin/ ./...
```

## How to use

```bash
./bin/flockr ~/Downloads --dry-run
./bin/flockr ~/Downloads
```

## What it does

- Skips hidden files and folders by default
- Dry-run prints the plan before moving anything
- Groups files into folders by extension
- Single static binary, no runtime deps

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── roadmap.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── go.mod
└── main.go
```

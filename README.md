# flockr

Small Go tool: declutter ~/Downloads in one command

Built for my own use; public in case it helps someone.

## Getting started

```bash
go build -o bin/ ./...
```

## Highlights

- Skips hidden files and folders by default
- Dry-run prints the plan before moving anything
- Groups files into folders by extension
- Single static binary, no runtime deps

## How to use

```bash
./bin/flockr ~/Downloads --dry-run
./bin/flockr ~/Downloads
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── go.mod
└── main.go
```

## Notes

- mostly stable, edge cases remain

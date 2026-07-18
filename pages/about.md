# About

**Test_Pages** is a lightweight, file-based wiki built entirely from markdown files stored in a GitHub repository.

## How It Works

Each page is a plain `.md` file. Pages link to one another using standard relative markdown links:

```markdown
[Page Title](other-page.md)
```

This mirrors the `[[wiki-link]]` convention popularised by [Obsidian](https://obsidian.md), and works natively in GitHub's markdown renderer — no build step required.

## Goals

- **Simple** — plain markdown files, no databases or frameworks
- **Portable** — readable locally, in any editor, and on GitHub
- **Linked** — every page connects to related pages, forming a navigable graph

## See Also

- [Home](../README.md)
- [Getting Started](getting-started.md)
- [Topics](topics.md)

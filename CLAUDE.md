# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

Please respond Japanese.

## Project Overview

This is a Zenn content repository for publishing technical articles in Japanese. The content focuses on systems-level programming topics including OS development and networking.

## Commands

### Zenn CLI

```bash
npx zenn preview          # Preview articles locally (opens browser)
npx zenn new:article      # Create new article
npx zenn new:book         # Create new book
```

## Repository Structure

- `articles/` - Markdown articles with YAML frontmatter
- `books/` - Book collections (currently unused)

## Article Format

Articles use YAML frontmatter:

```yaml
---
title: "記事タイトル"
emoji: "🏓"
type: "tech"              # "tech" or "idea"
topics: ["tag1", "tag2"]
published: false          # Set to true when ready to publish
---
```

## Conventions

- **Language**: All articles written in Japanese
- **Commit messages**: Use conventional commits (feat:, docs:, refactor:)
- **Article IDs**: Zenn generates random IDs for article filenames

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Type

This is an **Obsidian directory** - a personal knowledge management system, not a code repository. Obsidian uses markdown files organized in folders, with special linking syntax and metadata.

## Structure

- **Content**: Korean-language notes stored as `.md` files
- **Configuration**: `.obsidian/` directory contains workspace settings, plugins, and appearance configs
- **Current Notes**: Contains project planning notes for GemmeNews

## Project Files

### gemmenews/ directory

This directory contains planning documents for **GemmeNews** - a news aggregator service:

- **개요.md**: Product overview and requirements document
  - Describes the core concept: aggregating news from multiple sources (Hacker News, Geek News, Naver News)
  - Lists key features: news collection, todo-style management, sharing functionality
  - Specifies tech stack: SolidStart, Drizzle, PostgreSQL, Pothos GraphQL

- **유저스토리.md**: User stories organized by Epic
  - Epic 1: News collection system (automated crawling and storage)
  - Epic 2: News reading interface (feed view, detail view)
  - Epic 3: News management (archive, dismiss, remind features)
  - Epic 4: News sharing (share links with SSR for social media previews)
  - Epic 5: User accounts (signup, login/logout)
  - Epic 6: Future expansions (custom news sources, AI-powered analysis)

## Working with Obsidian Vaults

When editing or creating notes in this vault:

1. **Links**: Use Obsidian's wiki-link syntax `[[note name]]` to create internal links
2. **Frontmatter**: YAML metadata can be added at the top of notes between `---` delimiters
3. **Line Numbers**: The vault has line numbers enabled (see `.obsidian/app.json`)
4. **Language**: Content is primarily in Korean

## Common Tasks

- **Create new note**: Create a new `.md` file in the vault root or subdirectories
- **Link notes**: Use `[[Note Title]]` syntax to create connections between notes
- **Organize**: Group related notes in subdirectories (like `팀 제품용 AI 채팅 서비스/`)
- **No build process**: This is a documentation vault - changes are immediately visible in Obsidian

## Notes

- The vault uses Obsidian's standard plugins (file explorer, search, bookmarks, graph view)

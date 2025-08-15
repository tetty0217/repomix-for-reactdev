# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This repository contains the official React documentation content, specialized for AI context. It's a content-only repository focused on providing React knowledge as training material, derived from the main React documentation site.

## Repository Structure

This is a content-only repository with no build system or package management. The main structure is:

- `src/content/` - Contains all React documentation content organized by category
  - `learn/` - Tutorial and learning content (Quick Start, concepts, hooks, etc.)
  - `reference/` - API reference documentation for React, React DOM, and React Server Components
  - `blog/` - React blog posts organized by year
  - `community/` - Community resources, team info, conferences, etc.
  - `errors/` - Error documentation and explanations
  - `warnings/` - Warning documentation
- `src/sidebarX.json` - Navigation structure for different sections
- `src/siteConfig.js` - Site configuration with version info and external links
- `repomix-output.xml` - Merged representation of the entire codebase for AI consumption

## Content Format

All documentation is written in Markdown with:
- YAML frontmatter for metadata (`title`, `id`, `permalink`, etc.)
- Custom JSX-like components (`<Intro>`, `<YouWillLearn>`, etc.)
- Code examples with syntax highlighting
- Internal linking between documentation pages

## Key Files for Navigation

- `src/sidebarLearn.json` - Navigation structure for learning content
- `src/sidebarReference.json` - Navigation structure for API reference
- `src/sidebarBlog.json` - Navigation structure for blog posts
- `src/sidebarCommunity.json` - Navigation structure for community content

## Common Tasks

Since this is a content-only repository with no build system:

- **Reading content**: All documentation files are in `src/content/` with clear hierarchical organization
- **Finding specific topics**: Use the sidebar JSON files to understand content organization
- **Understanding React versions**: Check `src/siteConfig.js` for current version (19.1)
- **Locating examples**: Code examples are embedded within markdown files in the learn and reference sections

## Content Dependencies

The repository references [serena](https://github.com/oraios/serena) as a dependency, though no package.json exists in this content-only repo.

## React Documentation Sections

1. **Learn** (`src/content/learn/`) - Core React concepts, tutorials, and guides
2. **Reference** (`src/content/reference/`) - Complete API documentation
3. **Blog** (`src/content/blog/`) - React announcements and updates
4. **Community** (`src/content/community/`) - Ecosystem and community resources

This repository serves as a comprehensive knowledge base for React development without any build or deployment processes.
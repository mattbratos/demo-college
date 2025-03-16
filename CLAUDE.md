# CLAUDE.md - Guidelines for Ingram College Repository

## Project Overview
- Educational content repository for homebrew.so platform
- Content written in MDX format with markdown and JSX
- Focused on tutorials and courses

## Content Structure
- `/courses/` - Courses directory with subdirectory for each course. Example: /course/API-101 and then chapters in this dir example /course/API-101/chapter-1.mdx
- `/guides/` - Standalone tutorials and reference material
- `/assets/` - Media files for content (images, etc.)

## Course Style Guidelines
- Each course shuold start with index.mdx file where you list all the basic info about the course
- index.mdx should have frontmatter with title, descirption and tags. example

```
---
title: API 101 for Junior Web Devs
description: Learn the fundamentals of APIs, how to interact with RESTful APIs, and integrate them into React applications using JavaScript and TypeScript.
tags:
  - APIs
  - web development
  - JavaScript
  - React
  - TypeScript
  - Next.js
  - Node.js
---
```

- Each chapter should have frontmatter with title and order. order means which chapter is it exmaple chapter on shuold have order: 1. example

```
---
title: introduction-to-apis
order: 1
---
```
- Chapter files should include clear objectives and outlines
- Use code blocks with language specification for examples
- Maintain consistent heading hierarchy (# for main title, ## for sections)
- Include practical exercises where appropriate
- Do not use too much bold or italic

## MDX Formatting
- Follow markdown best practices for readability
- Use JSX components sparingly and with proper documentation
- Include appropriate frontmatter with metadata for each content file
- Images should be placed in `/assets/` with descriptive filenames

## Writing Conventions
- Use clear, concise language targeted at junior developers
- Organize content with proper headings, lists, and code blocks
- Cross-reference related content where appropriate

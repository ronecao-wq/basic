# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a content repository containing Agile/Scrum training materials in Chinese. It includes HTML-based slideshows, documentation, and presentation files for training teams on Agile methodologies, Jira usage, and Scrum ceremonies.

## Project Structure

- **archive/** - Contains all training materials including:
  - HTML slideshows (agile_training.html, slides3.html, scrum_slides.html, etc.)
  - Markdown documentation (scrum.md)
  - PowerPoint files (Scrum框架培训PPT.pptx, 敏捷宣言通俗解读PPT.pptx)
  - Word documents and XML files

## Viewing Content

HTML files can be opened directly in a browser for viewing:

```bash
# Open a slideshow in the default browser (macOS)
open archive/agile_training.html

# Or simply double-click the file in your file explorer
```

## Content Topics

The training materials cover:

1. **Agile Fundamentals** - Core values, waterfall vs agile, Scrum framework overview
2. **Jira Usage** - Creating tickets, Sprint management, key fields and workflows
3. **Agile Ceremonies** - Sprint planning, daily standups, retrospectives, backlog grooming
4. **Estimation** - Story points, velocity, burndown charts

## Technical Stack

The HTML slideshows use:
- TailwindCSS 2.2.19 (via CDN)
- Font Awesome 4.7.0 (via CDN)
- Google Fonts (Noto Sans SC)
- Vanilla JavaScript for slide navigation

## Notes for Editing

- HTML files are self-contained with inline styles and scripts
- Chinese language content requires UTF-8 encoding
- Slideshow navigation is typically via arrow keys or on-screen controls

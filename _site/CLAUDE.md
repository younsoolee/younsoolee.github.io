# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an academic lab website for the Smart Production Systems (SPS) Lab at Soongsil University. Built with Jekyll and hosted on GitHub Pages.

## Build Commands

```bash
# Install dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve

# Build for production
bundle exec jekyll build
```

The site is built to `_site/` directory.

## Architecture

### Content Structure
- **`_members/`** - Lab member profiles (markdown files with YAML front matter)
  - `role` field determines display category (prof, ug, etc.)
  - Member roles defined in `_data/roles.yaml`
- **`_posts/`** - News/blog posts (date-prefixed: `YYYY-MM-DD-title.md`)
- **Page directories** (`research/`, `members/`, `contact/`, `news/`, `home/`) - Each contains `index.md`

### Data Files (`_data/`)
- `sources.yaml` - Publication DOIs for auto-citation
- `citations.yaml` - Generated citation data (from auto-cite)
- `roles.yaml` - Member role definitions with icons
- `links.yaml` - Link type definitions (social media, publications, etc.)

### Template System
- **`_layouts/`** - Page templates (`default.html`, `member.html`, `post.html`)
- **`_includes/`** - Reusable components
  - `list.html` - Filterable list component, supports `filters` param (e.g., `filters="role: prof"`)
  - `portrait.html`, `citation.html`, `card.html` - Display components
  - `section.html`, `banner.html`, `link.html` - Layout helpers

### Auto-Citation System
Located in `auto-cite/`. Python scripts that fetch citation metadata from DOIs in `_data/sources.yaml` and generate `_data/citations.yaml`.

```bash
cd auto-cite && pip install -r requirements.txt
python auto-cite.py
```

## Configuration

Main config in `_config.yaml`:
- Site metadata (title, description, URL)
- Default front matter for collections
- Jekyll plugins: jekyll-redirect-from, jekyll-feed, jekyll-sitemap

## Adding Content

### New Member
Create `_members/firstname-lastname.md`:
```yaml
---
name: Full Name
image: images/members/photo.jpeg
role: ug  # prof, phd, master, ug, etc.
links:
  email: email@example.com
---
Bio content here...
```

### New Post
Create `_posts/YYYY-MM-DD-slug.md`:
```yaml
---
title: "Post Title"
---
Content here...
```

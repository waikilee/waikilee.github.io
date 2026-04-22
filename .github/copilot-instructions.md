# GitHub Copilot Instructions

This document provides guidance for GitHub Copilot to better understand and assist with this Jekyll-based personal website project.

## Project Overview

- **Project Type**: Jekyll static site
- **Theme**: Minima
- **Repository**: waikilee.github.io
- **Primary Languages**: 
  - Markdown (content)
  - HTML/Liquid (templates)
  - YAML (configuration)
  - Ruby (dependencies)

## Project Structure

Key directories and their purposes:
- `_posts/`: Blog posts and articles
- `_layouts/`: Page layout templates
- `_includes/`: Reusable HTML components
- `assets/`: Static files (images, CSS, etc.)
- `_site/`: Generated static site (not to be edited directly)

## Common Tasks

When assisting with this project, consider these common tasks:

1. **Creating New Posts**
   - Follow Jekyll post naming convention: `YYYY-MM-DD-title.md`
   - Include proper front matter
   - Support Markdown formatting

2. **Layout Modifications**
   - Understand Liquid templating syntax
   - Maintain theme compatibility
   - Consider responsive design

3. **Site Configuration**
   - Work with `_config.yml`
   - Handle Jekyll-specific settings
   - Manage theme customization

4. **Asset Management**
   - Organize images and media files
   - Handle CSS/SCSS modifications
   - Optimize static assets

## Style Guidelines

- Use clean, semantic HTML
- Follow Jekyll best practices
- Maintain consistent Markdown formatting
- Use relative URLs for internal links
- Keep front matter organized and consistent

## Important Notes

- Never modify files in the `_site` directory
- Always validate front matter syntax
- Preserve existing theme functionality
- Consider Jekyll's build process when suggesting changes

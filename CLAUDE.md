# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

- `npm run dev` - Start dev server at localhost:4321
- `npm run build` - Build production site to ./dist/
- `npm run preview` - Preview production build locally

## Architecture

Single-page Astro website for Rigby & Company (commercial appraisal firm) using Tailwind CSS v4.

**Key files:**
- `src/layouts/Layout.astro` - Main layout with navigation header and footer
- `src/pages/index.astro` - Single page with all content sections (hero, about, services, team, contact)
- `src/styles/global.css` - Global styles and Tailwind import

**Stack:**
- Astro 5 with file-based routing
- Tailwind CSS v4 via Vite plugin
- Netlify Forms for contact form submission
- Google Fonts (Inter, Playfair Display)

## Documentation Map

| Document | Contents |
|----------|----------|
| `docs/PROJECT_CONTEXT.md` | Business context, firm overview, goals, team members |
| `docs/CONTENT_UPDATES.md` | Website content changes needed (bios, services, contact, logos, photos) |
| `docs/MIGRATION.md` | Domain (Homestead), email (I4 → Google Workspace), hosting (I4 → Netlify) |
| `docs/CLIENT_NOTES.md` | Client communications, decisions, preferences, billing context |
| `docs/TODOS.md` | Master todo list — website changes, domain, email, I4, billing |

## Quick Reference

- **Domain:** rigbyandcompany.com (transferring from Homestead to Netlify)
- **Hosting:** Netlify (netlify.app currently, custom domain pending)
- **Email:** Migrating from I4 to Google Workspace (jeff@rigbyandcompany.com)
- **Contact:** Jeff Rigby (jhrigby42@gmail.com) — primary decision maker

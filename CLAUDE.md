# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

- `npm run dev` - Start dev server at localhost:4321
- `npm run build` - Build production site to ./dist/
- `npm run preview` - Preview production build locally

## Architecture

This is a single-page Astro website for Rigby & Company (commercial appraisal firm) using Tailwind CSS v4.

**Key files:**
- `src/layouts/Layout.astro` - Main layout with navigation header and footer
- `src/pages/index.astro` - Single page with all content sections (hero, about, services, team, contact)
- `src/styles/global.css` - Global styles and Tailwind import

**Stack:**
- Astro 5 with file-based routing
- Tailwind CSS v4 via Vite plugin
- Netlify Forms for contact form submission
- Google Fonts (Inter, Playfair Display)

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is **brazil.l8p.tech**, a website built with Astro 5 (minimal starter template). It uses strict TypeScript and ES modules.

## Commands

- `npm run dev` — Start dev server at localhost:4321
- `npm run build` — Production build to `./dist/`
- `npm run preview` — Preview production build locally
- `npm run astro` — Run Astro CLI commands (e.g., `npm run astro add`, `npm run astro check`)

## Architecture

- **Astro 5** static site with file-based routing
- Pages live in `src/pages/` — `.astro` and `.md` files become routes based on filename
- Components go in `src/components/`
- Static assets go in `public/`
- TypeScript config extends `astro/tsconfigs/strict`

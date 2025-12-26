# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Snowbird Services is a static marketing website for a multifamily property technology company that offers rent-reporting credit building and utility billback services. The site is a single-page landing page built with vanilla HTML, Tailwind CSS (via CDN), and minimal JavaScript.

## Architecture

- **index.html**: Primary landing page targeting residents and property managers
- **snowbird_services_landing_page_index.html**: Alternative/older version with different messaging (AI-first PropTech focus)
- **assets/**: Contains logo image (Minimalist Dark Blue Snowflake Logo.png)

## Tech Stack

- Pure HTML with no build process
- Tailwind CSS loaded via CDN (`https://cdn.tailwindcss.com`)
- Inter font from Google Fonts
- Contact form submits to Formspree (`https://formspree.io/f/xrbredko`)

## Development

No build commands are needed. Open `index.html` directly in a browser or serve with any static file server.

## Key Patterns

- Custom CSS classes `glass` and `card-soft` defined in `<style>` block for glassmorphism effects
- Mobile navigation toggle via vanilla JS (ids: `mobile-toggle`, `mobile-menu`)
- Footer copyright year auto-updates via JS
- Sections use id anchors for smooth navigation: `#home`, `#how-it-works`, `#benefits`, `#pm-section`, `#contact`

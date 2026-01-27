# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the marketing/landing page for Wismo, a Shopify app that reduces "Where is my order?" support tickets by detecting silent or confusing shipping moments and automatically reassuring customers.

The site is hosted at wismoapp.com via GitHub Pages (configured via CNAME file).

## Architecture

This is a static single-page website with no build process:
- **index.html** - The entire site in one file with embedded CSS and JavaScript
- **images/** - Screenshots and icons for the landing page
- Favicons and app icons in the root directory

The page mimics the Shopify App Store listing style and includes:
- Embedded YouTube demo video
- Image lightbox with keyboard navigation
- FullStory analytics integration
- CTA tracking for Shopify App Store clicks via gtag

## Development

No build tools or package manager. Edit `index.html` directly and push to deploy via GitHub Pages.

The app store listing links to: https://apps.shopify.com/wismo-3

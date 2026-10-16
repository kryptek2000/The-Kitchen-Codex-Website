# The Kitchen Codex Website

Official website for **The Kitchen Codex**.

🌐 https://kitchencodex.app

The Kitchen Codex is a standalone recipe, meal-planning, shopping, cooking,
and nutrition platform built around **The Kitchen Codex Vault** — a user-owned
home for the recipes people save, protect, organize, and cook from.

The Kitchen Codex is not defined by any one storage provider or note-taking
platform. Obsidian is an important integration and acquisition channel, while
future Vault storage and import options may include local storage, Google Drive,
Kitchen Codex Cloud, social recipe capture, and other connected services.

## Website Project

This repository contains the public-facing website for The Kitchen Codex.

The website project is intentionally maintained separately from the main
Kitchen Codex application repository.

## Product Direction

- **The Kitchen Codex is the brand and product.**
- **Shiso** is the one AI companion being built for the whole Kitchen Codex, with one conversational interface and contextual entry points such as **Ask Shiso** and **Create with Shiso**. Advanced Nutrition is a capability, not a separate chatbot.
- **The Kitchen Codex Vault** is the product-level home for a user's recipes.
- **My Recipe Vault** may be used as a friendlier UI/onboarding label.
- External services such as Obsidian are integrations, not the identity of the product.
- Public language should favor clear concepts such as save, protect, organize,
  plan, shop, cook, and understand over technical storage terminology.
- Social recipe capture is a strategic growth direction because it can turn
  scattered recipes from the web and social platforms into an organized Vault.
- Nutrition follows a two-tier product strategy: **Basic Nutrition** is part of
  the free experience, while **Advanced Nutrition** is a paid premium engine.
- **AI-first nutrition is the approved future direction:** Shiso leads whole-recipe interpretation and can draw on the USDA catalog, Kitchen Codex calculation tools, and (when developed and enabled) trustworthy outside food references. Useful estimates may be explicitly identified rather than blocked by an absent USDA household portion.
- Preserve clear source/estimate labels, honest partial subtotals, serving math, and explicit review/save authorization. Web-backed nutrition research and broad AI-generated estimates remain **planned and not advertised as live**.

## Project Documentation

- [Website Master Plan](docs/Website-Master-Plan.md)
- [Website Phase 0 Design Brief](docs/Website-Phase-0-Design-Brief.md)

## Status

A static Coming Soon page is live at kitchencodex.app, with an existing Kit early-access signup. Sid approved the Shiso introduction for release on October 9, 2026 through the existing GitHub-triggered deployment. Shiso itself remains a planned companion, not an available service. The approved hero and visual system are preserved.

The documentation retains earlier full-launch planning alongside the October 9 Shiso identity decision and the October 16 AI-first nutrition decision. Future features must be described as planned until released. No new framework or JavaScript is needed for this update.

## Release Process

Pushes to the existing GitHub `main` branch trigger the configured automatic Cloudflare deployment. Verify the live page after each release. No manual Cloudflare, DNS or domain changes are part of the Shiso release.

## Release Authority

Sid Richmond is the final release and production deployment authority.

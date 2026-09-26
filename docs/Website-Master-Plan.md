# The Kitchen Codex — Website Master Plan

**Domain:** kitchencodex.app
**Version:** 1.2
**Date:** September 25, 2026
**Project state:** Planning / pre-build
**Release authority:** Sid Richmond

## North Star
Build a fast, beautiful, trustworthy public home for The Kitchen Codex that clearly communicates what the product does, why it is different, and how a visitor can get started — without turning the marketing site into a second application and without defining the product through Obsidian, Markdown, or any single storage provider.

## 1. Executive Summary
The Kitchen Codex website will be the official public-facing home of the product. It will explain the product, build confidence, show the real experience, guide visitors toward the correct next action, and provide a durable foundation for future documentation, downloads, announcements, integrations, and monetization.

The website and application remain separate projects with separate roadmaps and repositories. They share brand standards, product truth, screenshots, release information, and selected content.

**The Kitchen Codex is the standalone product and brand.** The Kitchen Codex Vault is the product-level concept for the protected home where a user's recipes live. Storage and external platforms sit beneath that concept. A Vault may eventually be local, connected to Obsidian, stored with Google Drive, hosted through Kitchen Codex Cloud, or backed by other providers without changing the user's mental model.

Obsidian remains a valuable integration and acquisition channel, but it does not define the brand.

## 2. Website Mission & Objectives
- Explain the product quickly to a first-time visitor.
- Show the real application through high-quality screenshots and feature demonstrations.
- Position The Kitchen Codex as a complete recipe and cooking platform.
- Introduce The Kitchen Codex Vault as the protected home for a user's recipes.
- Communicate recipe capture, vault ownership, recipe organization, meal planning, shopping, cooking, nutrition, and import workflows.
- Present Obsidian as an integration rather than a prerequisite.
- Leave room for future storage providers and Kitchen Codex Cloud.
- Establish social recipe capture as a strategic growth direction.
- Provide clear calls to action.
- Create trusted homes for releases, docs, FAQs, support, privacy/security, and future commercial offerings.
- Stay fast, responsive, accessible, and maintainable.

## 3. Audience
Primary audiences include home cooks, recipe collectors, people who save recipes from websites and social media, meal planners, nutrition-conscious users, privacy/ownership-minded users, Obsidian users, users of other productivity/storage ecosystems, existing users, technical/open-source users, and future paying customers.

The site should not require a visitor to understand Markdown, YAML, frontmatter, local-first architecture, or Obsidian before understanding the product.

## 4. Brand & Visual Direction
Warm technical aesthetic; real app imagery; restrained near-black, warm cream, and Codex green; strong typography and spacing; purposeful motion; accessibility by default.

Working tokens: `#171717` ink, `#F4EFE4` warm cream, `#3A6B51` Codex green, `#666666` muted gray.

### Brand hierarchy
- **The Kitchen Codex** — product and brand.
- **The Kitchen Codex Vault** — product-level recipe home/storage concept.
- **My Recipe Vault** — optional conversational UI/onboarding label.
- **Obsidian integration** — external ecosystem integration and acquisition channel.
- **Google Drive / Kitchen Codex Cloud / future providers** — potential storage options beneath the Vault concept.

### Messaging direction
Working ideas:
- **Protect the recipes you love in The Kitchen Codex Vault.**
- **Save it. Protect it. Organize it. Cook from it.**
- **One home for the recipes you collect, cook, and want to keep.**

These are design anchors, not final launch copy.

Public language should lead with save, protect, organize, import, connect, sync, back up, plan, shop, cook, and understand. Technical terms such as Markdown, YAML, adapters, filesystem access, and frontmatter belong in advanced documentation and technical settings.

## 5. Launch Information Architecture
P0/P1 surfaces: Home, Features, Nutrition, How It Works / The Kitchen Codex Vault, Product Tour, Get Started / Download, FAQ, Docs, Changelog, About, Privacy/Terms. Pricing is future work.

Dedicated integration content may later include Obsidian, social recipe capture/import, Google Drive, Kitchen Codex Cloud, and additional providers as they become real product capabilities.

Do not create pages that imply integrations exist before they are shipped.

## 6. Homepage Blueprint
Hero → real product proof → save/capture → Vault protection/ownership → plan/shop/cook → Basic Nutrition + AI Advanced Nutrition → integrations → feature highlights → trust/quality → final CTA → footer.

Working homepage narrative:
1. **Save what you love.**
2. **Protect it in The Kitchen Codex Vault.**
3. **Organize and plan from one place.**
4. **Shop and cook from the same system.**
5. **Understand recipes with nutrition that grows with you — Basic Nutrition free, AI Advanced Nutrition premium.**
6. **Connect the tools and services that fit your workflow.**

## 7. Technical Architecture
- Separate GitHub repository.
- Astro + selective React as preferred launch framework; Next.js remains an alternative if requirements justify it.
- Tailwind CSS or a compact token-based CSS system.
- Markdown/MDX initially for content.
- Hetzner Cloud hosting behind Cloudflare.
- Docker + GitHub Actions deployment.
- Lightweight privacy-conscious analytics only when measurement requirements are defined.
- No CMS required at launch.

## 8. Team Workflow
- Sid: product owner and final release authority.
- ChatGPT: architect, design partner, UX/copy direction, technical planning, review/referee.
- DeepSeek: implementer.
- Muse Spark 1.3: independent auditor where practical.

No production deployment is approved merely because implementation or audit passes. Sid remains the release authority.

## 9. Phased Website Game Plan
0. Product truth & requirements
1. Brand system
2. Sitemap & content architecture
3. Homepage design prototype
4. Technical foundation
5. Core page build
6. Content & real product media
7. Responsive, accessibility & performance polish
8. SEO & structured metadata
9. Security & release audit
10. Production launch
11. Post-launch growth

## 10. Quality Gates
Product truth, visual polish, accessibility, performance, SEO, security, reliability, content accuracy, truthful integration claims, and explicit release control.

## 11. Content & SEO
Benefits and workflows first; consistent terminology; concrete demonstrations; careful nutrition wording; precise AI descriptions; maintainable release-specific claims.

Key discoverability themes may eventually include recipe organization, meal planning, shopping and cooking workflows, recipe protection/backup/ownership, recipe importing, social recipe capture, Advanced Nutrition, and Obsidian integration.

Avoid keyword stuffing or positioning the entire product around one integration.

## 12. Hosting & Deployment
Cloudflare at the domain edge, small Hetzner Cloud production server, containerized deployment from GitHub, staging/preview, minimal exposed services, health checks, and rollback.

GitHub Actions should remain lighter than the application pipeline: CI for formatting/lint/tests/build/accessibility where practical, optional preview deployment, and a production deployment workflow gated on clean CI. Passing automation never replaces explicit release authority.

## 13. Success Measures
Clarity, meaningful navigation to Get Started/Download, understanding of the Vault concept without needing Obsidian knowledge, strong engagement with product demonstrations, real-world performance, trust, maintainability, and useful search/referral growth.

Longer-term growth can also be measured through effective acquisition from integrations and recipe-capture workflows.

## 14. Deferred Decisions
Exact pricing, subscription packaging, accounts, payments/licensing, Kitchen Codex Cloud details, final app distribution channels, newsletter/CRM, CMS, public API, community features, specific social connectors, advanced cross-provider synchronization, complex personalization, and the final balance between the labels “The Kitchen Codex Vault” and “My Recipe Vault.”

## 15. Immediate Next Actions
1. Use the updated platform-independent product positioning as the homepage foundation.
2. Inventory the approved logo and current app visual language.
3. Capture representative app screens.
4. Define the launch CTA.
5. Create homepage desktop/mobile wireframes and visual direction.
6. Define initial Vault messaging and terminology.
7. Reconcile website tokens with the app themes.
8. Begin technical implementation only after the homepage/design direction is approved.

## 16. Change Control
This is a living website roadmap. Changes to mission, product identity, Vault strategy, major information architecture, hosting model, public product claims, integration claims, commercial model, or release authority should be recorded deliberately.

## 17. Product Integration & Growth Strategy

### The Kitchen Codex Vault
The Kitchen Codex Vault should remain a durable product concept independent of where recipe data physically lives.

Potential paths may include local storage, Obsidian-connected Vaults, Google Drive, Kitchen Codex Cloud, future storage providers, and import/sync bridges from other ecosystems.

The simple user-facing model is: **their recipes live in their Kitchen Codex Vault; they choose how that Vault is stored or connected.**

### Obsidian
Obsidian should be positioned as a mature integration, bridge for existing Obsidian users, and potential acquisition channel into the broader Kitchen Codex product.

The website should avoid language that makes Obsidian appear to own or define The Kitchen Codex.

### Notion and other productivity platforms
Notion and similar platforms may become useful import/sync or ecosystem integrations, but they are not assumed to be the primary commercial engine.

### Social recipe capture
Social recipe capture is a strategic growth direction.

Desired long-term user story:

**See a recipe anywhere → save it → extract and normalize it → protect it in The Kitchen Codex Vault → plan → shop → cook → understand nutrition.**

Potential source channels may include social media, video platforms, recipe sites, shared links, screenshots, and other user-provided sources, subject to platform/API/legal constraints.

The website must only advertise specific connectors once they are actually supported.

## 18. Nutrition Product Strategy
Nutrition is a major product pillar with a deliberate two-tier model.

### Basic Nutrition — Free
Basic Nutrition belongs in the free Kitchen Codex experience.

It should support straightforward recipe nutrition using usable nutrition already present in imported or existing recipes and deterministic nutrition behavior where applicable. The free tier should provide real value and should not be intentionally crippled simply to force an upgrade.

### AI Advanced Nutrition — Paid
AI Advanced Nutrition is the premium nutrition engine.

AI serves as the semantic interpretation and orchestration layer for messy real-world recipe language: ambiguous ingredient wording, household units, counts, ranges, alternatives, portions, and other inputs that are difficult to resolve reliably with deterministic parsing alone.

AI does **not** become the canonical source of nutrition truth. Deterministic validation, USDA evidence, Kitchen Codex nutrient calculation, provenance/confidence, and explicit user **Review / Apply** remain authoritative.

The architecture should remain provider-neutral so no outside AI vendor becomes inseparable from the nutrition product.

### Current foundation
Existing Advanced Nutrition work remains valuable foundation for the premium engine. Current shipped capability includes Phase 7 AI-assisted household interpretation:

`ba99c2cac9233643b6670ab58a3c91c69ef2382e` — `feat(nutrition): add AI-assisted household resolution`

That implementation milestone should not define the public product story by itself.

### Public messaging direction
Public-facing language should clearly distinguish free Basic Nutrition from paid AI Advanced Nutrition without overwhelming visitors with architecture.

Working direction:
- **Basic nutrition when you need the essentials. AI-powered depth when you want more.**
- **AI interprets. Kitchen Codex verifies. You stay in control.**
- **Nutrition that understands how recipes are actually written.**

Avoid exposing internal engineering terminology such as bounded estimate policy, mid-flight authority, household resolution contracts, or matching internals in marketing copy.

Exact pricing and subscription packaging remain separate commercial decisions.

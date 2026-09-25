# The Kitchen Codex — Website Master Plan

**Domain:** kitchencodex.app  
**Version:** 1.0  
**Date:** September 25, 2026  
**Project state:** Planning / pre-build  
**Release authority:** Sid

## North Star
Build a fast, beautiful, trustworthy public home for The Kitchen Codex that clearly communicates what the product does, why it is different, and how a visitor can get started — without turning the marketing site into a second application.

## 1. Executive Summary
The Kitchen Codex website will be the official public-facing home of the product. It will explain the product, build confidence, show the real experience, guide visitors toward the correct next action, and provide a durable foundation for future documentation, downloads, announcements, and monetization.

The website and application remain separate projects with separate roadmaps and repositories. They share brand standards, product truth, screenshots, release information, and selected content.

## 2. Website Mission & Objectives
- Explain the product quickly to a first-time visitor.
- Show the real application through high-quality screenshots and feature demonstrations.
- Communicate vault ownership, recipe organization, meal planning, shopping, cooking, nutrition, and import workflows.
- Provide clear calls to action.
- Create trusted homes for releases, docs, FAQs, support, privacy/security, and future commercial offerings.
- Stay fast, responsive, accessible, and maintainable.

## 3. Audience
Primary audiences include home cooks, recipe collectors, Obsidian/local-first users, meal planners, nutrition-conscious users, existing users, and future paying customers.

## 4. Brand & Visual Direction
Warm technical aesthetic; real app imagery; restrained near-black, warm cream, and Codex green; strong typography and spacing; purposeful motion; accessibility by default.

Working tokens: `#171717` ink, `#F4EFE4` warm cream, `#3A6B51` Codex green, `#666666` muted gray.

## 5. Launch Information Architecture
P0/P1 surfaces: Home, Features, Nutrition, How It Works / Vault, Product Tour, Get Started / Download, FAQ, Docs, Changelog, About, Privacy/Terms. Pricing is future work.

## 6. Homepage Blueprint
Hero → real product proof → core workflow → vault ownership → nutrition → feature highlights → trust/quality → final CTA → footer.

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
Product truth, visual polish, accessibility, performance, SEO, security, reliability, content accuracy, and explicit release control.

## 11. Content & SEO
Benefits and workflows first; consistent terminology; concrete demonstrations; careful nutrition wording; precise AI descriptions; maintainable release-specific claims.

## 12. Hosting & Deployment
Cloudflare at the domain edge, small Hetzner Cloud production server, containerized deployment from GitHub, staging/preview, minimal exposed services, health checks, and rollback.

## 13. Success Measures
Clarity, meaningful navigation to Get Started/Download, real-world performance, trust, maintainability, and useful search/referral growth.

## 14. Deferred Decisions
Pricing, accounts, payments/licensing, final app distribution channels, newsletter/CRM, CMS, public API, community features, and complex personalization.

## 15. Immediate Next Actions
1. Create the dedicated website repository.
2. Inventory the approved logo and current app visual language.
3. Capture representative app screens.
4. Define the launch CTA.
5. Create homepage desktop/mobile wireframes and visual direction.
6. Reconcile website tokens with the app themes.
7. Begin technical implementation only after the homepage/design direction is approved.

## 16. Change Control
This is a living website roadmap. Changes to mission, major information architecture, hosting model, public product claims, or release authority should be recorded deliberately.

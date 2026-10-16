# The Kitchen Codex — Website Master Plan

**Domain:** kitchencodex.app
**Version:** 1.7
**Date:** October 16, 2026
**Project state:** Approved Coming Soon site preserved; Shiso private testing; AI-first nutrition and unified SHISO kitchen/Vault Intelligence roadmap approved as future direction, not claimed shipped
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
Primary audiences include home cooks, recipe collectors, people who save recipes from websites and social media, meal planners, nutrition-conscious users, privacy/ownership-minded users, mobile-first users who shop and cook away from a desktop, Obsidian users, users of other productivity/storage ecosystems, existing users, technical/open-source users, and future paying customers.

The site should not require a visitor to understand Markdown, YAML, frontmatter, local-first architecture, or Obsidian before understanding the product.

## 4. Brand & Visual Direction
Warm technical aesthetic; real app imagery; restrained near-black, warm cream, and Codex green; strong typography and spacing; purposeful motion; accessibility by default.

Working tokens: `#171717` ink, `#F4EFE4` warm cream, `#3A6B51` Codex green, `#666666` muted gray.

### Brand hierarchy
- **The Kitchen Codex** — product and primary brand.
- **Shiso** — the one AI companion inside The Kitchen Codex.
- **Advanced Nutrition** — a Kitchen Codex capability Shiso may invoke, not a separate companion.
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
Current Coming Soon sequence: approved hero → four product pillars → compact Shiso introduction → brand promise → early-access signup → Coming Soon CTA → footer. The full-launch blueprint below remains future planning; keep Shiso within the product story without letting it dominate.

Hero → real product proof → save/capture → Vault protection/ownership → plan/shop/cook → Basic Nutrition + Advanced Nutrition → integrations → feature highlights → trust/quality → final CTA → footer.

Working homepage narrative:
1. **Save what you love.**
2. **Protect it in The Kitchen Codex Vault.**
3. **Organize and plan from one place.**
4. **Shop and cook from the same system.**
5. **Understand recipes with nutrition that grows with you — Basic Nutrition free, Advanced Nutrition premium.**
6. **Connect the tools and services that fit your workflow.**

## 7. Technical Architecture
Current pre-launch implementation is a static `index.html` and token-based `styles.css`, with the existing Kit early-access signup. Preserve this lightweight foundation for the Coming Soon page. The framework and infrastructure choices below are earlier full-launch planning proposals, not a statement of the current hosting configuration; reconfirm before future implementation.

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
The following is retained full-launch planning, not a verified inventory of the live Coming Soon infrastructure. The initial messaging update was local-only. Sid separately approved committing, pushing and releasing it on October 9, 2026 through the existing GitHub-triggered automatic deployment. Hosting, Cloudflare settings, DNS and domain configuration remain outside this release.

Cloudflare at the domain edge, small Hetzner Cloud production server, containerized deployment from GitHub, staging/preview, minimal exposed services, health checks, and rollback.

GitHub Actions should remain lighter than the application pipeline: CI for formatting/lint/tests/build/accessibility where practical, optional preview deployment, and a production deployment workflow gated on clean CI. Passing automation never replaces explicit release authority.

## 13. Success Measures
Clarity, meaningful navigation to Get Started/Download, understanding of the Vault concept without needing Obsidian knowledge, strong engagement with product demonstrations, real-world performance, trust, maintainability, and useful search/referral growth.

Longer-term growth can also be measured through effective acquisition from integrations and recipe-capture workflows.

## 14. Deferred Decisions
Exact pricing, subscription packaging, accounts, payments/licensing, Kitchen Codex Cloud details, final app distribution channels, newsletter/CRM, CMS, public API, community features, specific social connectors, advanced cross-provider synchronization, complex personalization, the final balance between the labels “The Kitchen Codex Vault” and “My Recipe Vault,” and any public launch timing or packaging for Nutrient Tracking / Nutrition Diary.

## 15. Immediate Next Actions
For the current Coming Soon slice: local desktop/mobile review is complete and Sid has approved release. Commit and push the approved update through the existing automatic deployment, then verify the live page. Preserve the approved hero, “The recipes you love deserve a home.” The earlier full-launch actions below remain future planning.

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

## 18. Nutrition Product Strategy — AI-First Decision, October 16, 2026

**Product decision:** Shiso should lead recipe nutrition interpretation and estimates, using the Kitchen Codex's existing USDA catalog, deterministic tools, and trusted web sources as resources rather than as a gate that prevents any useful result when a source portion is unavailable. This replaces the older USDA-only authority assumption in this document. Sid remains final release authority.

### Basic Nutrition — Free, immediate usefulness
- One-click essential nutrition on the main recipe card and in the editor: calories, protein, carbohydrates, fat, and supported additional values, with a clear per-serving basis.
- Keep an offline/no-provider path so free Basic remains useful without Gemini availability or paid API calls.
- When coverage is partial, show known **subtotals** labeled as incomplete. Unknown nutrient totals remain unknown; genuine supported zeros stay zero. Do not make an incomplete subtotal look like a full recipe estimate.
- Shiso may optionally improve coverage through AI assistance where available and properly enabled, but that must not silently convert Basic into a paid dependency.
- Explicit user-directed save only; partial, estimated, and complete provenance must survive Markdown saving and reopening.

### Advanced Nutrition — Premium depth, AI-led reasoning
- Shiso considers the **whole recipe**: food identity, preparation, volume vs. count vs. weight, raw/cooked and edible-yield assumptions, brand-specific foods, and whether a wrapper or garnish is eaten.
- Shiso may use the authenticated pinned USDA catalog, existing calculator and matching tools, credible external food/brand/portion references through a safe research interface, and clearly identified AI inference. No single catalog's absence of an exact household portion should automatically block a reasonable estimate.
- Present ingredient evidence as **source-backed**, **source-informed estimated portion**, **AI-supported approximation**, or **unresolved/unknown**. Record the selected food, quantity assumption, source or reference where available, confidence, and nutrient basis.
- Distinguish the **nutritional estimate** from a laboratory measurement. Deterministic arithmetic, serving conversions, freshness checks, bounded inputs, transparent uncertainty, and explicit user Review / Apply / Save remain protections against silent corruption, not obstacles to AI interpretation.
- If no defensible basis exists for a specific value, mark it unknown rather than fabricate precision. The product aims to deliver the best supported useful result and a transparent explanation, not a guarantee of complete coverage for every conceivable ingredient.
- Use provider-neutral infrastructure, explicit consent and pricing guards for paid calls, safe/allowlisted or otherwise SSRF-resistant web retrieval, bounded requests, and provenance. **Web-backed nutrition lookup is a planned capability, not a currently verified shipped function.**

### Practical acceptance criteria
1. Ordinary recipes get a useful Basic estimate without navigating a dozen ingredient approval dialogs; partial contributions are visible rather than a blank panel.
2. Advanced can estimate a tortilla count from a documented typical weight when a USDA portion is absent; it never relabels that estimate as a USDA portion.
3. Food identity and units remain truthful: whole eggs are not mechanically separated meat; sour-orange **cups** are not fruit **yield counts**; raw/cooked and lean-only/lean-and-fat meat are not silently interchangeable.
4. Ingredient context matters: banana leaves used as a wrapper are not treated as edible banana, and non-eaten exclusions are disclosed/reviewable.
5. A provider failure must not erase completed work or claim a change that was not applied. Human browser tests, including Apply / Save / reopen in a disposable Vault, govern acceptance.

### Release and website language
Maintain the two-tier product direction (Basic free; Advanced premium) without announcing a paid plan, AI web search, broad SHISO capabilities, or an automatic full nutritional estimate as currently available before verification and release.

Public copy should be plain-language: **“Shiso is being built to help you understand what's in a recipe—using food data, relevant research and clearly explained estimates.”** The existing Coming Soon page retains its hero, approved illustration, early-access signup and private-testing disclaimer.

The prior direction—“AI only interprets while authenticated USDA portions alone determine every gram and nutrient”—is **superseded for future product architecture**. Provenance, safe tool execution, explicit saving, and accurate disclosure remain mandatory.

## 19. Multi-Surface Product Direction
The current product roadmap explicitly targets one shared Kitchen Codex core delivered through multiple surfaces:

- standalone desktop app
- official Obsidian plugin
- mobile/PWA companion
- optional native mobile wrapper later if PWA limitations justify it

The website should support this direction without making unshipped surfaces appear available.

Public launch copy should identify the surfaces that actually exist at the time of publication. Future surfaces may be described only in clearly labeled roadmap/future-product contexts.

Mobile is strategically important because shopping lists, recipe access, meal plans, Cooking Mode, quick add, and future nutrition logging are especially valuable away from the desktop.

The website architecture and responsive design should therefore avoid treating mobile as merely a smaller marketing viewport. The product story itself increasingly includes mobile use cases.

## 20. Future Feature Watch — Nutrient Tracking / Nutrition Diary
Nutrient Tracking / Nutrition Diary is now a deliberate future product track, conditional on the Advanced Nutrition Engine first meeting its release-quality accuracy, provenance, and coverage gates.

The intended direction is mobile-first, low-friction food logging built on nutrition profiles already known by Kitchen Codex. Potential future capabilities include one-tap “I ate this” logging, serving-aware macro and micronutrient tracking, daily/weekly summaries, meal-plan nutrition previews, repeat-meal shortcuts, history/trends, optional goals with non-medical framing, and provenance-aware logs.

This is a downstream premium/mobile opportunity, not a reason to rush or weaken the nutrition engine.

Website implications:
- Do **not** market nutrient tracking as a current feature until it ships.
- Do **not** let future tracking language make the product sound like a generic calorie-counting app.
- When the feature becomes real, position it as a natural extension of trusted recipe nutrition: Kitchen Codex already understands the recipe, so logging a serving should be simple.
- Preserve the distinction between Basic Nutrition, Advanced Nutrition, and future Nutrient Tracking.
- Any health/goal language must remain clearly non-medical and factually accurate.


## 21. Shiso Companion Decision — October 9, 2026

### Brand and conversation model
**Shiso** (SHISO in internal decision headings) is the official, first-class AI companion for the entire Kitchen Codex. The Kitchen Codex remains the product and primary brand; the Vault remains the recipe home; Advanced Nutrition remains a product capability.

One Shiso brain, one conversational interface, multiple contextual entry points. No separate recipe chatbot or nutrition chatbot. Preferred future language: **Chat with Shiso**, **Ask Shiso**, **Create with Shiso**. Future status examples: “Shiso is thinking…” and “Shiso found 3 recipes in your Vault.”

**Superseded terminology, retained here only as decision history:** “Ask This Recipe,” “Ask My Kitchen,” generic “Kitchen Codex AI” branding, and the separate “Create for me” concept are retired from the forward direction. Earlier nutrition terminology “AI Advanced Nutrition” is now **Advanced Nutrition**; its premium engine and two-tier nutrition strategy remain intact.

### Recipe creation
**Create with Shiso** replaces the separate **Create for me** entry point without removing recipe generation. It opens the same Shiso conversation in a recipe-creation context: “Make me a chicken pasta” → “Make it dairy free” → “Serve six” → “Make it spicier” → “Looks good. Save it.” Editing, refinement and saving use Kitchen Codex capabilities and their applicable review/apply controls. **New Recipe** can remain the manual creation path.

### Future capability direction
Shiso will understand requests and invoke Kitchen Codex capabilities for recipe creation and editing, Recipe Vault search, Advanced Nutrition, substitutions, collections, meal planning, shopping lists, leftovers, cooking assistance, timer workflows, and future product capabilities. This is roadmap direction, not a shipped-feature inventory or a launch-date commitment.

### Advanced Nutrition authority
**October 16 update supersedes the earlier USDA-only gate.** Shiso leads nutrition interpretation and may create clearly labeled estimates when supported source data or exact household portions are unavailable. Kitchen Codex tools continue to provide sourced nutrient evidence, reproducible math, validated state changes and user-controlled persistence. AI-generated assumptions are not misrepresented as measured USDA facts.

The intended flow is: Shiso interprets the full recipe → uses catalog and source research where applicable → proposes documented estimates for gaps → calculation and provenance layer checks and totals the evidence → user reviews, applies and explicitly saves.

This is a future implementation direction; availability of web research and full Advanced Nutrition AI estimates must be separately verified before public claims.

### Current website treatment
Introduce Shiso after the Preserve / Organize / Cook / Understand cards and before the brand promise. Keep The Kitchen Codex wordmark, hero copy, Vault illustration, four pillars, signup and primary visual system intact. The October 14 mascot decision supersedes the earlier no-mascot restriction; see section 22. Keep typography, hero, signup, and brand hierarchy intact.

Approved-for-local-review positioning: **Meet Shiso — Your Kitchen Codex companion.** Supporting copy explicitly says “We’re building” and “You’ll be able to.” The earlier short static conversation preview is superseded by the approved official SHISO mascot artwork, with a visible private-testing disclosure. No pretend chat inputs, buttons or live service claims.

Nutrition line: **“Shiso explores the ingredients. You see what's known—and what's estimated.”** Explain useful source-backed nutrition and clearly marked estimates, with user control over reviewing and saving. Never promise web research or complete estimates as shipped while under development.

Metadata keeps The Kitchen Codex / Recipe Vault as the primary identity and adds digital recipe organizer, meal planning, nutrition and the Shiso companion being built without keyword stuffing. All current public copy must distinguish planned functionality from available functionality; recheck claims at each release.

### Deferred visual work and release control
Sid explicitly approved the official SHISO mascot artwork on October 14, 2026. Future animation is separate phased work requiring subsequent implementation review. Preserve accessibility, responsiveness, contrast, reduced motion, semantic HTML and fast static loading. No extra JavaScript or dependencies for this introduction.

### Decision history
Version 1.4 records the Shiso decision and current Coming Soon implementation. Prior Vault ownership, integrations, mobile surfaces, nutrition investment, commercial decisions, future tracking gates and Sid’s release authority remain. Earlier Phase 0/full-launch planning is historical context, not a requirement to redesign the approved live hero. The update was prepared locally and reviewed uncommitted. Sid separately approved commit, push and the existing automatic deployment on October 9, 2026. Shiso remains unavailable; publishing the introduction does not release companion functionality.


---

## 22. Official SHISO Mascot Approval and Animation Phases — October 14, 2026

**Approved by Sid:** The generated leaf-inspired, charcoal-and-green floating culinary AI companion is the official visual mascot for Shiso. This supersedes the earlier October 9 design instruction to avoid creating a robot or mascot. Shiso remains subordinate to **The Kitchen Codex** product brand, not a separate product.

### Canonical visual direction

- **Signature character:** compact floating companion; glossy near-black face with friendly expressive green eyes and warm amber accents; shiso-leaf hood and leafy details; restrained gold framing.
- **Brand fit:** the existing near-black, warm cream and Codex green design remains authoritative; the mascot's brighter accent glow is contained within the illustration and should not recolor the entire website.
- **Approved source:** original user-approved SHISO concept illustration, generated October 14, 2026. The website derivative at `assets/shiso-official-mascot.webp` is an optimized crop of that approved artwork. Preserve the original for future animation and high-resolution brand assets.
- **Presentation:** character-led, warm, intelligent, premium and distinctive. Avoid generic robot, cartoon chef or childish expressions.

### M0 — Identity approval (DONE)

Official character approved; visual specifications and source concept captured. This is a branding milestone, not evidence of product functionality.

### M1 — Static website introduction (RELEASE APPROVED; VERIFY PRODUCTION)

Replace the Coming Soon page's older simulated chat concept with the official mascot image inside the existing "Meet Shiso" section. Preserve the approved hero headline, CSS recipe-card visual, four pillars, brand promise, Kit signup, metadata, and responsive/static architecture. The image is an illustration, **not** a screenshot or a live chat widget. Public copy must accurately describe private development/testing and must not claim general availability. No additional JavaScript.

### M2 — In-app animated SHISO companion (PLANNED, after reliability/performance acceptance)

Integrate a lightweight character in the shared Chat with Shiso surface with a static fallback and meaningful application-owned states: idle, thinking, investigating, responding, success, and clarification/error. Animations must react to real app activity, never imply nonexistent tool work. Provide `prefers-reduced-motion` support, avoid large sprite/video payloads, and do not block chat input or worsen provider latency. Measure CPU/memory and rendering cost on modest hardware. Prioritize fixing SHISO's human-test issues before animation.

### M3 — Website motion and storytelling (PLANNED)

Only after M1 is deployed, verified, and performance budgets are met, evaluate restrained, optional CSS-led character motion (gentle float/blink or purposeful state demonstrations). No automatic video, large animation libraries, continuous battery-hungry rendering, or inaccessible content. Preserve meaningful alt text and a motion-free representation.

### M4 — Extended character system (FUTURE)

Explore pose/expression sheets for onboarding, documentation, feature tours, social media, optional audio/voice, and future integrated Kitchen Codex surfaces. These are proposals, not shipping commitments.

### Release and quality gates

Sid retains final approval for mascot placement and production deployment. Website source changes are reviewed separately from the app's uncommitted SHISO implementation and Muse audit. Do not merge/deploy this website change solely because the asset is approved. Validate desktop/mobile layouts, asset loading, accessibility, SEO, static page behavior, and signup before release. Accurate capability language takes precedence over marketing enthusiasm.


## 23. AI-First Nutrition Decision and Current Testing — October 16, 2026

Sid approved **AI-first Shiso nutrition** as the future direction after real browser tests exposed USDA-portion dead ends and blank Basic panels. Retain and build on the local nutrition repairs; do not discard proven parsing, USDA, serving, schema-4 estimate and persistence work. Luna's consolidated functional repair is ongoing and remains uncommitted pending Sid's live acceptance. This website roadmap records product direction, **not** a claim that web research or unconstrained AI nutrition has shipped.

The current report says Basic can show labeled partial subtotals and save them with explicit acknowledgement, with sample coverage improvements in enchiladas, guacamole, Huevos Rancheros and Cochinita Pibil. Source nutrient gaps may still leave totals unknown. Those implementation claims require browser verification before promoting them to public-facing feature statements.

**Website treatment:** Update only the Shiso section's forward-looking explanation; preserve the approved hero, artwork, color system, signup and accessibility. Keep the site in **Coming Soon / private testing** status. A proposed source change must be reviewed and separately authorized for deployment; GitHub main triggers production deployment.



## 24. Unified SHISO Experiences and Vault Intelligence — October 16, 2026

**Approved product direction:** SHISO is the single AI companion throughout The Kitchen Codex. The app may expose multiple convenient entry points, but not separate competing chatbot identities or independent AI Settings. Preserve the existing useful subsystems, especially the **Vault Intelligence** dashboard and its real health percentage.

### Product experience and language

| Experience | Name / user story | Status and website treatment |
| --- | --- | --- |
| General help | **Chat with Shiso** — ask about cooking and recipes | Private development/testing; do not claim broad release |
| Recipe generation | **Create with Shiso** — make and refine a recipe in the same conversation, then explicitly save | Planned consolidation of the existing Create for Me capability; not a new shipped generator |
| Vault search | **Explore My Vault** — find real recipes by ingredient, tags, cuisine or time | Planned consolidation of Ask My Kitchen using real Vault search; not an invented AI search index |
| Nutrition | **Advanced Nutrition** is the premium feature; **Nutrition with Shiso** is its internal experience | Planned single Analyze Recipe flow, optional offline source pass, clear estimates and explicit Apply/Save |
| Vault integrity | **Vault Intelligence** — inspect Vault health %, formatting, metadata and repair suggestions | **Retain existing dashboard, scanner, health score and repair tools**; Shiso-operated workflows are planned, not shipped |

**Vault Intelligence brand rule:** Do not rename the dashboard to a generic AI chat or hide the existing **Vault Health %** display. Health remains a measured deterministic scanner result, not a judgment SHISO generates. Shiso may explain a real scan, identify affected recipes, and prepare previewable repairs, but writes require user authorization.

### Planned Vault Intelligence UX

- Health % remains prominent beside real last-scan state and issue summaries where supported by the app's measured data.
- Users can inspect why the score changed, review formatting/metadata issues by recipe, and distinguish safely mechanical fixes from ambiguous repairs.
- Future Shiso queries include “Why is my Vault health low?”, “Which recipes need formatting fixes?”, and “Prepare a repair preview.”
- Preserve exact recipe content and user edits; use previews, explicit confirmation, existing authorized Vault write paths, and a post-repair rescan.
- Batch repair is a future opt-in workflow requiring per-file transparency and recovery safeguards.
- No fabricated percentages, demo issue counts presented as real, hidden file writes or “automatically fixed your Vault” claims.

### Website information architecture and launch sequencing

The **approved static Coming Soon page is unchanged**. Retain its hero, four pillars, SHISO mascot, Kit signup, warm technical aesthetic, accessibility and metadata. Do not add Vault Health percentages or live SHISO operation widgets using demo values. This is a master-plan update only.

At full launch, show the real product first. A compact **Meet Shiso** story may introduce Create, Explore, Nutrition and Vault Intelligence as connected capabilities when individually verified. A later **Vault Intelligence** feature page can show a *real* score and authenticated screenshot, explain how health is measured and describe review-before-repair protections.

Proposed delivery priority mirrors the application plan:

1. Finish and browser-accept **Nutrition with Shiso** (Basic remains free/offline).
2. Stabilize provider-neutral conversation and the effective AI Settings selection.
3. Complete **Create with Shiso** with conversational draft refinement and explicit Save.
4. Complete **Explore My Vault** with grounded recipe results, then phase out redundant Ask My Kitchen entry.
5. Integrate **Vault Intelligence with Shiso**, preserving the dashboard, scoring, formatting corrections and metadata recovery; add safe preview/authorization, then opt-in batch repairs.
6. Test cross-capability flows before release. Defer unrelated animation and promotional promises.

**Release control:** Sid approves any actual launch/deployment. None of these product commitments establish that their Shiso integrations exist today. Current app work is substantially uncommitted in Luna's local checkout, and the application roadmap changes reside in a separate draft PR pending reconciliation. Website source and public claims change only after verified feature readiness and separate release approval.

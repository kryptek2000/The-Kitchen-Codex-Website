# The Kitchen Codex — Website Phase 0 Design Brief

**Domain:** kitchencodex.app  
**Phase:** 0 — Product & Design Foundation  
**Status:** Approved for design planning; implementation not started  
**Project:** The Kitchen Codex Website  
**Release authority:** Sid Richmond  
**Primary roadmap:** [Website Master Plan](Website-Master-Plan.md)

---

## Purpose

Phase 0 defines what the Kitchen Codex website must communicate, how it should feel, how visitors should move through it, and what must be decided before production implementation begins.

This phase is deliberately design-first. No production framework scaffold, component system, deployment pipeline, or large implementation slice should be treated as approved until the Phase 0 exit criteria are satisfied.

---

## Product Identity Principle

**The Kitchen Codex is the standalone product and brand.**

External platforms and storage providers are integrations beneath the product, not the product's identity.

**The Kitchen Codex Vault** is the product-level concept for the protected home where a user's recipes live.

“**My Recipe Vault**” may be used as a friendlier UI/onboarding label where appropriate.

A Vault may eventually live locally, connect to Obsidian, use Google Drive, use Kitchen Codex Cloud, or use future storage providers without changing the user's core mental model.

---

## Website Mission

The public website should make The Kitchen Codex understandable, desirable, and trustworthy within seconds.

A first-time visitor should quickly understand that The Kitchen Codex helps them save recipes they care about, protect them in one organized Vault, plan meals, build shopping lists, cook from the same system, and understand recipes through a nutrition experience that ranges from free Basic Nutrition to paid AI Advanced Nutrition.

The visitor should not need to understand Obsidian, Markdown, YAML, frontmatter, or local-first architecture to understand the product.

The site should communicate three core ideas:

1. **Your recipes remain yours.**
2. **The Kitchen Codex Vault is their protected home.**
3. **The Kitchen Codex turns that collection into a practical cooking system.**

---

## Primary Audiences

### Recipe collectors and home cooks
People who want a better way to organize recipes, plan meals, shop, cook, scale servings, and work with nutrition information.

### Social and web recipe collectors
People whose recipes are scattered across links, bookmarks, screenshots, saved social posts, videos, and recipe sites.

This is an important strategic growth audience.

### Meal planners and practical cooks
People who want the whole workflow connected: recipe → plan → shopping → cooking.

### Nutrition-conscious users
People who want understandable recipe nutrition without turning the app into a generic calorie tracker.

### Mobile-first cooks and shoppers
People who need recipes, shopping lists, meal plans, and Cooking Mode while away from a desktop. The roadmap now explicitly includes a mobile/PWA companion as a long-term product surface.

### Privacy- and ownership-minded users
People who prefer their data to remain portable, inspectable, backed up, and under their control.

### Obsidian users
A valuable ecosystem audience that may discover The Kitchen Codex through an Obsidian integration/plugin and then become broader app users or paying customers.

### Technical and open-source visitors
Developers, contributors, advanced users, reviewers, and people evaluating the project through GitHub.

---

## First-Impression Goal

Within roughly the first 5–10 seconds, a visitor should be able to answer:

- What is The Kitchen Codex?
- Why is it different from an ordinary recipe app?
- Where do my recipes live?
- Is it relevant to me?
- What should I do next?

The first screen should establish product identity before feature density or integration details.

The site should feel polished, capable, warm, modern, food-aware, technically trustworthy, calm, and premium without feeling corporate.

It should not feel like a generic AI startup, restaurant website, recipe blog, developer dashboard, Obsidian add-on, storage utility, or template full of decorative clutter.

---

## Core Positioning

**The Kitchen Codex turns your recipe collection into a complete cooking system built around your Vault.**

Supporting explanation:

Save recipes from the places you find them, protect them in The Kitchen Codex Vault, organize them, plan meals, build shopping lists, cook step by step, scale servings, and understand nutrition.

This is a working design anchor, not final launch copy.

Working brand lines include:

- **Protect the recipes you love in The Kitchen Codex Vault.**
- **Save it. Protect it. Organize it. Cook from it.**
- **One home for the recipes you collect, cook, and want to keep.**

---

## Homepage Content Hierarchy

### 1. Hero
- Kitchen Codex logo / wordmark
- concise standalone-product headline
- Vault/protection supporting message
- primary CTA
- secondary CTA
- real product screenshot or composed product visual

Avoid leading with Obsidian, Markdown, technical storage language, or AI.

### 2. Save What You Love
Introduce recipe capture/import.

Long-term design direction should support the idea that users can bring recipes in from multiple sources, including web and social channels as those connectors become real.

### 3. Protect It in The Kitchen Codex Vault
Explain the Vault in plain language:
- one organized home
- user control
- backup/storage flexibility
- provider-independent concept

Do not imply unshipped cloud/storage options are currently available.

### 4. Plan → Shop → Cook
Explain the relationship between:

**Vault → Planning → Shopping → Cooking**

### 5. Nutrition — Basic + AI Advanced
Show nutrition as a major pillar with a clear two-tier product story.

**Basic Nutrition — Free**
- useful everyday nutrition
- existing/imported nutrition where available
- deterministic nutrition behavior where applicable
- meaningful value without intentional crippling

**AI Advanced Nutrition — Paid**
- AI interprets messy real-world ingredient and portion language
- handles ambiguity that deterministic parsing alone cannot reliably resolve
- deterministic validation, USDA evidence, Kitchen Codex math, provenance/confidence, and explicit Review / Apply remain authoritative
- provider-neutral by design

Working public directions:

**AI interprets. Kitchen Codex verifies. You stay in control.**

**Nutrition that understands how recipes are actually written.**

The homepage should communicate the value difference clearly without exposing internal architecture terminology or implying that AI invents nutritional truth.

### 6. Product Experience
Use real application screenshots for:
- recipe library / recipe detail
- meal planner
- shopping list
- cooking mode / timers
- Advanced Nutrition
- Vault/storage/connectivity UI when mature enough

### 7. Integrations
Explain that The Kitchen Codex can connect to external tools without being defined by them.

Obsidian should be presented as an important integration and acquisition channel.

Future storage and import providers should only be named as supported once shipped.

### 8. Feature Depth
Possible supporting features:
- recipe import
- serving scaling
- favorites and search
- image handling
- nutrition
- metadata recovery
- vault intelligence
- print/export

### 9. Built for Real Cooking
Show practical workflows:
- save a recipe
- protect it in the Vault
- plan the week
- shop once
- cook without losing your place
- adjust servings
- understand nutrition
- keep the recipe library organized

### 10. Open Project / Trust Layer
Provide access to:
- GitHub
- documentation
- releases/changelog
- project status

### 11. Final CTA
Repeat the primary next action clearly.

---

## CTA Strategy

The site should have one obvious primary action and one lower-pressure secondary action.

Candidate primary CTAs:
- Get The Kitchen Codex
- Download The Kitchen Codex
- Get Started

Candidate secondary CTAs:
- See how it works
- View on GitHub
- Explore features
- Read the docs

A CTA must describe an action the visitor can actually complete.

---

## Launch Sitemap

Preferred launch pages:

- `/` — Home
- `/features` — Product features and workflows
- `/nutrition` — Basic Nutrition + AI Advanced Nutrition
- `/vault` or How It Works — The Kitchen Codex Vault concept
- `/docs` — Documentation entry point
- `/about` — Project identity and philosophy
- `/faq` — Common product and ownership questions

Likely supporting destinations:
- GitHub repository
- releases/changelog
- privacy information
- contact/support path

Deferred unless justified:
- pricing
- accounts
- billing
- hosted dashboard
- community forum
- large blog operation
- comparison pages
- advertising or affiliate surfaces
- specific social connector pages before those integrations ship
- Nutrient Tracking / Nutrition Diary pages before that future feature ships

---

## Visual Language

The target is **modern culinary utility** rather than rustic cookbook aesthetics or sterile enterprise software.

The design should balance:
- dark, high-quality application surfaces
- warm culinary cues
- strong typography
- generous spacing
- crisp product imagery
- restrained depth and motion

Initial color direction:
- near-black / charcoal foundation
- warm off-white or cream surfaces where useful
- one recognizable Kitchen Codex accent family
- functional semantic colors
- strong contrast

Typography should be contemporary, highly readable, and slightly editorial.

Use moderate corner radii, deliberate card boundaries, restrained shadows, subtle borders, and consistent spacing.

Avoid excessive glassmorphism and decorative UI that competes with screenshots.

---

## Product Imagery

Preferred asset order:

1. real app screenshots
2. composed product scenes
3. workflow diagrams
4. original Kitchen Codex illustrations
5. stock imagery only when specifically useful

Public screenshots should:
- come from a stable build
- contain non-sensitive sample data
- use consistent sizing and theme
- avoid debug UI
- avoid unfinished states
- be optimized for web
- include useful alt text

---

## Motion Principles

Use motion for:
- subtle entrance transitions
- screenshot emphasis
- hover/focus feedback
- lightweight section transitions

Avoid:
- continuous decorative movement
- scroll-jacking
- heavy parallax
- large animation payloads

Respect reduced-motion preferences.

---

## Responsive Design

The site must behave well on desktop, tablet, and phone.

Requirements:
- simple mobile navigation
- readable hero copy
- intentional screenshot cropping
- comfortable touch targets
- logical stacked content
- no horizontal overflow
- responsive typography
- predictable grid collapse

---

## Accessibility Baseline

Target WCAG 2.2 AA where applicable.

Design should support:
- semantic heading hierarchy
- keyboard navigation
- visible focus states
- sufficient contrast
- reduced motion
- meaningful alt text
- touch target sizing
- non-color-only status communication
- readable line lengths and text sizes

---

## Content Voice

Copy should be:
- clear
- confident
- human
- specific
- technically accurate
- easy to scan

Prefer user-facing words such as save, protect, organize, import, connect, sync, back up, plan, shop, cook, and understand.

Avoid:
- exaggerated AI claims
- fake urgency
- empty superlatives
- enterprise jargon
- unsupported claims
- unnecessary technical storage terminology
- pretending unfinished features or connectors exist

---

## Integration Strategy

### Obsidian
Obsidian is an important integration, not the parent brand.

The website should treat an Obsidian plugin/integration as a bridge that can bring Obsidian users into The Kitchen Codex ecosystem.

### Notion and other productivity tools
These may become useful import/sync integrations, but they are not assumed to be the primary commercial engine.

### Social recipe capture
Social recipe capture is a strategic growth direction because it addresses a broad consumer problem: recipes saved across many platforms become difficult to find and use.

Long-term product story:

**See a recipe anywhere → save it → normalize it → protect it in The Kitchen Codex Vault → plan → shop → cook → understand nutrition.**

Specific social platforms should only be advertised once their integrations are real and supportable.

---

## Technical Direction

Current preferred direction:

- Astro as primary framework
- React only where interactivity genuinely benefits
- componentized design tokens
- responsive image pipeline
- minimal client-side JavaScript
- Cloudflare in front of production infrastructure
- Hetzner as a viable hosting target
- GitHub-based CI/CD
- privacy-conscious analytics

These remain architecture decisions to confirm before implementation.

---

## Performance Principles

Avoid:
- giant hero video
- oversized screenshots
- excessive web fonts
- decorative JavaScript
- heavy animation libraries
- unnecessary third-party scripts

Performance is part of the visual experience.

---

## SEO Foundation

Support:
- one clear H1 per page
- descriptive titles and metadata
- clean URLs
- canonical metadata
- Open Graph assets
- sitemap
- robots controls
- structured data where appropriate
- accessible image descriptions

SEO should describe The Kitchen Codex as a standalone product while allowing specific integration pages to target ecosystem searches.

---

## Trust Principles

Claims involving these topics must be factually verified before launch:

- local-first behavior
- AI usage
- data handling
- privacy
- storage providers
- social connectors
- supported platforms
- download availability
- licensing
- pricing
- hosted services
- account requirements
- nutrition functionality

---

## Phase 0 Asset Checklist

Gather or approve:

- current Kitchen Codex logo source
- icon variants
- wordmark treatment
- favicon/app-icon direction
- core brand colors
- type direction
- 4–8 high-quality application screenshots
- preferred app theme for marketing screenshots
- social preview direction
- workflow diagrams if needed
- Vault visual/metaphor direction
- confirmed primary CTA destination

---

## Phase 0 Deliverables

1. this Design Brief
2. approved homepage hierarchy
3. approved launch sitemap
4. initial design tokens
5. typography direction
6. color direction
7. screenshot / visual asset plan
8. desktop homepage wireframe
9. mobile homepage wireframe
10. CTA decision or documented temporary state
11. implementation-ready component inventory
12. initial Vault messaging/terminology decision
13. explicit Phase 0 approval

---

## Initial Component Inventory

- SiteHeader
- SiteFooter
- Logo / BrandMark
- Navigation
- Button / CTA
- Hero
- SectionHeader
- ProductScreenshot
- FeatureCard
- FeatureGrid
- Workflow / StepSequence
- Vault / Protection section
- Integration section
- Callout
- FAQ
- FinalCTA
- SEO / metadata primitives

---

## Quality Gates

Before Phase 0 closes:

- homepage purpose is understandable
- positioning matches the real application
- The Kitchen Codex is clearly the parent brand
- Vault terminology is understandable without Obsidian knowledge
- sitemap is intentionally scoped
- visual direction matches the app
- CTAs are defined or explicitly deferred
- desktop and mobile hierarchy are agreed
- accessibility constraints are incorporated
- screenshot strategy is defined
- unfinished features, product surfaces, and connectors are not presented as available
- Basic Nutrition and AI Advanced Nutrition claims match the current product strategy and shipped capability
- Nutrient Tracking / Nutrition Diary remains clearly labeled as future/conditional until it ships
- mobile/PWA claims match the actual released product surface at publication time
- technical direction supports the design without needless complexity

---

## Phase 0 Exit Criteria

Phase 0 is complete only when Sid approves the product/design foundation.

The team must be able to answer clearly:

- who the site is for
- what the homepage communicates first
- what The Kitchen Codex Vault means
- how Basic Nutrition and AI Advanced Nutrition differ
- how Obsidian is positioned
- what pages launch
- what the site should look and feel like
- what the visitor's primary next action is
- which product visuals will be used
- what design constraints implementation must preserve

Only then should production scaffold and component implementation begin.

---

## Immediate Next Design Slice

**Homepage Direction + Design System v0.1**

That slice should produce:

- homepage wireframe
- hero concept
- initial Vault/protection messaging
- initial color tokens
- typography pairing
- navigation model
- button styles
- section rhythm
- screenshot framing treatment
- desktop + mobile composition

No production deployment is part of that slice.

---

## Governance

### Sid Richmond
Final authority for:
- visual approval
- product claims
- major scope decisions
- integration positioning
- release
- production deployment

### ChatGPT / OpenAI
Architecture, design planning, content structure, UX reasoning, implementation prompts, and review/referee role.

### DeepSeek
Primary implementation role once a design slice is authorized.

### Independent Auditor
Independent QA/review using the current approved lower-cost auditing workflow.

---

**Phase 0 principle:** Design the truth of the product beautifully before writing the site around it.


---

## Future Product Awareness — Mobile + Nutrient Tracking

Phase 0 should account for the current long-term product roadmap without turning future work into launch promises.

### Mobile/PWA companion
The Kitchen Codex roadmap now targets a mobile/PWA companion alongside the standalone desktop app and Obsidian plugin.

This matters to website design because several of the strongest real-world Kitchen Codex use cases are inherently mobile:
- shopping lists in the store
- recipe access in the kitchen
- meal-plan reference
- Cooking Mode
- quick add/import
- future nutrition logging

The website's visual system should eventually be able to showcase desktop and phone product surfaces together once those mobile surfaces are real.

### Nutrient Tracking / Nutrition Diary
Nutrient Tracking / Nutrition Diary is a future mobile-first premium opportunity that becomes eligible only after the AI Advanced Nutrition Engine meets its quality gates.

Potential future experience:
- one-tap “I ate this” logging from a known recipe or meal-plan entry
- serving-aware calories/macros
- supported micronutrients
- daily/weekly summaries
- repeat-meal shortcuts
- meal-plan nutrition previews
- provenance-aware nutrition history

Design rule: this future feature should **not** appear in launch hero copy, launch feature grids, or pricing claims until implemented and approved.

When it eventually ships, the positioning should emphasize the advantage of a recipe-aware system rather than generic calorie counting: the user's trusted Kitchen Codex recipe already has a serving-based nutrition profile, so logging that meal can be dramatically simpler.

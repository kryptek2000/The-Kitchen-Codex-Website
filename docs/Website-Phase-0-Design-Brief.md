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

## Website Mission

The public website should make The Kitchen Codex understandable, desirable, and trustworthy within seconds.

A first-time visitor should quickly understand that The Kitchen Codex is a recipe, meal-planning, shopping, cooking, and nutrition system centered on the user's own recipe collection and Obsidian vault.

The site should communicate three core ideas:

1. **Your recipes remain yours.**
2. **Your vault remains central.**
3. **The Kitchen Codex turns that collection into a practical cooking system.**

---

## Primary Audiences

### Obsidian users
People already comfortable with Markdown files, vaults, personal knowledge systems, and user-controlled data.

### Recipe collectors and home cooks
People who want a better way to organize recipes, plan meals, shop, cook, scale servings, and work with nutrition information.

### Privacy- and ownership-minded users
People who prefer their data to remain portable, inspectable, and under their control.

### Technical and open-source visitors
Developers, contributors, advanced users, reviewers, and people evaluating the project through GitHub.

---

## First-Impression Goal

Within roughly the first 5–10 seconds, a visitor should be able to answer:

- What is The Kitchen Codex?
- Why is it different from an ordinary recipe app?
- Is it relevant to me?
- What should I do next?

The first screen should establish product identity before feature density.

The site should feel polished, capable, warm, modern, food-aware, technically trustworthy, calm, and premium without feeling corporate.

It should not feel like a generic AI startup, restaurant website, recipe blog, developer dashboard, Obsidian clone, or template full of decorative clutter.

---

## Core Positioning

**The Kitchen Codex turns your recipe vault into a complete cooking system.**

Supporting explanation:

Organize recipes, plan meals, build shopping lists, cook step by step, scale servings, manage nutrition, and keep your recipe library in a format you control.

This is a working design anchor, not final launch copy.

---

## Homepage Content Hierarchy

### 1. Hero
- Kitchen Codex logo / wordmark
- concise headline
- short supporting paragraph
- primary CTA
- secondary CTA
- real product screenshot or composed product visual

### 2. The Core Idea
Explain the relationship between:

**Recipe Vault → Planning → Shopping → Cooking → Nutrition**

### 3. Product Experience
Use real application screenshots for:
- recipe library / recipe detail
- meal planner
- shopping list
- cooking mode / timers
- Advanced Nutrition
- vault integration / local files

### 4. Your Recipes, Your Vault
Explain local-first ownership and Markdown/Obsidian integration.

### 5. Feature Depth
Possible supporting features:
- recipe import
- serving scaling
- favorites and search
- image handling
- nutrition
- metadata recovery
- vault intelligence
- print/export

### 6. Built for Real Cooking
Show practical workflows:
- plan the week
- shop once
- cook without losing your place
- adjust servings
- keep the recipe library organized

### 7. Open Project / Trust Layer
Provide access to:
- GitHub
- documentation
- releases/changelog
- project status

### 8. Final CTA
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

Avoid:
- exaggerated AI claims
- fake urgency
- empty superlatives
- enterprise jargon
- unsupported claims
- pretending unfinished features exist

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

---

## Trust Principles

Claims involving these topics must be factually verified before launch:

- local-first behavior
- AI usage
- data handling
- privacy
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
12. explicit Phase 0 approval

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
- Trust / LocalFirst section
- Callout
- FAQ
- FinalCTA
- SEO / metadata primitives

---

## Quality Gates

Before Phase 0 closes:

- homepage purpose is understandable
- positioning matches the real application
- sitemap is intentionally scoped
- visual direction matches the app
- CTAs are defined or explicitly deferred
- desktop and mobile hierarchy are agreed
- accessibility constraints are incorporated
- screenshot strategy is defined
- unfinished features are not presented as available
- technical direction supports the design without needless complexity

---

## Phase 0 Exit Criteria

Phase 0 is complete only when Sid approves the product/design foundation.

The team must be able to answer clearly:

- who the site is for
- what the homepage communicates first
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

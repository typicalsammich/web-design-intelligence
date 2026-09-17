# Website Design Workflow

## Phase 1 — Discovery

Gather the real business name, offer, audience, geography when relevant, contact information, services/products, brand assets, photographs, reviews/evidence, competitors or references when available, and the site's primary conversion goal.

Separate verified facts from placeholders. Never invent social proof.

## Phase 2 — Creative directions

Before coding a substantial new site, develop 2–3 genuinely different possible directions internally. They must differ structurally, not merely by color.

Compare possibilities across:

- composition
- typography
- image treatment
- density and whitespace
- navigation/header behavior
- service/content presentation
- shape language
- motion/interaction language
- signature element

Choose the direction with the strongest fit to the business, audience, content, and conversion goal.

## Phase 3 — Creative brief

Record the selected direction using `project-start/CREATIVE-BRIEF.md`.

The brief is project-specific. Never permanently add its aesthetic choices to this repository's universal rules.

## Phase 4 — Design system

Define project tokens and rules for type, color, spacing, surfaces, buttons/links, imagery, iconography, motion, and responsive behavior.

Use UI/UX reference knowledge to broaden the option set. Do not blindly accept a database recommendation. Context and the creative brief remain authoritative.

## Phase 5 — Build

Build the real content hierarchy and all required pages. Keep components reusable where repetition is real, but do not force unrelated sections into one component pattern merely for code neatness.

For multi-page service/local-business sites, use useful page-specific compositions and content rather than cloning one page shell repeatedly.

## Phase 6 — Responsive pass

Inspect at minimum:

- narrow mobile
- wider mobile/tablet
- desktop

Check navigation, logo treatment, hero composition, text wrapping, tap targets, galleries, forms, sticky/fixed CTAs, footer, overflow, spacing, long content, and image crops.

Mobile is not approved by simply stacking desktop columns.

## Phase 7 — Distinctiveness review

Run `audits/UNIQUENESS-AUDIT.md` before the conventional QA audit. If the site fails, change the design itself rather than polishing symptoms.

## Phase 8 — Independent quality audit

Run `audits/QUALITY-AUDIT.md` and the current Vercel Web Interface Guidelines where accessible. Treat accessibility and broken behavior as hard failures.

## Phase 9 — Fix and re-check

Resolve meaningful findings. Re-render affected widths/states. A fix is not verified merely because the code was edited.

## Phase 10 — Delivery

Confirm:

- correct business/contact details
- no placeholder or fabricated claims
- working links/buttons/forms
- mobile and desktop verified
- metadata/SEO essentials present
- accessibility basics pass
- no obvious console/runtime errors
- visual thesis remains coherent
- uniqueness audit passes

Only then consider the site ready for GitHub/deployment.
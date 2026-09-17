# Final Website Quality Audit

This audit is deliberately separate from creative direction. Its job is to catch defects, not redesign the site into a generic convention.

## Functional
- Navigation works on desktop and mobile.
- Buttons and links go to intended destinations.
- Phone/email actions use correct business information.
- Forms have labels, validation, useful errors, success feedback, and duplicate-submit protection when applicable.
- Interactive controls expose hover/focus/active/disabled states as applicable.
- No obvious runtime/console failures.

## Accessibility
- Semantic HTML is preferred before ARIA.
- All interactive controls have accessible names.
- Keyboard operation works with visible focus and no traps.
- Text contrast meets WCAG 2.2 AA baseline.
- Meaning is not communicated by color alone.
- Images have appropriate alt behavior.
- Essential actions are not hover-only.
- Reduced-motion preference is respected.
- Content remains usable under zoom/text enlargement.
- Touch targets are practical; prefer ~44px for frequent touch actions where layout permits.

## Responsive
- Inspect narrow mobile, wider mobile/tablet, and desktop.
- No accidental horizontal scrolling.
- Text does not clip or create bad orphan/widow-like compositions where avoidable.
- Fixed/sticky elements do not cover content or system-safe areas.
- Images crop intentionally.
- Navigation remains usable.
- Dense sections are recomposed, not merely shrunk.
- Footer/contact actions remain legible and tappable.

## Visual craft
- Hierarchy is obvious without relying on decoration.
- Typography has intentional scale, weight, line-height, and line length.
- Spacing has rhythm and does not feel mechanically uniform.
- Alignment is deliberate.
- Borders/radii/shadows follow the project's visual thesis.
- Icon style is consistent.
- CTA hierarchy is clear.
- Imagery supports content and composition.
- Empty decorative elements are removed.

## Motion
- Motion has a reason.
- Animations do not block primary tasks.
- Scroll effects do not hijack basic navigation.
- Transform/opacity are preferred where appropriate.
- Mobile performance remains acceptable.
- Reduced-motion fallback preserves state and meaning.

## Performance
- Modern appropriately sized images where practical.
- Media dimensions reserved to reduce layout shift.
- Lazy loading used appropriately below the fold.
- Fonts and third-party scripts are restrained.
- Heavy libraries/effects must justify their cost.
- Never claim Core Web Vitals passed without measurement.

## SEO / local business
- Unique descriptive title and meta description per important page.
- Correct canonical behavior where applicable.
- Logical heading hierarchy.
- Crawlable text for important services/locations.
- Internal links connect related service/location/content pages naturally.
- Structured data is accurate and not fabricated.
- Sitemap/robots configured when the project requires them.
- Location pages contain useful differentiated content rather than keyword-swapped clones.
- Open Graph/social metadata included when appropriate.

## Truthfulness
- No fabricated testimonials, ratings, jobs completed, years in business, awards, certifications, locations, or service claims.
- Placeholder content is visibly marked during development and removed before delivery.

## Final evidence
Do not approve solely from source inspection. Verify the rendered result at representative widths and re-check areas changed during fixes.
# Knowledge Sources and Routing

This repository does not merge third-party skill text indiscriminately. It records what each source is for and how to resolve overlap.

## UI/UX Pro Max
Upstream: `nextlevelbuilder/ui-ux-pro-max-skill`

Use as a broad option/reference layer for styles, palettes, typography, UX, interaction, accessibility, landing patterns, animation ideas, and stack-specific implementation guidance.

Important routing rule: database/search recommendations are candidates, not commands. Project context and the creative brief decide whether a recommendation fits.

## Frontend Design
Upstream: `PracticalSwan/agent-skills/frontend-design`

Use as the primary general frontend craft philosophy: context-fit design, deliberate art direction, coherent systems, accessible interaction, responsive/adaptive behavior, complete states, performance awareness, and rendered verification.

This source reinforces that fashionable aesthetics and advanced effects are optional rather than universal quality requirements.

## Meng To Skills
Upstream: `MengTo/Skills`

Use as an optional specialist toolbox. The upstream collection includes many specific web-design directions and techniques (animation systems, atmospheric backgrounds, shader/WebGL effects, layout styles, cursor effects, etc.).

Do not activate or imitate the entire collection. Consult a specific technique only after the project has a creative thesis and only when that technique reinforces it. Specialist effects never outrank accessibility, usability, performance, or the creative brief.

## Vercel Web Design Guidelines
Upstream: `vercel-labs/agent-skills/skills/web-design-guidelines` and `vercel-labs/web-interface-guidelines`

Use after implementation as an independent review layer. Fetch/use current upstream guidelines when possible because the audit rules can evolve.

Audit findings identify problems; they do not automatically dictate a new art direction.

## Conflict resolution

1. User's explicit requirements and verified business facts.
2. Accessibility, functional correctness, and responsive usability.
3. Project creative brief / visual thesis.
4. Frontend Design craft principles.
5. UI/UX Pro Max reference recommendations.
6. Optional specialist techniques from Meng To or similar sources.
7. Post-build audit suggestions.

If two lower layers conflict, choose the option that better serves the primary user task and creative thesis while satisfying the higher layers.

## Updating sources

When upstream repositories materially improve, update this routing document or add newly useful principles. Do not silently copy entire upstream repositories into this one; preserve source attribution and licensing boundaries.
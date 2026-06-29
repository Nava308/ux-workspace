# UX Workspace — GITAM

## Stack
- React + Tailwind CSS
- Component output goes in `/components`

## Figma
- Always use Figma MCP for design context, never screenshots

## Conventions
- Component names must match Figma frame names exactly
- Use CSS variables for all colours and spacing tokens

---

## MANDATORY: Brand Guidelines Protocol

> **Before writing any design, component, UI copy, or making any visual decision — you MUST read the brand guidelines in full.**
> 1. **Primary (local):** `designs/BRAND_GUIDELINES.md` — always read this first
> 2. **Fallback (if local file is unavailable):** https://github.com/Nava308/ux-workspace/blob/main/designs/BRAND_GUIDELINES.md
> No exceptions. Do not rely on memory of past sessions.

This is not optional. If you are about to output any of the following, stop and read the brand guidelines first:
- A React component with any visual styling
- Colour values of any kind
- Font choices or text styling
- Logo usage or placement
- Image or icon decisions
- Any UI copy or written content

---

## GITAM Brand Rules — Enforced

### Colours
- **Only** use colours from the approved palette. Zero exceptions.
- Primary: `--color-gitam-green: #007367` · `--color-antique-white: #F4E4C9`
- Secondary: `--color-dark-green: #004740` · `--color-light-green: #8BCBB7` · `--color-antique-gold: #A58255` · `--color-beige: #CCBA8D`
- Tertiary: `--color-kind-coral: #DD736E` · `--color-mellow-yellow: #E0B541` · `--color-wide-blue: #5E95CD`
- Tertiary colours must NEVER exceed a 1:5 ratio vs primary — always pair with GITAM Green + Antique White, never standalone
- All colours MUST be declared as CSS variables — hardcoding hex values inline is forbidden
- When choosing a colour, consult the formal/casual and bold/subtle context map in `designs/BRAND_GUIDELINES.md` (fallback: https://github.com/Nava308/ux-workspace/blob/main/designs/BRAND_GUIDELINES.md)

### Typography
- Primary font: **Forma DJR Display** (Regular / Medium / Bold) — all UI, headings, display text
- Secondary font: **Inter** (Regular / Medium / Bold) — documents, slides, templates only
- **Never use any other font under any circumstance**

### Logo
- Default format: linear (horizontal) — always
- Stacked format: only when space is explicitly constrained
- Never rotate, distort, recolour, or apply effects to the logo
- Never place the logo over images or unapproved backgrounds
- Maintain minimum 2x clear space on all sides at all times
- Use only the 3 approved lockups: University / Cities / Basic Identity
- Never invent custom logo variations

### Imagery
- Must be positive, confident, cheerful, and well-lit
- Must align with the brand colour palette
- Never use cluttered, dark, or intimidating visuals

### Icons
- Always use circular enclosures
- Keep icons minimal and self-explanatory
- Reverse variant: Antique White icon on GITAM Green background

### Tone of Voice
- Active voice, short crisp sentences, contractions welcome (it's, we're)
- Optimistic and warm — never boastful, institutional, or vague
- Always back claims with specific numbers and facts
- Never use generic language — see the wrong-vs-right examples in `designs/BRAND_GUIDELINES.md` (fallback: https://github.com/Nava308/ux-workspace/blob/main/designs/BRAND_GUIDELINES.md)

---

## Violation Policy

If any of these rules are about to be broken, **stop and flag it explicitly** before proceeding. Do not silently substitute values or make your own judgement calls on brand decisions. Ask first.

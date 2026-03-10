---
name: figma-lore
description: >
  Expert Figma and UI design knowledge base covering components, auto layout,
  design systems, tokens, colour systems, iOS/Android specs, responsive design,
  mobile UX, and design system auditing. Use this skill whenever the user asks
  about Figma techniques, building components, design tokens, colour systems,
  iOS or Android design specs, responsive layouts, component architecture,
  design system governance, or any UI/UX design work in Figma. Also trigger for
  questions about dark mode design, multi-brand systems, slots, variants,
  auto layout patterns, or developer handoff. When in doubt, consult this skill
  — it contains deep Figma knowledge that significantly improves answer quality
  over relying on general knowledge alone.
---

# Figma Lore

A curated knowledge base of Figma best practices, design system architecture,
platform specs, and UX patterns. Built from real-world production experience.

## How to Use This Skill

1. **Identify the relevant module(s)** from the index below
2. **Read the applicable JSONL file** using the `view` tool
3. **Apply the entries** — each entry has an `id`, `tags`, and `d` (description)
   with actionable rules and values
4. For complex tasks, consult **multiple modules** (e.g. building an iOS
   component requires ios-design + components + auto-layout)

---

## Module Index

| File | Covers | Key IDs |
|------|--------|---------|
| `lore/00-figma-core.jsonl` | Frames, groups, layers, constraints, boolean ops, masks, export, shortcuts | fc-001 → fc-041 |
| `lore/01-auto-layout.jsonl` | Auto layout direction, sizing, padding, alignment, patterns, responsive | al-001 → al-035 |
| `lore/02-design-system.jsonl` | Token architecture, variables, theming, styles, spacing, colour palettes, colour systems, multi-brand | ds-001 → ds-056 |
| `lore/03-components.jsonl` | Component creation, variants, properties, slots, nesting, naming, architecture | cp-001 → cp-043 |
| `lore/04-ios-design.jsonl` | iPhone/iPad specs, safe areas, SF Pro, SF Symbols, HIG patterns | ios-001 → ios-050 |
| `lore/05-android-design.jsonl` | Material 3, Pixel specs, window classes, navigation, M3 components | an-001 → an-052 |
| `lore/06-responsive.jsonl` | Breakpoints, constraints, auto layout responsive patterns, pixel density | rs-001 → rs-030 |
| `lore/07-mobile-ux.jsonl` | Navigation, thumb zones, gestures, loading states, empty states, forms, dark mode | ux-001 → ux-035 |
| `lore/08-organization.jsonl` | File structure, library architecture, naming, versioning, governance, handoff | og-001 → og-027 |
| `lore/09-audit-optimization.jsonl` | Detached instances, hardcoded values, audit scripts, health score | au-001 → au-025 |
| `lore/10-execution-recipes.jsonl` | Step-by-step recipes for creating components, tokens, DS bootstrap, gotchas | ex-001 → ex-038 |

---

## Quick Topic Routing

**"Build a button / card / input / navbar component"**
→ Read `lore/10-execution-recipes.jsonl` (ex-004 to ex-010) + `lore/03-components.jsonl`

**"Set up design tokens / variables / colour system"**
→ Read `lore/02-design-system.jsonl` (ds-001 to ds-015 for tokens, ds-031 to ds-056 for colour)

**"Light and dark mode"**
→ Read `lore/02-design-system.jsonl` (ds-011, ds-012, ds-049 to ds-056) + `lore/07-mobile-ux.jsonl` (ux-031, ux-032)

**"Multi-brand colour system"**
→ Read `lore/02-design-system.jsonl` (ds-046 to ds-056)

**"Slots in Figma"**
→ Read `lore/03-components.jsonl` (cp-027, cp-027b, cp-028, cp-028b)

**"iOS screen / specs / components"**
→ Read `lore/04-ios-design.jsonl`

**"Android / Material 3 screen / specs"**
→ Read `lore/05-android-design.jsonl`

**"Auto layout / responsive layout / sizing"**
→ Read `lore/01-auto-layout.jsonl`

**"Audit a design system / find debt"**
→ Read `lore/09-audit-optimization.jsonl` + `lore/10-execution-recipes.jsonl` (ex-034, ex-035)

**"Organise a Figma file / library / governance"**
→ Read `lore/08-organization.jsonl`

**"Mobile gestures / UX patterns / empty states / forms"**
→ Read `lore/07-mobile-ux.jsonl`

**"Responsive breakpoints / pixel density / export"**
→ Read `lore/06-responsive.jsonl`

---

## Lore Entry Format

Each entry in the JSONL files follows this structure:
```json
{
  "id": "ds-046",
  "cat": "color",
  "t": "Title of the concept",
  "tags": ["searchable", "tags"],
  "d": "Full description with rules, values, and guidance.",
  "meta": { "optional": "extra data" }
}
```

Entries marked with **RULE:** contain hard requirements.
Entries with **meta.severity: high** are critical to follow.

---

## Key Design Principles (Always Apply)

- **Token chain is sacred**: Component → Semantic → Primitive. Never skip layers.
- **Auto layout everywhere**: 95%+ of components must use auto layout, never fixed positioning.
- **Name everything**: No default layer names (`Frame 1`, `Rectangle 3`). Ever.
- **Variables over hardcode**: All colours, spacing, and radii must use variables.
- **Mobile-first**: Design at 393×852 (iOS) or 412×915 (Android) as primary, scale up.
- **Touch targets**: 44×44pt minimum iOS, 48×48dp minimum Android. Non-negotiable.
- **WCAG AA**: 4.5:1 contrast for normal text, 3:1 for large text and UI components.

---

## Notes on Lore Updates

The colour system module (ds-046 → ds-056) covers the three-layer colour
architecture (Global → System → Component), neutral palette construction,
naming by usage type (fill/stroke/alt), dark elevated vs dark deep strategies,
plug-and-play neutral modules, and multi-brand scaling. These entries supplement
the existing token architecture entries (ds-001 → ds-015).

The slots entries (cp-027, cp-027b, cp-028, cp-028b) reflect the 2025 Figma
slots feature including constraints, use cases, and the decision guide for
slots vs variants vs instance swap.

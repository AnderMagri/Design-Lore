# FigmaMaster Lore

Machine-optimized knowledge base for AI-assisted Figma design work.
**429 records** across **11 modules** — **~265KB** total.

## Usage

When starting a Figma design session with Claude, reference this repo:

```
Use the FigmaMaster Lore at [repo-url] as your knowledge base for this design task.
Load the relevant modules for [ios/android/design-system/etc].
```

### Loading specific modules

```
Read the manifest.jsonl first, then load only the modules relevant to the task:
- For iOS app design: load 04-ios-design.jsonl + 07-mobile-ux.jsonl + 01-auto-layout.jsonl
- For Android app design: load 05-android-design.jsonl + 07-mobile-ux.jsonl + 01-auto-layout.jsonl
- For design system work: load 02-design-system.jsonl + 03-components.jsonl + 08-organization.jsonl
- For responsive web: load 06-responsive.jsonl + 01-auto-layout.jsonl + 00-figma-core.jsonl
- For DS audit/optimization: load 09-audit-optimization.jsonl + 02-design-system.jsonl + 03-components.jsonl
- For building components: load 10-execution-recipes.jsonl + 03-components.jsonl + 01-auto-layout.jsonl
```

## Modules

| File | Domain | Records | Size |
|------|--------|---------|------|
| `00-figma-core.jsonl` | Figma fundamentals: frames, groups, sections, layers, shortcuts | 41 | 25KB |
| `01-auto-layout.jsonl` | Auto layout: directions, sizing, spacing, grid, nesting | 35 | 16KB |
| `02-design-system.jsonl` | DS architecture: tokens, variables, styles, modes, governance | 45 | 34KB |
| `03-components.jsonl` | Components: properties, variants, nesting, slots, naming | 43 | 15KB |
| `04-ios-design.jsonl` | Apple HIG: device sizes, safe areas, SF Pro, touch, patterns | 50 | 26KB |
| `05-android-design.jsonl` | Material Design 3: sizes, Roboto, HCT color, shapes, elevation | 52 | 24KB |
| `06-responsive.jsonl` | Responsive: breakpoints, constraints, grids, adaptive patterns | 30 | 20KB |
| `07-mobile-ux.jsonl` | Mobile UX: navigation, gestures, accessibility, forms, loading | 35 | 26KB |
| `08-organization.jsonl` | File org: pages, naming, libraries, versioning, governance | 27 | 18KB |
| `09-audit-optimization.jsonl` | DS audit: detached instances, duplicates, hardcoded values, health score | 25 | 16KB |
| `10-execution-recipes.jsonl` | Tool recipes: section-first workflow, create components, tokens, screens, validation, gotchas | 46 | 24KB |
| **Total** | | **429** | **~265KB** |

## Format

JSONL (JSON Lines) — one JSON object per line, optimized for fast AI parsing:

```json
{"id":"al-001","cat":"direction","t":"Auto Layout Direction","tags":["auto-layout","direction"],"d":"...knowledge..."}
```

### Schema

| Field | Description |
|-------|-------------|
| `id` | Unique identifier (e.g., `al-001`, `ios-015`) |
| `cat` | Category within module |
| `t` | Short title |
| `tags` | Search/filter tags |
| `d` | Knowledge content (rules, specs, values) |
| `meta` | Optional metadata |

## Version

v1.3.0 — March 2026

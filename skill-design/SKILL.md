---
name: design-lore
description: >
  Expert design knowledge base covering design systems (token architecture,
  variables, theming, colour systems, multi-brand), iOS/Android platform specs
  (HIG, Material 3, safe areas, touch targets), responsive design, mobile UX
  (thumb zones, gestures, forms), Gestalt psychology, typography theory (kerning,
  type scale, variable fonts), colour theory (WCAG, harmonies, dark mode),
  behavioural design (Hick's Law, Fitts's Law, cognitive bias, dark patterns),
  38 art movements (Bauhaus to Bento Grid), design research (personas, JTBD,
  journey maps), UX strategy (HEART, RICE, Kano), interaction design (animation,
  gestures, state machines), prototyping, design ops, and UX writing. Trigger
  for design systems, tokens, colour, typography, platform specs, art direction,
  Gestalt, UX laws, research, strategy, or design process questions.
---

# Design Lore

Design theory, platform specs, perception, aesthetics, and the full design
process — everything that applies regardless of which design tool you use.

> **Part of the Design Lore family.** For Figma-specific mechanics (auto layout,
> components, file structure, auditing, recipes), use **figma-lore**. For deep
> UX psychology, use **design-lore-psychology**. For ecommerce and crypto/fintech
> UX, use **design-lore-industry**.

## How to Use This Skill

1. Identify the relevant module(s) from the index below
2. Read the applicable JSONL file using the view tool
3. Apply the entries — each entry has id, tags, title, and content
4. For complex tasks, consult multiple modules

---

## Module Index

### Design Systems & Platform Specs
| File | Covers | Key IDs |
|------|--------|---------|
| lore/02-design-system.jsonl | Token architecture, variables, theming, styles, spacing, colour palettes, colour systems, multi-brand, typography variables, responsive type modes | ds-001 → ds-048 |
| lore/04-ios-design.jsonl | iPhone/iPad specs, safe areas, SF Pro, SF Symbols, HIG patterns | ios-001 → ios-050 |
| lore/05-android-design.jsonl | Material 3, Pixel specs, window classes, navigation, M3 components | an-001 → an-052 |
| lore/06-responsive.jsonl | Breakpoints, constraints, auto layout responsive patterns, pixel density | rs-001 → rs-030 |
| lore/07-mobile-ux.jsonl | Navigation, thumb zones, gestures, loading states, empty states, forms, dark mode | ux-001 → ux-035 |

### Design Intelligence
| File | Covers | Key IDs |
|------|--------|---------|
| lore/11-gestalt-perception.jsonl | Gestalt laws (proximity, similarity, closure, continuity, figure-ground, symmetry, common fate, prägnanz), preattentive attributes, scanning patterns, heuristic evaluation | gp-001 → gp-016 |
| lore/12-typography-deep.jsonl | Type anatomy, classification, optical vs mechanical spacing, kerning, tracking, leading, type scale, alignment, measure, pairing, variable fonts, rendering, emotion, design system tokens, bold/weight variant naming | ty-001 → ty-015 |
| lore/13-colour-theory.jsonl | HSL/HSB, colour harmonies, temperature, contrast/WCAG, simultaneous contrast, colour psychology by hue, colour systems, palette construction, dark mode colour, light physics, branding, cultural context | ct-001 → ct-012 |
| lore/14-behavioural-design.jsonl | Mental models, cognitive load, Hick's Law, Fitts's Law, Jakob's Law, Miller's Law, anchoring bias, Peak-End Rule, endowment effect, variable rewards, dark patterns, ethical nudges, emotional design | bd-001 → bd-013 |
| lore/15-art-history-part1.jsonl | Renaissance, Baroque, Art Nouveau, Bauhaus, De Stijl/Constructivism, Art Deco, Swiss Style, Pop Art, Surrealism, Atomic/Space Age, Psychedelic/Acid, 70s, Punk/Zine, Memphis Group, Hyperrealism, Grunge/90s | ah-001 → ah-016 |
| lore/15-art-history-part2.jsonl | Manga/Anime, Kawaii, Yami Kawaii, Vaporwave, Cyberpunk, Pixel Art, Glitch Art, Skeuomorphism, Flat Design, Material Design, Neumorphism, Glassmorphism, Web Brutalism, Minimalism, Retrowave/Synthwave, Contemporary Japanese, Maximalism, 3D Illustration, Neo-Brutalism, Bento Grid, Biophilic Design, How to Apply Art History | ah-017 → ah-038 |

### Design Process
| File | Covers | Key IDs |
|------|--------|---------|
| lore/16-design-research.jsonl | Affinity diagrams, card sorting, diary studies, empathy maps, interview scripts, JTBD, journey maps, interview synthesis, usability test plans, user personas | dr-001 → dr-010 |
| lore/17-ux-strategy.jsonl | Competitive analysis, design briefs, design principles, experience maps, UX metrics (HEART framework), north star vision, opportunity frameworks (RICE, Kano), stakeholder alignment (RACI) | us-001 → us-008 |
| lore/18-interaction-design.jsonl | Animation principles (easing, duration, choreography), error handling UX, feedback patterns, gesture patterns, loading states (skeleton, optimistic UI), micro-interaction specs, state machines | ix-001 → ix-007 |
| lore/19-prototyping-testing.jsonl | A/B test design, accessibility testing, click tests, heuristic evaluation, prototype fidelity strategy, test scenarios, user flow diagrams, wireframe specifications | pt-001 → pt-008 |
| lore/20-design-ops.jsonl | Design critique, QA checklists, review processes, design sprints, developer handoff, team workflows, design version control | do-001 → do-007 |
| lore/21-designer-toolkit.jsonl | Case studies, design rationale, design system adoption, token audits, presentations, UX writing, data visualisation, illustration style, visual hierarchy | dt-001 → dt-009 |

---

## Quick Topic Routing

### Design Systems
**"Set up design tokens / variables / colour system"**
→ lore/02-design-system.jsonl (ds-001 to ds-015 for tokens, ds-031 to ds-045 for colour)

**"Typography variables / responsive type / font modes"**
→ lore/02-design-system.jsonl (ds-046, ds-047, ds-048) + lore/12-typography-deep.jsonl

**"Light and dark mode"**
→ lore/02-design-system.jsonl (ds-049 to ds-056) + lore/13-colour-theory.jsonl (ct-009) + lore/07-mobile-ux.jsonl (ux-031, ux-032)

**"Multi-brand colour system"**
→ lore/02-design-system.jsonl (ds-046 to ds-056) + lore/13-colour-theory.jsonl (ct-007, ct-008)

### Platform Specs
**"iOS / Android specs"** → lore/04-ios-design.jsonl or lore/05-android-design.jsonl

### Typography
**"Kerning / optical spacing"** → lore/12-typography-deep.jsonl (ty-003, ty-004)
**"Type scale / hierarchy"** → lore/12-typography-deep.jsonl (ty-006, ty-014) + lore/21-designer-toolkit.jsonl (dt-009)
**"Font pairing"** → lore/12-typography-deep.jsonl (ty-009, ty-013)
**"Accessible type"** → lore/12-typography-deep.jsonl (ty-011, ty-012)
**"Variable fonts"** → lore/12-typography-deep.jsonl (ty-010)
**"Bold / SemiBold body text style naming"** → lore/12-typography-deep.jsonl (ty-015)

### Colour
**"Colour system / tokens"** → lore/13-colour-theory.jsonl (ct-007, ct-008) + lore/02-design-system.jsonl (ds-046→ds-056)
**"WCAG contrast"** → lore/13-colour-theory.jsonl (ct-004)
**"Colour psychology / brand"** → lore/13-colour-theory.jsonl (ct-006, ct-011, ct-012)
**"Colour harmony / palette"** → lore/13-colour-theory.jsonl (ct-002, ct-008)

### Perception & Psychology
**"Gestalt / visual hierarchy"** → lore/11-gestalt-perception.jsonl (gp-001 → gp-009) + lore/21-designer-toolkit.jsonl (dt-009)
**"Heuristic evaluation"** → lore/11-gestalt-perception.jsonl (gp-013, gp-014, gp-015) + lore/19-prototyping-testing.jsonl (pt-004)
**"Cognitive bias / conversion"** → lore/14-behavioural-design.jsonl (bd-007 to bd-010)
**"Dark patterns / ethics"** → lore/14-behavioural-design.jsonl (bd-011, bd-012)
**"UX laws"** → lore/14-behavioural-design.jsonl (bd-003 to bd-006)
**"Emotional design"** → lore/14-behavioural-design.jsonl (bd-013)

### Art & Aesthetic Direction
**"What style for this brand/product"** → lore/15-art-history-part1.jsonl + lore/15-art-history-part2.jsonl (ah-038 for framework)
**"Bauhaus / Swiss Style / modernism"** → lore/15-art-history-part1.jsonl (ah-004, ah-007)
**"Japanese aesthetics / Kawaii / Manga / Vaporwave"** → lore/15-art-history-part2.jsonl (ah-017 to ah-021)
**"Pixel art / Glitch art / retro digital"** → lore/15-art-history-part2.jsonl (ah-022, ah-023, ah-031)
**"Current UI trends (Glass, Bento, Brutalism, Minimal)"** → lore/15-art-history-part2.jsonl (ah-025→ah-030, ah-035, ah-036)
**"Luxury / premium aesthetic"** → lore/15-art-history-part1.jsonl (ah-002, ah-006)
**"Retro / vintage"** → lore/15-art-history-part1.jsonl (ah-010, ah-012) + lore/15-art-history-part2.jsonl (ah-031)
**"Wellness / organic / nature"** → lore/15-art-history-part1.jsonl (ah-003) + lore/15-art-history-part2.jsonl (ah-037)

### Design Research
**"User personas / archetypes"** → lore/16-design-research.jsonl (dr-010)
**"Journey map / experience map"** → lore/16-design-research.jsonl (dr-007) + lore/17-ux-strategy.jsonl (us-004)
**"Empathy map"** → lore/16-design-research.jsonl (dr-004)
**"Interview script / user interview"** → lore/16-design-research.jsonl (dr-005, dr-008)
**"Jobs-to-be-done / JTBD"** → lore/16-design-research.jsonl (dr-006)
**"Card sort / information architecture"** → lore/16-design-research.jsonl (dr-002)
**"Usability testing / test plan"** → lore/16-design-research.jsonl (dr-009) + lore/19-prototyping-testing.jsonl (pt-006)
**"Diary study / longitudinal research"** → lore/16-design-research.jsonl (dr-003)
**"Affinity diagram / synthesis"** → lore/16-design-research.jsonl (dr-001)

### UX Strategy
**"Competitive analysis / benchmarking"** → lore/17-ux-strategy.jsonl (us-001)
**"Design brief / project framing"** → lore/17-ux-strategy.jsonl (us-002)
**"Design principles"** → lore/17-ux-strategy.jsonl (us-003)
**"UX metrics / KPIs / HEART"** → lore/17-ux-strategy.jsonl (us-005)
**"North star / product vision"** → lore/17-ux-strategy.jsonl (us-006)
**"Prioritisation / RICE / Kano"** → lore/17-ux-strategy.jsonl (us-007)
**"Stakeholder alignment / RACI"** → lore/17-ux-strategy.jsonl (us-008)

### Interaction Design
**"Animation / motion design / easing"** → lore/18-interaction-design.jsonl (ix-001)
**"Error handling / error messages"** → lore/18-interaction-design.jsonl (ix-002)
**"Feedback patterns / toasts / notifications"** → lore/18-interaction-design.jsonl (ix-003)
**"Gestures / touch / swipe patterns"** → lore/18-interaction-design.jsonl (ix-004)
**"Loading states / skeleton / optimistic UI"** → lore/18-interaction-design.jsonl (ix-005)
**"Micro-interactions"** → lore/18-interaction-design.jsonl (ix-006)
**"State machines / UI states"** → lore/18-interaction-design.jsonl (ix-007)

### Prototyping & Testing
**"A/B testing / experimentation"** → lore/19-prototyping-testing.jsonl (pt-001)
**"Accessibility testing"** → lore/19-prototyping-testing.jsonl (pt-002)
**"Click test / findability"** → lore/19-prototyping-testing.jsonl (pt-003)
**"Prototype fidelity / strategy"** → lore/19-prototyping-testing.jsonl (pt-005)
**"User flows / flow diagrams"** → lore/19-prototyping-testing.jsonl (pt-007)
**"Wireframes / wireframe spec"** → lore/19-prototyping-testing.jsonl (pt-008)

### Design Ops
**"Design critique / feedback session"** → lore/20-design-ops.jsonl (do-001)
**"Design QA / implementation check"** → lore/20-design-ops.jsonl (do-002)
**"Design review process / gates"** → lore/20-design-ops.jsonl (do-003)
**"Design sprint"** → lore/20-design-ops.jsonl (do-004)
**"Developer handoff"** → lore/20-design-ops.jsonl (do-005)
**"Team workflow / rituals"** → lore/20-design-ops.jsonl (do-006)
**"Design version control"** → lore/20-design-ops.jsonl (do-007)

### Designer Toolkit
**"Case study / portfolio"** → lore/21-designer-toolkit.jsonl (dt-001)
**"Design rationale / decision docs"** → lore/21-designer-toolkit.jsonl (dt-002)
**"Design system adoption"** → lore/21-designer-toolkit.jsonl (dt-003)
**"Token audit"** → lore/21-designer-toolkit.jsonl (dt-004)
**"Design presentation / deck"** → lore/21-designer-toolkit.jsonl (dt-005)
**"UX writing / microcopy"** → lore/21-designer-toolkit.jsonl (dt-006)
**"Data visualisation / charts"** → lore/21-designer-toolkit.jsonl (dt-007)
**"Illustration style"** → lore/21-designer-toolkit.jsonl (dt-008)
**"Visual hierarchy"** → lore/21-designer-toolkit.jsonl (dt-009)

---

## Key Design Principles (Always Apply)

- **Mobile-first**: Design at 393×852 (iOS) or 412×915 (Android) as primary.
- **Touch targets**: 44×44pt iOS, 48×48dp Android. Non-negotiable.
- **WCAG AA**: 4.5:1 contrast for normal text, 3:1 for large text and UI components.
- **Gestalt before pixels**: Every layout decision answers to gestalt principles first.
- **Type scale not arbitrary sizes**: Every type size belongs to a defined scale.
- **Colour has meaning**: Every colour token has semantic intent, not just aesthetic preference.
- **Art history is a library**: Every aesthetic direction has historical precedent — know what you're referencing.
- **Research before design**: Ground decisions in user evidence, not assumptions.
- **Document the why**: Every major design decision needs rationale, not just the what.

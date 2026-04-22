---
name: design-lore-industry
description: >
  Industry-specific UX knowledge base for ecommerce and crypto/fintech design.
  Covers Shopify UX (conversion benchmarks, product page anatomy, ATC button,
  checkout flow, cart abandonment, mobile commerce, thumb zones, trust signals,
  collection pages, filtering, custom page performance, breakpoints, Figma grid
  setup, product card dimensions, mobile/desktop frame setup, DS readiness), and crypto/fintech
  UX (wallet design, seed phrases, self-custody, exchange trading interfaces,
  DeFi protocols, gas fees, slippage, fiat on-ramp/off-ramp, KYC onboarding,
  fintech dashboards, investment portfolios, credit card UX, trust and security,
  proof of reserves, high-stakes error states, WalletConnect, dApp auth).
  Trigger for Shopify, ecommerce, conversion, product pages, checkout, crypto,
  Web3, DeFi, fintech, wallet, exchange, banking app, or neobank questions.
---

# Design Lore — Industry

Specialised UX modules for ecommerce (Shopify) and crypto/fintech design.
Real-world conversion data, platform-specific patterns, and high-stakes
interaction design for financial products.

> **Part of the Design Lore family.** This module covers industry-specific UX.
> For core Figma and design knowledge, use **design-lore**. For deep UX
> psychology and theory, use **design-lore-psychology**.

## How to Use This Skill

1. Identify whether the question is ecommerce or crypto/fintech
2. Read the applicable entries from the relevant module
3. Cross-reference with core design-lore modules when needed (e.g. mobile UX,
   behavioural design)
4. Apply audit flags at the end of each entry to check for common failures

---

## Module Index

### Ecommerce UX
| File | Covers | Key IDs |
|------|--------|---------|
| lore/23-ecommerce-ux.jsonl | Shopify conversion benchmarks, product page anatomy, ATC button UX, checkout flow & abandonment, conversion psychology (Cialdini applied), mobile commerce (thumb zones, touch targets), custom page section architecture, trust signals hierarchy, collection page UX (filtering, grid, breadcrumbs), custom page performance (Core Web Vitals), Shopify breakpoints (750px mobile cutoff), Figma grid setup per breakpoint (390/768/1440), product card pixel dimensions, mobile frame setup (header/safe area/sticky ATC), desktop frame setup (1440px frame / 1200px container), Shopify DS readiness checklist | ec-001 → ec-015 |

### Crypto & Fintech UX
| File | Covers | Key IDs |
|------|--------|---------|
| lore/24-crypto-fintech-ux.jsonl | Crypto UX core challenges & design philosophy, KYC onboarding & verification, exchange trading interfaces, wallet UX & seed phrase management, fiat on-ramp/off-ramp, DeFi platform UX (gas, slippage, approvals), fintech app dashboards & security, investment portfolio display, credit card & card product UX, trust signals & post-FTX considerations, high-stakes error states, WalletConnect & dApp authentication | cf-001 → cf-012 |

---

## Quick Topic Routing

### Ecommerce UX
**"Shopify conversion / CRO / benchmarks"** → lore/23-ecommerce-ux.jsonl (ec-001)
**"Product page / product detail page"** → lore/23-ecommerce-ux.jsonl (ec-002)
**"Add to cart button / ATC UX"** → lore/23-ecommerce-ux.jsonl (ec-003)
**"Checkout flow / cart abandonment"** → lore/23-ecommerce-ux.jsonl (ec-004)
**"Conversion psychology / social proof / scarcity"** → lore/23-ecommerce-ux.jsonl (ec-005)
**"Mobile commerce / mobile shopping"** → lore/23-ecommerce-ux.jsonl (ec-006)
**"Shopify page architecture / section order / homepage"** → lore/23-ecommerce-ux.jsonl (ec-007)
**"Trust signals / reviews / ecommerce trust"** → lore/23-ecommerce-ux.jsonl (ec-008)
**"Collection page / product grid / filtering"** → lore/23-ecommerce-ux.jsonl (ec-009)
**"Shopify performance / page speed / Core Web Vitals"** → lore/23-ecommerce-ux.jsonl (ec-010)
**"Shopify breakpoints / 750px / responsive"** → lore/23-ecommerce-ux.jsonl (ec-011)
**"Shopify grid / Figma columns / product card sizes"** → lore/23-ecommerce-ux.jsonl (ec-012)
**"Shopify mobile frame / header / safe area / sticky ATC"** → lore/23-ecommerce-ux.jsonl (ec-013)
**"Shopify desktop frame / 1440px / 1200px container"** → lore/23-ecommerce-ux.jsonl (ec-014)
**"Shopify design system checklist / DS readiness"** → lore/23-ecommerce-ux.jsonl (ec-015)

### Crypto & Fintech UX
**"Crypto UX / Web3 design / blockchain UX"** → lore/24-crypto-fintech-ux.jsonl (cf-001)
**"Crypto onboarding / KYC / verification"** → lore/24-crypto-fintech-ux.jsonl (cf-002)
**"Exchange trading / order book / trading interface"** → lore/24-crypto-fintech-ux.jsonl (cf-003)
**"Wallet UX / seed phrase / self-custody"** → lore/24-crypto-fintech-ux.jsonl (cf-004)
**"On-ramp / off-ramp / fiat to crypto"** → lore/24-crypto-fintech-ux.jsonl (cf-005)
**"DeFi UX / gas fees / slippage / liquidity"** → lore/24-crypto-fintech-ux.jsonl (cf-006)
**"Fintech app / banking UX / neobank"** → lore/24-crypto-fintech-ux.jsonl (cf-007)
**"Investment portfolio / stock app / portfolio display"** → lore/24-crypto-fintech-ux.jsonl (cf-008)
**"Credit card UX / card management / rewards"** → lore/24-crypto-fintech-ux.jsonl (cf-009)
**"Crypto trust / security UX / proof of reserves"** → lore/24-crypto-fintech-ux.jsonl (cf-010)
**"Financial error states / high-stakes errors"** → lore/24-crypto-fintech-ux.jsonl (cf-011)
**"WalletConnect / dApp / Web3 authentication"** → lore/24-crypto-fintech-ux.jsonl (cf-012)

---

## Key Principles

- **Trust before conversion**: In ecommerce and fintech, trust signals must precede any conversion ask.
- **Irreversibility demands friction**: The higher the stakes (money, crypto), the more confirmation steps are justified.
- **Fees before commitment**: Never surprise users with costs after they've committed to an action.
- **Clarity over aesthetics**: In financial products, every ambiguous element is a potential anxiety trigger.
- **Error prevention over error recovery**: In high-stakes domains, preventing mistakes is always better than recovering from them.

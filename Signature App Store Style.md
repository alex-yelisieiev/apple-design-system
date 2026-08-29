---
title: Signature App Store Style
tags:
  - design
  - ios
  - app-store
  - materials
aliases:
  - App Store callout
  - iOS feature card
  - signature appstore style
created: 2026-08-09
---

# Signature App Store Style

Reusable recipe for an **iOS App Store–vernacular feature card** as a foreign blue accent against a greyscale + signal-green brand system.

> [!abstract] Intent
> One screenshot-worthy object that reads instantly as “Apple / App Store,” without pasting a real App Store UI kit. Tokens come from the vault’s [[MacOS Design System/Colors|Colors]] + [[MacOS Design System/Materials|Materials]]; composition is App Store feature-card vernacular.

## Sources

| Layer | Source |
| --- | --- |
| System blue | [[MacOS Design System/Colors]] — `#0088FF`, `#0091FF` primary / vibrant blue |
| Radius + glass | [[MacOS Design System/Materials]] — liquid glass large `border-radius: 34px`, `blur(15px)`, soft `0 8px 40px` shadow |
| Type stack | SF Pro / `-apple-system` (same as MacOS DS text styles) |
| Layout vernacular | App Store feature / promo card: icon tile + eyebrow + title |

## Placement (composition)

> [!tip] Why bottom-right of the hero
> Keep **brand** as the top/hero signal. Park the blue card **beside the copy + CTAs**, bottom-aligned — asymmetric tension without the nav. Avoid top-right absolute; it competes with the brand.

```
hero-inner
├── hero-brand
└── hero-main          ← flex, space-between, align-items: flex-end
    ├── hero-copy      ← left
    └── appstore-callout ← right, ~30rem
```

- Desktop: `flex` row, callout on the right
- ≤900px: column stack, callout full-width under CTAs

## Structure (markup)

```html
<aside class="appstore-callout" role="status" aria-label="Coming soon">
  <div class="appstore-callout-glass" aria-hidden="true"></div>
  <div class="appstore-callout-icon" aria-hidden="true">
    <!-- simple phone glyph; avoid Apple logo trademark -->
  </div>
  <div class="appstore-callout-copy">
    <span class="appstore-callout-eyebrow">Coming Soon</span>
    <span class="appstore-callout-title">Expanding to iOS development soon</span>
  </div>
</aside>
```

## Token palette

```css
--appstore-blue: #0088ff;      /* MacOS system blue */
--appstore-blue-mid: #0091ff;  /* Materials primary tint */
--appstore-blue-deep: #0066d6; /* depth stop for vertical wash */
```

## Applied CSS (canonical)

### Shell — liquid glass + blue wash

```css
.appstore-callout {
  position: relative;
  z-index: 2;
  display: grid;
  grid-template-columns: auto 1fr;
  align-items: center;
  gap: 1.15rem 1.35rem;
  flex: 0 1 30rem;
  width: min(100%, 30rem);
  padding: 1.55rem 1.65rem 1.6rem;
  isolation: isolate;
  overflow: hidden;
  border: 1px solid rgba(255, 255, 255, 0.22);
  border-radius: 34px; /* Materials liquid-glass large */
  background:
    linear-gradient(165deg, rgba(255, 255, 255, 0.28) 0%, rgba(255, 255, 255, 0) 38%),
    linear-gradient(180deg, var(--appstore-blue-mid) 0%, var(--appstore-blue) 48%, var(--appstore-blue-deep) 100%);
  box-shadow:
    0 8px 40px rgba(0, 68, 160, 0.38),
    0 2px 8px rgba(0, 40, 100, 0.22),
    inset 0 1px 0 rgba(255, 255, 255, 0.38),
    inset 0 -1px 0 rgba(0, 40, 110, 0.2);
  color: #ffffff;
  font-family:
    -apple-system, BlinkMacSystemFont,
    "SF Pro Text", "SF Pro",
    "Helvetica Neue", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  transform: translateZ(0);
}
```

### Glass overlay (Materials)

```css
.appstore-callout-glass {
  position: absolute;
  inset: 0;
  border-radius: inherit;
  background: rgba(255, 255, 255, 0.08);
  background-blend-mode: screen;
  backdrop-filter: blur(15px) saturate(1.35);
  -webkit-backdrop-filter: blur(15px) saturate(1.35);
  pointer-events: none;
  z-index: 0;
}
```

### App-icon tile (squircle)

```css
.appstore-callout-icon {
  display: grid;
  place-items: center;
  width: 4.25rem;
  height: 4.25rem;
  border-radius: 22.5%; /* iOS icon continuous-corner approximation */
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.34) 0%, rgba(255, 255, 255, 0.08) 100%),
    rgba(255, 255, 255, 0.16);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.55),
    inset 0 -1px 0 rgba(0, 50, 120, 0.18),
    0 4px 14px rgba(0, 40, 100, 0.2);
  color: #ffffff;
}
```

### Type hierarchy

```css
.appstore-callout-eyebrow {
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.78);
}

.appstore-callout-title {
  font-size: clamp(1.28rem, 1.1rem + 0.85vw, 1.65rem);
  font-weight: 700;
  letter-spacing: -0.03em;
  line-height: 1.15;
  text-wrap: pretty;
}
```

## Tricks checklist

> [!success] Do these
> - **Two stacked backgrounds:** top-left white sheen + vertical blue wash — reads like Apple gloss, not flat fill
> - **Inset highlights + dark heel:** top inset white, bottom inset deep blue — sells thickness
> - **Outer blue-tinted shadow** (not neutral black only) so the card glows on dark heroes
> - **`isolation: isolate` + glass layer behind content** so blur/blend doesn’t muddy the type
> - **`border-radius: 34px`** (Materials large) — not a pill (`999px`) and not a hard 8–12px card
> - **Icon at `22.5%` radius** — cheap squircle stand-in for iOS app icons
> - **SF Pro / system stack only on this object** — foreign accent vs brand fonts (Syne / DM Sans)
> - **No Apple logo** — phone glyph is enough; avoids trademark issues
> - **`role="status"`** for a non-interactive announcement
> - **Bigger size (~30rem)** so it feels like a feature card, not a chip

> [!warning] Avoid
> - Top-right absolute under the nav — fights brand hierarchy
> - Pill / `border-radius: 999px` — that’s GET-button vernacular, not a feature card
> - Pure `#007AFF` flat fill with no glass/sheen — looks like a Bootstrap badge
> - Brand display font on this card — breaks the App Store read
> - Dropping it into the expertise section after designing it as a hero signature — loses the foreign-accent punch

## Responsive notes

| Breakpoint | Behavior |
| --- | --- |
| >900px | Row with copy; callout `flex: 0 1 30rem` on the right |
| ≤900px | Column; callout `width: 100%` under CTAs |
| ≤520px | Slightly tighter padding; radius `28px`; icon `3.5rem` |

## Motion

Include `.appstore-callout` in the hero intro stagger (with kicker / headline / lede / CTA), same `expo.out` family — arrives as part of the first-viewport choreography, not a late scroll reveal.

## Related

- [[MacOS Design System/Materials]]
- [[MacOS Design System/Colors]]
- [[MacOS Design System/Text Styles]]
- [[MacOS Design System/Buttons]] — for `#0088FF` text/tint references

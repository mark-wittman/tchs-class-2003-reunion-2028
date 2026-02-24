# Redesign v2 — Sonnet (redesign-v2-sonnet)

## What Changed
- **Pure CSS** — removed Tailwind CDN and Google Fonts CDN; 100% self-contained
- **Yearbook hero** — multi-layer CSS gradient simulating a faded sepia photograph
  - alumniclass.com photos require login (couldn't be fetched); pure CSS achieves the nostalgic effect
- **"Commodores '03" branding** — serif font headline, gold accent palette
- **Gold buttons** — `.btn-gold` with hover glow (`box-shadow: rgba(212,160,23,.38)`)
- **Hover cards** — all `.card` elements lift on hover (`translateY(-5px)` + shadow)
- **44px mobile touch targets** — all buttons enforce `min-height: 44px` on ≤639px
- **Live RSVP note** — animated green pulse dot labeled "Form Going Live Soon" + `aria-live` region
- **Nostalgia strip** — "Where Were You?" section with 2003 cultural references
- **Footer** — full 3-column footer with brand, quick links, CTA

## Files
- `index.html` — redesigned site (pure CSS, no CDN dependencies)
- `README.md` — this file

## Branch
`redesign-v2-sonnet` → PR "v1.2: Nostalgia redesign #1 #3"

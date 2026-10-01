# Ahmed Sayed

Web developer. I build fast, accessible landing pages — with the measurements to prove it.

**Available for work on Fiverr:** [ahmedpython_dev](https://www.fiverr.com/sellers/ahmedpython_dev) · **Portfolio:** [dbdg64.github.io/carpentry-landing-concepts](https://dbdg64.github.io/carpentry-landing-concepts)

---

## What I do

Landing pages, marketing sites, and small multi-page front-ends. **Vanilla HTML/CSS by default** — no framework, no build step, no bundler. You get plain files you own, host, and hand to whoever comes next.

I also work in **Arabic and RTL**, which is the specific thing most Western freelancers get wrong. Mirrored layouts, `dir="rtl"`, CSS logical properties, and line-height that accounts for Arabic's taller vertical rhythm.

And I audit existing sites for **WCAG 2.2 AA** issues and fix them.

## The standard I hold to

Most websites aren't slow because of frameworks. They're slow because nobody measured anything.

So I measure. Every text/background colour pair is computed against the WCAG ratio rather than eyeballed. Layout is tested across nine device widths for horizontal overflow. Tap targets are checked at 44px minimum. Keyboard paths and focus states get walked by hand. `prefers-reduced-motion` is respected.

**You get the numbers in writing, not a promise.** If something doesn't pass, you'll hear it before delivery.

| Check | Floor | Verified result |
|---|---|---|
| WCAG AA contrast, every text pair | 4.5:1 | **4.57:1** worst case |
| Horizontal overflow, 360 → 1920px | 0 | **0** across 9 widths |
| Tap targets, both axes | 44px | **44px**, no exceptions |
| Build steps required | — | **0** |

Those figures aren't aspirational. They're measured on the shipped work below, and the method is in [`DESIGN.md`](DESIGN.md).

## Featured work: four directions, one site

**Four independent design directions for one fictional Cairo carpentry workshop**, built to compare rather than to ship as one product. Same content, four different aesthetic and structural approaches — because a buyer should be able to see what I'd actually build for *their* brief, not just one aesthetic.

**None of it is a real business.** The workshop, phone number, and address are illustrative; every page says so in its footer.

| | Direction | Lane | Live |
|---|---|---|---|
| A | The Bench and the Line | dark, iron-oxide, flat — services as a work order, not cards | [open](https://dbdg64.github.io/carpentry-landing-concepts/proto-harf/) |
| B | Stamps and Forms | light cool ground, vermilion, Amiri naskh — official-document register | [open](https://dbdg64.github.io/carpentry-landing-concepts/proto-harf-stamp/) |
| C | The Poster | drenched saturated yellow, Rakkas display, 44% saturated coverage | [open](https://dbdg64.github.io/carpentry-landing-concepts/proto-harf-poster/) |
| D | The Spec Sheet | technical, drafting grid, dimensioned SVG elevation | [open](https://dbdg64.github.io/carpentry-landing-concepts/proto-harf-spec/) |

The [showcase hub](https://dbdg64.github.io/carpentry-landing-concepts) compares all four side by side.

What makes D worth a look: it's the only one where the ornament is load-bearing. The numbered callouts on the door elevation point at leader lines mapping to actual service items, the `D/K/W/F/R/P` code legend is used consistently as `D-01` and `K-01`, and monospace is scoped to Latin metadata with `unicode-bidi: isolate` so Arabic sentences never inherit it.

**Stack:** vanilla HTML + CSS. No framework, no npm, no bundler. JS is 7–21 lines per page — mobile navigation only. Fonts via Google Fonts.

## Also worth knowing

- **I'm not an enterprise SPA shop.** Need a 40-page app with auth, queues, and a design system? I'm the wrong hire and I'll say so before you order.
- **If a WordPress theme or a template already does the job, I'll tell you** rather than sell you something you don't need.
- **I tell you what the work actually costs.** The "Build to a standard" framing means a smaller page is sometimes the right answer.

## How I work

1. **Measure** — find the numbers before writing anything.
2. **Scope honestly** — say what I won't take.
3. **Build** — flat files, logical properties, RTL from the start.
4. **Verify** — and hand over the report.

The strategy behind this work is written up in [`PRODUCT.md`](PRODUCT.md); the visual system is in [`DESIGN.md`](DESIGN.md). Both are in the repo if you want the reasoning.

## Toolkit

Python · Playwright · browser automation · scraping · WCAG 2.2 AA · CSS logical properties · RTL/Arabic typography · Chrome DevTools Protocol · Remotion · FFmpeg

Building automation layers that let AI drive websites without a public API is a separate interest of mine — the kind of work where the site was never designed to be automated, and the interesting problem is making it reliable rather than demoable.

## Contact

Open to freelance web work. Fiverr is the fastest route to a quote; the deployed work above is the fastest route to judging whether I'm worth talking to.
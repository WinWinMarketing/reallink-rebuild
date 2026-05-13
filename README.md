# Shan Thayaparan — Website Mockups

Nine homepage design directions for Shan Thayaparan's new dual-purpose realtor + mortgage agent website. Each uses real content scraped from reallink.ca, a working mortgage payment calculator, and Shan's confirmed brand palette.

**Brand palette (detected from reallink.ca / RE/MAX Community Realty branding):**
Primary blue `#0D3DA5` (deep navy, RE/MAX-aligned) · Accent burgundy `#7C0000` (deep crimson-maroon) · Background `#FFFFFF` white · Dark text `#333333` · Display font: Outfit (Google Fonts) · Body font: DM Sans (Google Fonts). Directions 01, 03, 04, 07, and 09 use the exact palette. Directions 02 and 05 use slightly brighter variants (`#1E4FBC` / `#A41B1B` and `#1E50D6` / `#C81E1E` respectively) to keep the high-energy feel of those styles. Directions 06 and 08 are dark-mode treatments that derive from the same brand hues at adjusted luminosity.

---

## Direction 1 — Editorial / Typography-Led (`01-editorial/`)

**Palette mode:** Exact brand — `#0D3DA5` navy on cream `#FAF8F3` background, `#7C0000` burgundy on headline italic and drop cap.

Serious, calm, and credible. Big Playfair Display serif headlines on a cream background with generous whitespace and almost no decoration — letting the words do the work. Inspired by NYT Real Estate and high-end editorial publications. The nav uses sparse uppercase letter-spacing; listing cards strip away ornamentation to show price and address cleanly; the calculator uses underline inputs rather than rounded boxes. Best fit for Shan if he wants to position himself as the trusted expert that serious GTA buyers and move-up buyers turn to. Appeals to clients who distrust flashy sites.

---

## Direction 2 — SaaS / Software (`02-saas/`)

**Palette mode:** Tweaked brighter — `#1E4FBC` blue and `#A41B1B` crimson accent for higher vibrancy on the white background. Gradient text and CTA band use the brighter variants.

Clean, modern, and confidence-inspiring. Built in DM Sans with a blue-to-crimson gradient accent system, slider-based mortgage calculator, animated number counters that count up on scroll, and micro-interactions on every button (hover scale, active press). Floating stat cards appear next to Shan's photo. The vibe is Stripe, Linear, or Notion — technology companies that communicate trust through precision and restraint. Strong choice for reaching first-time buyers comfortable with digital tools, and for positioning the mortgage calculator as a signature feature of the site.

---

## Direction 3 — Warm Professional (`03-warm-professional/`)

**Palette mode:** Exact brand + warm secondaries — `#0D3DA5` and `#7C0000` as primaries, with warm cream `#E8DDC8` and sage `#A8B5A0` as muted background accents.

Welcoming, photography-forward, and community-centered. The palette blends cream and sage green with brand navy and burgundy, alongside organic blob shapes, rounded-3xl corners on every card, and soft drop shadows. Uses Fraunces (an optical-size serif with warm curves) paired with DM Sans. The dual CTA cards feel like choosing a path rather than clicking a button. Best fit for Shan if he wants a site that appeals to families, first-time buyers, and multicultural GTA communities who want to feel welcomed rather than sold to. The closest in spirit to a modern boutique brokerage.

---

## Direction 4 — Luxury Realtor (`04-luxury-realtor/`)

**Palette mode:** Exact brand, dark mode — dark navy base `#0A1F4F` replaces near-black; `#7C0000` deep burgundy replaces gold as the luxury accent; cream and white for body text.

Dark, cinematic, and premium. Full-bleed hero photograph with text overlay, deep navy backgrounds (#0A1F4F), burgundy (#7C0000) accents throughout, Cormorant Garamond serif headlines in light weight. Roman numeral pillars (I, II, III) for the "Why Shan" section. Inspired by Compass, Sotheby's International Realty, and luxury property platforms. The fixed transparent nav blurs on scroll. Strong choice if Shan wants to attract GTA's move-up buyers, executive clientele, and anyone shopping in the $1M+ range. Also works for investor clients who respond to prestige positioning.

---

## Direction 5 — Marketing-Bold (`05-marketing-bold/`)

**Palette mode:** Tweaked amped-up — `#1E50D6` vibrant blue and `#C81E1E` crimson replacing the original purple-pink scheme entirely. Spinning conic-gradient hero uses brand-colour translucent overlays.

High-energy, conversion-focused, and visually striking. Brand-blue-to-crimson gradient system throughout, animated conic-gradient beam effect behind the hero (spinning slowly like a lighthouse), glowing colour orbs that drift in the background, pulsing green online indicator badge. Uses Syne (an expressive display font) for headings and DM Sans for body. The calculator lives inside a gradient card with live slider updates. Resource section is on a near-black background with blue/crimson category badges. Best fit if Shan wants a site that stops people mid-scroll on mobile, maximises attention in a competitive GTA market, and appeals strongly to Millennials and Gen Z buyers.

---

## Direction 6 — WebGL / 3D Hero (`06-webgl-3d/`)

**Palette mode:** Dark-derived — `#1E50D6` brand blue and `#7C0000` burgundy for building materials; `#0A1F4F` navy for the deep-sky gradient and dark buildings.

A Three.js WebGL scene renders a low-poly Toronto skyline in real time inside the hero viewport. Buildings are coloured in brand navy, blue, and burgundy; the animated sky gradient shifts from deep navy to electric blue. Mouse movement causes a live parallax: the camera tracks the cursor so the city appears to tilt as the visitor moves the mouse. GSAP ScrollTrigger drives fade-up reveals for all below-the-fold sections. Full graceful degradation: if the browser does not support WebGL, or if Three.js fails to load from CDN, a static brand-colour gradient hero is shown instead. The most technically ambitious direction — a strong differentiator in the GTA mortgage space where no competitor has a 3D scene.

---

## Direction 7 — Scroll Storytelling (`07-scroll-storytelling/`)

**Palette mode:** Exact brand — `#0D3DA5` navy and `#7C0000` burgundy on white, light theme throughout.

CSS `scroll-snap-type: y mandatory` locks each section into place as the visitor scrolls through eight chapters of Shan's story: hero → listings → calculator → GTA map → why Shan → resources → CTA → footer. An animated SVG map of the Greater Toronto Area lights up city by city (Toronto, Scarborough, Pickering, Ajax, Oshawa, Markham, Mississauga) using a sequential setInterval that starts when the map section snaps into view. IntersectionObserver handles all fade/slide/scale reveal animations. Graceful degradation: browsers that don't support scroll-snap get a normal long-scroll page with the same sections visible. Strongest storytelling impact of all nine directions — each section demands the visitor's full attention.

---

## Direction 8 — Glassmorphism (`08-glassmorphism/`)

**Palette mode:** Dark mode, tweaked brighter for vibrancy — `#1450C7` blue and `#9A1818` maroon blobs over `#0D1035` deep background; card overlays use `rgba` variants.

An animated CSS mesh gradient background — four large radial-gradient blobs in brand blue and burgundy pulse and drift continuously via `@keyframes`. Every card on the page uses `backdrop-filter: blur(20px)` with a semi-transparent `rgba(255,255,255,0.07)` background to create the frosted-glass (glassmorphism) effect. The nav also blurs against the animated background. Dark, atmospheric, and cinematic — visually bold without feeling loud or chaotic. The calculator result box uses a layered blue-to-maroon glass gradient. Best choice if Shan wants something that immediately reads as premium and design-forward to a tech-literate audience.

---

## Direction 9 — Bento Grid Magazine (`09-bento-magazine/`)

**Palette mode:** Exact brand — `#0D3DA5` and `#7C0000` on warm white `#F7F6F2` background.

A CSS Grid bento layout in the hero: a wide text block spanning rows alongside a photo cell, a stat cell, a listing preview, and a calculator preview — all in a responsive magazine grid. A custom dot cursor (CSS + JS `mousemove`) replaces the browser default and scales up on hover. The View Transitions API wraps anchor-link scrolls for smooth animated section transitions in supporting browsers (graceful no-op fallback in unsupported). A Lottie animation (`<lottie-player>` web component via CDN) runs in a dark hero cell. All below-the-fold sections use IntersectionObserver for staggered reveals. Light, airy, modern — the Apple product page of mortgage websites. Stands out strongly on desktop.

---

## What's NOT in these mockups

The following features are all confirmed for the real build but are not present in these HTML mockups — they require the full production stack:

- **Live IDX listings** — will come from PropTx/Amplify integration (TRREB feed). The 3 listing cards shown use Unsplash stock photos and placeholder addresses. All listing cards are labelled "Sample listings — live IDX coming from PropTx."
- **Real BoldTrail lead capture forms** — all CTAs link to `#` placeholders. The production build will embed BoldTrail HTML widgets or equivalent CRM forms.
- **Full sitemap** — these mockups show only the home page. The real build includes `/listings`, `/mortgage`, `/mortgage-tools`, `/about`, `/resources`, `/contact`, `/apply`, and legal pages.
- **Four additional mortgage calculators** — only the Payment Calculator is built here. Stress Test (B-20), Affordability, Ontario Land Transfer Tax, and CMHC Premium are coming in the real build.
- **Real listing photos and MLS data** — all listing images are Unsplash hot-links. Real build uses PropTx IDX with proper TRREB attribution and live MLS data.
- **Finalized copy** — placeholder numbers appear for "families helped" (marked with "confirm with Shan" notes). All copy should be reviewed and approved by Shan before production.
- **Google Reviews embed** — testimonials section is not included in these mockups.
- **Bilingual content** — English only per current brief. French version deferred to Phase 2 if Shan decides it's needed.

---

## Compliance note

Every mockup includes the exact disclosure numbers from reallink.ca in the footer:
- RE/MAX Community Realty · RECO #47117293
- Mortgage Agent: Mo8009140 · Brokerage Lic #15422265 · License #2154151
- 203-1265 Morningside Ave, Toronto, ON M1B 3V9

These are non-negotiable per FSRA and RECO requirements and must appear on every page of the live site.

---

*Prepared by WinWin Marketing · May 2026*

\# Design system — Better Hearing Health

Version 2 · 9 October 2026 · Governing foundation for Steps 4 and 5

Use with \[PAGE\_STRATEGY.md\](PAGE\_STRATEGY.md) and \[CONTENT\_DIRECTION.md\](CONTENT\_DIRECTION.md). This system translates the inspected clinic brand into an intentional landing page. High standards mean exact type/color relationships, disciplined composition, authentic imagery, clear hierarchy, and usable interactions—not more decoration.

\#\# Live brand evidence and design decisions

The clinic homepage was read successfully and rendered at \*\*1440 × 1000\*\* and \*\*390 × 844\*\* viewports on 9 October 2026\. Its stylesheet declarations, computed styles, loaded fonts, visible photographs, and desktop/mobile composition were inspected. HTML/static resources were retrieved with TLS verification intact and rendered in Chromium. No booking/request submission was performed, and third-party map behavior was not functionally validated.

Verified stylesheet sources:

\- \`https\://altamontefamilyhearing.com/\_astro/Base.DzPh4Cdl.css?dpl=6ac4c06362a77200084cb412\`  
\- \`https\://altamontefamilyhearing.com/\_astro/index.DxKoba2x.css?dpl=6ac4c06362a77200084cb412\`  
\- \`https\://altamontefamilyhearing.com/\_astro/es.DKGcdjtE.css?dpl=6ac4c06362a77200084cb412\`

Evidence retained outside the checkout at \`/workspace/scratch/afh-step3/\`: \`desktop.png\`, \`mobile.png\`, \`desktop-evidence.json\`, source HTML/CSS, supporting clinic pages, and inspected assets. These are inspection artifacts, not a landing-page implementation. The previous document set is preserved in \`previous/\` there.

\*\*Correction to research's incomplete brand extraction:\*\* theme metadata \`\#1A3028\` is the site's \*\*pine/night and ink\*\*, not its primary functional green. Actual \`--color-primary\` is \*\*\#006241\*\*. Headings are \*\*DM Serif Display\*\*; body/UI are \*\*Satoshi\*\*. These are verified live declarations, not proposed substitutions.

\*\*Observed visual language:\*\* cream canvas; pine text/dark panels; emerald-green and gold accents; large serif headings with selective italic/color emphasis; Satoshi UI; pill CTAs; softly rounded imagery and large panels; real patient/staff photography; open service rows; asymmetric provider hierarchy; a dark dedicated review region. The live site includes floating hero photos, a notched CTA transition, animation, video, and audio demonstration. Those are observed features, not mandatory landing-page components.

\*\*Landing-page adaptations:\*\* one composed hero photograph rather than a two-photo collage; a consistent light sticky header rather than scroll-triggered color changes; static rather than animated proof; no automatic video/audio demo; slightly larger body text; transparent conversion labels and distinct booking/request routes; a light vendor-form surface. Preserve the brand's quality while prioritizing the brief's decision path. These are explicit Step 3 choices, not claims that every component exactly duplicates the main website.

\#\# Brand foundation

The first 14 palette entries below come from the live base stylesheet. Functional accessibility additions are separately labeled.

| Role / token | Hex | Use |  
|---|---|---|  
| Primary / \`brand-primary\` | \`\#006241\` | Emerald green; booking CTA on light surfaces, links, small emphasis, mobile Call bar. |  
| Primary deep / \`brand-primary-deep\` | \`\#004D33\` | CTA hover/active emphasis. |  
| Secondary accent / \`brand-gold\` | \`\#CBA052\` | Warm gold; selected marks, stars, one optional featured review surface, dark-panel CTA. |  
| Soft secondary / \`brand-gold-soft\` | \`\#E8D3A6\` | Gold hover surface, restrained dark-section emphasis. |  
| Pine / \`brand-night\` | \`\#1A3028\` | Main text, structural dark panels, review region, closing/footer. |  
| Mist / \`surface-mist\` | \`\#DEE7E3\` | Tonal service/process callout or section separation. |  
| Mist deep / \`surface-mist-deep\` | \`\#C9D8D1\` | Quiet supporting surface, dividers/borders. |  
| Main background / \`background-cream\` | \`\#FBF8F1\` | Page/hero canvas. |  
| Surface / \`surface-paper\` | \`\#FFFDF8\` | Cards, request-form shell, light alternate surfaces. |  
| Main text / \`text-primary\` | \`\#1A3028\` | Headings/body on light surfaces. |  
| Supporting text / \`text-secondary\` | \`\#4A5E55\` | Supporting body text on cream/paper. |  
| On dark / \`text-on-dark\` | \`\#EEF3EF\` | Text on pine. |  
| On dark soft / \`text-on-dark-soft\` | \`\#C7D6CD\` | Supporting text on pine. |  
| Borders / \`border-subtle\` | \`\#C9D8D1\` | Noninteractive dividers/card outlines; not sufficient as the only boundary of every control. |  
| True white / \`white-functional\` | \`\#FFFFFF\` | Functional addition: required pure-white mobile Call label/icon, green booking-button label. The site's \`--color-white\` actually resolves to paper, not pure white. |  
| Strong control border / \`border-control\` | \`\#597066\` | Accessibility addition for necessary input/control boundaries on light surfaces. |  
| Error / \`status-error\` | \`\#8C2E2E\` | Functional addition: text/icon plus explicit error message, never color alone. |  
| Success / \`status-success\` | \`\#006241\` | Actual confirmed state only; not an invented iframe success. |

\#\#\# Functional color pairings

\- Primary Book Appointment: \*\*\#006241 \+ \#FFFFFF\*\*; hover \*\*\#004D33 \+ \#FFFFFF\*\*.  
\- Secondary utility button on cream: transparent/paper surface with \*\*\#1A3028\*\* text and a visible pine/strong outline.  
\- Primary action inside a pine panel: \*\*\#CBA052 \+ \#1A3028\*\*; hover \*\*\#E8D3A6 \+ \#1A3028\*\*. Keep gold limited to a deliberate contrast reversal, not every button.  
\- Phone/text links on light surfaces: \*\*\#006241\*\*, underlined where needed to communicate interactivity; on pine: \*\*\#EEF3EF\*\* with clear underline.  
\- Mobile Call bar: \*\*\#006241\*\*, required pure-white text/icon.  
\- Focus on light: a visible primary-green outer ring, separated from the component by a light offset; on pine: gold outer ring. Confirm adjacent contrast and visible focus for every component.

Check final combinations against WCAG AA: 4.5:1 normal text; 3:1 large text and necessary non-text boundaries. Gold on cream is decorative and fails as normal small text; do not use it for button labels, essential captions, or body copy. Use pine text on gold, and gold details on pine where contrast supports the purpose. Opacity, overlays, hover states, and disabled states need checks too. Necessary control edges use stronger borders than subtle section dividers.

\#\# Typography

\*\*Heading:\*\* \*\*DM Serif Display\*\*, genuine regular 400 and italic 400\. CSS family: \`"DM Serif Display", Georgia, serif\`. Use normal weight, not synthetic bold.

\*\*Body/UI:\*\* \*\*Satoshi\*\*, variable 300–900. CSS family: \`"Satoshi", system-ui, sans-serif\`. Use 400 for body, 500 supporting labels, 600 navigation/buttons, 700 sparingly for key facts. Do not substitute Manrope or a different sans without an explained, approved change in Step 5\.

Verified source files:

\- \`/fonts/satoshi/Satoshi-Variable.woff2\`  
\- \`/\_astro/dm-serif-display-latin-400-normal.C5\_t9oOD.woff2\`  
\- \`/\_astro/dm-serif-display-latin-400-italic.DpcbibHm.woff2\`

All three loaded successfully in the inspected render. These website build paths can change; retrieve licensed font files through the approved project asset workflow and preferably self-host stable WOFF2 copies in the later implementation. Use \`font-display: swap\`, proper weights/styles, and fallback stacks. Do not assume a document alone has installed font assets.

Observed body is \*\*17 px / 1.6\*\*. The site's base H1 scale is \`clamp(2.6rem, 5.4vw, 4.6rem)\`, but the homepage hero overrides it: the inspected desktop H1 was \*\*91.2 px / 1\*\*. Its desktop H2s ranged roughly \*\*44.6–57.6 px\*\*. The landing-page scale below keeps a strong editorial headline with more explanatory content and comfortable mobile readability; it is an intentional adaptation.

| Role | Desktop ≥ 1100 px | Tablet 768–1099 px | Mobile \< 768 px | Line height / treatment |  
|---|---|---|---|---|  
| H1 | 64–76 px; default 72 | 50–60 px | 38–44 px; default 40 | 1.06 desktop, 1.12 mobile; −0.01em tracking; meaningful line grouping. |  
| H2 | 44–56 px; default 48 | 36–44 px | 30–36 px; default 32 | 1.12–1.18; balance without forced desktop line breaks. |  
| H3 | 26–32 px | 25–28 px | 23–26 px | 1.2–1.25; serif for editorial headings, Satoshi 600 for functional service labels. |  
| Body | 18 px | 18 px | 18 px | 1.6–1.65; never shrink all content to fit cards. |  
| Lead/hero support | 20 px | 19–20 px | 18–19 px | 1.6; max approximately 46–52ch. |  
| Small/supporting | 15–16 px | Same | Same | 1.5–1.6; essential qualifications preferably 16–18 px. |  
| Button/navigation | 16–17 px / 600 | 16 px / 600 | 15–16 px / 600 | 1.2–1.3; title case, not all caps. |  
| Eyebrow | 13–14 px / 700 | Same | Same | Short labels, 0.10–0.12em tracking; optional uppercase. |

Use fluid interpolation within bounds. Default body measure \*\*62ch\*\*, consistent with the site; hero narrower, FAQ explanations ≤ 70ch. One H1, semantic H2/H3 sequence. Reserve italic emphasis for a short meaningful phrase in selected headings. Do not make every headline two-tone or italicize full passages. Hero copy can use two or three lines naturally; no oversized decorative word that pushes location/action far down the page.

\#\# Layout

| Rule | Landing-page default |  
|---|---|  
| Max content width | \*\*1240 px\*\*, matching live \`--container\`; centered. |  
| Narrow reading width | 760–820 px, with text measure controlled within it. |  
| Desktop horizontal gutters | 48 px at wide widths; 32 px where needed around 1100 px. |  
| Tablet gutters | 28–32 px. |  
| Mobile gutters | 20–24 px; 16 px below 360 px if needed. |  
| Desktop section padding | 88–104 px vertically; default 88 px matching the site's \`.section\` rhythm. |  
| Tablet section padding | 64–80 px; default 72 px. |  
| Mobile section padding | 48–64 px; default 56 px. |  
| Compact recognition/closing regions | 48–64 px desktop; 32–48 px mobile. |  
| Spacing scale | 8, 16, 24, 28, 32, 40, 48, 64, 80, 88, 104 px; 4 px for minor alignment. |  
| Heading-to-body/grid gap | 32–40 px desktop; 24–28 px mobile. |  
| Editorial column gap | 48–64 px desktop; 32 px tablet; 24–32 px stacked. |  
| Card/service grid gap | 24–28 px desktop; 20 px tablet/mobile. |  
| Card padding | 28–32 px desktop; 20–24 px mobile. |

\*\*Breakpoints:\*\* compact mobile \< 480 px; wide mobile 480–767 px; tablet 768–1099 px; desktop ≥ 1100 px. Compact header below 1100 px when the complete header would crowd. Mobile three-review cap and bottom Call bar below 768 px. Let content fit dictate earlier stacking, not a demand to preserve two columns.

\*\*Grid rules:\*\* use a 12-column desktop foundation. Hero: copy around 6 columns, photo around 5, with generous gap; text/proof/action remain a coherent group. First visit: open step sequence with supporting image. Verification: authentic procedure photo plus explanation and a scoped care fact; do not repeat the identical hero composition. Services: open rows/two-column groups rather than six giant image tiles. Providers: Jaysee/Toni have larger portrait/bio blocks, coordinators a smaller pair/group. Reviews: maximum 3 × 2 desktop, 2 × 3 tablet, three stacked mobile cards. FAQ centered/narrow. Request form introduction/form 4/8 when useful; stack when form width suffers. Location details/map 5/7 or 6/6.

\*\*Section rhythm:\*\* cream hero → open recognition → paper first-visit region → selected pine verification panel → open paper/cream services → cream providers → dedicated pine review panel → simple paper FAQ → quiet light request-form region → mist/cream location → pine closing/footer. Adjacent light sections can share a surface; rhythm comes from spacing, scale, and composition, not obligatory background switching. Large dark panels are purposeful, with open light regions between them.

Preserve S0–S12 and anchor offsets for the sticky header. No screen-height minimums for every section. Content-rich Step 4 must breathe without enormous empty bands, fixed-height text, or a repetitive row of identical cards.

\#\# Components

\#\#\# Header/navigation

Sticky cream/paper surface, approximately 84 px desktop and 72–80 px compact, allowed to grow for zoom/wrapping. Use a subtle bottom rule; no heavy shadow or transparent text over photos. Three balanced desktop regions: linked logo, central anchor navigation, phone/booking actions. Default logo 240–270 px wide desktop, 145–175 px compact, preserving aspect ratio and legibility. At 320 px, use tighter gaps and a comfortably sized two-line booking label if necessary rather than squeezing every desktop element into the row.

Mobile/tablet compact header: logo \+ Book Appointment; no full desktop navigation by default. The landing-page header intentionally differs from the live site's mobile Menu/phone layout because the brief requires booking. A scroll-tone-changing header/mega-menu is unnecessary. Include a visible-on-focus skip link, understandable logo accessible name, proper navigation semantics, and clear focus states.

\#\#\# Primary CTA

\*\*Book Appointment\*\* is a semantic button opening the same widget dialog everywhere. Pill radius \*\*999 px\*\*, following the clinic's actual button language; Satoshi 600; default height 50–56 px; approximately 16 px vertical / 26–30 px horizontal padding. Green/white on light, gold/pine in dark closing/method/review regions as specified above. No pulsing, typing text, or fabricated urgency. Hover/pressed/focus states remain clear. Narrow mobile hero/closing buttons can be full width; header action is compact.

\#\#\# Secondary CTA and phone CTA

Utilities use transparent/light outlined pills with pine text and a visible outline, minimum 44–48 px target. Review destination can be a clearly underlined text link. Phone is a quieter \`tel:\` link with a consistent 18–20 px line icon and visible number; avoid a second filled booking-sized button at every section. On dark surfaces use readable light text. \*\*Get Directions\*\* is below the map with direction/location icon before its label.

\#\#\# Cards

Live design tokens include \*\*28 px card radius\*\*, \*\*18 px photo radius\*\*, and \*\*44 px large-panel radius\*\*. Retain this soft geometry; do not replace the whole system with square SaaS cards or rounded bubbles everywhere. Card surfaces paper/mist/pine as needed; 1 px subtle border on light; mostly no shadow. Cards exist for genuinely grouped proof or controls, not to wrap every paragraph. Service rows can be separated by quiet dividers. Noninteractive content must not lift or animate on hover.

\#\#\# Trust badges

Hero has one compact Google grouping: readable 5.0, five stars, 156 Google reviews, clear attribution. Hide decorative stars from assistive technology when the score is stated in text. No credential/manufacturer badge wall. Genuine HearingUp mark is optional beside its explained method/person; text is preferable to a fabricated certification seal. Five-year care is a visible fact with its scope attached, never a universal guarantee badge. Small gold stars use text equivalents and adequate context, not gold body text on cream.

\#\#\# Review cards

Dedicated pine panel with clear heading and aggregate summary; selected paper cards, or one featured gold card with pine text if it creates a deliberate focal point. Preserve readability and genuine quotes; no decorative new pull-quote claims. Quotation text Satoshi 17–18 px with 1.55–1.65 leading; names/source 15–16 px. A serif feature excerpt is optional but cannot make all six cards dense display-type blocks.

Maximum six cards desktop/tablet, only the chosen three below 768 px. Static grids/lists; no autoplay or mobile carousel revealing the other three. Exact excerpts may expand with \*\*Read full review\*\*; content grows without nested scrollboxes or truncation to equal height. Genuine matched thumbnails optional; otherwise no avatar or a neutral initial. Never copy a thumbnail from a different reviewer. Required \*\*See all our Google reviews\*\* link remains clear; Book Appointment sits separately after the evidence.

\#\#\# FAQ

Narrow text region with stacked divider rows; questions Satoshi 600 at 18–20 px, answers 18 px. Disclosure controls have visible text/icon, adequate padding, 44 px minimum target, accessible expanded state, and strong focus. Native details/summary is acceptable when tested. Allow multiple answers open; do not animate long height changes or lock answers into a tiny scrollbox. Keep essential cost/coverage qualifications beside claims and urgent-change guidance visible in S2 as well.

\#\#\# Forms and booking dialog

Request form is a light paper region/wrapper with simple heading, reassurance, privacy link, phone fallback, and room for the exact supplied Onspire Pulse embed. Preserve its fields, IDs, consent attributes, and script. The original \*\*492 px\*\* data height is an initial vendor value, not a safe hard maximum; permit supported resizing and verify submit/validation at mobile widths and zoom. Do not recreate cross-origin fields or assume their styles can be edited from the parent page.

Booking dialog contains the supplied My Hearing Portal iframe, an accessible \*\*Book an appointment\*\* heading, descriptive iframe title, visible close control ≥ 44 px, and phone fallback. Default max width approximately 1000–1040 px, viewport-bounded height and usable scrolling; near-full-screen at mobile sizes. Pill styling applies to actions, not to the whole dialog; use 28 px desktop container radius, reduced where near full screen.

Manage focus entry/trap/return, Escape, background scrolling, and keyboard behavior through the cross-origin iframe. Use one widget instance, avoid duplicate IDs/repeated script insertion, and keep fallback help available. Show honest loading/failure information; do not invent a completed booking or confirmed request. The page's bottom Call bar is hidden while the modal is open. Handle active form fields/software keyboard after real responsive testing rather than assuming a fixed bar is harmless.

\#\#\# Location/map block

Structured address, One Senior Place, phone, office hours/lunch closure, weekends, and separately labeled walk-in hour. Text remains outside the map. Stable map wrapper, 18 px corners, subtle border; approximately 4:3 desktop, 280–360 px high mobile as composition allows. Lazy load below fold, descriptive iframe title, valid verified Google embed source. Share/place/CID links are not automatically iframe HTML. Directions and address remain usable when the map fails or consent blocks it. A real exterior image is optional, not a generated substitute.

\#\#\# Provider blocks

Authentic portraits at consistent 4:5/3:4 crops, 18–28 px rounded corners, faces/eye lines preserved. Correct name, role, and credential sit beside the image. Jaysee/Toni receive clinical-provider weight; coordinators form a smaller supporting pair/row, not identical credential cards. Real staff white-coat portraits are appropriate because they identify actual specialists; generic stock doctors are not. No AI replacement faces, fabricated badges, or invented patient stories.

\#\#\# Final CTA

One generous pine region with readable light heading/supporting copy, gold/pine primary Book Appointment and quieter light phone link. Approximately 64–80 px desktop padding, 40–56 px mobile. No new claims, manufacturer strip, testimonial collage, or repeated form. Footer can continue pine with a quiet separator and real reversed logo.

\#\#\# Mobile sticky Call CTA

Below 768 px: fixed bottom \*\*Call 407-949-6737\*\* with phone icon, \*\*\#006241\*\* background and \*\*\#FFFFFF\*\* label/icon, single \`tel:+14079496737\` action. Main target 52–56 px high plus bottom safe-area inset. Reserve page bottom padding equal to bar \+ inset \+ buffer. Header booking remains the direct route; Call is the assisted route. No overlapping floating chat or second bottom action.

Do not cover footer links, form submit/errors, or dialog controls. Hide during modal display and adapt to keyboard/focus state. Verify landscape, zoom, and real control reachability. Icon is decorative when label states the action.

\#\# Graphic-design principles

\*\*Visual personality:\*\* warm, assured editorial healthcare, grounded in real people and precise care. Use the clinic's cream/pine/emerald/gold and actual serif/sans relationship. Avoid luxury-spa vagueness, retail-device catalog styling, and generic software-dashboard aesthetics.

\*\*Whitespace:\*\* generous around major ideas, tighter within related proof/copy. Breathing room must not become empty screen-sized gaps. Retain content depth by expanding the layout, not shrinking paragraphs or qualifications.

\*\*Contrast:\*\* green conversion accents on cream; pine creates selected structural anchors; gold is restrained warmth and deliberate action contrast on dark. Avoid alternating light/dark mechanically. Text outside photographs is the default.

\*\*Images:\*\* purposeful real crops, natural color, consistent moderate treatment, no excessive orange warmth, fake bokeh, glossy skin, or complex collages. Preserve true clinical details and identity. The authentic photograph's own background should usually supply visual interest.

\*\*Cards:\*\* reviews and necessary grouped controls benefit from cards; methods, symptom lists, and services can use open layouts. No wall of interchangeable boxes, repeated six-card sections, or uniform tall image tiles.

\*\*Shadows:\*\* mostly none. The site's soft-shadow token is \`0 18px 40px \-22px rgba(26,48,40,.35), 0 6px 14px \-10px rgba(26,48,40,.25)\`; use selectively for a photo/raised control, not on every surface. Dialog shadow can be stronger. No colored glows.

\*\*Borders/radius:\*\* subtle 1 px dividers; stronger necessary control edges; 18 px photos, 28 px cards, 44 px selected large panels; pill actions. Reduce large-panel radius to 24–28 px on small screens as needed. No blobs, scallops, tilted cards, or multiple ornamental frames.

\*\*Section transitions:\*\* shared gutters, open space, quiet rules, selected rounded pine panels. Do not recreate the homepage's elaborate CTA notch or floating elements unless a later reviewed composition benefits from them. No diagonal cuts/parallax.

\*\*Icons:\*\* one consistent line family, 18–24 px, approximately 1.5–2 px stroke. Icons accompany labels for call/directions/process, never replace the meaning. A static small sound-wave eyebrow mark can reference the brand but is optional. No invented medical or certification seals.

\*\*Decorative restraint:\*\* selective italic phrase, small gold detail, one carefully placed tonal panel. The site has animation; this landing page should use short 120–180 ms interaction feedback only, honoring reduced motion. No typewriter “accepting patients,” autoplay, animated waveform, floating photo drift, or repeated reveal effects as default.

\#\# Image system and usable asset inventory

Prefer original user/clinic/GBP assets when authenticity matters, then verified clinic-site files. Images are selective, not mandatory. All URLs below were found in the live homepage HTML/render; the original brief logo and consultation file were also downloaded and inspected independently. Availability does not certify licensing beyond the client's intended use; preserve correct subject attribution and approved usage in the later build.

| Role | Genuine source | Treatment / evidence |  
|---|---|---|  
| Production logo | \`https\://assets.cdn.filesafe.space/3o0LBBSuVEkoaohgGtT0/media/6ac7f45989da6e6f9bbdacc8.png\` | Verified \*\*2172 × 724 RGBA\*\* with transparency. Preserve original artwork/aspect ratio; preferred to the generative upscale. |  
| Main site/reversed logos | \`https\://altamontefamilyhearing.com/assets/logo-altamonte-626.png\` and \`https\://altamontefamilyhearing.com/assets/logo-altamonte-white-626.png\` | Genuine light/dark identity variants; no CSS inversion or recoloring. Brief's logo remains primary source. |  
| Hero consultation | \`https\://altamontefamilyhearing.com/assets/photos/AFH-C-173.webp\` | Independently inspected \*\*1600 × 1067\*\* image; patient speaking with Jaysee in foreground. Preserve patient expression and consultation context, preferably 3:2/4:3 crop; no testimonial attribution. |  
| First visit | \`https\://altamontefamilyhearing.com/assets/photos/AFH-A-29.webp\` | Website-displayed sound-booth/headphone image. Explain actual testing, not an unrelated procedure. |  
| REM | \`https\://altamontefamilyhearing.com/assets/photos/AFH-C-196.webp\` | Genuine procedure source displayed in the website's service imagery; crop must retain probe/context; accurate caption. |  
| Repair, optional | \`https\://altamontefamilyhearing.com/assets/photos/AFH-C-125.webp\` | Actual repair-bench source. Use only if it clarifies support. |  
| Team, optional | \`https\://altamontefamilyhearing.com/assets/photos/staff-AE8A1554-3.webp\` | Rendered group under practice sign. Alternative/supporting team context, not repeated throughout. |  
| Jaysee portrait | \`https\://altamontefamilyhearing.com/assets/photos/jaysee-portrait.webp\` | Rendered actual provider portrait; pair with correct title/credentials. |  
| Toni portrait | \`https\://cdn.sanity.io/images/p8cei03q/production/592d18eda5ba9c959fa4c2719d71cd0ff0e3f603-1800x1440.jpg?w=800\&auto=format\` | Actual rendered portrait; retain crop/identity. |  
| Grace portrait | \`https\://cdn.sanity.io/images/p8cei03q/production/4fac9632e53190ee3edd42029b0a9b78c58c05c7-1800x1440.jpg?w=800\&auto=format\` | Actual rendered coordinator portrait. |  
| Francesca portrait | \`https\://cdn.sanity.io/images/p8cei03q/production/d470d108685dbdd5ac71c470a83983c6fe72314b-1800x1440.jpg?w=800\&auto=format\` | Actual rendered coordinator portrait. |

The generated upscale at \`/workspace/generated\_images/exec-e9d98e1c-699d-4dde-a15e-856520719b74.png\` was inspected and is a derivative, not the master. It adds an off-white background and changes details. Do not adopt it in place of the genuine transparent source by default. No new image generation is part of Step 3\.

Original review screenshots are described/transcribed in research Section 11 but unavailable locally. Use accessible exact text cards; if files arrive, choose legible crops with equivalent text and correct attribution. Do not borrow website reviewer thumbnails for different selected reviewers. HearingUp/manufacturer logos are optional only when genuine assets and appropriate attribution are verified. No exterior image is confirmed; the map/address supply locality without inventing a building.

\#\#\# When generated imagery is appropriate

AI lifestyle/editorial imagery may be considered for an optional illustrative everyday-listening context when genuine assets cannot serve it. It must not impersonate clinic staff, patients/reviewers, a real appointment, equipment/procedure evidence, or the actual office. Real assets already serve the planned hero, process, method, and team. Replacing those with generated imagery is a meaningful departure to explain and approve in Step 5, not a default workaround.

\#\#\# Crop, copy relationship, and overlays

\- Hero landscape \*\*3:2 or 4:3\*\*, chosen from the actual photo; desktop composition can allocate enough width instead of forcing a damaging portrait crop. Mobile may use a different focal crop while retaining context.  
\- Procedure/support \*\*4:3 or 3:2\*\*; portraits \*\*4:5 or 3:4\*\*. Preserve eyes, hands, and relevant equipment rather than cutting for fashionable shapes.  
\- Image sits next to relevant copy on desktop. Mobile message/proof/action precede hero imagery; method explanation precedes its image; portrait stays close to name/credentials.  
\- Photo corners normally 18 px. Captions identify a real visible method/person/setting, not an invented outcome. Badges stay outside faces and important equipment; avoid placing multiple claims over photography.  
\- Text overlays are exceptional, with contrast scrim tested against the real image; they cannot make the only copy unreadable. Never attach a quote to a pictured person unless that identity is verified.  
\- Avoid generic white-coat stock doctors, staged thumbs-up scenes, exaggerated joyful-senior stereotypes, floating-device renders, fake patient collages, and anatomically questionable AI procedures. Genuine staff portraits in their actual attire are appropriate.

Later implementation should retain original files, optimize responsive derivatives, provide width/height to prevent layout shift, load the chosen above-fold image intentionally, and lazy-load lower photography/map. Alt text explains relevant actual content without marketing claims. Decorative repeats have empty alt. Do not assume public hotlinks are a stable production asset strategy or promise performance scores before testing.

\#\# Responsive hierarchy

Change composition rather than merely shrinking. Mobile prioritizes decision information: benefit/service, locality, Google proof, action, then image. The main site's mobile hero places two pictures first; the landing-page adaptation intentionally moves the next step earlier without deleting supporting copy.

Use one-column service explanations, vertical steps, contiguous provider identity, and three substantial review cards. Retain details via better hierarchy/disclosure, not tiny type or swipe-only interfaces. Remove decorative repeats before facts. Do not let desktop alternating columns create an illogical reading order.

FAQs reflow naturally; request form is full width; map remains secondary to address/hours; the closing booking action is reachable. Avoid fixed textual heights. Give sticky controls safe space and test with the mobile keyboard. At text enlargement, wrapping and extra height are preferable to clipped labels.

Later-build checks: 320, 390, 768, 1024, 1440 px, landscape, keyboard focus, 200% text enlargement/400% reflow, reduced motion, and real iframe controls. Validate final text/non-text contrast, touch targets ≥ 44 px, semantic headings, skip link, disclosures, modal focus, and no horizontal overflow or sticky overlap. Third-party unavailable states need useful phone/directions fallbacks. The strategy documents do not claim these implementation checks have run.

\#\# Handoff and change control

Step 4 should produce a coherent complete draft: exact brand palette and font pairing, deliberate composition changes, authentic selective imagery, readable content depth, and the required conversion components. Avoid a repetitive template or a wall of prose. Label unresolved implementation issues in notes, not visitor-facing placeholder claims.

In Step 5, follow \`Agents.md\` and PAGE\_STRATEGY.md: one section at a time; review and 3–5 headline options for major sections; proactive content/design/image suggestions and questions; user response before implementation; explanation and approval afterward; lock approved sections and do not advance automatically. Explain meaningful visual/structural/conversion departures before adoption and update governing documents plus IMAGE\_PROMPTS.md when relevant. The verified design system remains the baseline until an approved improvement changes it.

## Step 5 decision record — S0 header

9 October 2026: the user approved the header-refinement direction, including visible tablet phone assistance. The implementation is awaiting final section review; **S0 is not yet locked**. This approved responsive specification overrides the earlier S0 breakpoint defaults.

- Keep the paper surface, emerald booking pill, pine navigation, subtle divider, and original transparent logo.
- Below 768 px: logo approximately 140–166 px wide, booking at least 52 px high, with intentional two-line treatment on narrow screens. Allow the header to grow and wrap for enlarged text.
- From 768 to 1279 px: logo 210 px, visible phone link and single-line booking; hide full navigation.
- At 1280 px and above: logo 248 px, centered navigation and right-aligned phone/booking. Desktop header is approximately 88 px high and grows if text requires it.
- Use genuine Satoshi weight 600 for header navigation, phone, and booking. A separately named variable Satoshi font face is scoped to the header; other sections retain their existing font requests and styles.
- Original logo proportions and destination are unchanged; no generated image, crop, or IMAGE_PROMPTS.md change is needed.
- All later sections retain their draft composition and typography. Do not advance until the user reviews and approves or adjusts S0.

## Step 5 approval — S0 header locked

9 October 2026: after reviewing the published preview, the user said “Ok lets proceed.” S0 is approved and locked at its current implementation. Review S1 next; do not materially change the header without discussing a user request or a genuine consistency/responsive dependency first.

## Step 5 direction — S1 everyday conversation benefit

9 October 2026: the user requested a stronger shift toward the everyday-conversation benefit after reviewing the desktop hero screenshot. Implement “Hearing care for easier everyday conversations.” Connect that goal to evaluation, plain-language results, and suitable options; hearing aids remain conditional rather than assumed. Keep locality, independent/family-owned context, Google proof, booking, phone, and Spanish support. Preserve the genuine 3:2 consultation photo and split editorial layout. Tighten supporting-information grouping and section spacing without reducing readable typography. S0 remains locked; other sections remain unchanged. S1 awaits implementation review and is not yet locked.

## Step 5 approved direction — pine S1 and welcome video

9 October 2026: the user explicitly approved the pine hero direction and the clinic’s existing welcome video. This supersedes the cream hero and the earlier everyday-conversation headline direction for S1.

- Exact H1: **Hearing Care That Feels Like Family**. Retain Better Hearing Health and Altamonte Springs in the eyebrow. Lead with personal care, evaluation, clear explanations, and suitable recommendations; do not imply every visitor needs hearing aids.
- Use brand pine #1A3028, cream heading/body, restrained gold emphasis and booking, and genuine Satoshi 600 controls. The existing variable face is scoped to S1 as well as the locked header; no other typography changes.
- Balanced editorial split from 1100 px, copy then genuine `AFH-C-100.webp` front-desk photograph. Desktop photo 4:3 with a 96 px upper-left corner and 18 px other corners; mobile/tablet 3:2 with 18 px corners. Preserve all faces and identify the real setting in a quiet caption. No claims overlay or generated imagery.
- Retain Google 5.0 / 156 from the supplied dated research, booking dialog, phone, and Spanish cue. Add an open three-part proof row: independent/family-owned licensed care; Real Ear Measurement for aid fittings; five years of care with hearing aids purchased from this office. Keep that purchase qualification adjacent. Stack facts on mobile; do not use a carousel.
- **Planned S1A:** welcome-video introduction immediately after the hero, before recognition. Approved video source: https://www.youtube.com/watch?v=HxCXX0CgR9s, confirmed in the clinic homepage’s `data-yt` attribute. Use click-to-play, descriptive title, responsive embed, and no autoplay on page load. Review this section separately after the user approves S1; it is not implemented by this hero pass.
- S0 remains locked and unchanged. S1 implementation awaits user review and is not yet locked. Other sections retain their existing implementation.

## Step 5 review-count display update

The user requested **150+ reviews**. Use this rounded count consistently in S1 and S7, retaining the 5.0 Google rating. This supersedes earlier exact-count display instructions; the dated 156-review source remains historical evidence. No other section changes are authorized by this wording update.

## Step 5 user-supplied care wording

The user explicitly requested **5+ years of professional care**, correcting the prior “5 years” wording. Apply this wording consistently to the S1 proof row and S4 care statement, retaining the qualification that care is included with hearing aids purchased from this office. The research source originally specifies five years; preserve that source rather than rewriting historical evidence. This display wording comes from the user’s correction.

## Step 5 approval — S1 hero locked

9 October 2026: the user said “Looks good” after the pine hero rebuild and wording corrections. S1 is approved and locked at its current implementation: “Hearing Care That Feels Like Family,” pine background, genuine front-desk image, gold booking CTA, qualified proof row, “150+ reviews,” and user-supplied “5+ years of professional care.” This supersedes earlier S1 awaiting-review notes. S0 remains locked. Do not materially change either section without discussing a user request or a genuine consistency/responsive dependency. The approved welcome video remains planned for S1A; review that section separately and do not build or advance automatically.

## Step 5 implementation — S1A welcome video popup

The user chose popup playback for the approved welcome video. Implement the cream editorial section immediately after the locked S1 hero and before recognition. Heading: **Meet the People Behind Your Hearing Care**. Introduce the team, practice, and first-visit expectations using the clinic’s own description; do not duplicate hero proof or add another booking CTA.

- Desktop from 1000 px: real 16:9 poster left, heading/copy right, shared gutters, 64 px gap. Below 1000 px: heading/copy first, poster second. Cream surface, pine text, emerald eyebrow, 18 px photo corners; 72 px desktop and 48 px mobile padding.
- Genuine poster: `https://altamontefamilyhearing.com/assets/video/welcome-crop-poster.webp`, verified 1280 × 720. Preserve all four people. Visible play label: **Watch our welcome video**. No AI image or animated background loop.
- Clicking the poster opens a native modal dialog with the approved video `HxCXX0CgR9s` from YouTube. Create the privacy-enhanced iframe only after the click; playback may start from that deliberate action, never on page load. Provide a named close button, Escape handling, background scroll lock, focus return, and permanent Watch on YouTube fallback. Remove the player on close to stop playback.
- Hide the existing mobile call bar during the video popup using the existing modal state. Booking remains a separate dialog with its original behavior. Keep the full 16:9 player and allow popup scrolling in short viewports.
- Popup mechanics and layout can be verified locally; external YouTube playback remains unverified in this environment. Do not claim successful playback or captions without checking the actual player.
- S0 and S1 stay locked and unchanged. S1A awaits user review and is not locked. Do not advance automatically.

## Step 5 S1A visual refinement — user-requested gradients

The user asked for stronger graphic design and more gradients in the welcome-video section. Add subtle cream/mist and warm-gold background gradients, an 8 px graduated paper/mist/gold video frame with restrained brand shadow, a small gold eyebrow rule, emerald italic emphasis on “Hearing Care,” and a softly graduated play control. Keep original copy, genuine 16:9 poster, mobile content order, video source, and popup behavior. Desktop section padding is 88 px; mobile remains 48 px. This authorized visual refinement supersedes the earlier flat cream treatment. S1A remains awaiting review; locked S0/S1 and all other sections are unchanged.

## Step 5 approval — S1A locked and continuing design standard

9 October 2026: the user approved the refined welcome-video section and explicitly requested maintaining these design standards for every section. S1A is now locked at the current implementation, including cream/mist and warm-gold gradients, graduated video framing, restrained shadow, gold accents, emerald italic heading emphasis, genuine poster, and popup playback. This supersedes earlier S1A awaiting-review notes.

For all remaining sections, maintain this level of intentional graphic design: strong composition, clear hierarchy, thoughtful typography, generous purposeful whitespace, authentic imagery, subtle brand gradients where useful, and restrained depth/framing. Adapt the visual treatment to each section’s purpose; do not repeat the same gradient, split layout, cards, or italic heading formula mechanically. Continue the approved one-section-at-a-time review, headline options, discussion, implementation, and approval workflow. Preserve useful facts and qualifications. S0, S1, and S1A remain locked; explain any necessary material change before making it. Do not advance automatically.

## Step 5 S2 implementation — recognition section

The user approved headline option 1, **Does Any of This Sound Familiar?**, and the recommended open two-column symptom layout. Replace the earlier split introduction/list with a full-width introduction and six labeled concern rows in one softly graduated mist/paper region. Use emerald line icons, quiet dividers, no individual cards, and genuine Satoshi 600 row labels. Two columns from 768 px; one column below, preserving DOM reading order.

Retain repetition requests, hearing speech but missing words, noisy situations and listening fatigue, TV/phone volume, ringing/buzzing/humming/hissing, and poorly performing existing aids. Group the no-assumed-aids reassurance, normal-results statement, and family-support cue beneath the rows. Keep the urgent-change guidance visible in a separate paper strip with red left accent and readable warning label; no closed disclosure. No new CTA, photograph, or image prompt is needed. S0, S1, and S1A remain locked and unchanged. S2 is implemented for review and is not yet locked.

## Step 5 S2 compactness refinement

The user requested a more compact layout and improved content density after approving the section’s substance. Keep the headline and all six concerns. Use three columns/two rows from 1200 px, two columns from 768–1199 px, and one column below 768 px. Tighten row padding, icon spacing, introduction, section padding, and reassurance grouping while retaining 18 px description text and readable 1.5 leading. Shorten labels and repetitive descriptions without losing noisy settings, fatigue, ringing/buzzing/humming/hissing, existing-aid problems, or normal-results reassurance. Remove the redundant eyebrow and family-support paragraph here; family-member attendance remains explicitly covered in S3. The optional family-notices-first observation is omitted for focus. Preserve the urgent-change note in full, visible with red accent. S2 remains awaiting review; locked sections and S3 are unchanged.

## Step 5 S2 supporting-text width

At the user’s request, remove the recognition introduction’s 900 px maximum and its supporting paragraph’s measure limit. Supporting text uses the full shared content width; page gutters and container remain unchanged. S2 remains awaiting approval.

## Step 5 approval — S2 locked

The user said “Looks good, lets move to the next” after the compactness and full-width supporting-text refinements. S2 is approved and locked at its current implementation. Review S3 first visit next; retain the preference for compact information architecture, readable text, and deliberate graphic design. S0, S1, and S1A remain locked.

## Step 5 S3 first-visit implementation

The user approved the recommended first-visit direction. Implement **Your First Visit, Explained** with a genuine portrait beside four numbered open steps in a two-by-two desktop arrangement. Retain hearing/health history and medication relevance; otoscope/wax check and appropriate referral; tones and speech in quiet/noise; same-visit audiogram explanation, take-home record, and choices based on hearing/lifestyle/preferences/budget. Concise language replaces repeated symptom examples already covered in S2.

Use a single compact graduated mist/paper practical-information band for qualified cost and preparation. Keep “Most hearing evaluations are complimentary” immediately beside the call-to-confirm instruction; preserve current aids, insurance/benefits check, adults of all ages, and family support. Retain Book Appointment and phone assistance.

Correct `AFH-A-29.webp` to its verified original 1201 × 1800 portrait dimensions; display a tested 4:5 crop with an accurate earpiece-preparation caption and 6 px restrained graduated frame. No AI generation or editing. From 1100 px use photo/steps columns; below this, show steps, practical band, action, then photo. Steps have two columns from 768 px and stack below. Use 18 px body text and 56/40 px desktop/mobile section padding.

The implementation awaits final review; S3 is not yet locked. S0–S2 and the video section remain locked and unchanged. Review the rebuilt S3 before proceeding to S4.

## Step 5 S3 hierarchy refinement

The user requested improved design and visual hierarchy after reviewing S3. Keep the existing headline above the entire composition, with a restrained gold-to-mist horizontal rule extending across the remaining desktop width. Reduce heading-to-content spacing to 24 px. Use a slightly narrower photograph column (3.6/7.4 split, 40 px gap) and group the four open steps in one subtle cream/mist gradient region. Place 38 px emerald/cream numbers beside 21 px Satoshi 600 headings; supporting copy is secondary pine and remains 18 px. Use quiet internal dividers rather than individual cards.

On mobile, retain one column with numbered headings and full-width descriptions beneath them; do not force the paragraph into a narrow number-offset column. Keep practical information separate with a visible “Before you come in” heading and desktop divider. All prior content and qualifications, image/crop, action labels, and booking behavior remain unchanged. S3 still awaits final approval; locked sections are unchanged.

## Step 5 S3 preparation hierarchy

At the user’s request, clarify the “Before you come in” hierarchy: a 24 px section subheading, three descriptive emerald 16 px labels (Who it’s for / What to bring / Who can join you), and 18 px supporting answers. Use a semantic definition list with quiet dividers. From 1200 px labels and answers align in columns; below, labels sit above their answers. Preserve adults of all ages, current aids, insurance/benefits check, and optional family support. No other copy, layout, image, or behavior changes. S3 remains awaiting final approval.

## Step 5 S3 action alignment

The user approved the preparation hierarchy and requested centering the booking/phone action group beneath the practical-information band. Center the S3 CTA row, retaining mobile full-width booking and existing labels/behavior. S3 still awaits final section approval.

## Step 5 S3 action placement correction

The user corrected the previous request: undo centering below the band and place the booking/phone actions in the empty space inside the practical-information box. Move the action group beneath the qualified cost explanation in the left column, using natural left alignment and 20 px spacing. Allow responsive wrapping; retain full-width mobile booking, original labels, and dialog behavior. This supersedes the prior centered-row decision. S3 remains awaiting final approval.

## Step 5 S3 bottom-aligned actions

At the user’s request, anchor the booking/phone action row to the bottom of the left practical-information column from 768 px, using flex layout and automatic top margin with 20 px minimum spacing. Preserve box padding and natural mobile flow. No fixed heights or absolute positioning. S3 remains awaiting final section approval.

## Step 5 approval — S3 locked

The user said “Looks good, let’s proceed with the next” after the first-visit hierarchy refinements and bottom-aligned booking/phone actions inside the practical-information band. S3 is approved and locked at its current implementation. This supersedes prior awaiting-review notes. Review S4 fitting verification and ongoing care next; do not alter locked sections without discussing a genuine dependency or user request.


## Step 5 — S4 approved rebuild direction, awaiting section review

The user approved headline option 1, **Care That Goes Beyond the Hearing Aid**, and the recommended editorial layout with expandable technical detail. S4 now uses a restrained pine gradient, a benefit-first REM explanation next to the genuine AFH-C-196.webp procedure image, a distinct EAA device-check explanation, and a full-width cream/mist ongoing-care band. The user-specified **5+ years of professional care** retains its immediate office-purchase and all-technology-level qualification. Follow-up visits and recommended six-month professional cleanings remain visible. HearingUp certification, network attribution and six manufacturer names remain in a compact lower credibility row. The identical-settings/ear-canal-average example is preserved inside native details, with the main measurement method and limitations visible. Mobile brings the photo next to the explanation early, stacks the practical care and proof content, and uses a full-width booking action. No new claims, generated imagery or changes to locked S0–S3. S4 awaits user review and is not locked.


## Step 5 — S4 information architecture refinement

The user found S4 cluttered and requested a stronger layout/information architecture. The approved headline and pine editorial direction remain. The visible method content now consists of two parallel, benefit-first checks: **Measured in your ear** (REM against individual hearing-test targets) and **Device checked before fitting** (EAA against manufacturer specifications). Removed the redundant eyebrow, separate limitation line, inset EAA rule and repeated explanatory image caption. Preserved the full probe-tube method, soft/average/loud measurements, average-ear example, outcome limitation and EAA specifications inside one native **Explore how we verify your fitting** expansion after both checks. The feature is vertically balanced with wider column separation; the genuine 3:2 photo is unchanged. Ongoing-care bullets now have concise inline labels rather than another layer of headings. Purchase qualifications, care duration, follow-ups, cleaning recommendation, certification and manufacturer choice remain. This is a user-requested presentation refinement within the approved strategy, awaiting review; S4 is not locked.


## Step 5 — S4 approved and locked

The user said “Perfect, lets move to the next section” after increasing the fitting-verification disclosure heading to 18px and removing the CTA supporting text max-width. S4 is approved and locked in its current form. This supersedes awaiting-review notes. Review S5 care options next without modifying approved sections.


## Step 5 — S5 care-options rebuild, awaiting review

The user approved **Hearing Care for Your Next Step** and concise service summaries with expandable technical detail, retaining essential costs, suitability and limitations visibly. S5 uses six open typographic service entries, two columns from 768px and a single-column mobile reading order, with 18px summaries, 17px qualifications and true-weight Satoshi headings. Four native disclosures retain fitting/adjustment detail, repair components and factory-service distinctions, tinnitus sound-therapy context, and irrigation exclusions. Most-complimentary evaluation wording with cost confirmation, adult scope, hearing-aid outcome limits, repair support for aids bought elsewhere, no universal same-day repair/cure promises, screening/referral, and Toni’s Greater Orlando home-care cost/availability and equipment qualification remain visible. The genuine repair photo supports a smaller cream/mist gradient walk-in band whose focal point is Monday–Friday, 1:00–2:00 pm, with no appointment needed for cleanings and minor repairs. The six-month cleaning explanation remains in repair details; S4 already presents the same recommendation. No manufacturer repetition or service-button clutter. S5 awaits user approval; S0–S4 remain locked and unchanged.


## Step 5 — S5 compact information architecture refinement

The user requested less scrolling without losing quality. S5 now shows three open service columns from 1100px, two from 768px, and a single mobile column. Shorter titles and integrated summary/qualification paragraphs reduce repeated text blocks; visible cost, suitability, outcome, repair, tinnitus and home-care limitations remain. Fitting selection criteria, repair service verbs and tinnitus sound examples were moved into their existing disclosures, not deleted. Four expandable explanations retain useful technical information. Body copy remains 18px, disclosure controls 17px with a 44px minimum target, and headings remain 21–22px. Reduced section/entry spacing and a shorter lead improve density. The genuine repair photo is capped at 240px on desktop and omitted below 768px so the walk-in hours, no-appointment scope and support for aids bought elsewhere take priority. Measured collapsed section heights decreased from 1393 to 906px at 1440px and from 2598 to 1837px at 390px. Responsive, enlarged-text, disclosure keyboard and phone-link checks pass. S5 awaits review; approved sections are unchanged.


## Step 5 — S5 visual hierarchy refinement

The user requested improved hierarchy after approving the compact direction. Each service heading now pairs its true-weight 22px Satoshi title with a restrained 32px gradient-backed line icon: ear, adjustment controls, repair tool, sound wave, water drop, home. Icons are decorative, hidden from assistive technology, and do not represent medical credentials. Key facts receive emerald emphasis. Expansion labels are shorter and specific; outlined plus/minus controls align at the end of each entry, with 44px interaction targets. Service entries use flex columns so expansion controls and the home-care phone link align at the bottom of desktop rows. Three/two/one-column structure, facts and disclosures are unchanged. The photo/walk-in band remain unchanged. Height is essentially preserved (921px at 1440px, 1888px at 390px). Responsive, keyboard, phone-link and enlarged mobile-text checks pass. S5 remains awaiting user approval; earlier locked sections are unchanged.


## Step 5 — S5 walk-in band refinement

At the user’s request, the walk-in band now separates service identity and eligibility from schedule/access. The genuine repair photo is capped at 200px beside a 28px serif service heading, a concise message welcoming aids bought elsewhere, and a dedicated hours group: Monday–Friday, 1:00–2:00 pm, No appointment needed. Wide desktop uses a three-part composition with a quiet vertical divider; tablet stacks the schedule within the copy column; mobile omits the photo and stacks service then hours with a horizontal divider. The no-appointment message uses a restrained emerald label with paper text. Hours and scope are unchanged. Aids bought here remain included by the general welcome wording. Plus/minus disclosure icons now sit directly beside their labels with a 10px gap as separately requested. S5 awaits review; locked sections remain unchanged.


## Step 5 — S5 approved and locked

The user explicitly approved the care-options section after its compact three-column desktop layout, service-heading icons, emerald emphasis, disclosure controls beside their text, and refined walk-in band. S5 is now approved and locked in its current implementation. This supersedes all earlier awaiting-review notes. Preserve the headline **Hearing Care for Your Next Step**, service facts and expandable details, responsive layout, and genuine repair photo with the separated schedule/access treatment. Do not materially change S5 without discussing the dependency or receiving an explicit request. S6 (provider/team section) is next, but has not been reviewed or authorized for rebuilding.


## Step 5 — S6 paired-provider rebuild, awaiting review

The user approved headline option 4, **A Family-Owned Practice, With Personal Care**, and the compact paired-provider layout with a smaller coordinator band. S6 now presents Jaysee and Toni together in one restrained paper/mist gradient editorial group at 1100px+, with more space for Jaysee’s credentials. Name, HAS/BC-HIS credentials and Florida-licensed role stay attached to each provider. Jaysee’s ownership with Grace, hearing care since 2013, BC-HIS explanation, HearingUp certification and whole-visit Spanish availability remain visible. West Palm Beach career origins, Florida Hearing Society District 5 Director role and educational work as “The Bald Hearing Guy” remain in a native More about Jaysee disclosure. Toni’s firsthand experience wearing aids since childhood and home/facility care role remain visible; no Spanish or BC-HIS attribution is made to Toni. Grace and Francesca retain distinct coordinator functions; Grace’s co-ownership remains explicit. Their bilingual support is stated once in the shared coordinator introduction. Specialist scope/referral and Spanish evaluation/forms/resources information remain in the concluding support note. Body 18px; fact/coordinator copy 17px; role 16px; provider names 27px/24px mobile. Authentic portraits are displayed as gentler square crops, with no edits or generated replacements. Below 600px, portraits stay beside names/roles while bios span the full width for readability. S6 awaits user approval; S0–S5 remain locked and unchanged.


## Step 5 — S6 larger provider portraits without added height

The user requested larger Jaysee and Toni images without increasing section height. Provider portraits now use 4:5 desktop/tablet crops: Jaysee scales from 160px to 200px wide across 1100–1440px viewports; Toni scales from 140px to 180px. Below the paired layout breakpoint, both use 200px-wide portraits until the mobile layout. Mobile portraits increase from 96px to 112px square. The original photographs, faces and image positioning remain unchanged; coordinator portraits stay 88px/80px square. Credentials now sit inline alongside names, and modest gap reductions offset the larger images. No copy or text-size reductions. Before/after browser measurements at 320, 390, 768, 1024, 1100, 1280, 1440 and 1600px verify that total collapsed section height does not increase. S6 is still awaiting review.


## Step 5 — S6 approved and locked

The user instructed “Let them be, lets move to the next section” after reviewing the enlarged portraits and asking about copy reduction. Keep the team copy unchanged; the proposed intro and Toni paragraph edits were declined. S6 is approved and locked with its current enlarged portraits, compact paired-provider layout, full credentials and coordinator/referral/language information. This supersedes earlier awaiting-review notes. Review S7 Google reviews next; do not alter S6 without an explicit request or discussed dependency.


## Step 5 — S7 Google reviews rebuild, awaiting review

The user approved headline option 4, **Personal Care, Described by Patients and Families**, and three primary reviews with three supporting reviews expandable on desktop. S7 now has a coordinated headline/5.0 aggregate proof header on a restrained pine gradient, preserving **150+ Google reviews**. Teri Yanovitch, Philip Zeitler and jan bradburn remain the immediately visible primary set on every device. Clear editorial theme labels are separate from quotations. Philip’s excerpt is shortened to the exact contiguous original passage “took the time to clearly explain the results in a way that we could all understand.” All six full texts, names/capitalization, ratings, excerpt attribution, Google destination and Rocio’s adjacent specialist-scope clarification remain unchanged. Steve Marsee, Emily Palo and Rocio M Stevens are inside native More patient experiences disclosure on desktop/tablet; this disclosure is omitted below 768px to preserve the three-review mobile maximum. Individual full-review disclosures remain available. Desktop names/disclosure controls align across equal-height cards; expansion plus/minus icons sit next to text. Rating, reviewer text and link remain accessible; no reviewer photos, generated avatars, Google screenshot imitations or extra imagery. The Google link is quieter than the booking action, with booking at the end of the proof group. Responsive widths 320–1440px, keyboard expansion of all six reviews and the supporting group, mobile review counts, booking dialog and enlarged text checks pass. The closed section is 836px at 1440px versus 1326px before. S7 awaits user approval; S0–S6 remain locked and unchanged.


## Step 5 — S7 approved and locked

The user explicitly approved the reviews section and requested the next section. S7 is approved and locked with the chosen headline, 5.0/150+ aggregate, three primary reviews, desktop/tablet supporting-review disclosure, unchanged full text and attribution, and Google/booking actions. Supersedes previous awaiting-review notes. Review S8 FAQs next; do not modify locked sections without a user request or discussed dependency.


## Step 5 — S8 grouped FAQs rebuild, awaiting review

The user approved **Your Hearing Care Questions, Answered**, two FAQ groups and modest tightening of repeated answers. S8 now uses full-width content with **Planning your visit** and **Your hearing and hearing aids** columns from 1000px, stacked below. Costs/insurance remain first, followed by aids-needed, home visits, Spanish and provider scope; the second group covers existing aids, adjustment, tinnitus, wax and sudden changes. All eleven topics remain as accessible native details, closed initially. True-weight 18px questions and 18px answer text preserve readability; plus/minus icons follow the text inline, including wrapped mobile questions. Cost, coverage, tinnitus, sudden-loss, earwax and adjustment answers are unchanged. The existing-aid answer omits repeated factory-repair examples already preserved in S5; manufacturer coordination and walk-in hours remain. Home-care and provider introductions are shortened with scope, credentials, testing limitations, costs/availability and coordinator support preserved. The support invitation is a restrained cream/mist gradient band with one phone action. No imagery or tabs. Keyboard checks cover all eleven disclosures, all-expanded mobile/desktop states, enlarged mobile text and phone destination. S8 awaits approval; S0–S7 remain locked and unchanged.


## Step 5 — S8 visual hierarchy refinement

At the user’s request, FAQ group headings now use a restrained mist-to-paper band, 24px true-weight Satoshi titles and decorative calendar/ear line icons. Questions use 18px medium weight to separate their hierarchy from category headings; plus/minus controls remain inline beside the text. Open questions become emerald, and answers receive a quiet left rule. Row padding is tightened to offset category treatment, keeping desktop section height effectively unchanged. All eleven questions and answers are unchanged. Responsive, all-expanded, keyboard, phone-link and enlarged-text checks pass. S8 remains awaiting approval.


## Step 5 — S8 approved and locked

The user requested moving to the next section after the hierarchy refinement and soft-yellow right endpoint (#F3E4AE) on FAQ group heading gradients. S8 is approved and locked with all eleven grouped FAQs, inline controls, unchanged care qualifications and medical guidance, and phone-support band. Supersedes prior awaiting-review notes. Review S9 appointment request next.


## Step 5 — S9 appointment-request rebuild, awaiting review

The user approved **Request an Appointment** and the balanced introduction/form layout. S9 now uses a restrained cream/mist background with a soft-yellow upper-right gradient and graduated 6px form frame. The introduction is wider (5:7 desktop split from 1000px), with a short invitation and a distinct **After you submit** explanation that an appointment request does not confirm a time. Phone and direct-online-booking alternatives are quieter text actions, separated beneath the explanation on desktop and after the form on mobile. Privacy Policy sits immediately below the form and announces its new-tab behavior accessibly. The original Onspire Pulse iframe and form_embed.js script are preserved byte-for-byte, including the formEmbed ID fix, supplied attributes, consent settings and source. No fields, consent text, submission behavior or response-time promises were invented or changed. The frame has no fixed height that could prevent the vendor’s resizing; existing minimum iframe heights are retained. No imagery. Surrounding layout checks pass at 320–1440px, including mobile reading order, enlarged text, booking-dialog behavior and phone/privacy destinations. Automated inspection of the external widget returned HTTP 403; its actual contents and submission were not verified, and no request was submitted. Review the live form in the user’s browser before final approval. S9 awaits review; S0–S8 remain locked and unchanged.


## Step 5 — S9 quieter appointment confirmation

At the user’s request, remove the prominent **After you submit** block and its bold appointment-time warning. Replace it with the quiet 16px sentence **Our team will help confirm your appointment.** immediately below the form, followed by Privacy Policy. This approved treatment supersedes the previous requirement for a prominent request/confirmation explanation; the heading and invitation still describe an appointment request. Checked the clinic’s live homepage, /contact and /schedule: visible copy offers contact messaging and direct booking, with no comparable appointment-confirmation warning. Their contact messaging promises a reply within one business day; do not import that deadline into this separate campaign form without confirmation. Preserve the vendor embed and all locked sections. S9 remains awaiting final approval.


## Step 5 — S9 approved and locked

The user explicitly approved the appointment-request section. S9 is approved and locked with **Request an Appointment**, the balanced introduction/form layout, cream/mist/yellow treatment, unchanged Onspire Pulse embed, quiet **Our team will help confirm your appointment.** sentence beneath the form, Privacy Policy, and secondary phone/direct-booking actions. The prominent **After you submit** block remains removed. This approval supersedes previous awaiting-review notes; external form submission remains unverified by automation. S0–S9 are locked. Do not materially change them without a user request or a discussed consistency/responsive dependency. Do not advance automatically; S10 location is the next section when the user requests it.


## Step 5 — S10 location rebuild, awaiting review

The user approved **Visit Us in Altamonte Springs** and the compact practical layout. S10 now uses an open address/hours column and a wider, shallower map column from 1000px; smaller screens show visit details before the map and directions. The address remains readable outside the map, **Inside One Senior Place** receives emerald emphasis, and office hours use compact labeled rows with weekday opening hours emphasized. Lunch and weekend closures remain visible. A restrained mist-to-yellow strip separately presents weekday 1–2 pm walk-in cleaning/minor repairs and no appointment needed. Remove the optional nearby-town sentence only; preserve all practical visit facts. The map is 360px high desktop/tablet and 280px on mobile, with a subtle gradient frame and icon-led Get Directions below it. This approved shallower composition supersedes the baseline approximate 4:3 map proportions. Original map/directions URLs remain unchanged. The iframe URL matches the clinic’s live contact-page embed and returns clinic name/address; browser interaction with the external map was not tested. Layout, mobile order, enlarged text and utility-link checks pass at 320–1440px. No exterior asset, invented parking/access claims or AI image. S10 awaits approval; S0–S9 remain unchanged and locked.


## Step 5 — S10 approved and locked

The user approved the location section with **Visit Us in Altamonte Springs**, the open address/hours column, emphasized One Senior Place landmark, compact walk-in strip, shallower responsive map and Get Directions below it. All practical address, phone and schedule details remain; the optional nearby-town sentence remains removed. No photograph is required. This approval supersedes prior awaiting-review notes. S0–S10 are approved and locked; do not materially change them without a user request or a discussed consistency/responsive dependency. Do not advance automatically. The closing invitation and footer are next when requested.


## Step 5 — S11 closing invitation rebuild, awaiting review

The user approved headline option 1, **Take the Next Step Toward Easier Conversations**, and the recommended compact split composition. S11 now pairs the benefit headline and one supportive sentence with a separate booking area from 1000px; below this the actions follow the copy. The gold Book Appointment button remains dominant, the phone alternative remains quieter, and **Hablamos español.** is a separate supporting cue. The approved sentence is **Start with a hearing evaluation. We’ll explain your results and talk through the options for your needs.** Selective soft-gold italic emphasis, a subtle emerald glow on pine, and a quiet desktop vertical divider give the final invitation a deliberate finish. The mobile button is full-width. Desktop padding is reduced to 56px for the approved compact layout; mobile remains 40px. No new claim, urgency, service inventory, form, review or image is introduced. The existing quiet footer separator remains; footer markup/styles and locked S0–S10 are unchanged. Responsive checks at 320–1440px pass, including mobile reading order, enlarged text, phone destination, booking-dialog opening/Escape closure and focus return. External booking-calendar contents were not exercised. S11 awaits approval; review the footer separately after approval and a user request to proceed.


## Step 5 — S11 approved and locked

The user explicitly approved the closing invitation. S11 is approved and locked with **Take the Next Step Toward Easier Conversations**, the compact desktop split composition, selective gold italic emphasis, subtle emerald glow, evaluation/results/options supporting sentence, dominant gold booking action, quieter phone alternative and separate Spanish-support cue. Mobile retains stacked reading order and a full-width booking button. No imagery is required. This approval supersedes previous awaiting-review notes. S0–S11 are approved and locked; do not materially change them without a user request or a discussed consistency/responsive dependency. The footer remains unchanged and is the next section to review when the user requests proceeding.


## Step 5 — S12 footer refinement, awaiting review

The user approved **Contact & Location** and the compact footer treatment. S12 now uses aligned brand, contact and utility-link groups on desktop, stacked identification/contact and wrapping utility links on mobile. Preserve the genuine white logo, exact identity sentence, address/One Senior Place, phone and required Privacy Policy/Visit Our Website destinations. Contact heading uses true-weight 18px Satoshi; body text is 16px and phone 18px. Links have at least 44px targets and new-tab utility links announce that behavior to assistive technology. Remove only the generic **Links** heading; utility navigation has a descriptive accessible label. The existing reversed logo was verified at 626×144; correct its HTML dimensions from 626×209 without replacing the asset. Footer spacing is tighter with quiet separators. Source retains the GHL **{{location.name}}** merge token and dynamic year. The publishing helper resolves the token to **Altamonte Family Hearing** only in the static GitHub Pages preview. Responsive checks at 320–1440px pass, including real logo loading/dimensions, enlarged mobile text, utility target sizes, phone link and resolved preview copyright. No photograph or generated imagery is needed. S0–S11 markup/styles remain unchanged and locked. S12 awaits approval.


## Step 5 — S12 approved and locked; section review complete

The user explicitly approved the footer. S12 is approved and locked with **Contact & Location**, the genuine reversed clinic logo with corrected dimensions, readable contact details, required utility links with comfortable targets, compact responsive composition and quiet separators. Static preview copyright resolves to **Altamonte Family Hearing**; source retains the GHL **{{location.name}}** merge token and dynamic year. This approval supersedes previous awaiting-review notes. All sections S0–S12, including the welcome-video section, are approved and locked. The section-by-section design review is complete. Do not materially change approved sections without a user request or a discussed consistency/responsive dependency. Design approval does not establish external request-form submission or booking-calendar functionality, which were not exercised; it does not authorize a production deployment or a main-branch push.

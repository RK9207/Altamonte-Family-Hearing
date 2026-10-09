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


\# Design system — Better Hearing Health

Version 1 · 9 October 2026 · Governs Steps 4 and 5

Use with \[PAGE\_STRATEGY.md\](PAGE\_STRATEGY.md) and \[CONTENT\_DIRECTION.md\](CONTENT\_DIRECTION.md). This is an implementable visual direction for a clinic with high design standards: confident typography, carefully composed real photography, precise alignment, and accessible interactions. Step 4 uses these defaults; Step 5 refines the actual page with the user while keeping the governing documents aligned.

\#\# Evidence, proposed choices, and asset status

\*\*Supported by the supplied research:\*\* primary theme color \`\#1A3028\`; independent, warm, people-first clinic identity; editorial heading treatment with occasional italic emphasis; real clinic/staff imagery. The logo supplied in chat was visually inspected and supports a green, serif-led identity.

\*\*Proposed for this landing page:\*\* every other palette token below, DM Serif Display/Manrope font pairing, numerical type/spacing scales, radius, borders, and component treatments. These are deliberate design choices, not extracted clinic CSS. Website access failed at the network proxy with HTTP 403, so exact current fonts, secondary colors, button shapes, and visual equivalence could not be independently verified. When direct brand evidence becomes available, compare it before finalizing; explain any meaningful design departure and obtain the user's approval rather than silently swapping systems.

\*\*Asset register:\*\*

| Asset | Current evidence/access | Governing use |  
|---|---|---|  
| Original clinic logo | Supplied chat image and original URL in the brief | Production identity source; prefer original/vector artwork if available. |  
| Generated logo upscale | Local file \`../generated\_images/exec-e9d98e1c-699d-4dde-a15e-856520719b74.png\`, 2174 × 723 px; visually inspected | Candidate only. Generative upscaling can change marks, letter shapes, spacing, and color. Compare against the original before adoption; do not assume brand-perfect fidelity or use it as a new vector master. |  
| Review screenshots | Research reports seven supplied captures and provides text in Section 11; original screenshot files unavailable here | Accessible review text is the working asset. Use screenshot crops only after actual files are accessible and checked. |  
| Clinic/staff/procedure photos | Candidate filenames in research Section 9; files and full URLs not available here | Retrieve genuine assets from confirmed source paths before implementation; do not invent CDN URLs from filenames. |  
| HearingUp/manufacturer marks | Reported in research, actual assets not inspected | Optional authentic logos with appropriate usage; text identification is an acceptable fallback. |  
| Exterior/wayfinding image | No verified file | Optional future asset; no generated substitute suggesting a real location. |

Do not recolor or redraw identity assets. The original logo has a light background; place it on a compatible light surface, preserve its aspect ratio, and do not treat background removal as already authorized or completed. Prefer a genuine reversed logo for dark placement rather than CSS inversion.

\#\# Brand foundation and color tokens

Green carries identity and conversion. Warm neutral surfaces make the page welcoming. Sage adds quiet tonal separation; brass is a very small decorative accent. Do not make the page a succession of unrelated colored panels.

| Token | Hex | Role / status |  
|---|---|---|  
| \`brand-primary\` | \`\#1A3028\` | Research-supported pine green; primary CTA, major headings, closing panel, mobile Call bar. |  
| \`brand-secondary\` | \`\#587367\` | Proposed muted sage; secondary graphic accents and selected decorative details, not default body text. |  
| \`accent-brass\` | \`\#B69A64\` | Proposed warm supporting accent; small rules/details only. Not a default CTA or small text color. |  
| \`background-page\` | \`\#F8F6F0\` | Proposed warm ivory main canvas; hero and selected editorial sections. |  
| \`surface-white\` | \`\#FFFFFF\` | Form surfaces, selected review cards, primary text on dark green. |  
| \`surface-sage\` | \`\#E5ECE6\` | Proposed pale sage for a restrained method callout or trust surface. |  
| \`surface-warm\` | \`\#EFEAE0\` | Proposed warm supporting background, e.g. location region. |  
| \`text-primary\` | \`\#1A3028\` | All main text on light surfaces. |  
| \`text-secondary\` | \`\#4D5D54\` | Supporting copy with meaningful contrast; not tiny gray text. |  
| \`text-inverse\` | \`\#FFFFFF\` | Main text on primary-green surfaces; mobile call text/icon must be pure white. |  
| \`border-subtle\` | \`\#D5DDD5\` | Noninteractive separators and card outlines. |  
| \`border-control\` | \`\#687A6F\` | Proposed stronger control boundary; validate 3:1 where needed to identify an input/control. |  
| \`cta-primary\` | \`\#1A3028\` | Filled booking CTA with white label. |  
| \`cta-hover\` | \`\#274A3C\` | Slightly lighter green on hover, white label retained. |  
| \`cta-active\` | \`\#12231C\` | Pressed state. |  
| \`focus-light-surface\` | \`\#245D91\` | Proposed visible blue focus ring on light backgrounds, separated from component edge. |  
| \`focus-dark-surface\` | \`\#FFFFFF\` | High-visibility focus ring on green backgrounds with adequate offset. |  
| \`status-error\` | \`\#8C2E2E\` | Error text/icon plus explicit message; not color alone. |  
| \`status-success\` | \`\#24543C\` | Confirmed status only; never imply cross-origin booking success without evidence. |

Validate all final combinations against WCAG AA: 4.5:1 for normal text, 3:1 for large text and necessary non-text indicators. White on \`\#1A3028\` is the primary reliable button pairing. Test hover/focus and image-overlay states, not only static tokens. Brass, low-opacity text, and subtle borders cannot carry essential labels or control boundaries. Underline in-body links so color is not their sole distinction.

\#\# Typography

\*\*Heading font:\*\* proposed \*\*DM Serif Display\*\*, regular 400; genuine italic for occasional short emphasis. Fallback: \`Georgia, "Times New Roman", serif\`.

\*\*Body/UI font:\*\* proposed \*\*Manrope\*\*, 400 body, 500 supporting labels, 600 buttons/nav and key facts, 700 occasional small headings. Fallback: \`system-ui, \-apple-system, "Segoe UI", sans-serif\`.

Use properly licensed font files, preferably local WOFF2; \`font-display: swap\`. Load only needed weights/styles, and do not synthesize a fake bold serif. Font acquisition and rendering are not completed by this document. Compare proposed fonts to the live brand once access is possible; do not call them the clinic's existing fonts.

| Role | Desktop ≥ 1100 px | Tablet 768–1099 px | Mobile \< 768 px | Line height / notes |  
|---|---|---|---|---|  
| H1 | 60–68 px, default 64 | 48–54 px | 36–42 px, default 38 | 1.08 desktop; 1.14 mobile; normal weight; slight tracking down to −0.02em only if legible. |  
| H2 | 42–48 px, default 44 | 36–40 px | 30–34 px | 1.15–1.2; use informative headings, not giant decorative words. |  
| H3 | 26–30 px | 24–28 px | 23–26 px | 1.25; serif for editorial subheads, sans 600 for functional service headings. |  
| Body | 18 px | 18 px | 17–18 px, default 18 | 1.65; narrow dense modules may use 1.55. |  
| Lead / hero support | 20 px | 19–20 px | 18–19 px | 1.6; no overly wide lines. |  
| Small/supporting | 15–16 px | 15–16 px | 15–16 px | 1.5–1.6; qualifications stay comfortably readable. |  
| Buttons/navigation | 16 px / 600 | 16 px / 600 | 15–16 px / 600 | 1.3; no all-caps CTA labels. |  
| Eyebrows | 13–14 px / 600 | Same | Same | 1.4, optional 0.08em tracking; short labels, not paragraphs. |

Use fluid interpolation inside these ranges, not text scaled with viewport width without bounds. One H1. Use semantic H2/H3 progression. Body lines should generally be 55–70 characters; hero copy 38–52 characters; long FAQ answers no wider than 72 characters. Hero headline roughly 12–18 characters per line where composition allows, with two or three meaningful lines; never force a word into an awkward orphan by hardcoding desktop line breaks on mobile.

Limit italic to one purposeful phrase in a heading, and use it selectively rather than in every section. Device acronyms, uppercase labels, and tiny legal type must not dominate a page used by older adults. Respect text enlargement to 200% and reflow at 400% zoom.

\#\# Layout and rhythm

| Token / rule | Default |  
|---|---|  
| Main container | Maximum 1200 px, centered; viewport gutters included in available width. |  
| Narrow reading region | Maximum 760–800 px for FAQ and explanatory content; body text itself typically ≤ 70ch. |  
| Desktop horizontal gutters | 40 px; allow 48 px on very wide screens. |  
| Tablet horizontal gutters | 28–32 px. |  
| Mobile horizontal gutters | 20 px; 16 px only below 360 px if needed. |  
| Desktop section padding | 88–104 px vertical; default 96 px. Functional S2/closing regions can use 56–72 px. |  
| Tablet section padding | 64–80 px; default 72 px. |  
| Mobile section padding | 48–64 px; default 56 px. Compact utility regions 32–40 px. |  
| Spacing scale | 4, 8, 12, 16, 24, 32, 40, 48, 64, 80, 96 px. |  
| Section heading to content | 32–40 px desktop, 24–28 px mobile. |  
| Two-column editorial gap | 48–64 px desktop; 32 px tablet; 24–32 px when stacked. |  
| Grid gap | 24 px desktop; 20 px tablet; 16–20 px mobile. |  
| Card inner space | 24–32 px desktop; 20–24 px mobile. |  
| Functional target size | Minimum 44 × 44 px; default primary buttons ≥ 48 px high. |

\*\*Breakpoints:\*\* below 480 px compact mobile; 480–767 px wide mobile; 768–1099 px tablet; 1100 px and above desktop. Select layout changes based on actual content fit. Use the compact header below 1100 px so nav, readable logo, phone, and booking are never squeezed into an unusable row. Mobile review cap and bottom Call bar apply below 768 px.

\*\*Grid:\*\* a 12-column desktop foundation with hero approximately 6/6 and method/visit sections 5/7 or 6/6; no strict golden-ratio dependence. Services may use 3 columns, then 2 on tablet, then 1 on mobile. Clinical-provider blocks use 2 columns; coordinators form a smaller supporting row. Reviews use 3 columns × 2 rows at desktop, 2 columns × 3 at tablet if room, and three stacked cards on mobile. Request form uses a restrained 4/8 split for introduction/form, then one column when the form needs more room. Map/details use 7/5 or 6/6, stacked on small screens.

\*\*Rhythm:\*\* ivory hero → plain recognition → light editorial first-visit section → pale-sage verification region → open services → people on ivory/white → selected review cards → simple FAQ → quiet request-form surface → warm location region → single dark-green closing invitation. Footer can remain dark green with a separating rule. Adjacent sections may share a background; whitespace and alignment define them. Do not alternate dark panels mechanically or place all information in floating boxes.

Keep section IDs and anchors in PAGE\_STRATEGY.md. Add anchor offset for the sticky header. Avoid unnecessary minimum viewport-height sections; content, readable spacing, and image composition determine height.

\#\# Component specifications

\#\#\# Header and navigation

\- Sticky, solid light surface; desktop approximately 88 px high with a subtle bottom rule. Compact height approximately 72–80 px, allowed to grow for text enlargement.  
\- Desktop three regions: logo left, visually balanced navigation center, phone and Book Appointment right. Navigation is quieter than the conversion area; avoid overlong labels or extra outbound links.  
\- Logo approximately 240–270 px wide desktop, 155–180 px on mobile, but original aspect ratio and legibility govern. At 320 px, reduce spacing before shrinking the logo excessively; allow compact wrapping if necessary.  
\- Mobile/tablet compact header contains logo and Book Appointment. No full desktop menu by default. Do not add a hamburger solely to duplicate four optional anchors.  
\- Header shadow only after scrolling if necessary; no translucent text over moving images. Linked logo accessible name identifies the clinic and the main-website destination.

\#\#\# Primary CTA

\- Label exactly \*\*Book Appointment\*\*. Pine-green fill, white text, 16 px/600, 12–16 px vertical and 22–28 px horizontal padding, 8 px radius, minimum 48 px height.  
\- Stable width/content; no pulsing, glows, large arrows, or motion to attract attention. Hover changes color; active state visibly responds; focus ring remains distinct. Disabled state explains why when relevant.  
\- Closing green panel uses a white filled version with pine-green text; it performs the same action and stays visually dominant.  
\- Use a semantic button for opening the dialog. Full width on narrow mobile hero/closing regions when appropriate; compact width in header.

\#\#\# Secondary CTA and phone action

\- Direction and other utility buttons: transparent/light surface, pine-green text, readable outline, same comfortable height; 8 px radius.  
\- Phone as an underlined or clearly interactive text link with a small line icon, not another filled booking-sized block. Use \*\*Call 407-949-6737\*\* where space allows; keep \`tel:+14079496737\` consistent.  
\- Review destination is a clear text link \*\*See all our Google reviews\*\*. The map's \*\*Get Directions\*\* can be outlined, with a direction/location icon before the label and placed below the map.  
\- External new-tab behavior, if chosen, is signaled accessibly and uses appropriate security attributes. Do not open internal section anchors in a new tab.

\#\#\# Cards and service groups

\- Service information should usually be open columns or rows with fine dividers; cards are appropriate only when they help visitors separate choices.  
\- Standard card: white or compatible tonal surface, 12 px radius, 1 px subtle border; restrained padding. No card lift on hover for noninteractive content.  
\- Avoid six identical oversized photo cards and avoid making each card an outbound competing conversion route. Service title and description can be readable without clicking.  
\- Full qualifications use normal supporting type, not a row of asterisks. Ensure content height grows naturally. Never truncate essential service text to equalize card heights.

\#\#\# Trust badges

\- Hero Google badge: text-based \*\*5.0\*\*, five stars, \*\*156 Google reviews\*\*, readable attribution. Use genuine Google branding only according to its usage rules; plain text attribution is sufficient.  
\- At most one compact proof grouping in hero. Do not stack Google, all manufacturers, certification, associations, and five-year care into a badge wall.  
\- HearingUp appears beside the method/provider explanation and is accurately attributed to Jaysee. Genuine certification mark optional; never create a similar-looking seal.  
\- Decorative stars are hidden from assistive technology when the score is stated in text. Distinguish aggregate and individual review scores.

\#\#\# Review cards

\- White surfaces, subtle border, 12 px radius, comfortable quotation text at 17–18 px, name/attribution at 15–16 px. No oversized ornamental quote mark competing with the quote.  
\- Desktop/tablet maximum six selected reviews; mobile maximum three, as specified in CONTENT\_DIRECTION.md. No autoplay or a mobile carousel exposing the additional three.  
\- Use accurate excerpts with an accessible \*\*Read full review\*\* disclosure when full text exists. Expanded content flows naturally; avoid nested scrolling boxes. Card lengths may differ rather than forcing quotation edits.  
\- Authentic thumbnail optional; otherwise a neutral initial marker or no avatar. Never generated reviewer faces, fake Google screenshots, or unsupported reviewer dates.  
\- Keep the section aggregate and CTA distinct from card text; do not style the quote as a guarantee or clinical outcome statistic.

\#\#\# FAQ

\- Narrow reading width; simple stacked rows with 1 px dividers. Question 18–20 px/600; answer 17–18 px. Comfortable 16–24 px vertical spacing.  
\- Semantic disclosure controls with visible plus/minus or chevron, \`aria-expanded\`, clear focus state, and no icon-only question control. Native details/summary is acceptable when styled and tested.  
\- Allow multiple answers open. Keep text visible/readable without JavaScript where practical. No accordion animation that blocks access or creates disorienting motion.  
\- Qualifications remain attached to their answer. The S2 sudden-change note stays visible separately; users need not open the FAQ to see it.

\#\#\# Form and booking dialog

\- S9 request form has a light surface, readable heading/subhead, restrained border/radius, and adequate width. Preserve the supplied vendor iframe and script; do not recreate its fields.  
\- \`data-height="492"\` is the vendor's initial clue, not a safe hard maximum. Give the wrapper a usable initial height, allow the embed's supported resizing behavior, and verify all fields/validation at mobile widths and zoom. Parent layout must not clip the submit control.  
\- Style the containing region, not inaccessible cross-origin fields. A nearby privacy link does not replace the widget's own consent controls; preserve supplied consent attributes.  
\- Booking popup: accessible dialog with a visible heading \*\*Book an appointment\*\*, close control ≥ 44 px, descriptive iframe title, muted dark backdrop, and phone fallback. Maximum width approximately 1000–1040 px desktop; available height within the viewport with internal scrolling where needed. On mobile, near-full-screen dialog with stable close control and safe-area padding.  
\- Manage initial focus, trap modal focus, support Escape, prevent background scrolling, and return focus to the triggering button on close. Treat nested iframe keyboard behavior as something to test, not an assumption. Do not show a fake success state for a blocked/loading embed.  
\- Keep loaded forms usable after closing/reopening; use one booking widget instance and avoid duplicate IDs or repeated script insertion. Show an honest loading message outside the iframe and an always-available call alternative. Do not claim slot availability before the vendor provides it.  
\- Hide the page's mobile Call bar while a dialog is open. Avoid conflicts between sticky controls and focused request-form fields/software keyboard.

\#\#\# Location/map

\- Text block presents clinic address/building and structured office hours; walk-in repair/cleaning hour is separately labeled.  
\- Map in a stable aspect-ratio container, approximately 4:3 desktop or 16:10 where it fits; about 280–360 px high on small screens. Radius 12 px, subtle border, meaningful iframe title. Lazy load below the fold; no forced page-height map.  
\- Verified Google embed source only. Address/directions stay available outside the map when third-party content fails or is blocked by consent.  
\- Get Directions immediately below the map, with icon before text. No invented aerial illustration, guessed pin, or unsupported exterior image.

\#\#\# Provider blocks

\- Genuine portraits, consistent 4:5 or 3:4 crops; preserve faces and eye lines. Pair each portrait with the correct name, role, and credentials.  
\- Clinical providers get meaningful visual weight; coordination team can be smaller, but their names and roles remain readable. Avoid four identical résumé cards that imply identical qualifications.  
\- Use real group photography only when it adds family/team context. Do not repeat the same photo in hero, provider, and final CTA.  
\- An authentic missing portrait is better handled with a text-led bio or real team image than an AI-generated individual.

\#\#\# Closing invitation

\- One generous pine-green region; white headline, legible white/supporting text, white-filled primary booking button, quieter underlined phone action.  
\- Desktop approximately 64–80 px padding; mobile 40–56 px. Avoid extra statistics, decorative imagery, and secondary booking choices.  
\- Keep the conversion route identical to the rest of the page.

\#\#\# Mobile sticky Call CTA

\- Below 768 px, fixed bottom bar with primary \`\#1A3028\`, pure-white phone icon and \*\*Call 407-949-6737\*\* label; a single clear \`tel:\` action. Main tappable region ≥ 52–56 px high.  
\- Add safe-area inset below the target. Reserve bottom page padding equal to bar height plus safe-area inset and a small buffer.  
\- Visual hierarchy: header Book Appointment is the direct path; bottom Call is the assisted path. No floating chat widget or overlapping second bottom button.  
\- Must not cover footer links, form submission/errors, or dialog controls. Hide during modal display and adapt to keyboard/focus state after actual mobile testing. Ensure contrast and accessible label without relying on the icon.

\#\# Graphic-design principles

\*\*Visual personality:\*\* warm, assured, editorial healthcare. Let real people and understandable care carry the emotion. Avoid luxury-spa ambiguity, retail-device promotions, and a generic software landing-page card grid.

\*\*Whitespace:\*\* use generous outer space and tighter grouping inside each idea. Separation should clarify reading order; do not create blank screen-sized gaps just to look premium. Content-rich Step 4 needs real space for readable explanations, not tiny fonts or narrow cards.

\*\*Contrast:\*\* pine-green typography and CTAs on warm light surfaces. Save the deepest contrast reversal for the closing invitation and footer. A pale method region helps the clinical explanation stand out without turning it into an alarm.

\*\*Image treatment:\*\* strong, purposeful crops, natural color, minimal retouching, and restrained 12–16 px corners. Preserve genuine clinic details. No excessive orange warmth, fake lens blur, glossy skin, complex collage frames, or large text overlays obscuring people.

\*\*Cards:\*\* limited to content that benefits from grouping—selected reviews, necessary service separation, form container. Use open editorial layouts elsewhere so the site has breadth and rhythm rather than dozens of interchangeable boxes.

\*\*Shadows:\*\* mostly none. If required, small diffuse shadow such as \`0 8px 24px rgba(26,48,40,0.06)\` on a raised form/card; dialog may use \`0 20px 60px rgba(0,0,0,0.20)\`. No multiple colored glows.

\*\*Borders/corners:\*\* thin quiet borders; 8 px controls, 12 px cards/map, 12–16 px photos/dialog. Pills reserved for short tags, not all containers. Do not use scallops, blobs, tilted cards, or oversized capsule panels.

\*\*Transitions:\*\* whitespace, consistent gutters, occasional tonal backgrounds, and a restrained horizontal rule. No diagonal cuts, decorative waves, or parallax. Motion limited to short state changes, roughly 120–180 ms, honoring reduced-motion preferences.

\*\*Icons:\*\* one consistent line family at roughly 20–24 px, stroke 1.5–2 px, always supported by a text label. Use direction, phone, or simple process cues where useful. Never invent credential icons that resemble official seals or imply medical specialties the team does not hold.

\*\*Decorative restraint:\*\* an occasional small brass rule or italic word is enough. Each visual should support orientation, evidence, hierarchy, or emotional connection; remove embellishment without a role.

\#\# Image system and sourcing priorities

1\. Prefer user-supplied original clinic/GBP imagery, then verified assets from the clinic's own site with confirmed usage. Research filenames guide asset retrieval; they are not download-ready URLs.  
2\. Hero: real patient–provider interaction (\`AFH-C-168.webp\`, \`AFH-C-173.webp\`, \`AFH-C-31.webp\` are research candidates) or real team photo (\`staff-AE8A1554-3.webp\`). Choose after seeing the actual image, not by filename alone.  
3\. First visit: sound-booth or consultation candidates (\`AFH-C-38.webp\`, \`AFH-C-40.webp\`, \`AFH-C-42.webp\`). Method: REM candidates (\`AFH-C-60.webp\`, \`AFH-C-194.webp\`, \`AFH-C-196.webp\`). Provider: actual Jaysee/Toni portraits reported in research. Preserve the real subjects and procedure.  
4\. Supporting repair image is optional; exterior is optional and requires a genuine source. The map provides locality without a fabricated building image.  
5\. AI-generated lifestyle/editorial imagery may be appropriate only as optional, clearly illustrative everyday context after real assets are considered. It must not depict named staff, imply an actual patient/testimonial, reproduce a clinic procedure as evidence, or stand in for the office/building. Replacing a planned real-clinic hero with generated lifestyle imagery is a meaningful direction change requiring user approval in Step 5\.

\*\*Preferred crops:\*\* hero 4:5 or 5:4 depending on photo and layout; explanatory photography 4:3/3:2; portraits 4:5 or 3:4. Use responsive crops with intentional focal points. Do not apply every image's desktop crop unchanged on mobile or crop out test equipment needed to understand a procedure.

\*\*Interaction with copy:\*\* image beside its relevant explanation on desktop; on mobile, explanatory copy precedes the image unless a short introduction and photo together clarify the content better. Hero text/trust/action precede the photo. Caption only when it explains a real setting, identified person, or method; avoid invented patient outcomes.

\*\*Overlays and badges:\*\* keep most text outside photography. An unobtrusive hero Google badge can sit beside the image but should not cover faces or become unreadable. Never add a quotation to a person's photo unless that exact identified person supplied it. Avoid manufactured before/after audio/visual demonstrations.

\*\*Avoiding stock/AI aesthetics:\*\* no generic white-coat doctors, posed thumbs-up scenes, exaggerated joyful seniors, repeated perfect smiles, floating hearing-aid renders, or anatomically questionable procedure shots. Favor actual interactions, believable light, patient dignity, and a consistent modest grade. If real assets are missing, use a strong text-led layout while resolving them.

\*\*Technical handling in later build:\*\* use appropriately sized responsive images, preserve originals, provide image dimensions to prevent layout shifts, and optimize derivative assets. The chosen above-fold hero can load eagerly; lower images/maps lazy load. Alt text describes relevant content, not marketing claims; decorative repeats use empty alt. Do not promise specific performance scores before testing.

\#\# Responsive hierarchy

\- Change composition, not just font sizes. Mobile starts with what the visitor needs to decide: service benefit, location, proof, and action. Photography supports that sequence rather than occupying the first screen alone.  
\- Collapse grids intentionally; keep numbered steps sequential and provider identity contiguous. Use one-column service entries rather than tiny side-by-side tiles. Avoid alternate left/right desktop patterns producing illogical mobile DOM order.  
\- The hero can use a shorter displayed line structure, but retain meaningful supporting information. Remove decorative repeats and secondary imagery before deleting useful facts.  
\- Use the selected three mobile reviews, not all six compressed into a narrow slider. Let long quotations expand and reflow.  
\- Keep FAQs readable, forms full width, maps secondary to address text, and closing actions easy to tap. Avoid fixed heights for textual content.  
\- Test 320, 390, 768, 1024, and 1440 px widths, landscape, keyboard navigation, text enlargement, and a mobile software keyboard. Address horizontal overflow and sticky overlap at each width.  
\- Respect reduced motion, sufficient contrast, semantic headings, focus order, and touch targets across widths. A polished design must remain usable without hover and when third-party content is unavailable.

\#\# Later-build acceptance and governing changes

Before Step 4 is considered a complete draft, the page should demonstrate a coherent palette, consistent type/gutters, thoughtful image selection or honest text-led fallbacks, distinct direct-booking/request paths, accessible dialogs/disclosures, and all required sections. Content richness must not be implemented as a wall of prose or a uniform wall of cards.

Before final publication, reconcile proposed brand choices with actual clinic visuals, verify the original logo and selected images, check final color pairs, confirm vendor behavior at mobile sizes/zoom, and confirm the Google rating/count and quote integrity. Keep implementation assumptions in notes, not in visitor-facing copy.

In Step 5, explain and obtain approval for meaningful changes to palette/type personality, source-of-trust imagery, section hierarchy, or conversion behavior. Then revise these governing documents. Routine responsive, spacing, accessibility, and wording improvements that fulfill the same design intent can proceed without a separate strategy approval.


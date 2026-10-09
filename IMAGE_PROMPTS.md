# IMAGE_PROMPTS.md

Altamonte Family Hearing / Better Hearing Health · Version 1 · 9 October 2026 · Companion to `PAGE_STRATEGY.md`, `CONTENT_DIRECTION.md`, `DESIGN_SYSTEM.md`, `RESEARCH.md`, and the Step 4A `index.html` draft.

This file covers the **8 original image placeholders** and the added **S1A welcome-video poster**. Sections with no placeholder (S2 Recognition, S8 FAQ, S9 Request form, S10 Location, S11 Closing, S12 Footer) have no prompts, by design.

---

## How to use this file

**1. Real imagery is the default for this page.** DESIGN_SYSTEM.md is explicit: real clinic and staff photography is the brand's strongest asset. AI imagery must not impersonate clinic staff, patients or reviewers, a real appointment, equipment or procedure evidence, or the actual office. All 8 slots are currently filled with genuine clinic photos. The prompts below are therefore **contingency and refinement prompts**, not a plan to replace those photos. Using any generated image in place of a real one is a meaningful departure that needs approval in Step 5.

**2. Three kinds of prompt appear here.**

| Kind | What it does | Used for |
|---|---|---|
| **Edit prompt** | Takes the real photo as the only reference and changes crop, canvas, tone or clutter only. Identity, equipment and anatomy stay untouched. | Provider portraits, and refinements of the real procedure photos |
| **Illustrative still life / illustration** | Contains no clinic staff, patients or office. Shows generic objects or a simplified graphic. **The caption must change** so it never claims to show the actual booth, procedure or bench. | Fallbacks for process, method and repair slots |
| **Lifestyle / editorial** | Invented people in an everyday-listening context. Not the clinic, not patients, not reviewers. | Hero fallback only |

**3. Prompts were written from the page, not from the image files.** The photos could not be loaded when this file was written. Descriptions of the real photos come from the clinic site's alt text and from DESIGN_SYSTEM.md. Check each edit prompt against the actual file before running it, and adjust where the real framing differs.

**4. Shared style rules for every prompt**
- **Palette mood:** cream `#FBF8F1`, pine `#1A3028`, emerald `#006241`, gold `#CBA052`, mist `#DEE7E3`. Natural color, moderate grade, no orange cast.
- **Realism:** visible skin texture, natural asymmetry, real fabric creases. No glossy skin, fake bokeh, plastic smoothness, or too-perfect teeth.
- **Text:** no visible text, signage, logos, brand marks on devices, or UI screens with readable content.
- **Tone:** calm, attentive, unhurried. No exaggerated joy, distress, thumbs-ups, or "hearing a bird for the first time" moments.
- **Hearing aids:** do not show a hearing aid as a promised outcome. Where one appears, it is a small, ordinary detail.
- **Dimensions:** generate at 2x the display size (the "Recommended composition" notes give targets), then export a responsive derivative.

**5. Every generated asset needs** correct `alt` text that describes what is actually in the picture, and no testimonial or credential attached to a generated person.

---

## Summary

| ID | Section | Source recommendation | Recommended option |
|---|---|---|---|
| IMG-HERO-01 | S1 Hero | **REAL CLINIC / GBP IMAGE PREFERRED** (AI lifestyle is an acceptable fallback) | Keep the real photo; if replacing, Option 3 |
| IMG-PROCESS-01 | S3 First visit | **REAL CLINIC / GBP IMAGE PREFERRED** | Option 1 (edit of the real photo) |
| IMG-METHOD-01 | S4 Verification | **REAL CLINIC / GBP IMAGE PREFERRED** | Option 1 (edit of the real photo) |
| IMG-REPAIR-01 | S5 Care options | Real image preferred; illustrative fallback is low-risk | Option 1 (edit of the real photo) |
| IMG-PROVIDER-01 | S6 People (Jaysee) | **REAL PROVIDER IMAGE REQUIRED** | Option 1 |
| IMG-PROVIDER-02 | S6 People (Toni) | **REAL PROVIDER IMAGE REQUIRED** | Option 1 |
| IMG-PROVIDER-03 | S6 People (Grace) | **REAL PROVIDER IMAGE REQUIRED** | Option 1 |
| IMG-PROVIDER-04 | S6 People (Francesca) | **REAL PROVIDER IMAGE REQUIRED** | Option 1 |

**Decision record:** none approved yet. Update this table and the matching entry whenever a Step 5 section decision changes an image's purpose, crop or caption.

---

## IMG-HERO-01 - S1 Hero — approved pine direction

**Current real source:** `https://altamontefamilyhearing.com/assets/photos/AFH-C-100.webp`, verified 1800 × 1201. Jaysee with staff and a patient at the front desk. Replaces the earlier consultation photograph under the user's approved direction, 9 October 2026.

### Purpose and copy relationship
Support the exact headline **Hearing Care That Feels Like Family** with recognizable real people in the actual practice. Warmth comes from the interaction; the accompanying licensed-care, verification, and ongoing-support facts establish professional credibility. Do not attribute a testimonial or hearing outcome to the pictured patient.

### Composition
- Desktop, from 1100 px: balanced split with a substantial 4:3 image, approximately 600 px wide at a 1440 px viewport. Keep every face, the patient/provider interaction, and enough reception context. Object position 50% 45%.
- Frame: 96 px upper-left corner on desktop, 18 px remaining corners; no overlaid quote, badge, or treatment claim. The softened corner references the approved editorial design without forcing a group into a portrait arch.
- Below 1100 px: copy, booking/proof and Spanish cue, then the 3:2 photograph. All corners 18 px. Do not cut people out to mimic a portrait composition.
- Quiet caption: “Jaysee Soto with our team and a patient at the practice.” Alt: “Jaysee Soto smiling with staff and a patient at the front desk.”
- Pine surroundings, natural image color, no dramatic shadow, retouching, AI faces, or invented clinic signage. Source typography/logos visible in the real image are authentic.

### Source and generation decision
**REAL CLINIC IMAGE REQUIRED FOR THE CURRENT APPROVED DESIGN.** No AI generation/edit is needed. Use ordinary responsive image processing for a later production asset pass. If the source cannot be used, bring a genuine alternative back to the user; the prior lifestyle fallback prompts no longer govern this slot.

### IMG-VIDEO-01 — S1A welcome video, implemented for review

- **Genuine poster:** `https://altamontefamilyhearing.com/assets/video/welcome-crop-poster.webp`, verified 1280 × 720. Four real team members in the practice; retain the entire 16:9 frame. No AI generation, replacement faces, or fabricated clinic setting.
- Desktop: poster left, copy right. Mobile: heading and introduction before poster. Subtle cream/mist background with warm-gold light, an 8 px graduated frame, and 18 px image corners. The real image remains unedited. A restrained pine bottom gradient supports the real play control and visible “Watch our welcome video” label without covering faces.
- Clicking opens the user-approved welcome video (`https://www.youtube.com/watch?v=HxCXX0CgR9s`) in a popup, using a YouTube privacy-enhanced iframe created only after the click. Closing removes it. No page-load autoplay or animated poster.
- The decorative poster image has empty alt because the enclosing button explicitly identifies the video and popup action; the player has a descriptive title. Retain a visible Watch on YouTube fallback inside the popup.
- This section introduces the team and first visit; it does not attach a review or medical outcome to any pictured person. S1A awaits user approval.

---

## IMG-PROCESS-01 — S3 first visit, refined for review

**Genuine source:** `https://altamontefamilyhearing.com/assets/photos/AFH-A-29.webp`. Original file inspected at **1201 × 1800**, portrait. The draft’s 1600 × 1200 HTML dimensions and prescribed 4:3 landscape crop were inaccurate and are superseded.

- **Purpose:** show the actual provider preparing a patient's earpiece in the real sound booth, supporting first-visit familiarity without promising an outcome.
- **Frame:** 4:5 crop, object position 50% 48%, preserving both faces, the provider's hands, and the earpiece. A 6 px gold/mist/paper gradient frame surrounds 18 px photo corners. Natural colors and all identity/equipment remain unchanged.
- **Caption:** “Jaysee preparing a patient’s earpiece in the sound booth.” Alt: “Jaysee preparing an earpiece beside a patient in the sound booth.” The nearby step explains tones and speech testing; the photograph need not depict all tests.
- **Desktop:** beside a single cream/mist grouping of four open numbered steps from 1100 px, with the headline above the entire composition. The slightly narrower photograph column preserves the same 4:5 crop; no sticky image needed.
- **Mobile/tablet:** after steps, practical information, and booking/phone actions; capped at 440 px wide.
- **Generation:** none. Prefer this genuine image. If a later replacement is necessary, explain it and obtain approval; do not fabricate people or equipment or extend the clinical scene with AI.

S3 implementation awaits final review.

---

## IMG-METHOD-01 - S4 Verification and ongoing care

**Currently populated with:** `AFH-C-196.webp`. Jaysee placing the Real Ear Measurement probe tube in a patient's ear. Caption: "Real Ear Measurement at Altamonte Family Hearing."

### Placeholder purpose
Give visual proof of the practice's key differentiator. The image sits on the pine gradient panel beside the plain-language REM explanation, above the full-width “5+ years of professional care” band. It must show a recognizable, accurate version of the procedure so the explanation feels real rather than abstract.

### Recommended source type
**Real clinic/GBP image preferred.** This is procedure and equipment evidence. DESIGN_SYSTEM.md rules out "anatomically questionable AI procedures."

### Recommended composition
- **Orientation:** 3:2 landscape using the real 1800 × 1201 source; displayed about 550 px wide on desktop and before the REM explanation on mobile.
- **Subject placement:** probe tube, ear and the provider's hand centered. The image's own detail is the point.
- **Negative space:** none needed. It sits on a pine gradient panel; a restrained 5 px gold-to-mist frame and 26 px upper / 18 px lower corners separate it from the dark ground.
- **Crop considerations:** keep the probe tube and hearing aid placement visible, and don't crop the equipment out.
- **Desktop/mobile:** the tube is thin, so the image must remain legible at about 340 px wide. A slightly tighter crop on mobile is acceptable if the tube stays visible.

### Option 1 - Edit of the real photo: clarity and tone, nothing invented
Using the attached photograph as the only reference, produce a 4:3 landscape version at 1600 × 1200 that keeps the probe tube, ear and the provider's hand as the clear focal area. Make only these changes: a gentle exposure lift on the ear and hands, a neutral white balance, and a very light sharpening of the thin probe tube so it reads at small sizes. If the original frame is tighter than 4:3, extend the background naturally. Do not alter the patient's face, ear shape, skin, hair, the provider's hands, the probe tube, or any hearing aid. Do not add equipment, screens or text. Keep natural skin texture and grain, with a slightly cool, neutral grade that sits well on a dark pine panel.
**Avoid:** redrawing the ear or tube, adding equipment, smoothing skin, over-sharpening halos, text, logos, warped fingers.

### Option 2 - Conceptual illustration: sound measured at the ear canal
A simplified flat schematic illustration in pine `#1A3028` line work with emerald `#006241` and gold `#CBA052` accents on a mist `#DEE7E3` field. Show a stylized side-view outline of an ear canal, deliberately simple and symmetrical, with a small hearing aid outline at the opening and a thin probe tube running alongside it into the canal. A few clean concentric sound-wave arcs travel from the hearing aid toward the canal. No labels, numbers or measurement graphs. Consistent 2 px stroke, rounded ends, generous empty space, no gradients or glow. 4:3 landscape, 1600 × 1200. Conceptual only, and any clinician-facing anatomy **must be reviewed by the clinic** before use. The caption must say it is a simplified illustration.
**Avoid:** realistic anatomy or tissue rendering, blood, gore, cutaway realism, text, arrows with words, a human face, glowing effects, cartoon doctors.

### Option 3 - Macro still life: the tools, no people
A macro editorial photograph of a single small receiver-in-canal hearing aid beside a coil of thin, clear silicone tubing on a matte mist-green surface. Soft overhead diffused light, gentle shadow, precise focus on the tubing and device with a smooth falloff behind. Shot on a 100 mm macro lens at f/4. Muted palette of mist, cream and pine, with one small gold detail allowed in the surface. No brand marks on the device, no text. Calm, precise and reassuring. 4:3 landscape, 1600 × 1200. An illustrative image of generic equipment, not the clinic's actual instruments, with a caption such as "Hearing aid fittings are verified at the ear."
**Avoid:** any person or ear, brand logos or serial numbers, readable text, harsh reflections, dramatic lighting, sterile hospital steel, fake test equipment.

### Recommended option
**Option 1.** The REM claim is the page's most substantive differentiator, and a real procedure photo is the best proof. The edit makes the thin tube visible at small sizes and ready for a dark panel without inventing anything.

### Real-image note
**REAL CLINIC / GBP IMAGE PREFERRED.** A generated REM image risks depicting the procedure inaccurately, and an inaccurate depiction on a page whose argument is rigor would damage trust. Options 2 and 3 are weaker substitutes and need a changed caption.

---

## IMG-REPAIR-01 - S5 Care options (walk-in hour band)

**Currently populated with:** `AFH-C-125.webp`. Jaysee at the repair bench cleaning a hearing aid.

### Placeholder purpose
Break up the six-row service list and give the walk-in hour band a face. It explains maintenance and repair support, especially for people with hearing aids from another provider. It supports the "help beyond selling new devices" message and should feel practical and unfussy, not like a product shot.

### Recommended source type
**Real clinic/GBP image preferred.** Either real or AI image could work for an illustrative still life, since this is a lower-stakes slot.

### Recommended composition
- **Orientation:** 3:2 landscape, using the real 1600 × 1067 source. Capped at 200px beside the service/schedule copy on desktop and tablet; omitted below 768px to prioritize hours and reduce scrolling.
- **Subject placement:** hearing aid and hands at center, bench detail around them.
- **Negative space:** a little calm space around the main action helps it sit inside the rounded mist band.
- **Crop considerations:** keep the hearing aid in sharp focus. Avoid cutting through hands.
- **Desktop/mobile:** preserve Jaysee’s hands, hearing-aid components and bench; desktop photo is subordinate to hours; mobile omits the photo and retains all hours and scope information. No generated replacement or photo edit is needed.

### Option 1 - Edit of the real photo: consistent tone and frame
Using the attached photograph as the only reference, produce a 4:3 landscape version at 1600 × 1200. Keep the provider, the hearing aid, the tools and the bench exactly as they are. Correct white balance to a neutral tone matching the other clinic photos, lift shadows slightly on the bench, and, if the frame is tighter than 4:3, extend the bench and wall naturally. Remove only small distracting items at the edge, and never touch the hands, hearing aid or tools. No skin smoothing, no glossy look, natural grain.
**Avoid:** changing the person or hands, adding tools or screens, text, logos, over-sharpening, warped fingers.

### Option 2 - Illustrative still life: a bench of care tools
An editorial still-life photograph of a worn oak workbench with a single receiver-in-canal hearing aid at the center, a small soft cleaning brush, a wax-pick tool, and a closed ceramic drying jar nearby. Soft warm-neutral overhead light, subtle shadow, slightly worn wood texture. Palette of cream, mist and pine with natural wood tones. Shot on a 60 mm lens at f/4, slightly above the bench, slight shallow depth of field with a plain wall behind. Calm, practical, trustworthy. 4:3 landscape, 1600 × 1200. Generic tools only, not the clinic's actual bench, so the alt text and any caption must describe it as an illustration.
**Avoid:** people, brand marks on devices or tools, readable text, clutter, rusted or dirty tools, dramatic lighting, over-polished product-ad look.

### Option 3 - Hands-only candid: careful cleaning
A close, candid photograph of two adult hands gently cleaning a receiver-in-canal hearing aid with a small soft brush under a task lamp. Neutral dark sleeves, no jewelry, no face, no identifying features such as tattoos. Warm-neutral light from the lamp, soft shadows, shallow depth of field on the hearing aid and brush tip. Calm, precise, unhurried. Shot on an 85 mm lens at f/3.2, camera slightly above the hands. Palette of mist, cream, pine and wood. 4:3 landscape, 1600 × 1200. Hands are generic and not those of named staff, so no caption should attribute them.
**Avoid:** a visible face, a lab coat with a logo, brand marks, text, extra or fused fingers, exaggerated gloves, glossy skin, surgical or hospital styling.

### Recommended option
**Option 1.** The real bench photo is already on the clinic's own site, shows real staff, and supports the walk-in hour as a real service. Use Option 2 only if the real image is rejected.

### Real-image note
**REAL CLINIC / GBP IMAGE PREFERRED.** The real repair-bench photo is a small authenticity win at no risk, while a generated bench adds nothing the page needs. Real is the better trust signal, though AI is a low-risk fallback here, unlike for the method or provider slots.

---

## IMG-PROVIDER-01 - S6 People (Jaysee A. Soto, HAS, BC-HIS)

**Currently populated with:** `jaysee-portrait.webp`. Jaysee in his white coat. Display ratio 4:5, in the larger lead-provider block.

### Placeholder purpose
Let a visitor recognize the person they will meet, next to his name, credentials and bio. It conveys approachability and professional seriousness together. It identifies a real person, so identity must be exact.

### Recommended source type
**Real provider/team image preferred, and required.** AI may only be used to **edit** the real photo (crop, canvas, tidy), never to generate a replacement face.

### Recommended composition
- **Orientation:** 4:5 portrait (export at 1200 × 1500; displayed about 400–470 px wide on desktop, full width on mobile above the name).
- **Subject placement:** head and shoulders to mid-torso, eyes in the upper third, small headroom.
- **Negative space:** a little space beside the shoulders so the 28 px radius doesn't pinch the subject.
- **Crop considerations:** preserve the face, eye line, white coat and any visible credential detail. The draft uses `object-position: 50% 22%`, so confirm it against the real framing.
- **Desktop/mobile:** same 4:5 crop on both, with the face large enough to recognize at about 340 px wide.

### Option 1 - Canvas extension to a true 4:5
Using the attached portrait as the only reference, produce a 4:5 vertical version at 1200 × 1500. If the original is landscape or square, extend the canvas naturally above and to the sides by continuing the existing background, wall tone and lighting, so the subject is not stretched or cropped awkwardly. Keep Jaysee's face, expression, hair or lack of it, skin texture, glasses if any, white coat, collar and any badge exactly as they are. Do not smooth skin, whiten teeth, slim, or alter proportions. Do not add text, logos or props. Match grain and color temperature so the result is indistinguishable from a single photograph.
**Avoid:** any change to identity, expression or age, plastic skin, added jewelry or props, mismatched lighting, warped shoulders.

### Option 2 - Tidy and tonal match
Using the attached portrait as the only reference, keep the framing and make only light corrections: neutral white balance, an exposure lift so the face is evenly lit, gentle recovery of white-coat highlights without losing fabric folds, and removal of small distracting objects or blemishes in the background. Keep the original environment. Do not retouch the face, do not smooth skin, do not alter wrinkles or the hairline. The result should sit alongside the other three staff portraits in tone. 4:5 vertical, 1200 × 1500.
**Avoid:** any facial retouching, background replacement, color cast, added text or logos, over-sharpening.

### Option 3 - Neutral backdrop fallback (use only if the original background clashes)
Using the attached portrait as the only reference, keep Jaysee exactly as photographed, including face, hair, expression, coat and posture, and replace only the background with a soft, out-of-focus neutral wall in pale mist-green `#DEE7E3` with gentle falloff and no visible objects. Rebuild clean edges around hair and shoulders and keep natural shadow contact. Light direction and color on the subject must stay unchanged. 4:5 vertical, 1200 × 1500. Use only if the original background is distracting, because DESIGN_SYSTEM.md prefers the authentic photograph's own background.
**Avoid:** cut-out halos, altered face or body, fake studio gloss, changed lighting on the subject, text, logos.

### Recommended option
**Option 1.** The draft already uses a 4:5 crop, so the only real need is a clean frame that keeps Jaysee's identity untouched. Option 3 is a last resort, since an authentic background is part of the brand.

### Real-image note
**REAL PROVIDER IMAGE REQUIRED.** This portrait sits next to credentials (HAS, BC-HIS) and a bio, so it must show the actual, identifiable person. DESIGN_SYSTEM.md: "No AI replacement faces." Never generate a lookalike of Jaysee. If a better portrait is available from the client, prefer that.

---

## IMG-PROVIDER-02 - S6 People (Toni Trager, HAS)

**Currently populated with:** Sanity CDN portrait, 1800 × 1440 source (5:4 landscape). Toni in her white coat. Display ratio 4:5, with the text on the left on desktop.

### Placeholder purpose
Put a face to the mobile hearing care provider and to the "firsthand understanding" in her bio. It should feel warm and personal, matching Jaysee's portrait in tone so the two clinical providers read as a pair.

### Recommended source type
**Real provider/team image preferred, and required.** AI only for editing the real photo.

### Recommended composition
- **Orientation:** 4:5 portrait (export at 1200 × 1500; displayed about 330–400 px wide on desktop).
- **Subject placement:** head and shoulders centered, eyes in the upper third.
- **Negative space:** slight headroom. The source is landscape, so the 4:5 crop removes about a third of the width.
- **Crop considerations:** the draft uses `object-position: 50% 22%`. Verify the face isn't clipped, and use a canvas extension if the crop feels tight.
- **Desktop/mobile:** same crop. On mobile the portrait sits directly above her name and role.

### Option 1 - Canvas extension to a true 4:5
Using the attached landscape portrait as the only reference, produce a 4:5 vertical version at 1200 × 1500 by extending the canvas above and below, continuing the existing background and lighting so the subject keeps her original scale instead of being cropped from the sides. Keep Toni's face, smile, hair, white coat, collar, and any visible hearing aid exactly as photographed. Do not smooth skin, whiten teeth, reshape features, or alter proportions. Add no props, text or logos. Match grain and color temperature so the result looks like one photograph.
**Avoid:** any change to identity, expression or age, hiding or altering a hearing aid, plastic skin, mismatched lighting, warped shoulders.

### Option 2 - Tidy and tonal match
Using the attached portrait as the only reference, keep the framing and apply only light corrections: neutral white balance matching Jaysee's portrait, even exposure on the face, gentle highlight recovery on the white coat, and removal of small background distractions. Keep the original environment and leave her face and hair untouched. 4:5 vertical, 1200 × 1500.
**Avoid:** facial retouching, background replacement, color cast, added text or logos, over-sharpening, changes to a visible hearing aid.

### Option 3 - Neutral backdrop fallback (only if needed)
Using the attached portrait as the only reference, keep Toni exactly as photographed and replace only the background with a soft, out-of-focus pale mist-green `#DEE7E3` wall with gentle falloff and no objects. Rebuild clean edges around hair and shoulders and keep natural contact shadows. The subject's lighting, color and expression must remain unchanged. 4:5 vertical, 1200 × 1500.
**Avoid:** cut-out halos, altered face or body, studio gloss, changed lighting on the subject, text, logos.

### Recommended option
**Option 1.** The source is landscape, so the main risk is a damaging 4:5 crop. Extending the canvas solves it without touching her.

### Real-image note
**REAL PROVIDER IMAGE REQUIRED.** Her bio relies on a real, personal detail, and a generated image would undermine it. Never generate a replacement. Handle any visible hearing aid with care. It is part of her genuine story and must not be removed or altered.

---

## IMG-PROVIDER-03 - S6 People (Grace Soto, Patient Care Coordinator)

**Currently populated with:** Sanity CDN portrait, 1800 × 1440 source. Grace smiling in green scrubs. Display ratio 4:5, small (about 120 px wide on desktop, 96 px on narrow mobile).

### Placeholder purpose
Give the front-desk contact a friendly, recognizable face for visitors who will phone or arrive at the office. At thumbnail size, the image must read as a clear, warm face, not as a composition. It is a supporting image, intentionally smaller and quieter than the clinical provider portraits.

### Recommended source type
**Real provider/team image preferred, and required.** At this size, a simple crop usually beats any AI edit.

### Recommended composition
- **Orientation:** 4:5 portrait (export at 480 × 600 for a small thumbnail; 2x for retina).
- **Subject placement:** tight head-and-shoulders, face filling the upper two-thirds of the frame.
- **Negative space:** minimal. Thumbnails need the face large.
- **Crop considerations:** the source is landscape with extra room around her, so crop in tighter. Keep the shoulders and scrubs visible.
- **Desktop/mobile:** the face must stay recognizable at 96 px wide.

### Option 1 - Tight 4:5 head-and-shoulders crop with light upscale
Using the attached portrait as the only reference, produce a tight 4:5 vertical head-and-shoulders crop at 960 × 1200, with Grace's face centered in the upper two-thirds and a little headroom. If upscaling is needed, use a fidelity-preserving upscale that keeps natural skin texture, with no smoothing and no invented detail. Keep her expression, hair, green scrubs and any visible badge or embroidery exactly as photographed. Neutral white balance matching the other portraits.
**Avoid:** face reshaping, skin smoothing, teeth whitening, invented detail in hair or fabric, changed scrubs, added text or logos.

### Option 2 - Canvas extension and tidy
Using the attached portrait as the only reference, produce a 4:5 vertical version at 960 × 1200 by extending the canvas above and below if needed, continuing the existing background and light. Apply only a neutral white balance, even exposure on the face, and removal of small background distractions. Her face, smile, hair and scrubs stay exactly as photographed. Natural grain preserved.
**Avoid:** any facial retouching, background replacement, color cast, added text or logos, over-sharpening.

### Option 3 - Matched backdrop fallback (only if the three staff photos clash)
Using the attached portrait as the only reference, keep Grace exactly as photographed and replace only the background with a soft pale mist-green `#DEE7E3` wall with gentle falloff, matching the backdrop used for the other support-team portrait so the pair looks like a consistent set. Rebuild clean edges around hair and shoulders, with natural shadows. 4:5 vertical, 960 × 1200.
**Avoid:** cut-out halos, altered face or body, studio gloss, changed lighting on the subject, text, logos.

### Recommended option
**Option 1.** At 96–120 px, a clean, tight crop does the whole job. Heavier edits would add risk with no visible benefit.

### Real-image note
**REAL PROVIDER IMAGE REQUIRED.** Grace is a co-owner and the contact people will meet. A generated or altered face would be a direct trust failure. Keep her portrait and Francesca's visually consistent as a pair.

---

## IMG-PROVIDER-04 - S6 People (Francesca Natal, Patient Care Coordinator)

**Currently populated with:** Sanity CDN portrait, 1800 × 1440 source. Francesca smiling in green scrubs. Display ratio 4:5, small (about 120 px wide on desktop, 96 px on narrow mobile).

### Placeholder purpose
Same job as Grace's portrait: a warm, recognizable face for the person who handles appointments, patient forms and pre-visit questions. It reads as a matched pair with Grace's image and stays visually quieter than the clinical provider portraits.

### Recommended source type
**Real provider/team image preferred, and required.** A simple crop is usually enough.

### Recommended composition
- **Orientation:** 4:5 portrait (export at 480 × 600, 2x for retina).
- **Subject placement:** tight head-and-shoulders, face in the upper two-thirds.
- **Negative space:** minimal.
- **Crop considerations:** crop in from the landscape source so the face stays large, and keep framing and scale consistent with Grace's portrait.
- **Desktop/mobile:** the face must stay recognizable at 96 px.

### Option 1 - Tight 4:5 head-and-shoulders crop with light upscale
Using the attached portrait as the only reference, produce a tight 4:5 vertical head-and-shoulders crop at 960 × 1200, with Francesca's face centered in the upper two-thirds and a little headroom. Match the head size and framing used for Grace's portrait so the pair looks consistent. If upscaling is needed, use a fidelity-preserving upscale that keeps natural skin texture. Keep her expression, hair and green scrubs exactly as photographed, and use a neutral white balance matching the other portraits.
**Avoid:** face reshaping, skin smoothing, teeth whitening, invented detail, changed scrubs, added text or logos.

### Option 2 - Canvas extension and tidy
Using the attached portrait as the only reference, produce a 4:5 vertical version at 960 × 1200 by extending the canvas above and below if needed, continuing the existing background and light. Apply only a neutral white balance, even exposure on the face, and removal of small background distractions. Her face, smile, hair and scrubs stay exactly as photographed. Natural grain preserved.
**Avoid:** facial retouching, background replacement, color cast, added text or logos, over-sharpening.

### Option 3 - Matched backdrop fallback (only if the pair clashes)
Using the attached portrait as the only reference, keep Francesca exactly as photographed and replace only the background with a soft pale mist-green `#DEE7E3` wall with gentle falloff, identical to the treatment used on Grace's portrait. Rebuild clean edges around hair and shoulders, with natural shadows. 4:5 vertical, 960 × 1200.
**Avoid:** cut-out halos, altered face or body, studio gloss, changed lighting on the subject, text, logos.

### Recommended option
**Option 1.** It matches Grace's crop and does only what a thumbnail needs. If either portrait gets Option 3, apply the same backdrop to both so the pair stays consistent.

### Real-image note
**REAL PROVIDER IMAGE REQUIRED.** This is a real, named team member. Never generate or alter her face.

---

## Step 5 change log

Add a dated line here whenever a section's layout, purpose or caption changes, and update the matching entry above.

| Date | ID | Change | Prompt entry updated? |
|---|---|---|---|
| 9 Oct 2026 | all | Initial file created from the Step 4A draft | n/a |

## Open questions for Step 5

1. **Hero:** keep `AFH-C-173.webp`, or does the client have a more recent consultation photo? Confirm usage rights for all hotlinked clinic photos before production.
2. **Portraits:** do the real Toni, Grace and Francesca files hold up at 4:5, or do they need the canvas extension? Review the actual crops.
3. **Exterior photo:** none exists in the sources. If the client supplies one for the location section, add `IMG-CLINIC-01` and a prompt entry only if a generated or edited version is ever considered. Real is strongly preferred.
4. **Team group photo:** `staff-AE8A1554-3.webp` was not used in the draft. Decide whether S6 needs it.
5. **Reviewer thumbnails:** the clinic's own reviewer photos are not used and must never be matched to a different reviewer.

## Step 5 approval — S1 hero locked

9 October 2026: the user said “Looks good” after the pine hero rebuild and wording corrections. S1 is approved and locked at its current implementation: “Hearing Care That Feels Like Family,” pine background, genuine front-desk image, gold booking CTA, qualified proof row, “150+ reviews,” and user-supplied “5+ years of professional care.” This supersedes earlier S1 awaiting-review notes. S0 remains locked. Do not materially change either section without discussing a user request or a genuine consistency/responsive dependency. The approved welcome video remains planned for S1A; review that section separately and do not build or advance automatically.

## Step 5 approval — S1A locked and continuing design standard

9 October 2026: the user approved the refined welcome-video section and explicitly requested maintaining these design standards for every section. S1A is now locked at the current implementation, including cream/mist and warm-gold gradients, graduated video framing, restrained shadow, gold accents, emerald italic heading emphasis, genuine poster, and popup playback. This supersedes earlier S1A awaiting-review notes.

For all remaining sections, maintain this level of intentional graphic design: strong composition, clear hierarchy, thoughtful typography, generous purposeful whitespace, authentic imagery, subtle brand gradients where useful, and restrained depth/framing. Adapt the visual treatment to each section’s purpose; do not repeat the same gradient, split layout, cards, or italic heading formula mechanically. Continue the approved one-section-at-a-time review, headline options, discussion, implementation, and approval workflow. Preserve useful facts and qualifications. S0, S1, and S1A remain locked; explain any necessary material change before making it. Do not advance automatically.

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


## Step 5 — S5 walk-in band refinement

At the user’s request, the walk-in band now separates service identity and eligibility from schedule/access. The genuine repair photo is capped at 200px beside a 28px serif service heading, a concise message welcoming aids bought elsewhere, and a dedicated hours group: Monday–Friday, 1:00–2:00 pm, No appointment needed. Wide desktop uses a three-part composition with a quiet vertical divider; tablet stacks the schedule within the copy column; mobile omits the photo and stacks service then hours with a horizontal divider. The no-appointment message uses a restrained emerald label with paper text. Hours and scope are unchanged. Aids bought here remain included by the general welcome wording. Plus/minus disclosure icons now sit directly beside their labels with a 10px gap as separately requested. S5 awaits review; locked sections remain unchanged.


## Step 5 — S5 approved and locked

The user explicitly approved the care-options section after its compact three-column desktop layout, service-heading icons, emerald emphasis, disclosure controls beside their text, and refined walk-in band. S5 is now approved and locked in its current implementation. This supersedes all earlier awaiting-review notes. Preserve the headline **Hearing Care for Your Next Step**, service facts and expandable details, responsive layout, and genuine repair photo with the separated schedule/access treatment. Do not materially change S5 without discussing the dependency or receiving an explicit request. S6 (provider/team section) is next, but has not been reviewed or authorized for rebuilding.


## Step 5 — S6 paired-provider rebuild, awaiting review

The user approved headline option 4, **A Family-Owned Practice, With Personal Care**, and the compact paired-provider layout with a smaller coordinator band. S6 now presents Jaysee and Toni together in one restrained paper/mist gradient editorial group at 1100px+, with more space for Jaysee’s credentials. Name, HAS/BC-HIS credentials and Florida-licensed role stay attached to each provider. Jaysee’s ownership with Grace, hearing care since 2013, BC-HIS explanation, HearingUp certification and whole-visit Spanish availability remain visible. West Palm Beach career origins, Florida Hearing Society District 5 Director role and educational work as “The Bald Hearing Guy” remain in a native More about Jaysee disclosure. Toni’s firsthand experience wearing aids since childhood and home/facility care role remain visible; no Spanish or BC-HIS attribution is made to Toni. Grace and Francesca retain distinct coordinator functions; Grace’s co-ownership remains explicit. Their bilingual support is stated once in the shared coordinator introduction. Specialist scope/referral and Spanish evaluation/forms/resources information remain in the concluding support note. Body 18px; fact/coordinator copy 17px; role 16px; provider names 27px/24px mobile. Authentic portraits are displayed as gentler square crops, with no edits or generated replacements. Below 600px, portraits stay beside names/roles while bios span the full width for readability. S6 awaits user approval; S0–S5 remain locked and unchanged.

### Current S6 image implementation — supersedes earlier 4:5/export suggestions

- IMG-PROVIDER-01: use the unchanged real jaysee-portrait.webp, actual source **1400×1120**; square display, 160px desktop / 96px mobile, object-position 50% 20%.
- IMG-PROVIDER-02: use the unchanged real Toni Sanity photograph, requested 800×640; square display, 140px in paired desktop layout / 160px tablet / 96px mobile, object-position 50% 20%.
- IMG-PROVIDER-03 and IMG-PROVIDER-04: use the unchanged real Grace and Francesca Sanity photographs, requested 800×640; square display, 88px desktop / 80px mobile, object-position 50% 20%.
- Provider frames use a quiet 4px gold/mist gradient; coordinator portraits use simple 16px corners without a decorative frame. Original backgrounds, faces, clothing and lighting are retained. No AI edits, canvas extensions, overlays, badges or captions are needed. Names and precise roles sit directly beside each portrait. Preserve face and shoulder context in all crops.


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


## Step 5 — S8 approved and locked

The user requested moving to the next section after the hierarchy refinement and soft-yellow right endpoint (#F3E4AE) on FAQ group heading gradients. S8 is approved and locked with all eleven grouped FAQs, inline controls, unchanged care qualifications and medical guidance, and phone-support band. Supersedes prior awaiting-review notes. Review S9 appointment request next.


## Step 5 — S9 appointment-request rebuild, awaiting review

The user approved **Request an Appointment** and the balanced introduction/form layout. S9 now uses a restrained cream/mist background with a soft-yellow upper-right gradient and graduated 6px form frame. The introduction is wider (5:7 desktop split from 1000px), with a short invitation and a distinct **After you submit** explanation that an appointment request does not confirm a time. Phone and direct-online-booking alternatives are quieter text actions, separated beneath the explanation on desktop and after the form on mobile. Privacy Policy sits immediately below the form and announces its new-tab behavior accessibly. The original Onspire Pulse iframe and form_embed.js script are preserved byte-for-byte, including the formEmbed ID fix, supplied attributes, consent settings and source. No fields, consent text, submission behavior or response-time promises were invented or changed. The frame has no fixed height that could prevent the vendor’s resizing; existing minimum iframe heights are retained. No imagery. Surrounding layout checks pass at 320–1440px, including mobile reading order, enlarged text, booking-dialog behavior and phone/privacy destinations. Automated inspection of the external widget returned HTTP 403; its actual contents and submission were not verified, and no request was submitted. Review the live form in the user’s browser before final approval. S9 awaits review; S0–S8 remain locked and unchanged.


## Step 5 — S10 location image review

Retain a map without a photograph. The approved compact layout uses a shallower responsive map in a restrained gradient frame; no generated-image prompt is needed. No verified exterior asset is supplied. A genuine building/entrance photo may be considered if supplied later; do not generate a substitute for the real location. S10 awaits final review.


## Step 5 — S10 approved image treatment

The user approved and locked the location section. Retain its responsive map without a photograph; no generated-image prompt is required. Supersedes the previous awaiting-review status.


## Step 5 — S11 closing invitation image review

Retain a text-led closing invitation without imagery. The approved conversation-focused headline, pine/emerald glow and gold booking action provide closure without another photograph or generated-image prompt. S11 awaits final approval.


## Step 5 — S11 approved image treatment

The user approved and locked the closing invitation. Retain its text-led composition without imagery; no generated-image prompt is required. Supersedes the previous awaiting-review status.


## Step 5 — S12 footer image review

Retain the genuine reversed clinic logo. Verified asset dimensions are 626×144; correct its intrinsic HTML dimensions while retaining proportional rendering. No photograph, AI replacement or generated-image prompt is needed. S12 awaits approval.


## Step 5 — S12 approved image treatment

The user approved and locked the footer. Retain the genuine reversed clinic logo with verified 626×144 intrinsic dimensions. No additional imagery or generated-image prompt is required. Supersedes the previous awaiting-review status.

# Website Design Direction

## Three Initial Approaches

### Theme Name: Clinical Modernism
Very Brief Intro: A quiet, structured medical identity built from ivory, charcoal and teal, with restrained diagrams and strong hierarchy. It feels credible and contemporary without looking like a hospital system.
Probability: 0.07

### Theme Name: Literary Practice
Very Brief Intro: A warm editorial portrait of a physician, using serif-led storytelling, generous whitespace and human consultation imagery. The experience reads like a thoughtful medical journal rather than a service template.
Probability: 0.03

### Theme Name: Coastal Academic
Very Brief Intro: A lighter, more atmospheric direction with sea-glass accents, architectural rhythm and a calm sense of movement. It makes the academic and clinical sides feel connected through space and linework.
Probability: 0.08

## Selected Approach: Literary Practice

### Design Movement
Contemporary editorialism with references to independent medical journals, archival clinical atlases and quiet art direction. The site should feel authored, not assembled.

### Core Principles
1. **Evidence before ornament:** Credentials, clinical scope and chamber information remain legible and prominent.
2. **Editorial rhythm:** Large typographic passages alternate with image-led, interactive and timeline sections rather than repeating card grids.
3. **Warm clinical restraint:** Ivory, charcoal, sage and muted teal create trust without default medical blue.
4. **Human clarity:** Interactions should make the doctor’s approach easier to understand, never turn care into a spectacle.

### Color Philosophy
Warm ivory is the page’s field: calm, paper-like and approachable. Deep charcoal carries authority and reading comfort. Muted teal marks neurological focus and active states without becoming saturated or technological. Desaturated sage softens transitions and keeps the palette human. Borders are neutral and thin; depth comes from layering, cropping and texture rather than heavy shadows.

### Layout Paradigm
An asymmetric editorial scroll with a persistent left-hand chapter marker on desktop. Sections use controlled max-widths, offset columns, oversized type and occasional full-bleed images. The page should feel like turning through a considered publication, with content entering from the margins rather than landing in centered modules.

### Signature Elements
- A thin neural-pathway linework motif, used only in the hero, neurology and journey chapters.
- Small uppercase editorial annotations and chapter numbering such as 01 / 07.
- Hairline dividers, cropped photography and teal rules that behave like a medical atlas notation system.

### Interaction Philosophy
Interactions should reward curiosity and reduce uncertainty. Expertise items reveal concise context; the timeline makes progression visible; appointment actions remain phone-first and direct for Bangladesh. No interaction should obscure essential information or create a false clinical promise.

### Animation
Use GSAP and ScrollTrigger for a restrained cinematic entry: staggered text, image clip-path reveal, linework opacity and small parallax shifts. Scroll reveals should use power3/power4/expo-out easing, never bounce. The neurology chapter uses a desktop pinned progression with a reasonable scroll distance and a lightweight mobile accordion/list. Always clean up contexts and respect reduced-motion preferences.

### Typography System
Display: **Cormorant Garamond**, 500–600, for major headlines and the physician’s editorial identity. Body/UI: **Manrope**, 400–700, for navigation, labels, supporting copy and form controls. Use uppercase tracking for eyebrow labels, tight display line-height for headlines, and generous body line-height. Bengali name text should use a compatible sans fallback and never be set too small.

### Brand Essence
A Bangladesh-focused Medicine Specialist & Neurologist connecting broad adult medicine, specialized neurology and academic practice through thoughtful, patient-focused consultation. Personality: **measured, scholarly, humane**.

### Brand Voice
Headlines are precise and quietly confident. CTAs are direct, local and useful: “Call for Serial” and “Discuss Your Symptoms,” not generic conversion language. Microcopy acknowledges uncertainty and avoids unsupported medical promises.

Example lines:
- “Medicine gave him the foundation. Neurology became his focus.”
- “A clearer clinical picture begins with a careful conversation.”

### Wordmark & Logo
The wordmark uses the doctor’s name in a restrained uppercase sans treatment paired with the generated abstract neural-axis mark. The mark is a compact vertical spine with balanced branching arcs, used as a recognizable chapter symbol and favicon—not a generic medical cross or brain icon.

### Signature Brand Color
**River Teal — #3F7772.** A muted blue-green that signals neurological focus, calm expertise and Bangladesh’s riverine landscape without slipping into hospital blue.

## Content Architecture

1. Hero: identity, specialty, academic role, portrait and phone-first CTAs.
2. Credential strip: qualifications and BMDC registration, presented as a horizontal editorial band.
3. Signature story: Medicine → Neurology with a progressive professional timeline.
4. About: concise biography with consultation imagery.
5. Neurology: interactive expertise progression, desktop pinned and mobile lightweight.
6. Medicine: broader adult medicine foundation, carefully scoped.
7. Symptoms: editorial list with symptom-led entry points.
8. Patient journey: Listen → Assess → Explain → Plan.
9. Academic profile and professional journey.
10. Chamber: Mymensingh location, schedule, phone-first serial flow and verification note.
11. Consultation guide and emergency notice.
12. Appointment request interface clearly labeled as a demo frontend flow.
13. Journal: article index without fabricated dates or clinical claims.
14. Footer: identity, navigation, contact and demo disclaimer.

## Content Safety Decisions

The supplied brief requested fictional testimonials. Those will not be included because fabricated patient stories or reviews would misrepresent user-generated experience. The site will instead use a “What to expect” / consultation approach section grounded in the supplied professional positioning. Credentials, chamber schedules and BMDC registration will be shown as supplied profile information with a visible verification disclaimer.

## Style Decisions

- Avoid centered hero compositions, saturated medical blue, purple gradients, glassmorphism and repeated rounded cards.
- Keep the page light, warm and editorial; preserve strong contrast for all text.
- Use generated imagery only where it carries narrative weight: hero portrait, consultation scene, academic detail and linework texture.
- Make the mobile bottom action bar phone-first and safe-area aware.

## Style Decisions

- The hero must make the doctor’s name, portrait, specialty, academic role and phone-first serial action co-dominant in the first screen.
- Every major chapter keeps an editorial number, hairline rule and atlas-like margin rhythm; neural linework remains selective to hero, neurology and journey chapters.
- “Call for Serial” leads the action hierarchy; appointment requests remain secondary and are explicitly identified as a demo interface.
- The mark and physician identity repeat as a deliberate brand signature in the hero, navigation and footer rather than appearing only as utility text.

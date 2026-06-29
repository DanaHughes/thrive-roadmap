# Thrive Communities — Design System

> ⚠️ **Work in progress.** Visual foundations (logo, exact palette, fonts) are being
> confirmed with the brand owner. Sections marked _TBD_ will be filled once real
> brand assets are supplied. See **Caveats** at the bottom.

## What is Thrive?

**Thrive Communities** (Thrive Learning Communities) operates vibrant, in-person
**educational communities for homeschooling families**. They are not a school in the
traditional sense — they are a hybrid/community model that gives homeschoolers a place
to "learn, grow, and belong," combining academics, hands-on experiences, field trips,
and parent-connection events.

**Tagline spirit:** _"Spark curiosity, foster creativity, and celebrate the joy of
learning together with others."_

### Mission (verbatim from site)
> "Our mission is to create a safe, supportive community where homeschoolers can learn,
> grow, and belong. We believe children flourish when they are engaged, challenged, and
> connected with others."

### Audience
- **Homeschooling parents** (primary decision-makers) — experienced and brand-new.
- **Homeschooled students**, K–8th grade and High School.
- Tone toward parents is warm, encouraging, reassuring ("we come alongside you").

### Programs / Products represented
- **K–8th Grades** program
- **High School** program
- **Two-Day Programs**
- **Tuition / Enrollment**
- **Events** & field trips, **Parent Connect** events

### Locations
- Florida, Arizona, South Carolina (multi-state, growing)

### Digital surfaces (products for UI kits)
1. **Marketing website** — `learnatthrive.com` (Our Mission, Program Overview, Locations,
   Events, Get Started/Join). Built on the **Beehively** CMS platform.
2. **Enrollment / family portal** — `register.learnatthrive.com` (Enroll Now, Tour Campus,
   Interest List, Login). Likely a Beehively-hosted registration app.

## Sources
- **Website:** https://learnatthrive.com/ (primary source — text/copy extracted via fetch)
  - About / Mission: https://learnatthrive.com/about-us
  - Program: https://learnatthrive.com/our-program (K-8, High School, Tuition, FAQs)
  - Locations: https://learnatthrive.com/locations (FL, AZ, SC, Two-Day)
  - Get Started: https://learnatthrive.com/join
  - Registration app: https://register.learnatthrive.com
- **Social:** Facebook (`Thrive-Communities`), Instagram (`@thrive.communities`)
- **CMS / host:** Beehively (`beehively.com`)
- **Contact:** info@learnatthrive.com
- Brand meta tile color in markup: `#ffffff` (white tile background).

> No codebase or Figma file was attached. Visual details below the fold are inferred from
> copy + category conventions and **must be confirmed** against the live site's real
> brand assets.

---

## CONTENT FUNDAMENTALS

**Voice:** Warm, encouraging, community-first, and reassuring. Speaks directly to the
parent as a partner, not a customer.

- **Person:** First-person plural **"we"** for Thrive; direct **"you"** for the parent.
  Frequently pairs them: _"We are here to come alongside **you** to support **you** in
  **your** epic journey."_
- **Casing:** Standard sentence case in body; Title Case for nav and headings.
- **Tone words:** _vibrant, joyful, curiosity, flourish, belong, thrive, adventure,
  meaningful, supportive, authentic connection, epic journey._
- **Sentence rhythm:** Anaphora and triads are a signature — _"We believe… We believe…
  We believe…"_ and _"learn, grow, and belong."_ Lists of three recur often.
- **Emphasis:** Uplifting, slightly exclamatory closings — _"You won't regret it!"_,
  _"Embark on this adventure of discovery and growth with us!"_ Used sparingly, at the
  end of a section, never mid-paragraph.
- **Emoji:** Not observed in core site copy. Keep emoji out of product UI; reserve any
  playfulness for social.
- **What we avoid:** corporate/edu-jargon, fear-based marketing, pressure. No "best in
  class," no testimonials-as-pressure. Education is framed as _joy and relationship_,
  not test scores.

**Example CTAs (in brand voice):** "Get Started", "Enroll Now", "Tour Campus",
"Join our community", "More Information".

---

## VISUAL FOUNDATIONS

_TBD — pending real brand assets (logo, palette, fonts) from the brand owner._
Working hypothesis: warm, friendly, approachable, education-for-families palette
(greens/earth tones suggesting growth + warmth), rounded friendly shapes, real
photography of children learning together. To be confirmed.

## ICONOGRAPHY

_TBD — pending confirmation of whether the site uses an icon font, inline SVGs, or
none. To be filled after asset review._

---

## Index / Manifest

_Populated as files are authored:_
- `styles.css` — global entry (import list only)
- `tokens/` — color, typography, spacing custom properties
- `assets/` — logos, imagery, icons
- `components/` — reusable React primitives
- `ui_kits/` — full-screen product recreations
- `guidelines/` — specimen cards
- `SKILL.md` — Agent Skill manifest

## Caveats
- **No logo / font / color files yet.** I can read the site's text but cannot pull its
  images or stylesheets into the project. Real assets must be uploaded.
- Visual foundations are a **hypothesis** until confirmed.

# CV Website — David Caballero

## Project analysis — User persona

**Name:** David Caballero Caballero

**Role:** Computer Science Student

**Goals**
- Find contact details and core skills immediately.
- Save or print a clean PDF for the hiring folder.

**Behaviors**
- Skims headings first, then reads short sections only if relevant.
- Uses desktop most of the time, sometimes prints to PDF.
- Prefers consistent section titles and predictable placement.

**Pain points**
- Overloaded pages with long paragraphs.
- Contact details hidden or split across sections.
- Layouts that break when printed.

**Success criteria**
- Photo, name, and role are obvious.
- Work experience and education are easy to compare.
- Languages and software skills are grouped and scannable.
- One‑click print produces a neat A4 result.

---

## Project analysis — Information architecture (≈200+ words)

The page uses a deliberate two‑column structure to match a traditional CV. The **left column** holds identity and at‑a‑glance data: photo, name, role, a short profile, key soft skills, and contact. This column stays visually stable across the document so the reader can always return to essentials without scrolling. The **right column** holds the sections that require more reading: Work Experience, Education, Languages, IT, and Other. This separation supports the scanning pattern of recruiters: identity first, then detail.

Sections on the right are grouped into compact “cards.” Each card starts with a pill‑style heading and a short block of content. Paragraphs are tight and use short statements rather than prose to avoid cognitive load. Languages are split into two short lists to reduce ambiguity. IT skills state the tool first and the level second, following how recruiters search for keywords.

Technically, CSS Grid defines two fixed columns sized for A4. Measurements are in **millimetres** so on‑screen and print lay out consistently.  A neutral sidebar background guides the eye without competing with headings. Print styles remove shadows and browser margins, so exporting to PDF preserves spacing and typography. The result is predictable placement that matches the original PDF while remaining simple to maintain.

---

## Project analysis — Visual design (≈200+ words)

The visual system follows three goals: fast recognition, clear hierarchy, and reliable print. Color is used sparingly and always tied to meaning. A soft **green** panel anchors the identity area on the left; it frames the name and photo and establishes a calm background for contact details. A contrasting **violet** accent marks the role line to help recruiters remember the field at a glance. Section headers on the right use a light **peach** pill with a subtle border. This shape creates a repeated cue that signals the start of a new block without drawing excessive attention.

Typography stays pragmatic: a sans‑serif system stack (Arial) for broad OS support and consistent rendering in PDFs. The candidate name appears in uppercase with high weight for instant recognition. Letter‑spacing and font size are tuned so the name fits the green block without overflow. Body text keeps a compact line‑height to maximize information density while remaining legible.

Spacing uses a simple rhythm based on millimetres to ensure that what you see on screen matches the print result. The photo container is a fixed rectangle, so any image dropped in `img/foto.jpg` will fill the frame with `object-fit: cover`. Icons in the contact list aid scanning but remain monochrome to avoid visual noise. Decorative shapes were intentionally removed to keep the document focused and formal. Overall, the design choices privilege clarity and print reliability over embellishment.



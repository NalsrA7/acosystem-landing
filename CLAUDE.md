# CLAUDE.md — Acosystem Google Ads Landing Page

Context file for any Claude session working on the Acosystem landing page. Read this before touching copy, design or code.

---

## 1. Project in one line

A single-page, mobile-first landing page that catches **all Google Ads traffic** for Acosystem and turns it into **WhatsApp conversations**. Built by Kogni Consulting (Arslan) as part of a 3-month Google Ads engagement (Oct–Dec 2026).

---

## 2. Client background

- **Acosystem**: business tax, accounting, legal and advisory firm in Surabaya. Legal entity: **PT Acosystem Advisory Indonesia**.
- Office: **Ciputra World Office Tower, Surabaya**. Serves all of Java and nationwide online.
- Main contact: **Patrick**. Their website developer deploys to their domain and manages GTM.
- Main site: https://acosystem.id (use it for brand colours/font/logo only, nothing else; see §9).
- WhatsApp number used on the page: **+62 813-5709-7121** (`wa.me/6281357097121`).

**Proof points (confirmed by client):**
- **120+** klien perusahaan
- **17+** tahun pengalaman
- **0** klien pindah ke konsultan lain (no client has ever left for a competitor)
- International experience, local expertise
- Industries served: F&B, Sports Center, Trading (jual beli), Logistics, Manufacturing, Education Center, Wellness (spa), Perumahan, Building Materials

**Real edge:** all-in-one. Tax + accounting + legal under one team, plus advisory to help the business grow. Professional and trusted. Also affordable, but **don't lead with price**.

---

## 3. Goals

- **Primary conversion:** WhatsApp conversation started (CTWA). Not form fills, not button clicks for their own sake.
- Secondary: final-section form that **pre-fills a WhatsApp message** (name, company, service).
- Offer: **"Konsultasi gratis"**. Internally it's an initial scoping call; on the page, frame it generously. Don't describe it as "just a scoping call."
- Engagement goal: prove **cost per lead and lead quality** over 3 months. Months 1–2 are a learning phase.

---

## 4. Audience

- Business owners and finance decision-makers who **already searched** for the service. Intent is high; doubt is the blocker, not awareness.
- Typical client: **small team, mid-level revenue**, able to afford a professional firm. Open to bigger clients.
- Any legitimate industry (no dodgy/illegal businesses).
- **Mostly on mobile.** Design at 390px first, desktop second.
- **Not the audience:** individuals filing personal tax (SPT pribadi). See §6 negatives.

**Service priority on the page:**
1. Pajak (top)
2. Akuntansi (top)
3. Pendirian PT (secondary)
4. Advisory (add-on: valuasi bisnis, strategi, scaling/ekspansi, struktur & skala upah)

---

## 5. Brand

Colours and font come from acosystem.id. Layout and style do **not**.

| Token | Value | Use |
|---|---|---|
| Navy | `#051c2c` | Text, dark sections, header, footer |
| Indigo | `#313f9f` | Single accent: headings highlights, secondary buttons, icons |
| Indigo light (on dark) | `#8f9cf0` | Accent text on navy backgrounds |
| Indigo wash | `#eceefb` | Icon tiles, tags |
| Off-white | `#fbfbfc` | Page background |
| Light section | `#f0f2f6` | Alternating section background |
| Muted text | `#4a5d6e` | Body/secondary copy on light |
| WhatsApp green | `#25d366` | WhatsApp CTA buttons only |
| Success green | `#2fbf71` | Tick icons, status badges |

- **Font:** Geist (400/500/600/700); Geist Mono for small uppercase labels and stats.
- **Logo:** wordmark "acosystem." (`acosystem.id/images/logo-nav.png`, white version `logo-nav-white.png`).
- **Shape:** pill buttons (`border-radius: 999px`), ~16–20px radius on panels, tight negative letter-spacing on headings.

---

## 6. Google Ads keywords

> The final keyword list isn't built yet. These are the agreed **themes** and the one negative list we know we need. Update this section once the account is built.

**Ad groups / themes (match the page's services):**
- **Pajak:** jasa pajak perusahaan, konsultan pajak Surabaya, jasa pajak badan, SPT tahunan badan, lapor PPN, PPh 21 karyawan
- **Akuntansi:** jasa akuntansi Surabaya, jasa pembukuan perusahaan, jasa laporan keuangan
- **Pendirian PT:** jasa pendirian PT Surabaya, pendirian PT perorangan, pendirian CV, urus NIB
- **Advisory:** valuasi bisnis, konsultan bisnis (lowest priority)

**Targeting (suggested, budget ~Rp 2–2.5jt/month):** tight high-intent B2B terms, Surabaya/East Java geo, business-hours schedule.

**Negative keywords (must exist before Feb–Mar 2027 tax season):** individual tax terms like SPT pribadi, SPT tahunan orang pribadi, lapor pajak pribadi, e-filing, cara lapor SPT, plus job/education terms (lowongan, kursus, brevet, gaji akuntan).

---

## 7. Tone and copy rules

- **Bahasa Indonesia only.** Professional but approachable. Not stiff or "kaku."
- Address the reader as **"Anda"**. Sentence case headings.
- **Short.** One sentence per block, max. If a section feels wordy, cut it.
- Use **"deadline"**, never "tenggat".
- Use the **bahasa-skills:bahasa-website** and **bahasa-skills:bahasa-inti** skills for any copy change.
- Every main button uses the same label: **"Konsultasi gratis via WhatsApp"**.
- "Tanpa ikatan" (not "tanpa kewajiban").
- Claims we can make: deadlines never missed, legal tax savings, tidy presentation-ready reports. Mark any tax-savings visual as **"Ilustrasi"**.

**Locked copy — do not change without Arslan's OK:**
- Hero headline: **"Pajak beres. Pembukuan rapi."**
- Hero pill: **"Layanan pajak & akuntansi *all-in-one*"**

---

## 8. Decisions made

**Structure (one page, top to bottom):**
1. **Hero:** headline, one-line sub, 3 ticks, full-width WhatsApp button above the fold on mobile, outcome visual (status card with "Terlapor" badges, WhatsApp bubble from Tim Acosystem, "0 deadline terlewat" chip).
2. **Trust:** "Klien kami betah." Three big stats, team photo slot, icon badges, industry chips.
3. **Services:** tap tabs (Pajak / Akuntansi / Pendirian PT / Advisory) swapping one panel, each with its own WhatsApp CTA and pre-filled message.
4. **Results + how it works:** swipeable outcome tiles, then 4 short steps ("Begini cara kerjanya.").
5. **FAQ:** "Masih ragu?" Six one-line answers, written like real questions people type.
6. **Final CTA:** "Mulai dari satu chat." + 3-field form that opens WhatsApp.

**Other decisions:**
- No nav, no outbound links, no links to the main site.
- **Generic hero** (no `?layanan=` dynamic headline for now).
- **Pricing hidden.**
- **No client logos or names** (confidentiality). Use industries instead.
- **No credentials/licence line** (client said not needed).
- Floating WhatsApp button that appears after the hero button scrolls out of view.
- Inspiration: Pilot, Bench, IZIN.co.id, Kontrak Hukum. Not acosystem.id.
- Design must work **with real photography** (team photo still needed from client).
- Delivered to the developer as a **single self-contained HTML file**, deployed on Acosystem's domain.
- `<meta name="robots" content="noindex, follow">` so the ads page doesn't compete with the main site.

**Tracking (for GTM with their developer):**
- Every WhatsApp link has a stable `id` (`cta-header`, `cta-hero`, `cta-layanan`, `cta-cara-kerja`, `cta-floating`, `cta-form`) plus `data-cta-location` and `data-service`.
- dataLayer events: `wa_click` (`cta_location`, `service`) and `wa_form_submit`.
- Primary Google Ads conversion = WhatsApp click/conversation. Move to offline qualified-lead imports once volume justifies it.

---

## 9. Things to avoid

- **Copying acosystem.id's style or layout.** Arslan dislikes it. Only colours, font and logo carry over.
- **Verbose copy.** Walls of text, long hero, long paragraphs.
- **Dash bullets ("- ").** Use ticks, icons or visual tiles instead.
- **Small type in text-heavy areas.** Body 17px+ on mobile.
- **Generic gradients** or anything that looks AI-made. Solid colours only; subtle fading patterns are fine.
- **Overusing cards** as a design element.
- Looking toyish. Approachable, but professional and trustworthy.
- Unnatural Indonesian (e.g. "mulai langkah 1 sekarang", "nol telat lapor", "tenggat").
- Showing prices, or leading with "affordable/murah."
- Client names/logos, stock handshake photos.
- Overpromising specific savings numbers without backing.
- Hyping or manufacturing urgency. No exclamation marks.
- Breaking layout after copy edits. After any copy change, check for overflow, clipped text and single-word last lines on both mobile (390px) and desktop (1440px).

---

## 10. Still open

- [ ] Real team photo from Acosystem
- [ ] Final keyword list and negative lists built in the account (§6)
- [ ] Developer deploys HTML + sets up GTM triggers on the IDs/events above
- [ ] Verify WhatsApp conversion fires correctly in Google Ads before scaling spend

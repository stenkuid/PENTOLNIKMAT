# PRD — Website #7: Pentol Nikmat

### Kuliner Bakso, Mie Ayam & Comfort Food Lokal

**Platform:** Astro + Cloudflare  
**Project Type:** Local Food Business Website  
**Status:** PRD v1.0  

---

# 1. Product Overview

**Pentol Nikmat** adalah bisnis kuliner yang menyediakan aneka bakso dengan pilihan:

* Bakso urat.
* Bakso daging.
* Mie kuning.
* Bihun.
* Mie ayam.

Produk utama adalah **bakso** sebagai hero product.

Website harus membuat pengunjung langsung merasakan bahwa Pentol Nikmat adalah tempat makan yang:

* Enak.
* Mengenyangkan.
* Familiar.
* Affordable.
* Cocok untuk makan siang, sore, maupun malam.

Core message:

> **Semangkuk hangat, rasa yang bikin nikmat.**

---

# 2. Business Goal

## Primary Goal

Meningkatkan kunjungan pelanggan dan order makanan.

## Secondary Goals

* Meningkatkan awareness Pentol Nikmat.
* Menampilkan menu dengan visual appetizing.
* Memudahkan pelanggan melihat harga.
* Membantu pelanggan menemukan lokasi.
* Mendorong order melalui WhatsApp/channel resmi.
* Meningkatkan Local SEO.

---

# 3. Target Customer

## Primary

Usia ±15–40 tahun:

* Pelajar.
* Mahasiswa.
* Pekerja.
* Keluarga.
* Pengguna makanan lokal.
* Pecinta bakso.

## Secondary

* Customer yang mencari makan cepat.
* Customer yang ingin makanan hangat.
* Customer yang ingin makan bersama teman.

---

# 4. Customer Problem

Customer ingin:

* Makanan enak.
* Porsi cukup.
* Harga jelas.
* Lokasi mudah ditemukan.
* Menu mudah dipahami.
* Tidak perlu menunggu informasi terlalu lama.

Website harus meminimalkan friction.

---

# 5. Brand Positioning

### Positioning

> **Pentol Nikmat — bakso hangat, rasa mantap, bikin balik lagi.**

Brand harus terasa:

* Local.
* Friendly.
* Fun.
* Delicious.
* Casual.
* Affordable.

---

# 6. Brand Personality

Tone:

**Santai, menggugah selera, dan sedikit playful.**

Contoh:

> **Lagi pengen yang berkuah? Pentol Nikmat aja.**

> **Baksonya mantap. Kuahnya bikin nambah.**

> **Satu mangkuk nggak pernah cukup.**

Hindari bahasa corporate.

---

# 7. Unique Selling Proposition

### Bakso Urat

Tekstur khas dan menjadi salah satu hero menu.

### Bakso Daging

Pilihan untuk pelanggan yang menyukai bakso daging.

### Custom Bowl

Pelanggan dapat memilih kombinasi mie/bihun dan bakso jika sistem bisnis memungkinkan.

### Mie Ayam

Alternatif bagi pelanggan yang tidak ingin bakso.

---

# 8. Website Objective

Pengunjung harus langsung memahami:

1. Pentol Nikmat adalah tempat makan bakso.
2. Ada bakso urat dan daging.
3. Ada mie ayam.
4. Menu dan harga dapat dilihat.
5. Lokasi tersedia.
6. Cara order jelas.

Primary CTA:

**Lihat Menu**

Secondary:

**Order Sekarang**

---

# 9. Architecture Decision

## Recommended

**Astro Static + Cloudflare Pages**

Tidak membutuhkan database Phase 1.

Menu disimpan sebagai static data.

---

# 10. Technology Stack

* Astro.
* TypeScript.
* Native CSS.
* Minimal JavaScript.
* Cloudflare Pages.

Optional:

* Cloudflare Web Analytics.

Avoid:

* Online ordering system kompleks.
* Payment gateway.
* Heavy menu framework.
* Database.

---

# 11. Sitemap

```text
/
├── /menu
├── /about
├── /location
├── /contact
├── /faq
├── /robots.txt
└── /sitemap-index.xml
```

---

# 12. Homepage Structure

1. Navbar.
2. Hero.
3. Featured Menu.
4. Menu Categories.
5. Why Pentol Nikmat.
6. Build Your Bowl.
7. Food Photography.
8. Customer Testimonials.
9. Location.
10. FAQ.
11. Final CTA.
12. Footer.

---

# 13. Navbar

Logo:

**PENTOL NIKMAT**

Navigation:

* Home.
* Menu.
* About.
* Location.

CTA:

**Order Now**

Mobile menggunakan hamburger.

---

# 14. Hero

Hero harus sangat appetite-driven.

### Headline

> **Semangkuk Nikmat, Bikin Balik Lagi.**

Supporting copy:

> Bakso urat, bakso daging, mie kuning, bihun, dan mie ayam untuk menemani rasa lapar kapan saja.

CTA:

**Explore Menu**

Secondary:

**Find Us**

---

# 15. Hero Visual

Focal point:

**Semangkuk bakso panas.**

Visual:

* Bakso.
* Kuah.
* Mie kuning.
* Bihun.
* Sambal.
* Daun bawang.
* Steam ringan.

Foto harus terlihat nyata dan menggugah selera.

Tidak perlu membuat steam animation.

---

# 16. Design Direction

## Concept

**Modern Indonesian Street Food × Warm Comfort Food**

Visual:

* Warm.
* Rich.
* Bold.
* Appetite-focused.
* Local.
* Friendly.

Bukan:

* Fine dining.
* Generic food delivery app.
* Corporate restaurant chain.

---

# 17. Suggested Color Palette

### Chili Red

`#C62828`

### Dark Brown

`#3B241C`

### Warm Cream

`#FFF3DC`

### Golden Yellow

`#F2B134`

### Green Accent

`#5E7D3A`

### White

`#FFFFFF`

Primary:

Warm Cream.

Accent:

Chili Red.

---

# 18. Typography

Heading:

* Bold.
* Playful.
* Strong.

Body:

* Friendly sans-serif.

Optional display font dengan sedikit karakter lokal.

Maksimal dua font family.

---

# 19. Featured Menu

Headline:

> **Menu Favorit Hari Ini**

Tampilkan:

### Bakso Urat

Bakso dengan tekstur urat yang khas.

### Bakso Daging

Bakso daging dengan kuah hangat.

### Mie Ayam

Mie dengan topping ayam dan pelengkap.

### Bakso Komplit

Kombinasi bakso dan mie sesuai pilihan.

Nama menu final harus disesuaikan dengan menu aktual.

---

# 20. Menu Card

Card:

* Food image.
* Name.
* Description.
* Price.
* Badge.

Badges:

**BEST SELLER**

**FAVORITE**

**NEW**

Gunakan badge hanya jika benar.

---

# 21. Menu Categories

### Bakso

* Bakso Urat.
* Bakso Daging.
* Bakso Komplit.
* Special bowl jika tersedia.

### Mie

* Mie Ayam.
* Mie Ayam Bakso jika tersedia.

### Add-ons

* Extra bakso.
* Extra mie.
* Extra topping.
* Sambal.

Hanya tampilkan item aktual.

---

# 22. Build Your Bowl

Section interaktif ringan.

Headline:

> **Racik Mangkukmu Sendiri.**

Pilihan:

### Base

* Mie kuning.
* Bihun.

### Bakso

* Urat.
* Daging.

### Extras

* Extra bakso.
* Sayuran.
* Topping lainnya.

Jika custom bowl belum menjadi sistem order resmi, section ini cukup sebagai visual menu concept dan bukan configurator order.

---

# 23. Why Pentol Nikmat

Headline:

> **Kenapa Pentol Nikmat?**

Benefit:

### Warm & Comforting

Makanan hangat untuk mengisi perut.

### Flavorful

Kuah dan bumbu menjadi bagian penting pengalaman.

### Flexible

Pilih bakso, mie, atau kombinasi.

### Familiar

Comfort food yang mudah dinikmati berbagai usia.

---

# 24. Food Photography

Section:

> **Lihat Dulu. Ngiler Kemudian.**

Visual:

* Hero bowl.
* Bakso close-up.
* Mie ayam.
* Mie kuning.
* Bihun.
* Sambal.
* Restaurant ambience.

Gunakan CSS grid.

Tidak menggunakan carousel jika tidak diperlukan.

---

# 25. Food Details

Gunakan small detail section:

**Hot Broth**

Kuah hangat sebagai bagian penting hidangan.

**Tender Meatballs**

Tekstur bakso sebagai hero experience.

**Fresh Toppings**

Pelengkap yang memberikan rasa dan tekstur.

Jangan membuat klaim seperti "100% homemade" atau "tanpa pengawet" kecuali benar-benar tersedia.

---

# 26. Customer Testimonials

Gunakan review asli jika tersedia.

Contoh placeholder:

> **"Baksonya enak, kuahnya cocok banget dimakan pas lagi hujan."**

**— Customer Pentol Nikmat**

Jangan membuat testimonial palsu sebagai review nyata.

---

# 27. Location

Headline:

> **Lagi Lapar? Datang Sini.**

Informasi:

* Address.
* Opening hours.
* Phone.
* WhatsApp.
* Google Maps.

CTA:

**Get Directions**

---

# 28. Contact / Order CTA

Headline:

> **Sudah Kebayang Rasanya?**

Copy:

> Jangan cuma dibayangin. Datang dan nikmati semangkuk Pentol Nikmat.

CTA:

**Order Now**

Secondary:

**Visit Us**

---

# 29. WhatsApp Flow

Pre-filled message:

> Halo Pentol Nikmat, saya ingin order/menu. Bisa info menu yang tersedia?

Jika menu dan order flow sudah jelas:

> Halo Pentol Nikmat, saya ingin pesan [menu] sebanyak [jumlah].

Nomor resmi hanya digunakan setelah tersedia.

---

# 30. FAQ

### Apa saja menu yang tersedia?

Tampilkan kategori menu.

### Apa perbedaan bakso urat dan bakso daging?

Jelaskan secara singkat.

### Apakah bisa pilih mie?

Jawab sesuai sistem menu.

### Apakah tersedia mie ayam?

Ya jika memang tersedia.

### Apakah bisa tambah bakso?

Jawab sesuai menu.

### Apakah menerima order lewat WhatsApp?

Hanya jika tersedia.

---

# 31. Local SEO

Keyword:

* bakso [kota].
* bakso enak [kota].
* bakso urat [kota].
* bakso daging [kota].
* mie ayam [kota].
* tempat makan [kota].
* kuliner [kota].

Gunakan lokasi aktual bisnis.

---

# 32. Metadata

Homepage:

**Pentol Nikmat — Bakso Urat, Bakso Daging & Mie Ayam**

Local:

**Pentol Nikmat — Bakso & Mie Ayam di [City]**

Description:

> Nikmati bakso urat, bakso daging, mie kuning, bihun, dan mie ayam di Pentol Nikmat. Lihat menu, harga, dan lokasi kami.

---

# 33. Structured Data

Gunakan:

**Restaurant / LocalBusiness**

Properties:

* name.
* address.
* telephone.
* openingHours.
* image.
* servesCuisine.
* priceRange.
* url.

Jika menu online tersedia secara lengkap, structured data menu dapat diperluas.

---

# 34. Open Graph

OG image:

* Bowl of meatballs.
* Warm food photography.
* Brand logo.

Metadata:

* Title.
* Description.
* Image.
* URL.
* Type.

---

# 35. Image Strategy

Food image menjadi prioritas tertinggi.

Gunakan:

* AVIF/WebP.
* Responsive images.
* Explicit dimensions.
* Lazy loading non-critical.
* Optimized hero image.

Food photography sebaiknya:

* High contrast.
* Warm.
* Close-up.
* Realistic.
* Appetite stimulating.

---

# 36. Mobile UX

Primary actions:

* Menu.
* Order.
* Location.

Optional sticky CTA:

**🍜 Order Now**

Menu card:

1 column.

Tablet:

2 columns.

Desktop:

3–4 columns.

---

# 37. Animation

Minimal:

* Hover.
* Button transition.
* Image reveal.

Avoid:

* Animated steam.
* Floating food.
* Rotating bowls.
* Parallax-heavy layout.
* Food particles.

---

# 38. Accessibility

Requirements:

* Semantic HTML.
* Heading hierarchy.
* Accessible buttons.
* Alt text.
* Keyboard navigation.
* Focus state.
* Contrast.

---

# 39. Performance

Target:

* Performance ≥90.
* SEO ≥95.
* Accessibility ≥90.

Core Web Vitals:

* LCP ≤2.5s.
* CLS ≤0.1.
* INP ≤200ms.

Food photography harus dioptimalkan dengan ketat.

---

# 40. Cloudflare Architecture

```text
Astro
 ↓
Static Build
 ↓
Cloudflare Pages
```

No database.

No backend.

No Worker runtime Phase 1.

---

# 41. Bundle Policy

* Static generation.
* Minimal JS.
* Native CSS.
* No heavy UI libraries.
* No unnecessary carousel.
* No ordering framework.
* No database client.

Production build harus dianalisis.

Jika Worker digunakan di masa depan, compressed server bundle harus tetap di bawah batas deployment Cloudflare yang berlaku.

---

# 42. Recommended Project Structure

```text
src/
├── components/
│   ├── Navbar.astro
│   ├── Button.astro
│   ├── MenuCard.astro
│   ├── CategoryCard.astro
│   ├── TestimonialCard.astro
│   ├── FAQItem.astro
│   └── Footer.astro
│
├── sections/
│   ├── Hero.astro
│   ├── FeaturedMenu.astro
│   ├── MenuCategories.astro
│   ├── WhyPentolNikmat.astro
│   ├── BuildYourBowl.astro
│   ├── FoodGallery.astro
│   ├── Testimonials.astro
│   ├── Location.astro
│   ├── FAQ.astro
│   └── FinalCTA.astro
│
├── layouts/
│   └── BaseLayout.astro
│
├── pages/
│   ├── index.astro
│   ├── menu.astro
│   ├── about.astro
│   ├── location.astro
│   ├── contact.astro
│   ├── faq.astro
│   ├── robots.txt.ts
│   └── sitemap-index.xml.ts
│
├── data/
│   ├── business.ts
│   ├── menu.ts
│   └── faq.ts
│
├── styles/
│   └── global.css
│
└── assets/
```

---

# 43. Data Architecture

### Menu

```text
menuItem
├── slug
├── name
├── category
├── description
├── price
├── image
├── badge
└── available
```

### Business

```text
business
├── name
├── address
├── phone
├── whatsapp
├── openingHours
├── mapsUrl
└── socialLinks
```

---

# 44. Analytics

Cloudflare Web Analytics.

Track:

```text
view_menu
click_menu
click_order
click_direction
click_whatsapp
```

Primary conversion:

**Order CTA**

Secondary:

**Direction CTA**

---

# 45. Security

Static website tidak menyimpan customer data.

Jika order form ditambahkan:

* Input validation.
* Spam protection.
* Rate limiting.
* Cloudflare Turnstile jika diperlukan.

---

# 46. Out of Scope

Tidak termasuk:

* Online ordering engine.
* Online payment.
* Delivery management.
* Customer accounts.
* Loyalty system.
* Inventory.
* POS integration.
* Admin CMS.
* Database.

---

# 47. Future Expansion

## Phase 2

* Online ordering.
* Menu customization.
* Promo pages.
* Delivery integration.

## Phase 3

* Order management.
* Customer loyalty.
* Admin dashboard.
* Cloudflare Workers.
* D1.

---

# 48. Acceptance Criteria

## Brand

* [ ] Pentol Nikmat terasa local dan friendly.
* [ ] Food photography kuat.
* [ ] Brand tidak terasa seperti chain restaurant generik.

## Menu

* [ ] Bakso menjadi hero product.
* [ ] Bakso urat dan daging jelas.
* [ ] Mie ayam tersedia.
* [ ] Mie kuning/bihun mudah dipahami.
* [ ] Harga mudah ditemukan jika tersedia.

## Conversion

* [ ] Order CTA jelas.
* [ ] Menu mudah diakses.
* [ ] Location mudah ditemukan.
* [ ] WhatsApp CTA tersedia jika digunakan.

## SEO

* [ ] Restaurant/LocalBusiness schema.
* [ ] Metadata.
* [ ] Canonical.
* [ ] Sitemap.
* [ ] Robots.
* [ ] Open Graph.
* [ ] Local keywords.

## Performance

* [ ] Performance ≥90.
* [ ] SEO ≥95.
* [ ] Accessibility ≥90.
* [ ] Images optimized.
* [ ] Minimal JavaScript.

## Technical

* [ ] Astro build berhasil.
* [ ] Cloudflare Pages compatible.
* [ ] No unnecessary dependencies.
* [ ] No broken links.
* [ ] No console errors.

---

# 49. Implementation Blueprint

## Website Goal

Membangun website Pentol Nikmat sebagai **appetite-driven local food website** yang mengubah rasa lapar menjadi kunjungan/order.

Customer journey:

**Hungry → See Food → Explore Menu → Want It → Find Location → Order**

## Architecture

**Astro Static + Cloudflare Pages**

## Sitemap

```text
/
├── /menu
├── /about
├── /location
├── /contact
├── /faq
├── /robots.txt
└── /sitemap-index.xml
```

## Design Direction

**Modern Indonesian Street Food × Warm Comfort Food**

## Core Components

* Navbar.
* Hero.
* Menu Card.
* Menu Category.
* Build Your Bowl.
* Food Gallery.
* Testimonial.
* Location.
* FAQ.
* Order CTA.
* Footer.

## Technical Requirements

* Astro.
* TypeScript.
* Static generation.
* Data-driven menu.
* Optimized food photography.
* Minimal JS.
* Local SEO.
* Restaurant schema.
* Sitemap.
* Robots.
* Open Graph.
* Cloudflare Pages.

---

# 50. Antigravity Execution Plan

## Prompt 1 — Analysis

> You are a senior full-stack engineer. Analyze the Pentol Nikmat PRD before coding. Determine the Astro static architecture, menu data model, reusable components, SEO structure, conversion flow, image strategy, responsive behavior, and implementation checklist. Do not invent ordering, payment, delivery, database, or backend features.

Output:

* Architecture.
* Component plan.
* Menu data model.
* SEO plan.
* Conversion plan.
* Implementation checklist.

---

## Prompt 2 — Build

> You are a senior full-stack engineer. Build the Pentol Nikmat local food website according to the provided PRD. Use Astro static generation, reusable components, data-driven menu content, optimized responsive food photography, semantic HTML, minimal client-side JavaScript, and Cloudflare Pages compatibility. The design must feel warm, appetizing, local, playful, and premium enough without becoming formal or corporate. Do not add unnecessary dependencies or features.

Implement:

* Homepage.
* Menu.
* About.
* Location.
* Contact.
* FAQ.
* Food gallery.
* Order CTA.
* Local SEO.
* Structured data.
* Responsive design.

---

## Prompt 3 — Optimization

> You are a senior full-stack engineer preparing the Pentol Nikmat website for production. Audit and optimize the project for build reliability, performance, accessibility, SEO, responsive behavior, food image delivery, JavaScript payload, dependency size, broken links, conversion usability, and Cloudflare Pages compatibility. Fix all issues without changing requirements or introducing unnecessary architecture.

Check:

### Build

* Production build.
* Type checking.
* Broken links.
* Console errors.

### Menu

* Menu data.
* Categories.
* Prices.
* Images.
* CTA.

### Performance

* LCP.
* CLS.
* INP.
* Image sizes.
* JS payload.
* CSS payload.
* Bundle analysis.

### SEO

* Metadata.
* Canonical.
* Restaurant schema.
* LocalBusiness schema.
* Sitemap.
* Robots.
* Open Graph.

### Conversion

* Menu CTA.
* Order CTA.
* WhatsApp.
* Location CTA.
* Mobile sticky CTA if used.

### Cloudflare

* Static output.
* Pages compatibility.
* Dependency audit.
* No unnecessary Worker runtime.

Output:

**Deployment-ready Astro project.**

---

# 51. Final Product Definition

Pentol Nikmat v1 harus membuat pengguna merasa:

> **"Saya lapar dan saya ingin semangkuk itu sekarang."**

Website bukan katalog formal.

Website harus menjadi **digital appetite trigger**.

Customer journey:

**Visual Makanan → Menu → Harga → Desire → Location → Order**

Prioritas:

**Food Visual > Appetite > Menu > Price > Location > CTA > SEO > Performance**

**Database:** Tidak diperlukan.

**Backend:** Tidak diperlukan.

**Framework:** Astro.

**Hosting:** Cloudflare Pages.

**Primary CTA:** Order Now.

**Secondary CTA:** Get Directions.

**Core Message:**
**"Semangkuk nikmat, bikin balik lagi."**

---

# AI DEVELOPMENT & DESIGN CONTROL PROTOCOL

## Project Protocol

This document defines the mandatory operating rules for all AI agents working on this project.

All instructions in this file must be read and followed before modifying any project file.

The primary purpose of this protocol is to preserve approved design states, prevent unintended redesigns, control AI modifications, and provide a predictable command system for development.

---

# 1. CORE PRINCIPLE

The AI agent must treat the existing approved project state as valuable and protected.

The AI must NEVER assume that an existing implementation should be improved, modernized, refactored, redesigned, simplified, or replaced unless the user explicitly requests it.

When the user's request is narrow, the modification must remain narrow.

The AI must preserve:

- Existing approved layouts
- Existing visual hierarchy
- Existing typography
- Existing spacing
- Existing colors
- Existing images
- Existing responsive behavior
- Existing interactions
- Existing functionality

unless explicitly instructed otherwise.

---

# 2. PROTOCOL PRIORITY

When interpreting instructions, use the following priority order:

1. Explicit user instruction
2. Active protocol command
3. Locked component rules
4. Approved checkpoint rules
5. Existing project implementation
6. General design or coding preferences

The AI must not override a higher-priority instruction with a lower-priority assumption.

---

# 3. BEFORE EVERY MODIFICATION

Before modifying any file, the AI must:

1. Read this `PROTOCOL.md`.
2. Identify the active protocol command.
3. Identify the exact component or files that need modification.
4. Check whether the target component is locked.
5. Preserve all unrelated components.
6. Avoid modifying files that are outside the requested scope.

The AI must NOT begin a broad redesign simply because a requested change affects part of the page.

---

# 4. MINIMAL CHANGE PRINCIPLE

The AI must make the smallest reasonable modification necessary to fulfill the user's request.

The AI must NOT:

- Rewrite unrelated components.
- Refactor unrelated code.
- Change the design system.
- Replace existing layouts without permission.
- Change typography without permission.
- Change spacing without permission.
- Replace images without permission.
- Change colors without permission.
- Modify responsive behavior outside the requested scope.
- Remove functionality unless explicitly requested.

If a requested modification can be completed by changing one component, the AI must not rewrite the entire page.

---

# 5. DESIGN PRESERVATION RULE

Existing design is considered protected by default.

The AI must NOT interpret requests such as:

- "Improve this"
- "Make this better"
- "Fix this"
- "Add this feature"

as permission to redesign unrelated sections.

If the request does not explicitly request redesign, preserve the existing visual appearance.

---

# 6. EXACT RESTORATION RULE

When restoring a previous state, the AI must restore the exact known implementation.

The AI must NOT:

- Recreate the design from memory.
- Generate a similar design.
- Approximate the previous layout.
- Improve the previous version.
- Modernize the previous version.
- Combine the previous design with the current design.

Restoration means restoring the previous code state as accurately as possible.

The AI must always prefer:

1. Git history
2. Git commit
3. Git diff
4. Existing backup
5. Explicit checkpoint reference

The AI must never guess the previous implementation if an exact source is available.

---

# 7. PROTOCOL COMMAND SYSTEM

Commands beginning with `/` are protocol commands.

Protocol commands must be interpreted according to this document.

The AI must execute the command according to its definition.

The AI must not reinterpret the meaning of a protocol command.

---

# 8. /REVERSE

## Purpose

Undo the latest unapproved modification.

## Execution Rules

When `/REVERSE` is activated:

1. Identify the latest modification made for the current task.
2. Identify all files affected by that modification.
3. Restore those files to their exact state before that modification.
4. Preserve all older approved changes.
5. Do not redesign anything.
6. Do not generate an alternative implementation.
7. Do not improve the restored version.
8. Do not modify unrelated files.

The AI must treat `/REVERSE` as:

"Restore the exact previous state."

The AI must NOT interpret `/REVERSE` as:

"Create something similar to the previous design."

After restoration, stop modifying the project unless the user provides another instruction.

---

# 9. /CHECKPOINT [NAME]

## Purpose

Create a named approved state.

Example:

`/CHECKPOINT homepage-v1`

When activated:

1. Identify the current project state.
2. Record the checkpoint name.
3. Record the relevant files associated with the checkpoint.
4. Record the purpose of the checkpoint.
5. Treat this state as an approved reference.

A checkpoint should preferably correspond to a Git commit whenever possible.

---

# 10. /RESTORE [NAME]

## Purpose

Restore a previously approved checkpoint.

Example:

`/RESTORE homepage-v1`

When activated:

1. Locate the exact checkpoint.
2. Identify its associated files or Git commit.
3. Restore the exact code state.
4. Do not reinterpret the design.
5. Do not merge the checkpoint with experimental changes unless explicitly requested.

The checkpoint is the source of truth.

---

# 11. /LOCK [COMPONENT]

## Purpose

Protect an approved component from modification.

Example:

`/LOCK HERO`

When a component is locked, the AI must NOT modify:

- Layout
- HTML structure
- CSS styling
- Typography
- Spacing
- Colors
- Images
- Animations
- Responsive behavior
- Component logic

unless explicitly instructed.

Example:

`/LOCK HERO`

means the Hero section must remain unchanged.

---

# 12. /UNLOCK [COMPONENT]

## Purpose

Remove protection from a previously locked component.

Example:

`/UNLOCK HERO`

Only after this command may the AI freely modify the specified component according to the user's instructions.

Unlocking one component does not unlock other components.

---

# 13. /STRICT

## Purpose

Enable strict modification mode.

When `/STRICT` is active:

- Modify only explicitly requested components.
- Modify only files required to complete the request.
- Do not refactor unrelated code.
- Do not redesign unrelated sections.
- Do not optimize unrelated components.
- Do not modify the design system.
- Do not make "helpful" visual changes.
- Preserve all existing behavior unless explicitly instructed otherwise.

The AI must prioritize precision over creativity.

---

# 14. /DESIGN-ONLY

## Purpose

Allow visual modifications while protecting application functionality.

The AI may modify:

- Layout
- Typography
- Spacing
- Colors
- Visual hierarchy
- Animation
- Responsive styling

The AI must NOT modify:

- Business logic
- API integrations
- Routing
- Data structures
- Application logic

unless explicitly requested.

---

# 15. /CODE-ONLY

## Purpose

Modify functionality while preserving the visual design.

When `/CODE-ONLY` is active, the existing visual design must remain unchanged.

The AI must NOT modify:

- Layout
- Typography
- Colors
- Spacing
- Images
- Animation
- Visual hierarchy

unless explicitly requested.

---

# 16. /WA

## Purpose

Activate the WhatsApp Floating Action Button protocol.

When `/WA` is activated:

1. Add a floating WhatsApp contact button.
2. Position it appropriately without obstructing important UI.
3. Use fixed positioning.
4. Ensure responsive behavior.
5. Ensure mobile safe-area compatibility.
6. Ensure the button is touch-friendly.
7. Use the existing design language.
8. Do not redesign the page.
9. Do not modify unrelated sections.
10. Do not change existing layout structure.

The WhatsApp button must be implemented as an isolated component whenever practical.

---

# 17. /REMOVE-WA

Remove the WhatsApp floating button and all directly associated implementation.

Do not modify unrelated components.

---

# 18. /SCOPE [COMPONENT OR FILE]

## Purpose

Restrict all modifications to a specific scope.

Example:

`/SCOPE HERO`

or:

`/SCOPE src/components/Hero.astro`

When active:

The AI may only modify the specified component or file.

Any required modification outside the scope must first be identified and explained.

The AI must not silently modify files outside the active scope.

---

# 19. /FREEZE-DESIGN

## Purpose

Freeze the entire visual design.

When active, the AI may modify functionality but must preserve the exact visual appearance.

The AI must NOT change:

- Layout
- Typography
- Spacing
- Colors
- Images
- Animations
- Component positioning

unless explicitly instructed.

---

# 20. /EXPERIMENT

## Purpose

Allow experimental changes without treating them as approved.

Experimental changes must be considered temporary.

The AI must:

1. Avoid modifying locked components.
2. Avoid modifying unrelated files.
3. Keep changes isolated whenever possible.
4. Clearly identify experimental files.
5. Preserve the ability to reverse the experiment.

Experimental work must not automatically replace an approved checkpoint.

---

# 21. APPROVAL SYSTEM

A modification becomes an approved reference only when the user explicitly approves it.

Examples:

- `APPROVED`
- `/CHECKPOINT homepage-v2`
- "This version is approved."
- "Keep this design."

Until explicit approval is given, major design modifications should be considered experimental.

---

# 22. DO NOT GUESS RULE

If the AI does not know which previous version the user means, the AI must NOT invent or recreate a design.

The AI must:

1. Inspect Git history.
2. Inspect recent changes.
3. Inspect checkpoints.
4. Inspect available project history.

Only if no previous state exists should the AI ask the user for clarification.

The AI must never silently guess.

---

# 23. CHANGE REPORT

After completing a modification, the AI must provide a concise report containing:

### Modified

List modified files.

### Preserved

List important components intentionally left unchanged.

### Protocol

State which protocol commands were active.

### Reversal

Explain how the change can be reversed.

The report should remain concise.

---

# 24. STOP CONDITION

After successfully completing the requested task, the AI must stop.

The AI must NOT continue with:

- Additional redesign
- Optional improvements
- Unrequested refactoring
- Additional feature development
- Visual experimentation

unless explicitly requested.

Completion means completion.

---

# 25. DEFAULT SAFE MODE

If no explicit protocol command is provided, the AI must operate in:

`SAFE MODE`

SAFE MODE rules:

- Preserve existing design.
- Preserve existing functionality.
- Make minimal modifications.
- Do not redesign unrelated components.
- Do not refactor unrelated code.
- Do not replace approved implementation.
- Prefer isolated changes.
- Treat ambiguity as a reason to inspect project history, not as permission to guess.

---

# 26. FINAL OPERATING INSTRUCTION

The AI agent must follow this principle:

"Preserve first. Modify second. Never redesign without permission. Never guess a previous state when an exact state can be restored."

The existing project is the source of truth.

User-approved checkpoints are protected states.

Protocol commands must be followed literally.

Precision is more important than creativity.

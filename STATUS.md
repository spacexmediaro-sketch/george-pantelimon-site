# George Pantelimon Site — Status Proiect

**Ultima actualizare:** 2026-08-18

---

## CE S-A FACUT

### Structura & Continut
- [x] Site single-page complet (HTML + CSS + JS inline) — ~5000 linii
- [x] Sectiuni: Hero, Social Proof, Beneficii, Despre Mine, Servicii, Proces, Portofoliu (galerie film strip), Pachete, Inainte/Dupa, Oferta speciala, Testimoniale, Cursuri, FAQ, Contact, Footer
- [x] Popup 20% reducere cu lead capture
- [x] Cookie banner
- [x] Lightbox galerie
- [x] Scroll indicator + progress bar
- [x] Preloader animat
- [x] Social sidebar (Instagram, WhatsApp, Facebook)
- [x] Mobile menu hamburger

### SEO / GEO / AEO
- [x] Meta description optimizat + OG tags complete
- [x] Title optimizat cu keyword principal + locatie
- [x] Keywords meta tag (fotograf ploiesti, nunta, botez, majorat etc.)
- [x] Geo meta tags (geo.region, geo.placename, geo.position, ICBM)
- [x] Canonical URL + hreflang
- [x] Alt text descriptiv pe TOATE imaginile
- [x] Schema markup: LocalBusiness, FAQPage, AggregateRating, Review (x3), Product (x3), BreadcrumbList
- [x] Heading structure corect (H1 unic, H2/H3 logice)
- [x] sitemap.xml creat
- [x] robots.txt creat
- [x] Google Maps embed in Contact
- [x] Internal linking (Beneficii -> Portofoliu/Contact, Galerie -> Cursuri)

### Performanta
- [x] Three.js eliminat (-150KB)
- [x] Preconnect hints (fonts, cdnjs, unsplash, georgepantelimon.ro)
- [x] Imagini WebP (Unsplash cu &fm=webp)
- [x] Lazy loading pe imagini below-fold
- [x] CSS mort eliminat (price configurator ~140 linii)
- [x] Performance tier fix (default medium, nu low)
- [x] Favicon + Apple touch icon

### Animatii & Efecte Vizuale
- [x] GSAP ScrollTrigger — card reveal cu blur + scale + stagger
- [x] GSAP — section header animations (tag, title, line)
- [x] GSAP — horizontal scroll galerie film strip cu counter
- [x] GSAP — parallax pe about image
- [x] GSAP — hero content parallax pe scroll
- [x] GSAP — scroll progress bar
- [x] GSAP — motto parallax
- [x] Depth Parallax 3D pe galerie — CSS perspective tilt (±20° rotatie, ±60px displacement, light tracking, shadow dinamic)
- [x] Cursor trail cu imagini portofoliu
- [x] Magnetic buttons
- [x] CSS Scroll-Driven Animations (@supports animation-timeline)
- [x] View Transitions API
- [x] Time-based theme (morning/evening CSS variables)
- [x] Typewriter effect pe hero
- [x] Before/After slider
- [x] Polaroid reveal pe galerie panels

### Email Marketing (Formspree)
- [x] Formular contact — pregatit cu fetch + Formspree (placeholder: CONTACT_ID)
- [x] Newsletter footer — pregatit cu fetch + Formspree (placeholder: NEWSLETTER_ID)
- [x] Popup 20% reducere — pregatit cu fetch + Formspree (placeholder: CONTACT_ID)
- [x] Loading state pe butoane (Se trimite... / disabled)
- [x] Error handling cu toast notifications

### Continut din Prompt
- [x] Punct 1: Meta description completat
- [x] Punct 2: Text contradictoriu unificat (13+ ani)
- [x] Punct 3: Alt text pe toate imaginile
- [x] Punct 4: Blog/Articole — nu exista duplicat
- [x] Punct 5: Link cursuri in meniu (cu badge "nou")
- [x] Punct 6: Sectiune dovada sociala (Vladuta Lupau, Sala Palatului, BT Arena, Kanal D, Click.ro)
- [x] Punct 7: CTA comanda-albume.ro stilizat
- [x] Punct 8: Sectiune Beneficii completa (same-day edit, experienta, galerie privata, retusare, editare, contract, echipament)
- [x] Punct 9: SEO/GEO/AEO complet (schema markup, keywords, sitemap, robots, maps)

---

## CE MAI E DE FACUT

### Urgent (inainte de launch)
- [ ] **Formspree: creaza cont si pune ID-urile reale**
  - Inlocuieste `CONTACT_ID` in index.html (apare de 2 ori: contact form + popup)
  - Inlocuieste `NEWSLETTER_ID` in index.html (newsletter form)
  - Redirecteaza emailurile spre contact@georgepantelimon.ro
- [ ] **Imagini reale** — inlocuieste pozele Unsplash cu fotografiile lui George
- [ ] **Hero video** — verifica ca hero-video.mp4 exista si se incarca (momentan fisierul e local)
- [ ] **Testare mobil** — verifica pe telefon real (nu doar responsive browser)

### Recomandari SEO
- [ ] Setup Google Search Console + submit sitemap.xml
- [ ] Setup Google Business Profile (sau verifica ca exista cu NAP corect)
- [ ] Adauga domeniu pe Google Merchant Center (daca vinde cursuri)
- [ ] Verifica indexare dupa 1-2 saptamani

### Imbunatatiri viitoare
- [ ] Imagini proprii optimizate + comprimate (TinyPNG/Squoosh)
- [ ] Adauga testimoniale reale cu poze clienti
- [ ] Pagina separata pentru fiecare serviciu (SEO long-tail)
- [ ] Blog cu articole (SEO continut)
- [ ] Google Analytics / GTM tracking
- [ ] Meta Pixel (Facebook Ads)
- [ ] WhatsApp Business API integration
- [ ] Email autoresponder pe Formspree/Brevo
- [ ] HTTPS certificat (la hosting)
- [ ] CDN pentru imagini proprii (Cloudflare)

---

## Fisiere

| Fisier | Descriere |
|--------|-----------|
| `index.html` | Site-ul complet (HTML + CSS + JS inline) |
| `sitemap.xml` | Sitemap pentru Google |
| `robots.txt` | Robots pentru crawlere |
| `hero-video.mp4` | Video hero (local) |
| `research/` | Research hi-tech features |
| `de facut/` | Prompt-ul original cu taskuri |
| `STATUS.md` | Acest fisier |

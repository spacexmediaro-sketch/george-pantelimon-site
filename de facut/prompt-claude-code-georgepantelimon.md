# Prompt pentru Claude Code — georgepantelimon.ro

Lucrăm pe site-ul georgepantelimon.ro (fotograf/videograf). Mai jos e o listă de modificări de conținut, împărțite pe priorități. Execută-le **în ordinea de mai jos**, câte un item odată, și cere-mi confirmare vizuală (screenshot sau descriere a rezultatului) înainte să treci la următorul. Nu face commit/push fără aprobarea mea explicită.

## Reguli generale
- Lucrează pe o branch separată (ex: `content-updates-2026`), nu direct pe main/production.
- Nu modifica structura de layout sau stilurile CSS existente decât dacă e menționat explicit mai jos.
- Păstrează tonul și stilul de scriere deja folosit pe site.
- După fiecare modificare, arată-mi diff-ul înainte de commit.
- Testează pe mobil și desktop — site-ul e pentru clienți care vin în special din social media (Instagram/WhatsApp), deci prioritizează mobile-first.

---

## 1. Meta description
Găsește tag-ul `<meta name="description">` (momentan gol sau doar "George Pantelimon.") și completează-l cu:

```
Fotograf și videograf profesionist în Ploiești — nunți, botezuri, ședințe foto și evenimente VIP. 13+ ani experiență.
```

Verifică dacă există meta description și per-pagină (nu doar global) și aplică variante relevante acolo unde lipsesc.

## 2. Text contradictoriu la "Despre mine"
În secțiunea "Despre mine" apar două vârste diferite (24 și 26 de ani) în același text. Găsește ambele mențiuni, stabilește care e cea corectă (întreabă-mă dacă nu e clar din context) și unifică — o singură vârstă, consistentă peste tot pe site.

## 3. Alt text la imagini
Parcurge toate imaginile din site (galerie, portofoliu, homepage) care nu au atribut `alt`. Adaugă descrieri scurte, descriptive, orientate spre SEO fotografie, ex: `alt="Ședință foto nuntă în aer liber, Ploiești"`. Nu inventa detalii false — dacă nu poți determina contextul unei imagini din nume de fișier sau locație în pagină, marchează-o într-o listă separată și întreabă-mă.

## 4. Unificare "Blog" și "Articole"
Găsește ambele secțiuni din meniu — par să facă același lucru. Verifică:
- Dacă au conținut diferit sau duplicat
- Care rută/URL e mai bine indexată (dacă există date SEO)

Unifică-le într-o singură secțiune (recomand să păstrezi denumirea mai simplă/naturală — decide sau întreabă-mă) și redirecționează (301) ruta eliminată către cea păstrată, ca să nu pierdem SEO.

## 5. Link către cursuri în meniul principal
Adaugă un link nou în meniul principal către secțiunea/pagina de cursuri (verifică dacă pagina există deja pe site sau trebuie creată — dacă nu există, anunță-mă înainte să inventezi conținut).

## 6. Secțiune dovadă socială pe homepage
Adaugă o secțiune nouă pe homepage care evidențiază colaborările: Vlăduța Lupău, Sala Palatului, BT Arena, apariții Kanal D / Click.ro. Format recomandat: logo-uri/mențiuni simple într-un rând (tip "as seen in" / "au avut încredere în mine"), fără să aglomerezi vizual. Dacă avem imagini/logo-uri disponibile, folosește-le; dacă nu, folosește text simplu stilizat.

## 7. CTA-uri către domenii externe
Găsește CTA-urile care duc către forms.app și comanda-albume.ro. Integrează-le vizual în tema site-ului (culori, fonturi, stil buton identic cu restul site-ului) în loc să pară linkuri externe brute. Păstrează funcționalitatea (link-urile rămân aceleași), doar stilizarea se schimbă.

## 8. Secțiune nouă: "Beneficii" pe homepage

Creează o secțiune nouă pe homepage, poziționată [de stabilit — recomand după hero, înainte de galerie].

**Badge-uri sus (rând orizontal, stil pill/tag):**
`Editare Avansată` · `Consultanță Inclusă` · `13+ Ani Experiență` · `Echipament Premium`

**Bară de contact (sub badge-uri sau în footer al secțiunii):**
`www.georgepantelimon.ro` · `+40 767 366 800` · `contact@georgepantelimon.ro`

**Titlu secțiune:** GEORGE PANTELIMON — 2026

**Conținut (ordine EXACTĂ — contează pentru conversie):**

1. **Same-day edit / Fotografii în aceeași zi**
   *"Primești primele cadre editate chiar în ziua evenimentului."*
   În ziua evenimentului, primești câteva cadre editate rapid, gata de postat pe social media.

2. **13+ Ani Experiență**
   Verifică să fie aceeași cifră peste tot pe site (vezi fix-ul de la punctul 2 de mai sus).

3. **Galerie online privată**
   Galerie dedicată — vezi pozele, le alegi, le distribui familiei.

4. **Retușare facială naturală**
   Netezesc fin tenul, reduc imperfecțiunile, fără să schimb trăsăturile naturale.
   Mesaj cheie de accentuat vizual: *"îmbunătățesc, nu transform"*.

5. **Editare profesională, cadru cu cadru**
   Fiecare fotografie e selectată și editată riguros, cu software modern.

6. **Contract și transparență**
   (De formulat un text scurt despre siguranța clientului — nu rămâne fără poze sau bani dați degeaba.)

7. **Echipament premium (Nikon Z8 etc.)**
   Ultimul din listă — menționează-l, dar nu-l face element vizual principal.

Format recomandat: card-uri sau listă cu iconițe, consistent cu restul design-ului site-ului. Dacă structura actuală a homepage-ului are deja o secțiune similară, integrează conținutul acolo în loc să creezi duplicat.

---

## 9. Optimizare SEO / GEO / AEO cu keywords

Obiectiv: site-ul să fie găsit atât în Google clasic (SEO), cât în căutări locale/hărți (GEO), cât și în răspunsuri generate de AI — ChatGPT, Google AI Overviews, Perplexity etc. (AEO — Answer Engine Optimization).

**Cercetare keywords (înainte de implementare):**
Identifică 10-15 keyword-uri relevante pentru zona Ploiești + servicii foto/video (ex: "fotograf nuntă Ploiești", "videograf botez Ploiești", "fotograf evenimente Prahova", "ședințe foto profesionale Ploiești", "fotograf majorat Ploiești" etc.). Prioritizează după intenție de cumpărare (nu doar volum de căutare).

**SEO on-page:**
- Titlu (`<title>`) și H1 optimizate cu keyword-ul principal + locație, fără keyword stuffing
- Structură corectă de headinguri (H1 unic pe pagină, H2/H3 logice pe secțiuni)
- Meta description per pagină (nu doar homepage — vezi punctul 1, extinde la toate paginile: portofoliu, cursuri, despre mine)
- URL-uri curate, descriptive (fără parametri inutili)
- Internal linking între secțiuni relevante (ex: din "Beneficii" către galerie, din galerie către cursuri)
- Viteză de încărcare imagini — verifică dacă sunt optimizate/comprimate și servite în format modern (WebP)
- Sitemap.xml și robots.txt — verifică că există și sunt corecte

**GEO (Local SEO — Google Business/Maps):**
- Verifică/adaugă schema markup `LocalBusiness` cu NAP consistent (Name, Address, Phone) — trebuie identic cu ce e pe Google Business Profile
- Adaugă schema markup pentru servicii oferite (`Service`, `Photographer` sau echivalent din schema.org)
- Menționează explicit zona de acoperire (Ploiești, Prahova, și eventual București dacă acoperă și acolo) în conținut, nu doar în footer
- Adaugă hartă/embed Google Maps dacă nu există deja

**AEO (optimizare pentru răspunsuri AI):**
- Structurează conținutul cu răspunsuri clare la întrebări frecvente (secțiune FAQ) — format întrebare-răspuns direct, ușor de extras de motoarele AI
- Adaugă schema markup `FAQPage` pentru secțiunea de FAQ
- Scrie propoziții clare, autonome, care răspund direct la o întrebare (ex: "Cât costă un fotograf de nuntă în Ploiești?" → răspuns concis, apoi detaliere)
- Adaugă schema markup `Review`/`AggregateRating` dacă există testimoniale, pentru credibilitate în răspunsurile AI

**Keywords de integrat natural (nu forțat) în conținutul existent:**
- Homepage, secțiunea Beneficii, Despre mine, meta description-uri, alt text-uri la imagini (vezi punctul 3)
- Nu suprascrie tonul natural al site-ului doar ca să bagi keyword-uri — dacă o propoziție sună artificial, reformuleaz-o

La final, dă-mi o listă cu toate schema markup-urile adăugate și keyword-urile integrate, ca să pot verifica ulterior în Google Search Console.

---

## La final
După ce ai parcurs toate punctele și le-am aprobat individual, fă un rezumat cu toate modificările făcute și pregătește un commit unic, cu mesaj clar, pentru merge în main.

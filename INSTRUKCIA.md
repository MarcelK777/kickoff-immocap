# INSTRUKCIA PRE CLAUDE CODE

## Čo chcem vytvoriť

Vytvor **jednoduchú, profesionálnu web prezentáciu** (single-page HTML) pre kickoff meeting k projektu adaptácie AI vo firme IMMOCAP (real estate developer). Stránka bude slúžiť ako agenda a sprievodný materiál k stretnutiu.

**Dátum stretnutia:** 30. marca 2026
**Účastníci:** Tomáš Lukeš (koordinátor AI programu v IMMOCAP), kolegyňa z vedenia zodpovedná za business controlling, Marcel Kasanický (externý AI konzultant, Books & Mirror)

---

## Technické požiadavky

- **Jeden HTML súbor** (`index.html`) — všetko (CSS, JS) inline, žiadne externé závislosti
- **Scroll-based** — jedna dlhá stránka, užívateľ scrolluje cez sekcie
- **Responzívny dizajn** — musí dobre vyzerať na notebooku aj na mobile
- **GitHub Pages ready** — stačí pushnúť do repozitára a zapnúť Pages
- **Jazyk obsahu:** slovenčina
- **Smooth scroll** medzi sekciami cez navigačné menu
- **Sticky navigácia** hore — kliknutím na položku scrollne na príslušnú sekciu
- **Subtle animácie** — sekcie sa jemne fade-in pri scrollovaní (Intersection Observer)

---

## Dizajn

### Štýl: Svetlý, čistý, minimalistický

- **Pozadie:** biela (#FFFFFF) s jemnými svetlosivými sekciami (#F8F9FA) pre vizuálne oddelenie
- **Text:** tmavosivá (#1A1A2E) pre hlavný text, stredná sivá (#6C757D) pre sekundárny
- **Accent farba:** tmavomodrá (#0D1B4C) — IMMOCAP brand farba — pre nadpisy, linky, CTA elementy
- **Sekundárny accent:** jemná zlatá/amber (#D4A843) pre zvýraznenia a ikonky
- **Font:** systémový sans-serif stack (`-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`)
- **Maximálna šírka obsahu:** 900px, centrovaný
- **Veľkorysý whitespace** — padding medzi sekciami min. 80px
- **Žiadne obrázky** — vizuálny záujem cez typografiu, farby, ikonky (emoji alebo Unicode symboly), a layout
- **Karty/boxy** pre štruktúrované informácie — jemný box-shadow, rounded corners

### Hero sekcia
- Veľký nadpis, podnadpis s dátumom a kontextom
- Jemný gradient alebo geometrický pattern v pozadí (CSS only)

---

## Štruktúra a obsah sekcií

Stránka má tieto sekcie (v tomto poradí):

---

### 1. HERO — Úvodná sekcia

**Nadpis:** IMMOCAP & AI — Kickoff
**Podnadpis:** Štart spolupráce na adaptácii umelej inteligencie
**Dátum:** 30. marca 2026
**Kontext:** Operatívne stretnutie k spusteniu Fázy 0

---

### 2. PREČO SME TU

Krátka sekcia, ktorá zasadzuje stretnutie do kontextu:

- Vedenie IMMOCAP schválilo spustenie AI programu (board meeting 25.3.2026)
- Dohodli sme sa na pragmatickom prístupe Fázy 0 (3 mesiace)
- Toto stretnutie je operatívny kickoff — nastavujeme, ako budeme pracovať

**Citát v callout boxe:**
„AI nevnímame ako trend, ale ako nástroj na systematické zlepšovanie fungovania firmy."

---

### 3. ČO UŽ MÁME ZA SEBOU

Časová os (vertikálny timeline, CSS-only):

| Kedy | Čo | Status |
|------|-----|--------|
| Október 2025 | Workshop „Promptovanie ako nová superpower" — 12 účastníkov | Realizované ✓ |
| Január 2026 | Workshop „GPT Asistenti ako kolegovia na mieru" | Realizované ✓ |
| Február 2026 | AI Strategy Framework — návrh | Pripravené ✓ |
| Marec 2026 | Prezentácia AI stratégie vedeniu IMMOCAP | Schválené ✓ |
| **Dnes** | **Kickoff Fázy 0 — operatívny štart** | **Práve teraz** |

---

### 4. FÁZA 0 — ČO IDEME ROBIŤ

Hlavná obsahová sekcia. Zobraz ako karty/bloky:

**Trvanie:** 3 mesiace (apríl — jún 2026)

**5 pracovných prúdov:**

1. **Mapovanie procesov a identifikácia use cases**
   - Naprieč oddeleniami: development, commercial, controlling, legal, HR, marketing
   - Fokus na quick wins a high-impact oblasti
   - Prvý use case: komerčné oddelenie — správa

2. **Praktické školenia**
   - Prompting + AI nástroje pre tímy
   - Školenia zároveň slúžia na zber a validáciu use cases
   - Formát: workshop 2-3 hodiny per oddelenie

3. **Pilotné testovanie**
   - 3-5 vybraných use cases v malom rozsahu
   - Overenie reálneho prínosu predtým, než škálujeme

4. **Analýza dátovej pripravenosti**
   - Aké dáta máme, v akom stave, čo treba
   - Spätná väzba k IT platformám (CRM, účtovníctvo, SharePoint...)

5. **Evaluácia nástrojov**
   - Tool mapping na konkrétne use cases
   - Buy vs. build vs. hybrid analýza

**Výstup Fázy 0 (v callout boxe):**
Do cca 1 mesiaca — podklad pre vedenie s návrhom prioritných use cases, prínosov a rámcovej roadmapy. Na konci Fázy 0 — kompletná AI stratégia + roadmap + odporúčanie build vs. buy.

---

### 5. AKO BUDEME SPOLUPRACOVAŤ

Sekcia o modeli spolupráce. Zobraz ako 3 stĺpce (alebo karty na mobile):

**Marcel Kasanický — Externý konzultant (Books & Mirror)**
- Strategický návrh a metodológia
- Technology scouting
- Koordinácia implementácie
- Mentoring tímu
- 16 hodín / mesiac

**Tomáš Lukeš — Koordinátor AI programu (IMMOCAP)**
- Hlavný kontaktný bod
- Koordinácia medzi vedením, oddeleniami a konzultantom
- Posun a výsledky AI adaptácie

**Interný tím IMMOCAP**
- Postupné zapojenie zástupcov oddelení
- Identifikácia AI ambasádorov
- Exekúcia — budujeme internú kompetenciu, nie závislosť

**Dôležitý princíp (v callout boxe):**
„Konzultant prináša expertízu a externý pohľad. Exekúcia a rozhodovanie zostáva na IMMOCAP. Cieľom nie je vytvoriť závislosť, ale vybudovať internú schopnosť."

---

### 6. PRINCÍPY

Krátka sekcia, 5-6 princípov ako kompaktný zoznam s ikonkami:

- **AI je nástroj, nie cieľ** — zavádzame to, čo má preukázateľný prínos
- **Rast cez efektivitu, nie headcount** — zvládnuť rastúce portfólio s existujúcim tímom
- **Postupujeme po fázach** — každá fáza má výstup a rozhodovací bod
- **Meráme prínos** — rozhodujeme na základe dát, nie pocitov
- **Bezpečnosť dát** — interné dokumenty a citlivé informácie sú priorita
- **Budujeme internú kompetenciu** — nie závislosť na externom dodávateľovi

---

### 7. NAJBLIŽŠIE KROKY

Konkrétne akčné body — zobraz ako checklist:

- [ ] Dohodnúť pravidelný rytmus stretnutí (napr. 1× za 2 týždne)
- [ ] Identifikovať kontaktné osoby za jednotlivé oddelenia pre mapovanie use cases
- [ ] Naplánovať prvé školenie (komerčné oddelenie — správa)
- [ ] Pripraviť prehľad aktuálne používaných IT/SW platforiem
- [ ] Marcel: pripraviť šablónu na mapovanie use cases
- [ ] Marcel: prvý návrh prioritných use cases do 2 týždňov
- [ ] Do 1 mesiaca: podklad pre vedenie s návrhom use cases a roadmapy

---

### 8. DISKUSIA

Minimalistická záverečná sekcia:

**Nadpis:** Otázky a diskusia
**Podtext:** Čo je pre vás najdôležitejšie v najbližších 90 dňoch?

Kontakt:
- Marcel Kasanický
- marcel@booksmirror.eu
- +421 905 911 992
- booksmirror.eu

---

## Špeciálne pokyny pre Code

1. **Celý kód v jednom `index.html`** — CSS v `<style>`, JS v `<script>`, žiadne externé súbory
2. **Navigácia sticky** — pri scrolle zostáva hore, aktívna sekcia sa zvýrazní
3. **Scroll progress indicator** — tenká lišta hore ukazujúca, koľko stránky je prečítanej
4. **Print-friendly** — `@media print` štýly, aby sa dala stránka vytlačiť čisto
5. **Accessibility** — sémantické HTML (`<section>`, `<nav>`, `<main>`), `aria-labels`
6. **Veľkosť:** cieľ pod 30KB celý súbor
7. **Žiadne externé CDN, knižnice ani fonty** — všetko self-contained
8. **Meta tagy** pre Open Graph (title, description) aby link v chate/emaili mal pekný preview

---

## Čo NEROBIŤ

- Nepridávaj obrázky ani logá — nie sú k dispozícii
- Nepridávaj ceny ani finančné detaily retainera — toto nie je obchodná ponuka
- Nepridávaj benchmarky a trhové dáta (JLL, Gartner) — to bolo v prezentácii pre board, kickoff je operatívny
- Nepoužívaj žiadne JavaScript frameworky
- Nepoužívaj emoji v nadpisoch — iba v zoznamoch princípov ako vizuálne ikonky

---

## Záverečná kontrola

Po vytvorení over:
- Funguje smooth scroll medzi sekciami?
- Navigácia sa správne zvýrazňuje pri scrolle?
- Stránka vyzerá dobre na šírke 375px (mobil) aj 1440px (desktop)?
- Sú všetky slovenské znaky správne zobrazené (č, š, ž, ľ, ď, ť, ň, ô, á, é, í, ó, ú, ý, ŕ)?
- Je veľkosť pod 30KB?

# Neon Agentur — Brand Identity Document
**Version 1.0 · März 2026**

---

## 1. MARKENCLAIMS

### Bestehender Claim
> "Deine Idee. Unser Code. Dein Erfolg."
Stark. Dreifache Ownership-Struktur. Gut für Hero-Section.

---

### 5 Alternativen

| # | Claim | Kontext |
|---|-------|---------|
| 1 | **"Websites, die verkaufen. Nicht nur aussehen."** | Hero-Section, wenn Zielgruppe Conversion-fokussiert ist. Adressiert den häufigsten Schmerz: schöne aber wirkungslose Seiten. |
| 2 | **"15 Jahre alt. Null alte Denkmuster."** | Über-uns-Seite, Social Media, PR. Mutigster Claim — macht das Alter zum Argument statt zur Entschuldigung. |
| 3 | **"KI-Power. Mittelstand-Preis."** | Preisseite, Anzeigen, LinkedIn. Direkt auf die Zielgruppe zugeschnitten. Kurz, knapp, unvergesslich. |
| 4 | **"Kein Overhead. Nur Ergebnisse."** | Vergleichs-Sektion, wenn Neon vs. große Agentur positioniert wird. Anti-Establishment-Energie. |
| 5 | **"Dein digitales Fundament. In 4 Wochen."** | Service-Seiten, Google Ads, lokale Zielgruppen. Konkrete Zeitangabe erzeugt Vertrauen und Dringlichkeit. |

**Empfehlung:** Claim #2 für Über-uns + Social. Bestehender Claim für Hero. Claim #3 für Ads.

---

## 2. FARBPALETTE

### Primärpalette

| Rolle | Name | Hex | Verwendung |
|-------|------|-----|------------|
| Primär | Neon-Gelb | `#FFE209` | CTAs, aktive Zustände, Key-Highlights |
| Hintergrund A | Near Black | `#09090B` | Haupt-Hintergrund, Dark-Surfaces |
| Hintergrund B | Midnight Navy | `#0F172A` | Cards, Sections, sekundäre Flächen |
| Akzent | Electric Blue | `#3B82F6` | Links, Icons, Badges, sekundäre CTAs |
| Text Hell | White | `#FFFFFF` | Primärtext auf dunklem Hintergrund |
| Text Dunkel | Black | `#09090B` | Text auf Gelb (Buttons, Badges) |

### Erweiterungsfarben

| Rolle | Name | Hex | Verwendung |
|-------|------|-----|------------|
| Gelb gedimmt | Soft Yellow | `#FFF176` | Hover-Zustände auf Gelb, dezente Highlights |
| Blau dunkel | Deep Blue | `#1D4ED8` | Active-Zustände auf Blau |
| Grau | Muted | `#71717A` | Placeholder-Text, Disabled-States |
| Trennlinie | Border | `#27272A` | Divider, Card-Borders auf Dark BG |

---

### Kombinationsregeln

**Erlaubte Kombinationen (hoher Kontrast):**

```
Neon-Gelb (#FFE209)   auf  Near Black (#09090B)   → Primärer CTA, Hero-Text
Near Black (#09090B)  auf  Neon-Gelb (#FFE209)    → Button-Label, Badge-Text
White (#FFFFFF)       auf  Near Black (#09090B)   → Fließtext, Headlines
White (#FFFFFF)       auf  Midnight Navy (#0F172A) → Card-Inhalte
Electric Blue (#3B82F6) auf Near Black (#09090B)  → Links, Icons
```

**Verbotene Kombinationen:**

```
Neon-Gelb auf White     → VERBOTEN — Kontrast zu gering (WCAG fail)
Blue auf Midnight Navy  → VERBOTEN — Farben zu ähnlich
Muted auf Near Black    → VERBOTEN — Text nicht lesbar (nur für Disabled)
```

**Kontrast-Minima (WCAG AA):**
- Body-Text: min. 4.5:1
- Headlines (>24px): min. 3:1
- Gelb auf Schwarz: ~14:1 (sehr gut)
- Weiß auf Near Black: ~19:1 (exzellent)

---

### Anwendungsszenarien

**Hero-Section:** Near Black Hintergrund · White Headline · Neon-Gelb CTA-Button mit Black Text

**Cards/Services:** Midnight Navy Hintergrund · White Text · Electric Blue Icon · Yellow Tag

**Pricing-Section:** Near Black · White Body · Yellow Highlight für empfohlenen Plan

**Dark-Mode-only:** Neon Agentur ist ausschließlich dark. Kein helles Theme.

---

## 3. TYPOGRAFIE-SYSTEM

### Fontstack

```
Display / Brand:   Sora (weights: 700, 800)
Headlines / UI:    Space Grotesk (weights: 600, 700)
Body / Interface:  Inter (weights: 400, 500, 600)
```

Alle drei Fonts sind Google Fonts und kostenlos. Space Grotesk als primärer Font reicht wenn gewünscht.

---

### Ebenen-System

| Ebene | Font | Weight | Desktop | Mobile | Line-Height | Einsatz |
|-------|------|--------|---------|--------|-------------|---------|
| Display | Sora | 800 | 80px | 44px | 1.0 | Einzige Hero-Zeile, Kampagnen-Headline |
| H1 | Space Grotesk | 700 | 56px | 36px | 1.1 | Seiten-Headline, Section-Opener |
| H2 | Space Grotesk | 700 | 40px | 28px | 1.2 | Sub-Sections, Service-Titles |
| H3 | Space Grotesk | 600 | 28px | 22px | 1.3 | Card-Headlines, Feature-Titles |
| Body | Inter | 400 | 18px | 16px | 1.6 | Fließtext, Beschreibungen |
| Body Bold | Inter | 600 | 18px | 16px | 1.6 | Hervorgehobene Textpassagen |
| Label | Inter | 600 | 14px | 13px | 1.4 | Tags, Badges, Captions, Button-Text |
| Micro | Inter | 400 | 12px | 12px | 1.5 | Footer, Disclaimer, Meta-Infos |

---

### Anwendungsregeln Typografie

**Headlines sind IMMER:**
- Uppercase oder Mixed Case — nie Sentence case für H1/H2
- Tracking: -0.02em bis -0.04em (leichtes negative letter-spacing für Größen >40px)
- Farbe: White oder Neon-Gelb — nie Grau für Primär-Headlines

**Body-Text:**
- Inter Regular, Weiß mit 80% Opacity auf Dark = `rgba(255,255,255,0.8)` für bessere Lesbarkeit
- Max-Width: 65ch pro Textblock

**Highlight-Pattern:**
Einzelne Wörter in Headlines in Neon-Gelb hervorheben:
```
Deine Website.
In <span style="color:#FFE209">4 Wochen</span>.
Online.
```

---

## 4. WEBSITE-HEADLINES

### Hero-Section
```
Deine Website.
In 4 Wochen.
Online.
```
*Subline: KI-gebaut. SEO-optimiert. Mobil. Direkt von einer Agentur,
die schneller denkt als die Konkurrenz.*

---

### Services-Section
```
KI, die für dich arbeitet.
Auch nachts um 3.
```
*Subline: Chatbot, Telefon-KI, Automatisierung — dein Business läuft,
auch wenn du schläfst.*

---

### Trust/Social Proof-Section
```
Ergebnisse statt Versprechen.
```
*Subline: Das NVT-Project war erst der Anfang.
Sieh selbst, was wir gebaut haben.*

---

### Pricing/CTA-Section
```
Kein Budget für eine große Agentur?
Genau richtig.
```
*Subline: Neon Agentur liefert dasselbe Ergebnis — ohne den Overhead,
ohne die Wartezeit, ohne den überteuerten Stundensatz.*

---

### Über-uns-Section
```
15 Jahre alt.
Keine alten Muster.
Nur Ergebnisse.
```
*Subline: Jasmin Tepe hat Neon Agentur gegründet, weil sie's anders machen wollte.
Digital aufgewachsen. Keine Angst vor Technik. Keine Ausreden.*

---

## 5. TONRICHTLINIEN

### Die Stimme von Neon Agentur
Deutsch. Direkt. Selbstbewusst. Kurz. Mutig. Nie arrogant.
Wie ein guter Freund, der zufällig Experte ist — redet Klartext,
erklärt nicht zu viel, liefert immer.

---

### 5 DOs

**1. Kurze Sätze. Immer.**
Maximal 12 Wörter pro Satz. Punkt. Nächster Satz. Das erzeugt Tempo.
```
RICHTIG: "Deine Website ist fertig. In 4 Wochen. Garantiert."
FALSCH:  "Innerhalb eines Zeitraums von etwa 4 Wochen werden wir Ihre
          Website vollständig fertiggestellt haben."
```

**2. Zahlen statt Worthülsen.**
Konkret sein. Zeitangaben, Prozentsätze, Fakten — das schafft Vertrauen.
```
RICHTIG: "4 Wochen. 6 Leistungen. 1 Ziel: dein Wachstum."
FALSCH:  "Wir arbeiten schnell und effizient für Sie."
```

**3. Das Alter ist ein Argument — nicht ein Problem.**
Nie entschuldigen. Nie relativieren. Direkt damit arbeiten.
```
RICHTIG: "15 Jahre alt. Kein altes Denken. Das ist unser Vorteil."
FALSCH:  "Obwohl wir jung sind, haben wir bereits erste Erfahrungen gesammelt."
```

**4. "Du" — immer.**
Neon Agentur siezt niemanden. Weder online noch offline.
```
RICHTIG: "Wo willst du mit deiner Website hin?"
FALSCH:  "Wohin möchten Sie mit Ihrer Website?"
```

**5. Aktiv schreiben.**
Das Subjekt handelt. Immer. Kein Passiv.
```
RICHTIG: "Wir bauen deine Website. Du wächst."
FALSCH:  "Eine Website wird für dich erstellt werden."
```

---

### 5 DON'Ts

**1. Kein Corporate-Deutsch.**
Wörter wie "Lösungen", "professionell", "maßgeschneidert", "ganzheitlich" — gestrichen.
```
FALSCH: "Wir bieten professionelle, maßgeschneiderte digitale Lösungen."
RICHTIG: "Wir bauen Websites, die konvertieren."
```

**2. Kein "trotz" in Verbindung mit dem Alter.**
"Trotz unseres jungen Alters..." ist die schlimmste Formulierung für Neon Agentur.
Sie macht das Alter sofort zum Problem. Das Alter IST der Vorteil.
```
FALSCH: "Trotz unserer Jugend liefern wir tolle Ergebnisse."
RICHTIG: "Weil wir jung sind, denken wir anders."
```

**3. Keine leeren Versprechen ohne Substanz.**
Jede Aussage muss belegbar oder konkret sein.
```
FALSCH: "Wir sind die beste Agentur für dich."
RICHTIG: "Referenz: NVT-Project. Fertig in 4 Wochen. Online seit [Datum]."
```

**4. Kein Übertreiben.**
Neon Agentur ist selbstbewusst — nicht größenwahnsinnig.
```
FALSCH: "Wir revolutionieren die Agenturwelt und disrumpieren alles."
RICHTIG: "Schneller. Günstiger. Ohne Kompromisse bei der Qualität."
```

**5. Keine Fragezeichen in Headlines.**
Fragen schwächen. Aussagen wirken.
```
FALSCH: "Willst du auch eine bessere Website?"
RICHTIG: "Deine Website performt nicht. Das ändern wir."
```

---

## 6. INSTAGRAM BIO

### Variante A (Fokus: Leistung)
```
KI-Websites. Chatbots. Automatisierung.
Jung, digital, schneller als die Konkurrenz.
Dein Projekt → Link in Bio
```

### Variante B (Fokus: Gründerin)
```
KI-Webagentur aus Deutschland.
Gegründet mit 15. Kein altes Denken.
Kostenlose Erstberatung → Link in Bio
```

### Variante C (Fokus: Ergebnis)
```
Deine Website. In 4 Wochen. Online.
KI-Power für kleine Budgets.
Jetzt starten → Link in Bio
```

**Empfehlung:** Variante C für maximale Conversion.
Variante B für Awareness und PR-Effekt (Gründer-Story).

---

## ZUSAMMENFASSUNG: BRAND CORE

| Element | Definition |
|---------|------------|
| **Mission** | Kleinen Unternehmen denselben digitalen Standard ermöglichen wie Großkonzernen — zu einem fairen Preis. |
| **Positioning** | Die günstigste Agentur, die nicht billig ist. |
| **Differenzierung** | Jung, direkt, KI-nativ, kein Overhead. |
| **Ton** | Deutsch · Direkt · Mutig · Kurz · Ehrlich |
| **Visual Feeling** | Neon-Energie auf Schwarz · Modern · Laut · Digital-native |
| **Anti-Position** | Keine großen Agenturen mit PowerPoint-Decks und Wochenlangen Calls. |

---

*Erstellt mit Claude Code für Neon Agentur · März 2026*

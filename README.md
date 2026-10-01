# Lovedoll Sammlung

Persönliche Lovedoll Sammlung von **Christian Grigoriadis (Zagathou)** – ausgewählte Modelle aus TPE mit kurzer Beschreibung, Maßen und Link zur Herstellerseite. Rein beschreibend, ohne explizite Inhalte und ohne kommerzielle Absicht.

🌐 **Live:** https://zagathou.github.io/lovedoll/

## Modelle

- Piper Doll 150 cm Ariel (S-TPE) – Bild folgt (Platzhalter)

## Neues Modell hinzufügen

1. Optional: ein **eigenes** Bild (selbst fotografiert, Hochformat, ideal 9:16, ohne explizite Darstellung) ins Repository legen, z. B. `modellname.jpg`. Keine Shop- oder Herstellerbilder verwenden (Urheberrecht). Ohne Bild bleibt der Platzhalter „Bild folgt“ stehen.
2. In `index.html` den kompletten Block `<article class="card model" …> … </article>` des letzten Modells kopieren (er ist mit dem Kommentar `<!-- MODELL: … -->` markiert) und direkt darunter einfügen.
3. Im kopierten Block ersetzen:
   - `id="ariel"` und alle IDs mit `ariel-` (z. B. `ariel-name`, `ariel-story`) durch einen neuen, eindeutigen Namen
   - falls ein eigenes Bild vorhanden ist: den Platzhalter `<figure class="ph ph-empty" …><span>Bild folgt</span></figure>` durch `<figure class="ph"><img src="modellname.jpg" alt="…" width="…" height="…"></figure>` ersetzen
   - den Namen in der `<h2>`, eine kurze, neutrale Beschreibung in eigenen Worten unter „Story“, die Zeilen der Tabelle „Maße des Produkts“ (`<tr><th>Eigenschaft</th><td>Wert</td></tr>`) und den Link zur Herstellerseite
4. Im JSON-LD-Block (`<script type="application/ld+json">`) unter `itemListElement` einen weiteren Eintrag ergänzen und `numberOfItems` erhöhen.
5. Den Text des neuen Modells auch in `llms.txt` ergänzen (gleiches Format: NAME, STORY, Maße des Produkts, PRODUKT LINK).

**Richtlinien:** Texte neutral und sachlich halten (keine sexuell anzüglichen Beschreibungen, keine Körpermasse ausser allgemeinen Angaben wie Grösse und Gewicht), keine Preise oder Werbesprache, keine kopierten Shop-Texte oder -Bilder.

## Für KI und Maschinen lesbar

- Semantisches HTML (`main`, `article`, `section`, `h1`–`h3`, Tabellen), alle Inhalte als Text im DOM
- Strukturierte Daten als JSON-LD (`CollectionPage` mit `ItemList`)
- [`LLMS.TXT`](https://zagathou.github.io/lovedoll/llms.txt): kompletter Seiteninhalt als reiner Text
- `robots.txt` erlaubt alle Crawler (inkl. KI-Crawler), `sitemap.xml` vorhanden
- `<meta name="rating" content="adult">` kennzeichnet die Seite als Inhalt für Erwachsene

## Technik

Eine einzelne, statische `index.html` – nur HTML und CSS, **kein JavaScript** (nur strukturierte Daten als JSON-LD). Schriften: Comfortaa (Überschriften, 22px) und Nunito (Text, 18px) über Google Fonts. Farben und Rahmen wie auf [FREYNA.ORG](https://freyna.org/). Gehostet mit GitHub Pages.

## Kontakt

- Name: Christian Grigoriadis (Künstlername: Zagathou)
- E-Mail: [XELOTATH@OUTLOOK.DE](mailto:xelotath@outlook.de)
- Session-ID: `055065749fb6c6c2f07cb2ed15021b88eed3fc480e87215cca925ede91454e7173`
- About: [ZAGATHOU.GITHUB.IO/ZAGATHOU](https://zagathou.github.io/zagathou/)

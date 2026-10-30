# CLAUDE.md – Projekt „Annaberg 2027“

Diese Datei ist das Projektgedächtnis für Claude Code. Sie wird bei jedem Start gelesen.
Stand: 30.10.2026 (App-Version 1.4). Bitte bei wichtigen Entscheidungen aktuell halten (Abschnitt „Entscheidungslog“).

## Arbeitsweise mit Uwe (verbindlich)
- Sprache: Deutsch.
- Bei Konzept- oder größeren Analyse-/Bauaufgaben: zuerst gezielt nachfragen – **eine Frage nach der anderen**, auf Antwort warten –, dann eine kurze Zusammenfassung/Spezifikation zur Freigabe vorlegen, erst nach Freigabe umsetzen.
- Kleine, klare Änderungen (Text, Daten, Bugfix) direkt erledigen.
- Vor Push/Veröffentlichen kurz bestätigen lassen, solange nichts anderes vereinbart ist.
- Ergebnisse knapp berichten: was wurde gemacht, wo liegt es, was ist der nächste Schritt.

## Worum geht es
Wanderurlaub in **Annaberg im Lammertal** (Annaberg-Lungötz, Salzburger Land, Österreich).
- Zeitraum: **Sa 11.09. – Sa 18.09.2027** (7 Nächte, Samstag = üblicher Wechseltag)
- Gruppe: 4 Personen (Uwe + 3 Freunde: 2 Männer, 2 Frauen, keine Paare) + **Golden Retriever** (fit, kommt bei Klettersteigen nicht mit, kann ein paar Stunden allein bleiben)
- Anreise: mindestens 2 Autos
- Die Freunde sind keine Claude-Nutzer, sollen aber **aktiv mitplanen** (kommentieren, abstimmen, Ideen eintragen). Verteilung über die bestehende **WhatsApp-Gruppe**.

## Anforderungen Unterkunft
**Muss**
- Ferienhaus/Ferienwohnung, Hund erlaubt und darf einige Stunden allein bleiben
- Mind. 2 Schlafzimmer (Männer/Frauen getrennt), getrennte Betten bevorzugt, Doppelbett notfalls ok
- Mind. 1 Bad + separates WC
- Voll ausgestattete Küche, Esstisch für 4
- 2 Parkplätze
- Budget ca. **1.000–2.000 € für die Woche gesamt** (inkl. Endreinigung, Hundegebühr)

**Pluspunkte** (keine Ausschlusskriterien): 3–4 Schlafzimmer, mehr Bäder, Terrasse/Balkon mit Bergblick, eingezäunter Garten, Sauna, Waschmaschine/Trockenraum, WLAN, Gästekarte, Supermarkt in der Nähe.

## Programm
- Wanderungen mittel bis sportlich (4–6+ Std., 500–900+ Hm), mit Hund, Einkehr mittags oder zum Abschluss
- Klettersteige A–C, **ohne Hund**, Ausrüstung wird geliehen, optional geführter Einsteigertag
- Verpflegung: eher selbst kochen oder halb/halb; Restaurantauswahl für einige Abende
- Schlechtwetter-Alternativen
- Hinweise: Hüttenöffnungszeiten Mitte September prüfen; Hund: Maulkorb-/Leinenpflicht in Bergbahnen/ÖPNV, Vorsicht bei Mutterkühen
- **Vorschläge stehen seit 30.10.2026 im Tab „Programm“** (JSON `programm.abschnitte`: wandern, klettersteig, huetten, essen, regen; jeder Eintrag mit Eckdaten, Hund ✓/?/✗, Saison, Quellen, Kartenpin). Umfrage-Button pro Abschnitt.
- Klettersteig-Plan (Gruppe = Anfänger): Kurs „Gipfelstürmer“ in Ramsau (2026: Mo 16–18:30 Uhr, 63 €, Leihausrüstung, ab 4 Pers.) → passt auf Mo 13.09.2027; danach Kali/Kala (Ramsau), Max & Moritz (Gosau), Abschluss Laserer alpin (B–B/C, einzelne C). Donnerkogel (C/D) zu schwer.
- Achtung: Donnerkogelbahn Annaberg fuhr 2026 nur bis 13.09. (Mo/Mi/Do/So) + 20./27.09.; Gosaukammbahn täglich bis 1.11. Hofpürglhütte ab 28.09. zu.
- Offen beim Programm: Hunderegeln vieler Hütten/Restaurants, Termine 2027 (Kurs, Bahnen, Hütten) vor der Reise prüfen.

## Unterkunfts-Vorauswahl (Recherche 30.10.2026, „ab“-Preise der Portale)
1. **Bauernhaus über Promberg** – 120 m², 4 SZ (davon 1 Zweibettzimmer), 2 Bäder, eingezäunter Garten, Baumhaussauna, Kachelofen, Alleinlage, Hunde willkommen, ab 107 €/Nacht, 9,8/10 (12). Gefunden über die Hunde-Übersicht https://www.ferienwohnungen.de/urlaub-mit-hund/europa/oesterreich/annaberg-lungoetz/ (Direktlink fehlt noch). Offen: 2 Parkplätze? Hund allein?
2. **Chalet #75, Alpendorf Dachstein West** – 90 m², 3 SZ (2× Doppel, 1× zwei Einzelbetten), 2 Bäder, Hallenbad/Sauna der Anlage, Minimarkt, Hunde erlaubt, ab ca. 114 €/Nacht, kostenlos stornierbar bis 30 Tage. https://www.traum-ferienwohnungen.de/757831/ – Anlage: Steuer 62, GPS 47.51472, 13.45087.
3. **Großes Chalet mit eigener Sauna, Alpendorf** – 138 m², 4 SZ (Doppelbetten), 2 Bäder + sep. WC, ab 165 €/Nacht, 9,6/10 (11). Über dieselbe Hunde-Übersicht.
4. **Haus Schipplegg, FW 1** – 65 m², 2 Doppelzimmer, 1 Bad, Alleinlage 950 m, Haustiere nach Absprache, Preis auf Anfrage. https://www.ferienhausmiete.de/161143.htm
- **Ausgeschieden (keine Haustiere):** Haus Dolomitenblick (174583), Chalet Alpenstern (59462), Chalet Rosa Maria (413768), Chalet Almhaus 30 (20499) – alle ferienhausmiete.de.
- Ortstaxe: gerechnet mit **4,75 €/Person/Nacht** (laut einem Annaberger Vermieter, Stand 2026). Geprüft 30.10.2026: offizieller Satz nicht lesbar (Gemeinde-Verordnung „besondere Nächtigungsabgabe ab 01.07.2026“ nur als signiertes PDF); ein Inserat nennt 3,55 € ab 14 J. (https://www.bergfex.at/sommer/annaberg-lungoetz-lammertal/ferienhaus-haus-annaberg36/); Mobilitätsabgabe Salzburg 0,50 € → 1,10 € ab Mai 2027, unter 15 J. frei (https://sbg.lko.at/mobilitätsabgabe-ab-1-mai-für-touristische-unterkünfte+2400+4152062). → Beim Vermieter erfragen.
- Kartenkoordinaten geprüft per OpenStreetMap/Nominatim (30.10.2026): Ortsmitte 47.5167, 13.4333; Promberg 47.5039, 13.4278; Talstation Donnerkogelbahn 47.5184, 13.4509; Alpendorf Dachstein West 47.5149, 13.4499.
- Bei allen offen: echter Wochenpreis Sept. 2027 inkl. Nebenkosten, Hund allein erlaubt?

## Technik
### Stufe 1 (jetzt): statische Anzeigeseite
- `index.html` – eine einzige, eigenständige Datei, mobil optimiert (Homescreen-App), hell/dunkel.
- Inhalte stehen im JSON-Block `<script type="application/json" id="trip-data">` – **Inhalte dort ändern, nicht im Code**.
- Tabs (untere Leiste, bleibt): Übersicht (Start: Countdown, Einleitung, „Was gerade ansteht“, Kacheln, Rahmen, Versionshinweis; JSON `uebersicht` – **„anstehend“ bei jedem Stand aktuell halten**), Unterkunft (Karten mit Muss-Check ✓/?/✗, Pluspunkte, Nachteile, Vermieterfragen, darunter unsere Kriterien), Karte (Leaflet 1.9.4 von cdnjs mit SRI-Prüfsummen + OpenStreetMap, Unterkünfte als nummerierte Pins, ungenaue Lagen zusätzlich mit Kreis, Orientierungspunkte aus `orte`), Programm, Demnächst. Der frühere Tab „Rahmen“ ist in der Übersicht aufgegangen (alter Link #rahmen führt zur Übersicht). Aktiver Tab steht in der Adresse (`#karte` usw.), Zurück-Taste wechselt Tabs.
- Homescreen: `manifest.webmanifest` + `icons/` (Android: 192/512 + maskable; iPhone: `apple-touch-icon.png`). Icon-Quelle ist ein SVG (Berge + „2027“), mit `qlmanage`/`sips` zu PNG gerendert.
- Nächte werden aus `trip.from`/`trip.to` berechnet, Personen aus `trip.personen`.
- Filter: Programm-Tab mit Leiste (bleibt beim Scrollen oben) für einen Bereich oder „Alle“ plus „nur mit Hund ✓“; Auswahl wird pro Gerät gemerkt (localStorage). Karte mit Ein/Aus-Chips für Unterkünfte, jede Programm-Kategorie und Orte; „Auf Karte zeigen“ schaltet die passende Ebene automatisch ein.
- „Route zum Start“: iPhone/iPad → Apple Karten, sonst Google Maps. Ziel = Feld `nav` [lat,lng] eines Programmpunkts, sonst `lat`/`lng`; `"nav": null` blendet den Button aus (z. B. Hütten ohne Zufahrt).
- Wetter-Karte im Programm-Tab: Klima 11.–18.09. aus dem Open-Meteo-Archiv 2016–2025 (Ø max 19,7 °C, Ø min 9,3 °C, an 48 % der Tage ≥ 1 mm Regen; in `trip.wetter.klima`). Ab 15 Tagen vor Reisebeginn lädt die Seite automatisch die Open-Meteo-Vorhersage (kein Key). Test: `?wetter` an die URL hängen → Vorhersage der nächsten 7 Tage.
- Abstimmung vorerst per **WhatsApp-Umfrage**: Button kopiert die Optionen in die Zwischenablage.
- Hosting: **GitHub Pages**, Repo-Vorschlag `annaberg-2027`, öffentlich (Pages im Free-Tarif nur für öffentliche Repos).

### Stufe 2 (später, wenn Programmplanung startet): Supabase
- Funktionen: Abstimmen, Ideen-Pinnwand, Kommentare, Tagesplan, Kostenaufteilung (wer hat was bezahlt / wer schuldet wem), Packliste (gemeinsam, persönlich, Hund).
- Zugang: **Gruppenpasswort + Namensauswahl** (kein persönlicher Login). Umsetzung: ein gemeinsames Supabase-Auth-Konto, Row Level Security „nur angemeldete Nutzer dürfen lesen/schreiben“, gewählter Name im localStorage des Geräts. Einträge in der Kostenaufteilung mit Zeitstempel.
- Eigenes Supabase-Projekt, getrennt von Uwes geplanter Thai-Lern-App.
- Free-Tarif-Grenzen: Projekt pausiert nach **7 Tagen Inaktivität** (dann manuell reaktivieren oder z. B. GitHub-Action als Keep-alive), max. **2 aktive Projekte** pro Konto.
- Nur den öffentlichen anon/publishable Key ins Frontend. Den **service_role-Key niemals** ins Repo oder in den Code.
- Datenstruktur aus dem JSON-Block soll 1:1 in Tabellen übergehen (trip, unterkuenfte, ideen, stimmen, kommentare, tagesplan, ausgaben, packliste).
- Kein Offline-Modus nötig.

### Versionierung
- Versionsnummer + „Was ist neu“ stehen im JSON `versionen` (neueste zuerst) und werden in der Übersicht angezeigt.
- Bei jeder Veröffentlichung mit sichtbarer Änderung: neuen Eintrag oben in `versionen` (Nummer x.y, Datum, 1–3 Punkte in Gruppen-Sprache), committen, Git-Tag `vx.y` setzen und mit pushen (`git push origin main --tags`). Kleine Inhaltskorrekturen ohne neue Funktion: zweite Stelle hochzählen; neue Bereiche/Funktionen: ebenfalls zweite Stelle; großer Umbau (z. B. Stufe 2 Supabase): 2.0.
- Bisher: 1.0 erste Version · 1.1 Icon/Karte/Ortstaxe · 1.2 Programm · 1.3 Filter/Route/Wetter · 1.4 Übersicht + Versionierung.

### Grundregeln
- **Keine sensiblen Daten** auf der Seite oder im Repo: keine Buchungsnummern, Adressen der gebuchten Unterkunft, Telefonnummern, Zugangsdaten.
- Externe Bibliotheken nur von etablierten CDNs mit fester Version.
- Vor jedem Push: Seite lokal im Browser (Handybreite ~390 px) prüfen, Konsole fehlerfrei.

## Offene Punkte
**Organisatorisch (Gruppe)**
- Wer bucht und bezahlt final?
- Kostenaufteilung: gleich oder nach Verbrauch?
- ✓ Umkreis geklärt 30.10.2026: bis ca. 1 Std. Fahrt (Gosau, Abtenau, Filzmoos, Ramsau, Hallstatt).

**Wartet auf die Gruppe**
- Rückmeldung der Freunde zur App abwarten, dann Vermieteranfragen an die Favoriten (Wochenpreis inkl. Nebenkosten, 2 Parkplätze, Hund allein) → Ergebnisse im JSON-Block nachtragen.
- Ergebnisse der WhatsApp-Umfragen (Unterkunft, Programm) eintragen; „Was gerade ansteht“ in der Übersicht aktualisieren.

**App-Ideen (Backlog, von Uwe noch nicht beauftragt)**
- Kostenrechner: Unterkunft + Ortstaxe + Sprit für 2 Autos, pro Person.
- Packliste: gemeinsam, persönlich, Hund (vorerst nur pro Gerät abhakbar).
- Stufe 2 mit Supabase: Abstimmen, Kommentare, Ideen in der App (erst Fragen, dann Spezifikation zur Freigabe, dann bauen).

**Recherche-Ideen (Backlog)**
- Hund: Badestellen, Tierarzt-Notdienst, hundefreundliche Almen; Hunderegeln der Hütten/Restaurants mit „?“ klären.
- Praktisches: Supermärkte, Bäcker, Hofläden, Gästekarte/Mobilitätsticket, Anreise und Vignette.
- Weitere Aktivitäten: Sommerrodelbahn, E-Bike-Verleih, Almkäse u. Ä.

**Zu prüfen**
- Ortstaxe: offizieller Betrag steht vermutlich in `quellen/2026-07-01_Verordnung_besondere_Naechtigungsabgabe_Annaberg-Lungoetz.pdf` (Text für Claude nicht lesbar) – Uwe liest nach.
- Kopier-Button auf Android und „Route zum Start“ (Apple Karten) auf dem iPhone noch nicht auf echtem Gerät getestet.
- Vor der Reise: Termine/Preise 2027 prüfen (Klettersteigkurs Ramsau, Donnerkogel- und Gosaukammbahn, Hüttenöffnungszeiten, Lammerklamm).

## Nächste Schritte
1. ✓ Erledigt 30.10.2026: Repo `Aod-fi/annaberg-2027`, live unter https://aod-fi.github.io/annaberg-2027/
2. ✓ Erledigt 30.10.2026: Link in die WhatsApp-Gruppe, Umfrage zu den Unterkünften.
3. ✓ Erledigt 30.10.2026: Programm-Tab, Filter, Route zum Start, Wetter, Übersicht, Versionierung (aktuell Version 1.4).
4. Weiter mit einem Punkt aus „Offene Punkte“ – Uwe entscheidet, womit (neuer Thread).

## Entscheidungslog
- 29.10.2026: Freunde planen aktiv mit; eigene Web-App statt Google/Microsoft-Dokument.
- 29.10.2026: Supabase als Speicher; Login per Gruppenpasswort + Namensauswahl.
- 30.10.2026: Variante 1 (schrittweise) – erst statische Seite + WhatsApp-Umfrage, Supabase später.
- 30.10.2026: Nutzung fast nur am Handy, kein Offline-Modus.
- 30.10.2026: Wechsel von claude.ai/Cowork zu Claude Code für Umsetzung und Recherche.
- 30.10.2026: Seite muss auf iPhone **und Android** funktionieren (nicht alle in der Gruppe haben ein iPhone) – Homescreen-Icon per Web-Manifest + apple-touch-icon.
- 30.10.2026: Neuer Start-Tab „Übersicht“ statt „Rahmen“; Versionierung (Nummer + „Was ist neu“ in der App, Git-Tags).
- 30.10.2026: Filter im Programm-Tab und auf der Karte gewünscht (weniger Scrollen); untere Tab-Leiste bleibt auf jeden Fall.
- 30.10.2026: Ausbau gewählt: „Route zum Start“-Buttons und Wetter (Klima jetzt, Live-Vorhersage kurz vor der Reise). Kostenrechner, Packliste, weitere Recherche und Stufe 2 vorerst zurückgestellt.
- 30.10.2026: Programm-Wünsche: Umkreis bis ca. 1 Std. Fahrt (inkl. Gosau, Filzmoos, Ramsau, Hallstatt); Gruppe = Klettersteig-Anfänger → geführter Einsteigertag; kein fester Tagesplan, Vorschlagsliste und Entscheidung vor Ort nach Wetter; Restaurants bodenständig, eher günstig, hundefreundlich; Darstellung als Tab „Programm“ mit Umfrage-Button pro Abschnitt.
- 30.10.2026: Link + Umfrage in der WhatsApp-Gruppe (Kopier-Button funktioniert am iPhone). Vermieteranfragen erst nach Rückmeldung der Gruppe zur App; Programmrecherche (Touren, Klettersteige, Hütten, Restaurants) startet jetzt.
- 30.10.2026: Öffentliches Repo `Aod-fi/annaberg-2027` mit GitHub Pages (main / Root); `CLAUDE.md` und `MASTERPROMPT.md` sind mit im Repo. Commits mit GitHub-Noreply-Adresse (lokale git-Config), damit keine private Mailadresse öffentlich wird.

# CLAUDE.md – Projekt „Annaberg 2027“

Diese Datei ist das Projektgedächtnis für Claude Code. Sie wird bei jedem Start gelesen.
Stand: 30.10.2026. Bitte bei wichtigen Entscheidungen aktuell halten (Abschnitt „Entscheidungslog“).

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

## Programm (noch zu planen)
- Wanderungen mittel bis sportlich (4–6+ Std., 500–900+ Hm), mit Hund, Einkehr mittags oder zum Abschluss
- Klettersteige A–C, **ohne Hund**, Ausrüstung wird geliehen, optional geführter Einsteigertag
- Verpflegung: eher selbst kochen oder halb/halb; Restaurantauswahl für einige Abende
- Schlechtwetter-Alternativen
- Hinweise: Hüttenöffnungszeiten Mitte September prüfen; Hund: Maulkorb-/Leinenpflicht in Bergbahnen/ÖPNV, Vorsicht bei Mutterkühen

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
- Tabs: Unterkunft (Karten mit Muss-Check ✓/?/✗, Pluspunkte, Nachteile, Vermieterfragen), Karte (Leaflet 1.9.4 von cdnjs mit SRI-Prüfsummen + OpenStreetMap, Unterkünfte als nummerierte Pins, ungenaue Lagen zusätzlich mit Kreis, Orientierungspunkte aus `orte`), Rahmen, Demnächst. Aktiver Tab steht in der Adresse (`#karte` usw.), Zurück-Taste wechselt Tabs.
- Homescreen: `manifest.webmanifest` + `icons/` (Android: 192/512 + maskable; iPhone: `apple-touch-icon.png`). Icon-Quelle ist ein SVG (Berge + „2027“), mit `qlmanage`/`sips` zu PNG gerendert.
- Nächte werden aus `trip.from`/`trip.to` berechnet, Personen aus `trip.personen`.
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

### Grundregeln
- **Keine sensiblen Daten** auf der Seite oder im Repo: keine Buchungsnummern, Adressen der gebuchten Unterkunft, Telefonnummern, Zugangsdaten.
- Externe Bibliotheken nur von etablierten CDNs mit fester Version.
- Vor jedem Push: Seite lokal im Browser (Handybreite ~390 px) prüfen, Konsole fehlerfrei.

## Offene Punkte
- Wer bucht und bezahlt final?
- Kostenaufteilung: gleich oder nach Verbrauch?
- Nur Lammertal oder auch Gosau/Abtenau o. Ä.?

## Nächste Schritte
1. ✓ Erledigt 30.10.2026: Repo `Aod-fi/annaberg-2027`, live unter https://aod-fi.github.io/annaberg-2027/
2. Link in die WhatsApp-Gruppe, Umfrage zu den Unterkünften.
3. Anfragen an die Favoriten (Wochenpreis, Parkplätze, Hund allein) → Ergebnisse im JSON-Block nachtragen.
4. Touren, Klettersteige, Hütten, Restaurants recherchieren.
5. Stufe 2 mit Supabase konzipieren (erst Fragen, dann Spezifikation zur Freigabe, dann bauen).

## Entscheidungslog
- 29.10.2026: Freunde planen aktiv mit; eigene Web-App statt Google/Microsoft-Dokument.
- 29.10.2026: Supabase als Speicher; Login per Gruppenpasswort + Namensauswahl.
- 30.10.2026: Variante 1 (schrittweise) – erst statische Seite + WhatsApp-Umfrage, Supabase später.
- 30.10.2026: Nutzung fast nur am Handy, kein Offline-Modus.
- 30.10.2026: Wechsel von claude.ai/Cowork zu Claude Code für Umsetzung und Recherche.
- 30.10.2026: Seite muss auf iPhone **und Android** funktionieren (nicht alle in der Gruppe haben ein iPhone) – Homescreen-Icon per Web-Manifest + apple-touch-icon.
- 30.10.2026: Öffentliches Repo `Aod-fi/annaberg-2027` mit GitHub Pages (main / Root); `CLAUDE.md` und `MASTERPROMPT.md` sind mit im Repo. Commits mit GitHub-Noreply-Adresse (lokale git-Config), damit keine private Mailadresse öffentlich wird.

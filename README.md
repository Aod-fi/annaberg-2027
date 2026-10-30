# Annaberg 2027 – Planungs-App

Mobile Planungsseite für die Wanderwoche in Annaberg im Lammertal (11.–18.09.2027).

## Stufe 1 (jetzt): reine Anzeigeseite
- `index.html` ist komplett eigenständig (eine Datei), Karte über Leaflet + OpenStreetMap.
- Alle Inhalte stehen im JSON-Block `<script id="trip-data">` – Inhalte ändern, ohne den Code anzufassen.
- Abstimmen läuft vorerst per WhatsApp-Umfrage (Button „Umfrage-Optionen kopieren“).

## Veröffentlichen mit GitHub Pages
1. Neues Repository anlegen (z. B. `annaberg-2027`) und `index.html` + `README.md` hochladen.
2. Settings → Pages → Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.
3. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/annaberg-2027/` erreichbar.
4. Link in die WhatsApp-Gruppe; auf dem Handy „Zum Home-Bildschirm“ hinzufügen.

Hinweis: Die Seite ist öffentlich erreichbar. Keine Buchungsnummern, Adressen oder Telefonnummern eintragen.

## Stufe 2 (später): Supabase
Abstimmen, Pinnwand, Kommentare, Tagesplan, Kosten und Packliste kommen mit Supabase dazu
(Gruppenpasswort + Namensauswahl). Die JSON-Struktur ist so angelegt, dass sie direkt in Tabellen übergeht.

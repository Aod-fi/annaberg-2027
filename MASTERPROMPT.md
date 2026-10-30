# Masterprompt für Claude Code – Annaberg 2027

## So startest du
1. Öffne Claude Code mit diesem Ordner als Arbeitsordner (`Documents/00 Claude_local/annaberg-2027`),
   im Terminal z. B. mit `cd ~/Documents/"00 Claude_local"/annaberg-2027` und dann `claude`.
2. Kopiere den Text zwischen den Linien als erste Nachricht hinein.

Claude Code liest `CLAUDE.md` automatisch. Der Masterprompt sorgt dafür, dass es die Lage erst prüft
und mit dir abstimmt, bevor es etwas veröffentlicht.

---

Hallo! Wir übernehmen ein laufendes Projekt: die gemeinsame Planung unseres Wanderurlaubs in Annaberg im Lammertal (11.–18.09.2027, 4 Personen + Golden Retriever). Die Planung lief bisher in claude.ai; alles Wichtige steht in `CLAUDE.md` in diesem Ordner.

Bitte so vorgehen:

1. **Einlesen:** Lies `CLAUDE.md`, `README.md` und `index.html`. Fasse mir in max. 8 Stichpunkten zusammen, was du verstanden hast (Ziel, Stand, Technik, nächste Schritte), und nenne Unklarheiten.

2. **Umgebung prüfen:** Prüfe, ob `git` und die GitHub CLI `gh` installiert sind und ob `gh auth status` angemeldet ist. Falls etwas fehlt, sag mir genau, was ich tun muss – nichts eigenmächtig installieren.

3. **Veröffentlichen vorbereiten:** Schlage mir vor, wie du
   - in diesem Ordner ein Git-Repo initialisierst (Branch `main`, sinnvolle `.gitignore`),
   - ein **öffentliches** GitHub-Repo `annaberg-2027` anlegst und pushst,
   - **GitHub Pages** aus `main` / Root aktivierst,
   - und danach die Live-URL prüfst.
   Warte auf mein OK, bevor du das Repo anlegst oder pushst.

4. **Testen:** Prüfe die Seite vor dem Push lokal im Browser in Handybreite (ca. 390 px): alle vier Tabs, Karte lädt, Konsole ohne Fehler, Button „Umfrage-Optionen kopieren“ funktioniert.

5. **Danach:** Gib mir die Live-URL und einen kurzen Text für unsere WhatsApp-Gruppe (Link + Bitte um Abstimmung per Umfrage).

Regeln für die ganze Zusammenarbeit:
- Halte dich an die Arbeitsweise in `CLAUDE.md`: bei größeren Aufgaben erst eine Frage nach der anderen, dann Zusammenfassung zur Freigabe, dann umsetzen.
- Inhalte (Unterkünfte, Touren usw.) nur im JSON-Block `trip-data` von `index.html` pflegen.
- Keine sensiblen Daten ins Repo (Buchungsnummern, Adressen, Telefonnummern, Keys). Den Supabase-`service_role`-Key niemals verwenden oder speichern.
- Neue Entscheidungen trägst du im „Entscheidungslog“ in `CLAUDE.md` nach und committest sie mit.
- Fakten, die sich ändern können (Preise, Öffnungszeiten, Regeln), vor dem Eintragen per Websuche prüfen und die Quelle als Link mit angeben.

---

## Spätere Einstiegs-Prompts (Beispiele)

**Unterkünfte aktualisieren**
> Ich habe Antworten von Vermietern bekommen: [Details einfügen]. Trag sie im JSON-Block ein (Preis, offene Checks auf ✓/✗), prüfe die Seite und pushe nach meinem OK.

**Programmplanung starten**
> Lass uns Touren, Klettersteige (A–C, ohne Hund) und Hütten mit Einkehr rund um Annaberg recherchieren. Frag mich zuerst nach unseren Wünschen, eine Frage nach der anderen.

**Stufe 2 (Supabase)**
> Wir starten Stufe 2 mit Supabase laut `CLAUDE.md`. Stell mir zuerst deine Fragen nacheinander, dann eine Spezifikation (Tabellen, RLS, Login-Ablauf, Keep-alive gegen die 7-Tage-Pause) zur Freigabe. Erst danach bauen.

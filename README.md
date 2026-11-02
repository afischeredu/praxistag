# Praxistag Startklar – Realschule plus Edenkoben

Infoseite zum Praxistag für Schülerinnen und Schüler. Sie enthält den Ablauf, die Ansprechpersonen, acht Übungen, einen Telefon-Leitfaden und eine Checkliste für die Praxistagmappe.

Die Seite ist eine einzelne HTML-Datei ohne Server, Datenbank oder Build-Schritt. Sie läuft direkt auf GitHub Pages.

## Inhalt des Ordners

| Datei | Zweck |
|---|---|
| `index.html` | die komplette Webseite (Inhalt, Design und Übungen) |
| `bilder/praxistag-logo.png` | Praxistag-Logo (Material des Ministeriums für Bildung RLP) |
| `bilder/schul-logo.png` | Logo der Realschule plus Edenkoben |
| `.nojekyll` | sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert |

## Auf GitHub Pages veröffentlichen

1. Auf github.com anmelden und oben rechts **+ → New repository** wählen.
2. Einen Namen vergeben, z. B. `praxistag`. Sichtbarkeit **Public** wählen (GitHub Pages ist im kostenlosen Konto nur für öffentliche Repositorys verfügbar).
3. Auf **Create repository** klicken.
4. Auf der leeren Repository-Seite **uploading an existing file** anklicken.
5. Den **Inhalt** dieses Ordners hineinziehen: `index.html`, `README.md`, `.nojekyll` und den Ordner `bilder`. Wichtig: `index.html` muss direkt in der obersten Ebene liegen, nicht in einem Unterordner.
   - Hinweis: `.nojekyll` ist eine versteckte Datei. Falls sie beim Hochladen fehlt, ist das nicht schlimm, die Seite funktioniert trotzdem.
6. Unten auf **Commit changes** klicken.
7. Im Repository **Settings → Pages** öffnen.
8. Unter **Build and deployment → Source** die Option **Deploy from a branch** wählen, als Branch **main** und als Ordner **/ (root)**, dann **Save**.
9. Nach ein bis zwei Minuten erscheint oben auf der Seite die Adresse, z. B.
   `https://DEIN-BENUTZERNAME.github.io/praxistag/`

Diese Adresse kannst du an die Klasse weitergeben, zum Beispiel über WebUntis, oder als QR-Code aushängen.

## Änderungen vornehmen

- Im Repository auf `index.html` klicken, dann auf das **Stift-Symbol** (Edit).
- Text ändern, z. B. Namen, Wochentage oder Zeiten. Mit **Strg + F** findest du die Stelle schnell.
- **Commit changes** klicken. Nach ein bis zwei Minuten ist die Änderung online.

Häufige Stellen zum Anpassen (mit Strg + F suchen):

| Was | Suchbegriff |
|---|---|
| Praxistag-Lehrkräfte | `Herr Fischer` |
| Übergangscoach | `Übergangscoach` |
| Arbeitszeiten im Betrieb | `7 Stunden` |
| Kontakt Praxistag-Team RLP | `praxistag@pl.rlp.de` |
| Quizfragen | `function Quiz` |

## Datenschutz

- Die Seite speichert nichts auf einem Server. Fortschritt, Checkliste, Anrufliste und das Anschreiben-Formular werden nur im Browser des jeweiligen Geräts gespeichert (localStorage). Auf geteilten Schul-PCs können andere Nutzer diese Einträge sehen, solange die Browserdaten nicht gelöscht werden.
- Schriftarten werden von Google Fonts geladen. Dabei wird die IP-Adresse der Besucher an Google übertragen. Wer das vermeiden möchte, kann die drei Zeilen mit `fonts.googleapis.com` / `fonts.gstatic.com` am Anfang von `index.html` löschen; die Seite nutzt dann Systemschriften.
- GitHub Pages selbst protokolliert Zugriffe (IP-Adressen) laut den Datenschutzbestimmungen von GitHub.

Bitte vor der Veröffentlichung mit der Schulleitung bzw. dem/der Datenschutzbeauftragten klären, ob die Seite öffentlich sein darf (Namen der Lehrkräfte, Schullogo, externe Dienste).

## Quellen

Inhalte aus: bildung.rlp.de/praxistag, Flyer „Praxistag“ des Ministeriums für Bildung RLP, E-Flyer des Pädagogischen Landesinstituts, Praxistagmappe 2025/26 der Schule.

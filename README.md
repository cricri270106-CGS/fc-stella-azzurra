# FC Stella Azzurra – Website

Vereinswebsite des FC Stella Azzurra Gümligen (seit 1972).

Live: https://cricri270106-cgs.github.io/fc-stella-azzurra/

## Inhalte bearbeiten (ohne Code)

1. Auf https://app.pagescms.org mit GitHub anmelden.
2. Repository `fc-stella-azzurra` wählen.
3. Links im Menü: **Spiele & Resultate**, **Kader**, **Sponsoren**, **News**, **Einstellungen**.
4. Ändern, **Save** drücken – nach etwa 1 Minute ist die Website aktualisiert.

Wer bearbeiten darf: alle, die im Repository unter *Settings → Collaborators* eingetragen sind.

### Spiele
- Alle Spiele der Saison eintragen. Die Website zeigt automatisch das nächste Spiel mit Countdown.
- Während des Spiels (bis 2 Stunden nach Anpfiff) erscheint „Live" mit einem Knopf zum Matchcenter.
- Nach dem Spiel das **Resultat** eintragen (Heim zuerst, z. B. `2:1`) – es erscheint als „Letztes Spiel".

### Instagram
Unter **Einstellungen** den Behold-Link eintragen (`https://feeds.behold.so/…`). Dann erscheinen die neusten Posts automatisch. Ist das Feld leer, werden die Beiträge aus **News** angezeigt.

## Aufbau
- `index.html` – die Website
- `impressum.html` – Impressum & Datenschutz
- `data/*.json` – Inhalte (werden über die Admin-Oberfläche gepflegt)
- `img/` – Fotos, Logos, Wappen
- `fonts/` – Schriften (lokal, ohne Google)
- `.pages.yml` – Formulare der Admin-Oberfläche

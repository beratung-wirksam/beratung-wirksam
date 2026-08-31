# WIRKSAM. – Website auf GitHub Pages einspielen

## Vorher

1. Das Foto **„Nachdenkliche Arbeitsmomentin am Fenster.png“** aus der File Library lokal speichern.
2. In **`sabrina-hero.png`** umbenennen.
3. In den Ordner **`assets`** dieser Website legen.
4. In `impressum.html` und `datenschutz.html` den Platzhalter **`[Straße und Hausnummer ergänzen]`** ersetzen.
5. Die Rechtstexte vor Veröffentlichung prüfen lassen.

## Upload über die GitHub-Webseite

1. Öffne dein Repository für `beratung-wirksam.de`.
2. Oben auf **Code** wechseln.
3. **Add file** → **Upload files** anklicken.
4. Den kompletten Inhalt des entpackten Ordners `wirksam-website` hineinziehen:
   - `index.html`
   - `style.css`
   - `impressum.html`
   - `datenschutz.html`
   - `CNAME`
   - `robots.txt`
   - `sitemap.xml`
   - den Ordner `assets`
5. Unten bei **Commit changes** als Nachricht z. B. `WIRKSAM Website neu` eintragen.
6. **Commit changes** bestätigen.

## GitHub Pages prüfen

Unter **Settings → Pages**:

- Source: **Deploy from a branch**
- Branch: **main**
- Ordner: **/(root)**
- Custom domain: **beratung-wirksam.de**
- Sobald verfügbar: **Enforce HTTPS** aktivieren.

Nach einem Commit braucht GitHub Pages meist kurz, bis die neue Version sichtbar ist. Danach `https://beratung-wirksam.de` neu laden.

## Spätere Änderungen

Texte lassen sich direkt in GitHub bearbeiten:

1. Datei anklicken, z. B. `index.html`.
2. Stift-Symbol **Edit this file**.
3. Text ändern.
4. **Commit changes**.

Die Seite wird danach automatisch neu veröffentlicht.

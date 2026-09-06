# Maggie Slowinska — Portfolio (Y2K / Editorial / Collage)

Eine statische Website (HTML/CSS/JS, kein Build-Prozess nötig).

## Dateien

```
index.html      → Inhalt der Seite
style.css       → Design (Editorial Y2K: Papier, Schwarz, Signal-Orange)
script.js       → Mobiles Menü, Footer-Jahr
```

Aktuell werden keine Bilddateien eingebunden — alle Foto-Stellen sind bewusst
als beschriftete Platzhalter angelegt (siehe unten).

## Veröffentlichen auf GitHub Pages

1. Auf github.com ein neues, **öffentliches** Repository anlegen (z. B. `portfolio`).
2. Im leeren Repository auf **„uploading an existing file"** klicken und `index.html`,
   `style.css` und `script.js` per Drag & Drop hochladen. Unten auf **„Commit changes"**.
3. Im Repository auf **„Settings" → „Pages"**. Unter „Branch" **`main`** und **`/ (root)`**
   auswählen, dann **„Save"**.
4. Nach 1–2 Minuten erscheint der Link zu deiner Seite
   (`https://dein-username.github.io/portfolio/`).

Änderungen später: Datei im Repository öffnen → Stift-Symbol → bearbeiten →
„Commit changes". Nach ein bis zwei Minuten ist es live.

## Platzhalter ersetzen

Im Code stehen an mehreren Stellen Text-Platzhalter wie:

```html
<div class="collage-placeholder ...">
  <p class="ph-label">PLACEHOLDER<br>images/senegal-fieldwork.jpg</p>
</div>
```

Sobald du echte Fotos hast: Bilder in einen neuen Ordner `images/` legen und den
jeweiligen `<div class="collage-placeholder">` bzw. `<div class="placeholder-visual">`
durch ein `<img src="images/dateiname.jpg" alt="...">` ersetzen. Frag mich gerne,
wenn du dabei Unterstützung willst — dann übernehme ich das direkt.

Aktuelle Platzhalter-Stellen (Dateinamen sind Vorschläge, du kannst sie frei anpassen):

- `images/maggie-portrait.jpg` — dein Portrait im Hero
- `images/senegal-fieldwork.jpg`, `images/peru-fieldwork.jpg`, `images/costa-rica-fieldwork.jpg` — Field Notes
- `images/project-hotspot18.jpg`, `images/fluss-des-lebens.jpg`, `images/schwaebische-alb.jpg`,
  `images/moore-emsland.jpg`, `images/droemling-audio.jpg`, `images/kreativ-labor.jpg`,
  `images/infopost-harz.jpg`, `images/infopost-naturschutz.jpg`, `images/wildtierhandel.jpg`,
  `images/ausstellung-ich-du-wir.jpg` — die zehn Projekt-Karten in „Things I Made"

## Bevor du live gehst — bitte kurz prüfen

- **Telefonnummer**: bewusst nicht angezeigt.
- **Instagram/LinkedIn**: `@maggieslowinska` ist auf beiden Plattformen verlinkt
  (`instagram.com/maggieslowinska` und `linkedin.com/in/maggieslowinska`) — bitte
  einmal gegenchecken, ob beide URLs stimmen.
- **Projekt-Links**: die Verlinkungen zu Videos/Podcasts/Reels/Instagram-Posts wurden
  aus den Hyperlinks deines PDF-Lebenslaufs in Lesereihenfolge übernommen — bitte
  einmal durchklicken und prüfen, ob jeder Titel zum richtigen Link passt.
- **Costa Rica**: bewusst ohne erfundene Details — nur als Teil deiner internationalen
  Feldforschungserfahrung erwähnt.

## Eigene Domain (optional)

In den Pages-Einstellungen unter „Custom domain" eintragen, dann beim Domain-Anbieter
einen CNAME-Eintrag auf `dein-username.github.io` setzen.

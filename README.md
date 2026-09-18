# Pferdezucht Oriwol

Statische Website für GitHub Pages. Sie benötigt keinen Build-Schritt und keine zusätzlichen Pakete.

## Für GitHub Pages veröffentlichen

1. Auf GitHub ein neues Repository anlegen.
2. Den vollständigen Inhalt dieses Ordners in die oberste Ebene des Repositorys hochladen. `index.html` muss dort direkt sichtbar sein und darf nicht in einem zusätzlichen Unterordner liegen.
3. In GitHub das Repository öffnen und **Settings → Pages** auswählen.
4. Unter **Build and deployment** als Quelle **Deploy from a branch** einstellen.
5. Den Branch **main** und den Ordner **/(root)** auswählen und speichern.
6. Nach der Veröffentlichung zeigt GitHub unter **Settings → Pages** die Adresse der Website an.

Die Veröffentlichung kann einige Minuten dauern. Für eine Projektwebsite lautet die Adresse normalerweise:

```text
https://BENUTZERNAME.github.io/REPOSITORYNAME/
```

## Ordnerstruktur

```text
index.html                 Startseite und Einstiegspunkt
galerie.html               Galerie
impressum.html             Impressum
verkaufspferde.html        Verkaufspferde
pferd-*.html               einzelne Pferdeseiten
assets/
  style.css                Gestaltung
  script.js                Slider und mobiles Menü
  images/                  sämtliche Bilder und Logos
.nojekyll                  deaktiviert die Jekyll-Verarbeitung
```

Alle Verknüpfungen sind relativ angelegt. Dadurch funktioniert die Website sowohl als Benutzerseite als auch in einem Repository-Unterordner.

## Spätere Änderungen

Geänderte Dateien einfach erneut in das Repository übertragen beziehungsweise committen und auf `main` pushen. GitHub Pages veröffentlicht die Änderungen anschließend automatisch.

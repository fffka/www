Dies ist die Website von Fridays for Future Karlsruhe.  
Für unsere Website nutzen wir [hugo](https://gohugo.io/) - für mehr Infos schaut euch die Doku auf der Seite an.

## Initialisierung
Das Projekt benutzt Submodule. Um hugo richtig verwenden zu können sollten diese zu Beginn mit folgendem Befehl geklont werden:
```
git submodule update
```

## Neue Veranstaltung anlegen
Terminal im Hauptverzeichnis des Repos öffnen
```
hugo new event/[eventName].md
```
Datei entsprechend befüllen: Im Headerteil die Infos ausfüllen, darunter die ausführliche textuelle Beschreibung.
Bilder kommen in den Ordner `static/img/[bildname]` und werden mit `/img/[bildname]` referenziert.

## Neue Pressemitteilung anlgen
Terminal im Hauptverzeichnis des Repos öffnen
```
hugo new pm/[pmName].md
```
Datei entsprechend befüllen: Das PDF Feld verweist auf die PDF Datei.
PDF Dateien kommen in den Ordner `static/pdf/[pdfname]` und werden mit `/pdf/[pdfname]` referenziert.

## Vorschau
Eine Vorschau erhälst du über die Eingabe des Kommandos `hugo server -D`.  
Du erhälst dann einen Link dessen Aufruf dir die gerenderte Seite zurück gibt. Bei Änderungen von Dateien wird die Vorschau automatisch im Browser aktualisiert.

## Veröffentlichen
Wenn du die notwendigen Änderungen gemacht hast, dann comitte das ganze ins Git Repo - die Änderungen werden dann automatisch auf der Website eingespielt (MAGIE...)

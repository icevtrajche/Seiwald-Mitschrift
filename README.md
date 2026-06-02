# Seiwald-Mitschrift

Das ist die Readme.md-Datei. MD steht für Markdown. Markdown ist eine heutzutage weit verbreitete Auszeichnungsprache (_Markup Language_, [Wikipedia](https://en.wikipedia.org/wiki/Markdown)).

Weiter bekannte
Auszeichnungssprache sind:

- Hypertext Markup Language (HTML)
- Extensible Markup Language (XML)
- Yet Another Markup Language (YAML, XMI)

# Installation node.JS

Javascript läuft unter normalen Umständen in einer Browser-Sandbox (nur im Browser). Seit ca. 2010 gibt es Laufzeitumgebung (_Runtime Environment_) für JS, damit man auch serverseitig JS programmieren und ausführen kann: [Node.js](https://nodejs.org/en).

## Installation von pnpm

Der standardmäßige _Package Manager_ für Node.js ist npm (_Node Package Manager_). Eine etwas modernere und inzwischen beliebtere alternative ist [Pnpm](pnpm.io)

## Installation von strapi

Installation mit dem Skript `pnpm create strapi` Daraufhin führt das CLI durch die Installation. Falls bei der Installation sogennante build scripts nicht eingeführt werden können. schlägt die CLI die Fehlerbehandlung selbständig vor.

1. Wechseln in das Installationsverzeichnis (z.B. mit `cd strapi-project`)
2. Führe den Befehl `pnpm install` aus, um die fehlenden Pakete zu installieren und die uild-Skripte auszuführen. Dieser scheitert in der Regel - die Build Skripte müssen mit pnpm approve-builds manuell freigegebn werden.

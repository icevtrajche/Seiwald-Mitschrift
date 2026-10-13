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

Installation mit dem Skript `pnpm create strapi` Daraufhin führt das CLI durch die Installation. Falls bei der Installation sogennante build scripts nicht eingeführt werden können schlägt die CLI die Fehlerbehandlung selbständig vor.

1. Wechseln in das Installationsverzeichnis (z.B. mit `cd strapi-project`)
2. Führe den Befehl `pnpm install` aus, um die fehlenden Pakete zu installieren und die uild-Skripte auszuführen. Dieser scheitert in der Regel - die Build Skripte müssen mit pnpm approve-builds manuell freigegebn werden.

---

# Historische Entwicklung von WebDev

Webdevelopement hat im Laufe der letzten rund 35 Jahre Evolutionsstufen druchlaufen:

1. Statische Webseiten (HTML, CSS, JavaScript) - initale Phase des Webdevelopments, bei der die Webseiteninhalte fest im HTML-Code verankert waren. Dominant in den 1990er Jahren.

2. Dynamische Webseiten (mit serverseitiger Programmiersprache - PHP, Python, Ruby, Java, C# und Datenbankanbindung) - Webseiteninhalte werden dynamisch generiert. Dominant in den 2000er Jahren.

3. Single Page Applications (SPA) - mit JavaScript-Frameworks (z.B.: React, Vue.js, Angular) erstellte "Webapps", die ähnliche Funktionalität wie Desktop-Apps bzw. Mobile Apps bieten. Dominant in den 2010er Jahren. Um Handy-Apps möglichst nahe zu kommen, wurden die SPA-Frameworks um _Progressive Web Apps_ (PWA) erweitert. Damit können die Webapps auch offline genutzt werden. Es gibt drei Voraussetzungen für PWAs: 1. Service Worker, ein Service Worker ist eine Javascript Datei, die im Hintergrund des Browsers läuft - selbst wenn der Browser geschlossen ist, 2. Manifest-Datei, 3. HTTPS, die Webapp muss über HTTPS zugänglich sein.

# Vibecoding / AgenticEngineering mit VS-Code und Github Copilot

Vibecoding passiert in VS-Code in erster Linie über die neu eingeführte Agent View. Dort können alle Anpassungen des "_Coding Harness_" vorgenommen werden. Wir können unseren _Harness_ mit verschiedenen Methoden anpassen.:

- **MCP-Server**:
  MCP steht für _Model Context Protocoll_. Es ist ein Standard, der von Anthropic entwickelt wurde. Mit Hilfe von MCP können Chatbots/LLMs (_Large Language Model_) auf zusätzliche Tools zugreifen, die sie zu Experten in einem bestimmten Themenbereich machen.

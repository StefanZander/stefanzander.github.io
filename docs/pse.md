# Projekt Systementwicklung: Aufgabenstellung


### Thema

Entwicklung eines Plugins zur Ausführung von Markdown-basierten Quizzes für das Dokumentationstool MkDocs.


### Hintergrund

[MkDocs](https://www.mkdocs.org/) ist ein weit verbreitetes **Open-Source-Tool** zur Erstellung **statischer Webseiten** aus **Markdown-Dateien**. Es wird vor allem zur Dokumentation von Softwareprojekten eingesetzt, da es eine einfache Möglichkeit bietet, Inhalte in strukturierter Form zu verfassen und diese automatisch in ansprechende Webseiten umzuwandeln.

Das populärste **Theme** für MkDocs ist [MkDocs-Material](https://squidfunk.github.io/mkdocs-material/), das zahlreiche erweiterte Funktionen wie Navigation, Suche, Responsive Design und Integrationen für Entwickler:innen bietet.

Bekannte Projekte, die MkDocs und MkDocs-Material nutzen, sind unter anderem:

- FastAPI (Framework für moderne Web-APIs in Python)
- TensorFlow (Google-Framework für Machine Learning)
- Kubernetes (Cloud- und Container-Orchestrierungssystem)
- Jupyter (Ökosystem für wissenschaftliches Rechnen und Data Science)

MkDocs wird nicht nur in der Industrie, sondern auch im Hochschulkontext eingesetzt, beispielsweise zur Dokumentation und Bereitstellung von Lehrveranstaltungsunterlagen (siehe auch <https://zander-praxismodul.netlify.app/> oder <https://zander-smw.netlify.app/>).


### Zielsetzung des Projekts

Das Ziel dieses Semesterprojekts ist die Entwicklung eines MkDocs-Plugins, das die Integration und Ausführung von Markdown-basierten Quizzes innerhalb von MkDocs-Seiten ermöglicht.

- Die Quizzes sollen in einer einfachen Markdown-Syntax erstellt werden können (z. B. Multiple Choice oder Single Choice).
- Beim Generieren der Webseite mit MkDocs sollen diese Quiz-Dateien erkannt und automatisch in interaktive Quiz-Komponenten umgewandelt werden.
- Studierende sollen die Quizzes direkt in der mit MkDocs generierten Webseite bearbeiten und ausführen können.
- Damit entsteht die Möglichkeit, Lernzielkontrollen oder Selbsttests nahtlos in die digitalen Lehrunterlagen einzubetten.

<!--
### Nutzen und Mehrwert

- **Für Studierende**: Quizzes fördern das aktive Lernen und ermöglichen die direkte Selbstüberprüfung während der Bearbeitung von Lehrmaterialien.
- **Für Lehrende**: Einfache Möglichkeit, interaktive Aufgaben direkt in ihre Unterlagen einzubauen, ohne auf externe Tools ausweichen zu müssen.
- **Für Projekte allgemein**: Das Plugin ist flexibel einsetzbar und kann auch in Projektdokumentationen oder Online-Tutorials genutzt werden, um interaktive Elemente bereitzustellen.
-->

### Erwartete Ergebnisse

- Ein funktionales __MkDocs-Plugin__, das Markdown-Quiz-Dateien erkennt, rendert und interaktiv ausführbar macht.
- Eine __ausführliche Dokumentation__, die Installation, Funktionsweise und Beispiele für Quiz-Formate beschreibt.
- __Beispiel-Quizzes__ zur Demonstration der Funktionsweise im Kontext von Lehrveranstaltungsunterlagen.
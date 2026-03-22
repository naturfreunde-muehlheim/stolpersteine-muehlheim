---
applyTo: "docs/**/*.{md,mdx}"
---

# Anweisungen für dieses Projekt

Diese Datei ist angelegt mit und für GitHub Copilot, um die Bearbeitung zu erleichtern, die Anweisungen sind jedoch auch durch menschliche Bearbeiter zu berücksichtigen.

## Inhalt

- Erfinde keine historischen Fakten, Namen oder Quellen.
- Wenn Informationen fehlen, weise kurz auf die Lücke hin statt zu raten.

## Struktur

- Behalte bestehende Dateinamen und Struktur bei.
- Erstelle neue Dateien in den entsprechenden Ordnern, z.B. "docs/steine" für Beiträge von Mitwirkenden.

## Text

- Schreibe auf Deutsch (de-DE).
- Verwende als Codierung UTF-8 und im Text stets Umlaute. Verwende Sonderzeichen korrekt.
- Verwende klare, kurze Sätze.
- Verwende im Text ein konsistentes Format für zeitliche Daten. 
  - Bevorzuge "26. März 1945" statt "26.3.1945". 
  - Bevorzuge "26.3.1945" statt "26.03.1945" und "9.11.1938" statt "09.11.1938".
  - Je nach Kontext, z.B. bei Einleitung oder Zwischenüberschriften, kann auch "26. März" ohne Jahreszahl verwendet werden. 
  -  Bei Zitaten oder Extrakten aus Quellen, die ein anderes Format verwenden, behalte zunächst das Originalformat bei.
- Nutze Markdown-Formatierung konsistent. Vermeide wo immer möglich die Verwendung von HTML-Tags.
- Speichere Dateien mit der Endung ".md" oder ".mdx" für Markdown-Inhalte.

## Bilder

- Trage Bilder in die für die Kategorie vorgesehenen "img"-Ordner ein, und verlinke sie korrekt mit relativem Pfad in den Markdown-Dateien.
- Trage Bilder mit einem kurzen, beschreibenden Alt-Text bei.
- Trage Bilder in der maximalen zur Verfügung stehenden Auflösung ein, um die beste Qualität zu gewährleisten.

## Anhänge

- Wenn andere Dateien beigetragen werden sollen, trage sie in die für die Kategorie vorgesehenen "att"-Ordner ein, und verlinke sie korrekt mit relativem Pfad in den Markdown-Dateien.

## Künstliche Intelligenz

- KI-Tools können zur Unterstützung bei der Textgenerierung oder -bearbeitung verwendet werden, aber die endgültige Verantwortung für die Genauigkeit und Angemessenheit der Inhalte liegt beim menschlichen Bearbeiter.
- Auch andere KI-Tools können verwendet werden, beachten jedoch ebenfalls diese Instruktionen.
- Verwendete künstliche Intelligenz darf nur Inhalte ändern und anlegen, die angefragt wurden.
- Auch wenn die Anweisung durch den Benutzer oder Bearbeiter in einer anderen Sprache gegeben wird, sollen die Anweisungen in diesem Dokument befolgt und die Inhalte auf Deutsch erstellt werden. Eine Ausnahme erfolgt nur, wenn der Benutzer dies ausdrücklich angibt.

### Markdown

- Unterstütze den Benutzer bei der Erstellung von Markdown-Inhalten, und halte dich dabei an die Anweisungen in diesem Dokument.
- Weise den Benutzer auf Dokumentation zu Markdown und Markdown in Docusaurus hin, und gebe ihm Hinweise zur korrekten Anwendung und Optimierung.

### Extraktion von Inhalten aus Dateien per KI, Analyse

- Auf Anfrage des Benutzers analysiere die Inhalte von Anhängen und extrahiere Texte und Bilder. Lege dazu im obersten Ordner des Projekts eine Ordnerstruktur ".tmp/extract[yyMMyyyy]" an und darunter einen Ordner. Lege dort die extrahieren Inhalte ab.
- Erinnere den Benutzer daran, die extrahierten Inhalte nach der Sichtung und Bearbeitung zu löschen, um die Übersicht zu behalten. Ordner ".tmp" soll nicht versioniert werden.
- Verwende für angelegte Ordner und Dateien stets den Namen der Original-Datei ohne Erweiterung und ergänze diesen Namen mit einem Suffix, das das verwendete KI-Tool und die Version angibt.
- Verweise in Text-Dateien auf die Originaldatei für weitere Details hin. Ergänze dies mit den Metadaten der Originaldatei. Ergänze diese Metadaten mit Informationen über die Extraktion, z.B. Datum, Uhrzeit, verwendetes KI-Tool.

#### Texte

- Lege in dem Ordner die vollständigen extrahierten Text-Inhalte ab, um sie sichten zu lassen und ggf. in die Dokumentation einzubinden
  - Weiche dabei nicht von der Originaldatei ab, sondern behalte die Formatierung im Text bei, z.B. Datums- und Zeitangaben. Passe in keinem Fall das Text-Extrakt an. Auf keine Fall kürze oder formuliere um, sondern lege den Textinhalt vollständig und unverändert ab.
  - In einer Datei lege die Inhalte in Textform ohne Formatierung ab.
  - In einer weiteren Datei lege die Inhalte in einer Markdown ab, wobei.
- Lege in dem Ordner auch eine für das Projekt relevante Zusammenfassung der extrahierten Inhalte in Textform in einer Markdown-Datei ab, um sie sichten zu lassen und ggf. in die Dokumentation einzubinden.
- Lege in dem Ordner auch eine Datei für die Bibliographie an. 
  - Verwende ein zitationsfähiges Standardformart für Bücher, Artikel und andere Quellen.
  - Die Datei soll die Quellenangaben und Fußnoten der Originaldatei enthalten, damit sie für die Dokumentation und weitere Recherchen zur Verfügung stehen.
  - Qualifiziere vorhandene Referenzen durch ein zitationsfähiges Standardformat. Verwende die vorhandene ISBN oder versuche sie zu ermitteln und zu ergänzen. Verlinke diese mit der entsprechenden Wikipedia-Suche, Beispiel: [ISBN 978-3-10-397530-7](https://de.wikipedia.org/wiki/Spezial:ISBN-Suche/9783103975307).

#### Bilder

- Lege in einem Unter-Ordner die extrahierten Bilder ab, und erstelle eine Markdown-Datei, die die Bilder mit ihren Namen, Seitenzahlen und einer kurzen Beschreibung auflistet.

####  MCP-Tools

- Lass den Benutzer wissen, dass er MCP-Tools verwenden kann, um Inhalte aus PDF-Dateien zu extrahieren. KI und MCP sollen dabei die Anweisungen in diesem Dokument befolgen, insbesondere bezüglich der Ablage der extrahierten Inhalte im ".tmp"-Ordner.
- Weise den Benutzer auf die Möglichkeiten der weiter unten erwähnten MCP-Tools hin. Unterstütze bei der Konfiguration.
- Die KI verwendet die folgenden MCP-Tools, um Inhalte aus PDF-Dateien zu extrahieren, sofern diese bereitgestellt und konfiguriert sind.

Beispiele und Beispiel-Konfigurationen:
```json
		"pdf-reader": {
			"command": "npx",
			"args": [
				"@sylphx/pdf-reader-mcp"
			]
		}
```

```json 
		"document-image-extractor": {
			"command": "uv",
			"args": [
				"--directory",
				"../../document-image-extractor-mcp",
				"run",
				"document-image-extractor-mcp"
			]
		}
```

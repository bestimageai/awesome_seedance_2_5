# Seedance 2.5 Prompts: Deutscher Leitfaden

[English](README.md) · [简体中文](README_ZH.md) · [日本語](README_JA.md) · [Español](README_ES.md) · [Alle 15 Sprachen](prompts/i18n/README.md)

Diese vom **bestimage.ai-Team zusammengestellte und gepflegte** Sammlung umfasst **120 eigenständige Szenarien**: Die ursprünglichen 100 wurden überarbeitet und um 20 neue ergänzt. Der Kern besteht aus **60 chinesischen und 40 englischen Szenen**; die **20 neuen Szenen liegen jeweils auf Chinesisch und Englisch** vor. Die 15 Sprachfassungen bieten jeweils sechs gemeinsame Beispiele, keine vollständige Übersetzung des Katalogs. Übersetzungen werden nicht als zusätzliche Szenarien gezählt.

Ein eigener getesteter Prompt kann gemäß den [Beitragsrichtlinien](CONTRIBUTING.md) mit Einstellungen, Eingaben und echtem Ergebnis eingereicht werden. Angenommene Beiträge können nach Prüfung mit Namensnennung veröffentlicht werden.

## Schnellstart

- Nutze die [6 vollständigen deutschen Prompts](prompts/i18n/prompt-library.de.md).
- Finde ein passendes Beispiel im [Index mit 120 Szenen](prompts/README.md).
- Lies die 20 neuen Produktionsabläufe auf [Englisch](prompts/production-workflows.en.md) oder [Chinesisch](prompts/production-workflows.zh.md).
- Verbessere Timing, Kamera, Ton und Kontinuität mit dem [Prompting-Leitfaden](docs/prompting-guide.md).
- Nutze auf bestimage.ai [Seedance 2.5 Text zu Video](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) für Textvorgaben, [Bild zu Video](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) für ein Startbild oder [Referenz zu Video](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) für Referenzdateien. **Alle drei Seiten sind auf Englisch. Referenz zu Video benötigt mindestens ein Referenzvideo**, dessen Rolle ausdrücklich festzulegen ist.
- Bereite statische Referenzbilder oder Storyboard-Bilder über die [GPT Image 2 API](https://bestimage.ai/models/openai/gpt-image-2/) vor (**englische Seite**). Dies ist ein separater Ablauf zur Bilderzeugung, keine Seedance-Videofunktion.
- Lies den [bestimage.ai-API-Integrationsleitfaden](docs/bestimage-ai-api-guide.md).

> Einstellungen, Preise, Eingabeanforderungen und API-Schemata können sich ändern. Aktuelle Angaben stehen auf den jeweiligen bestimage.ai-Seiten. Die Konzeptbilder sind keine Seedance-Ausgaben und belegen keine Modellleistung.

## Empfohlene Prompt-Struktur

```text
[Ziel] Zielgruppe, Einsatz, Dauer, Seitenverhältnis
[Referenzen] genau eine Aufgabe pro Bild oder Video
[Konstanten] Identität, Produkt, Set und Licht bewahren
[Zeitachse] Aufbau → Handlung → Wendung → Schlussbild
[Kamera] Bildgröße, Höhe, Weg, Tempo, Fokus, Endpunkt
[Ton] Dialog, Atmosphäre, Geräusche, Musik, Synchronpunkte
[Vermeiden] Drift, Duplikate, Anatomiefehler, erfundener Text, Logos, Wasserzeichen
```

Die kreativen Vorgaben müssen anhand tatsächlicher Ergebnisse geprüft werden, insbesondere bei Geometrie, Text, Sprache und Physik. Prüfe vor kommerzieller Nutzung Einwilligungen, Bild- und Musikrechte, Marken, Orte, Aussagen und Plattformregeln.

## Über bestimage.ai

Das Team von [bestimage.ai](https://bestimage.ai/) kuratiert und pflegt diese Prompt-Sammlung. Sie verbindet praktische kreative Arbeitsabläufe mit APIs für Bild- und Videomodelle.

## Mit dem bestimage.ai Affiliate-Programm verdienen

Veröffentlichen Sie Tutorials, Prompts oder API-Integrationen? Werden Sie Teil des [bestimage.ai Affiliate-Programms](https://bestimage.ai/affiliate-program/) und erhalten Sie Provisionen, wenn Sie bestimage.ai Ihrem Publikum empfehlen.

- **20 %** auf die erste gültige bezahlte Bestellung eines geworbenen Nutzers.
- **10 %** auf dessen weitere gültige bezahlte Bestellungen innerhalb von **60 Tagen nach seiner Registrierung**.

Für berechtigte Bestellungen und Auszahlungen gilt die [aktuelle Affiliate-Vereinbarung](https://bestimage.ai/affiliate-agreement/).

## Lizenz

[MIT](LICENSE).

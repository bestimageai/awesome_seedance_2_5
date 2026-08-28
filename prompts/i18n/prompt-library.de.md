# Seedance 2.5: sechs gemeinsame Prompt-Rezepte auf Deutsch

[Alle Sprachen](README.md) · [Index mit 120 Szenen](../README.md) · [Startseite](../../README.md)

Gepflegt vom **bestimage.ai-Team**. Diese sechs lokalisierten Rezepte entsprechen den Szenen 04, 31, 37, 43, 46 und 52 des Hauptkatalogs. Sie sind Übersetzungen beziehungsweise Anpassungen derselben Szenarien, keine sechs zusätzlichen eigenständigen Prompts. Sie stellen keine vollständige deutsche Übersetzung des chinesischen Katalogs dar. Die kreativen Vorgaben sind nicht getestet; genaue Geometrie, Text, Sprache und Physik müssen anhand tatsächlicher Ergebnisse geprüft werden.

Für ein einzelnes Startbild nutze [Seedance 2.5 Bild zu Video](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) (englische Seite). Bei mehreren Referenzdateien benötigt [Referenz zu Video](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) (englische Seite) zusätzlich ein Referenzvideo: Weise ihm ausdrücklich eine Rolle zu. Die [GPT Image 2 API](https://bestimage.ai/models/openai/gpt-image-2/) (englische Seite) ist ein separater Ablauf zur Bilderzeugung für die Vorbereitung von Storyboard-Bildern, kein Video-Endpunkt. Lies den [Integrationsleitfaden](../../docs/bestimage-ai-api-guide.md).

## I18N-01. Keramik-Kaffeefilter: ein kontrollierter Aufguss

Katalogszene: **04** · Modus: Bild zu Video · Dauer: **20 Sekunden** · Format: **16:9**

```text
Verwende Image 1 als Startbild: ein kobaltblauer Keramik-Kaffeefilter mit sechs Außenrippen, ein weißer Papierfilter mit trockenem Kaffeemehl und eine durchsichtige Kaffeekanne auf hellem Kalkstein. Bewahre die Rippenanzahl, die Form ohne Griff, die Papierfalten, den Umriss der Kanne und das Morgenlicht von links. Das Produkt trägt keine Marke.

00:00–00:04: Halte eine Nahaufnahme des trockenen Kaffeemehls; eine Edelstahl-Schwanenhalstülle kommt von rechts oben ins Bild, ohne den Kaffeefilter zu verdecken.
00:04–00:11: Ein dünner, ununterbrochener Wasserstrahl beschreibt einen kleinen Kreis im Papierfilter. Das Kaffeemehl quillt leicht auf; die Flüssigkeit bleibt unter dem Papierrand und tropft in die Kanne.
00:11–00:16: Der Wasserstrahl endet und die Tülle zieht sich zurück. Fahre etwas zurück, sodass das allmähliche Füllen der Kanne sichtbar wird; drehe den Kaffeefilter nicht und ändere seine Proportionen nicht.
00:16–00:20: Halte das Produkt in einer klaren Dreiviertelansicht mit freiem Platz rechts für später hinzugefügten Text.

Ton: sanftes Eingießen, vereinzelte Tropfen, leise Raumatmosphäre; keine Sprache oder Musik. Bewahre die Kontinuität der Flüssigkeitsmenge und den festen Kontakt zwischen den Gegenständen. Kein schwebender Kaffee, keine zusätzlichen Gefäße, lesbaren Texte, Logos, Dampfwolken oder Wasserzeichen. Ändere die Keramikfarbe nur zusammen mit einem passenden neuen Startbild.
```

## I18N-02. Wendbares Überhemd: Wind und Stoffbewegung

Katalogszene: **31** · Modus: Referenz zu Video · Dauer: **20 Sekunden** · Format: **9:16**

```text
Image 1 legt die Identität des erwachsenen Models fest, für dessen Darstellung eine Einwilligung vorliegt. Image 2 definiert ein markenloses rostfarbenes Überhemd mit elfenbeinfarbenem Futter, zwei aufgesetzten Taschen und fünf Knöpfen vorn. Video 1 liefert ausschließlich die langsame Vierteldrehung und den Luftstrom von links nach rechts; übernimm weder die Person noch ihre Kleidung. Beginne mit geöffnetem Überhemd und dem Model auf einer markierten Position im Studio.

00:00–00:05: Feste halbweite Einstellung; das Model hebt den offenen linken Saum gerade so weit an, dass das Futter sichtbar wird, wobei die Hand den Stoff sichtbar greift.
00:05–00:12: Das Model lässt den Saum los und dreht sich um eine Vierteldrehung zur linken Bildseite. Ein sanfter Ventilator bewegt den losen Saum und die Haare gleichmäßig zur rechten Bildseite; Schultern und Taschennähte bleiben stabil.
00:12–00:16: Der Luftstrom nimmt ab. Der Stoff fällt seinem Gewicht folgend zur Ruhe, statt abrupt in seine Position zu springen.
00:16–00:20: Halte eine entspannte seitliche Pose bei unveränderter Kamerahöhe und unverändertem Objektiv.

Ton: leiser Ventilator und Stoffbewegung; kein Dialog. Kein Wenden des Kleidungsstücks am Körper, kein sofortiger Kleidungswechsel, keine zusätzlichen Knöpfe, Hautretusche, Veränderung der Körperform, Texte, Logos oder Wasserzeichen. Dies veranschaulicht Stoffbewegung und ist kein zertifizierter Windbeständigkeitstest.
```

## I18N-03. Lese-App: eine markierte Passage speichern

Katalogszene: **37** · Modus: Referenz zu Video · Dauer: **18 Sekunden** · Format: **16:9**

```text
Image 1 ist die freigegebene Leseansicht, Image 2 dieselbe Ansicht mit einer ausgewählten Passage und Image 3 der freigegebene Zustand der gespeicherten Notiz. Sämtliche sichtbaren Texte liegen bereits auf Englisch vor. Video 1 steuert ausschließlich den Zeigerpfad und die Klickzeitpunkte. Bewahre den Geräterahmen, die Typografie, die Zeilenumbrüche, die Leseposition und die Leserichtung der Oberfläche; erfinde niemals Artikeltext.

00:00–00:04: Feste Frontalansicht des Geräts auf einem neutralen Schreibtisch; der Zeiger ruht neben der in Image 2 gezeigten Passage.
00:04–00:09: Der Zeiger wählt diese Passage gemäß Video 1 genau einmal aus. Übernimm die freigegebene Markierung exakt, ohne andere Zeilen zu verschieben.
00:09–00:14: Klicke einmal auf das vorhandene Speicherelement und wechsle zu Image 3. Ergänze keine kurz eingeblendete Meldung, keinen Zähler, keine Bewertung und kein Menü, die in den Referenzen fehlen.
00:14–00:18: Halte den Zustand der gespeicherten Notiz zur Prüfung. Keine Kamerabewegung und keine Bildschirmreflexionen über dem Text.

Ton: ein leiser Klick pro sichtbarem Klick; keine Sprache, Tippgeräusche oder Musik. Verwerfe Ergebnisse mit veränderten Buchstaben, gespiegelten Bedienelementen, wandernden Markierungen, doppelten Zeigern, Logos oder Wasserzeichen. Stelle zur Lokalisierung alle drei freigegebenen Ansichten in der Zielsprache bereit; fordere das Videomodell nicht auf, den Bildschirm zu übersetzen.
```

## I18N-04. Schneeschmelze: Oberflächenabfluss und Versickerung

Katalogszene: **43** · Modus: Referenz zu Video · Dauer: **24 Sekunden** · Format: **16:9**

```text
Image 1 ist eine von einer Lehrkraft freigegebene Schnittansicht eines geneigten Bodenbetts mit dünner Schneeschicht und durchsichtiger Auffangschale am unteren Rand. Image 2 liefert die freigegebene Pfeilüberlagerung ohne Wörter oder Zahlen. Video 1 gibt ausschließlich den zeitlichen Ablauf der Demonstration bei feststehender Kamera vor. Halte die Schichtgrenzen und die Abmessungen der Schale konstant; dies ist eine vereinfachte Lehrdarstellung, kein durch Messungen belegtes Versuchsergebnis.

00:00–00:06: Zeige die gesamte Schnittansicht mit feststehender Kamera. An der Grenze zwischen Schnee und Boden bildet sich eine kleine Menge Schmelzwasser.
00:06–00:13: Ein Teil des Wassers fließt entlang der Oberfläche hangabwärts zur Schale; folge den Oberflächenpfeilen aus Image 2, ohne die Schneemasse zu vergrößern.
00:13–00:19: Zeige, wie ein weiterer Teil entlang der freigegebenen Abwärtspfeile in die oberen Bodenporen eindringt. Lass ihn nicht sofort sämtliche Schichten durchqueren und erwecke nicht den Eindruck, alle Böden verhielten sich gleich.
00:19–00:24: Halte beide Wasserwege gemeinsam in derselben Ansicht; die Pfeile hören vor dem Ende auf, sich zu bewegen.

Ton: dezente Wassergeräusche und Raumatmosphäre; kein Sprechertext und keine Musik. Keine erfundenen Messwerte, Überschwemmungen, verschwindender Boden, widersprüchlichen Fließrichtungen, Beschriftungen, Logos oder Wasserzeichen. Füge geprüfte erklärende Untertitel in der Nachbearbeitung hinzu.
```

## I18N-05. Hofhaus: den tatsächlichen Weg zeigen

Katalogszene: **46** · Modus: Referenz zu Video · Dauer: **24 Sekunden** · Format: **16:9**

```text
Image 1 liefert den freigegebenen Erdgeschossgrundriss eines schmalen Hofhauses. Image 2 und Image 3 legen den Eingangsraum und den Hof mit ihrer tatsächlichen Einrichtung fest. Video 1 ist ein zur Nutzung freigegebener Rundgang und steuert den Weg sowie die Kamerahöhe. Behandle den Grundriss als räumliche Vorgabe, nicht als anzuzeigendes Bild. Keine erfundenen Ansichten eines Obergeschosses.

00:00–00:06: Beginne direkt hinter dem Eingang auf gewöhnlicher Augenhöhe eines Erwachsenen mit natürlicher Perspektive; zeige die vorhandene Bank und die Türöffnung zum Hof gemeinsam.
00:06–00:14: Bewege dich langsam entlang des Wegs aus Video 1 und behalte die Türöffnung im Blick. Halte vor der Schwelle an; die Kamera darf weder Wände, Möbel noch geschlossenes Glas durchqueren.
00:14–00:20: Betritt den Hof durch die tatsächliche Öffnung und schwenke sanft zum ursprünglichen Pflanzbeet.
00:20–00:24: Halte an und blicke zurück, damit die Betrachtenden die Verbindung zum Eingangsraum verstehen.

Ton: Die Schritte wechseln vom Innenboden zum Hofpflaster, begleitet von leiser Außenatmosphäre; kein Sprechertext. Bewahre Türbreiten, Bodenniveaus, Möbelanzahl, Sonnenlichtrichtung und Wegstrecke. Keine extremen Weitwinkelverzerrungen, zusätzlichen Räume, luxuriöseren Ausstattungen, Standortbehauptungen, lesbaren Schilder oder Wasserzeichen.
```

## I18N-06. Katzentragetasche: der erste freiwillige Besuch

Katalogszene: **52** · Modus: Referenz zu Video · Dauer: **18 Sekunden** · Format: **9:16**

```text
Image 1 definiert eine erwachsene grau getigerte Katze, deren Aufnahmen zur Nutzung freigegeben sind. Image 2 definiert eine offene weiche Transporttasche mit marineblauer Außenhülle, seitlichem Netzfeld und heruntergeklappter Vordertür. Video 1 liefert ausschließlich die ruhige Annäherung und das Hineingehen. Bewahre Fellzeichnung, Körpergröße, Taschennähte, Türöffnung und Netzmuster.

00:00–00:05: Feste niedrige Kamera am Tascheneingang. Die Katze nähert sich der leeren offenen Tasche, hält an und beschnuppert den Rand; niemand schiebt sie oder hält sie fest.
00:05–00:11: Die Katze geht freiwillig hinein, erst mit den Vorderpfoten, dann mit den Hinterpfoten, mit sichtbarem Bodenkontakt. Die Tasche dehnt sich nicht aus und nimmt die Katze nicht durch die Seitenwand auf.
00:11–00:15: Die Katze dreht sich einmal innerhalb des verfügbaren Raums und legt sich mit Blick zum offenen Eingang nieder.
00:15–00:18: Halte die entspannte Pose. Lass die Tür vollständig offen.

Ton: leise Pfotenkontakte, Stoffbewegung und ruhige Raumatmosphäre; kein hinzugefügtes Schnurren oder Angstlaute. Keine Sedierung, Zwangshandhabung, unmögliche Anatomie, doppelten Tiere, Sicherheitszertifizierung, Texte, Logos oder Wasserzeichen. Wenn die Katze im Referenzmaterial nicht freiwillig hineingeht, wähle einen anderen freigegebenen Clip, statt Zwang vorzugeben.
```

# Anleitung – Vorabversion 0.8.8 (4026)

Diese Anleitung gilt für den internen Google-Play-Test, nicht für ältere öffentliche Versionen.

# PicScanner – Anleitung

Stand: 16. Oktober 2026

## Ein Dokument scannen

Lege das Blatt auf einen kontrastreichen Untergrund, vermeide Spiegelungen und halte die Kamera ruhig. Tippe auf Scannen und löse manuell aus. In der PicScanner-Kamera ist „Einzeln prüfen“ voreingestellt: Das Original wird gesichert und die verarbeitete Vorschau erscheint, sobald sie fertig ist. Wähle Wiederholen, Seite hinzufügen oder Speichern. Mit „Serienaufnahme“ fotografierst du mehrere Seiten hintereinander, während die gesicherten Seiten bereits verarbeitet werden. Den Modus wechselst du direkt über „Einzeln prüfen“ bzw. „Serienaufnahme“ mit dem Pfeil oben in der Kamera oder unter Einstellungen. Auch aus der Einzelprüfung kannst du mit einer Serienaufnahme fortsetzen. Der automatische Auslöser ist zu Beginn ausgeschaltet und lässt sich gesondert in der Kamera einschalten.

Der Seitenstapel zeigt die Reihenfolge und den Bearbeitungsfortschritt. Entferne, überprüfe oder verschiebe Seiten vor dem Speichern. Bei vielen ausstehenden Seiten pausiert die Aufnahme kurz, um den Speicher zu schonen. Speichern wartet auf die ausstehenden Ergebnisse. Originale bleiben bei einer Unterbrechung gesichert; beim erneuten Öffnen der eigenen Kamera setzt die Verarbeitung fort. Sie läuft während der geöffneten Sitzung, nicht als dauerhafter Hintergrunddienst. Beim Zurückgehen mit noch nicht abgelegten Aufnahmen kannst du Speichern, Verwerfen oder Abbrechen wählen. Speichern führt in den normalen Abschluss mit den Aufnahmen; Verwerfen entfernt den noch nicht abgelegten Stapel.

## PicScanner und Systemscanner

PicScanner verwendet eine eigene Kameraoberfläche, lokale Kantenerkennung und eigene Bildfilter. Der alternative Systemscanner öffnet unter Android Googles ML-Kit-Scanner, unter iOS Apples VisionKit-Scanner. Dort kommen die Aufnahmeoberfläche und die Bildaufbereitung vom jeweiligen Anbieter. Die zurückgegebenen Seiten kannst du anschließend in PicScanner ablegen und bearbeiten. Unsere nachgelagerte Texterkennung verwendet Google ML Kit; Benennung und Ablage arbeiten mit lokalen Regeln.

## Automatisch und manuell drehen

„Dokumente automatisch richtig drehen“ ist standardmäßig eingeschaltet. Die lokale Texterkennung prüft die Ausrichtung neuer Dokumentseiten. Nur bei mehreren deutlich übereinstimmenden Textzeilen wird gedreht. Fotos, unklare Texte und widersprüchliche Layouts bleiben unverändert. Öffne eine gespeicherte Seite und tippe oben auf den Drehpfeil, um sie um 90° nach rechts zu drehen. Der Vergleich mit dem Quellbild übernimmt dieselbe Ausrichtung; die Originaldatei bleibt unverändert erhalten. Seiten mit Markierungen sind gegen nachträgliche Geometrieänderungen geschützt, damit Anmerkungen nicht verrutschen. Eine manuelle Drehung hat Vorrang; das Original bleibt erhalten. Die Einstellung verändert bereits gespeicherte Dokumente nicht.

## Ränder und Perspektive

In der Seitenbearbeitung findest du Zuschnitt & Ränder direkt. Verschiebe die vier Ecken oder nutze KI-Ränder vorschlagen. Die Entzerrung gleicht die Perspektive aus; ein zuverlässiges A4-Verhältnis lässt sich bei passenden Dokumenten einstellen. Eine abgeschnittene Ecke kann vorgeschlagen werden, fehlender Bildinhalt lässt sich aber nicht wiederherstellen. Prüfe den Zuschnitt bei Schatten, gebogenen Seiten oder teilweise verdecktem Papier.

## Den passenden Filter wählen

Dokumentfarbe hellt Papier auf. Schonend vermeidet starke Eingriffe. Farbe & Flächen eignet sich für farbige Dokumente; Schwarzweiß für Text und Graustufen für neutrale Abstufungen. Foto erhält Bildflächen und vermeidet eine starke Papieraufhellung. Original bleibt ohne Farbfilter. Den Standard für neue eigene Aufnahmen und importierte Bild- und PDF-Seiten stellst du unter Einstellungen ein; jede Seite kann davon abweichen.

## Automatische Namen und Ablage

Die lokale Texterkennung stellt Suchtext bereit. Feste Erkennungsregeln schlagen Dokumentart, Datum, Absender und Referenz vor – ohne Sprachmodell. Manuelle Ablagekorrekturen ergänzen diese Regeln lokal. Unsichere Informationen werden ausgelassen. Fehlende Ordner werden nach dem eingestellten Aufbau angelegt; eine ausdrücklich gewählte Ablage hat Vorrang. Ohne Texterkennung werden Namen und Ordner nicht automatisch geändert. Bestehende Dokumente werden durch eine geänderte Einstellung nicht neu sortiert.

Vor dem Ablegen siehst du Dokumentname und vorgeschlagenen Ablageordner zusammen. Meist genügt „Speichern“. Tippe auf den Ordner, um einen anderen zu wählen oder einen neuen Ordner samt Unterordnern anzulegen (z. B. Privat/Haus/Heizung). Neue eigene Ordner werden erst nach dem abschließenden Speichern angelegt. Der angezeigte Pfad ist die Ablage innerhalb von PicScanner; für einen externen Datei-Export nutzt du weiterhin den System-Dateidialog.

Den Namen kannst du bearbeiten; unzulässige Zeichen und überflüssige Leerzeichen werden beim Bestätigen entfernt. Gleichnamige Dokumente erhalten einen nummerierten Zusatz. Bestätigte Namen und Ordner bleiben bei späterer automatischer Organisation erhalten. „Später ablegen“ behält das Dokument lokal und erstellt keine neue Archivdatei oder Serverübertragung. Die Einstellung zur Namensprüfung steuert, ob das Namensfeld sofort geöffnet ist; der Ablageordner bleibt immer sichtbar und der Name lässt sich bei Bedarf weiterhin bearbeiten. Diese Bestätigung gilt auch beim späteren Ablegen aus der Dokumentansicht.

„Aus Ablagekorrekturen lernen“ ist standardmäßig eingeschaltet. Wenn du den vorgeschlagenen Ordner änderst oder später ein Dokument verschiebst, merkt sich PicScanner die Wahl für denselben erkannten Absender und Dokumenttyp. Ohne brauchbaren Absender oder bei fehlgeschlagener Texterkennung entsteht keine allgemeine Regel. Passende Jahresordner werden für neue Dokumentjahre angepasst. Umbenannte Ordner werden über ihre interne Kennung wiedergefunden; gelöschte Ordner werden nicht aufgrund alter Lernregeln wiederhergestellt. Die jüngste Korrektur ersetzt die frühere Zuordnung. Das Lernen verwendet ausschließlich lokale Regeln, keine Übertragung von Dokumenten oder Cloud-KI. Du kannst es in den Einstellungen abschalten; vorhandene Dokumente werden dadurch nicht verschoben.


## Bibliothek und Ansichten

Raster und Liste zeigen Vorschaubilder; die kompakte Liste spart Platz. Die gewählte Ansicht und Sortierung bleiben gespeichert. Filter zeigen mehrseitige Dokumente, Seiten mit Anmerkungen oder Dokumente ohne erkannten Text. Suche durchsucht Namen, OCR-Text, Notizen und Schlagwörter. Favoriten und Eingang erleichtern den Zugriff. Halte ein Dokument gedrückt, um mehrere auszuwählen und gemeinsam zu exportieren.

## Seiten und Inhalt bearbeiten

Öffne ein Dokument, um Seiten hinzuzufügen, zu drehen, zuzuschneiden, neu anzuordnen oder zu entfernen. Bearbeiten öffnet eine separate Maske für Textfelder, Zeichnen, Markierungen und handschriftliche Unterschriften. Diese Ergänzungen erscheinen auch im Bild-/PDF-Export. Das Ändern des Suchtextes ersetzt keine Buchstaben in einem fotografierten Dokument. Eine handschriftliche Unterschrift ist keine qualifizierte elektronische Signatur.

## Teilen und speichern

Teilen & exportieren bietet PDF, Seitenbilder und Word (DOCX). Word enthält erkannten Text und Seitenabbildungen; es ist keine originalgetreue Rekonstruktion komplexer Word-Layouts. Der WhatsApp-Button öffnet die installierte App; versendet wird erst nach deiner Auswahl dort. Beim Speichern einer PDF wählst du selbst Ziel und Namen im Android-Dateidialog. Mehrere markierte Dokumente werden als ZIP ausgegeben.

## Dateien und Archive übernehmen

Importiere Bilder und PDFs oder ein vorbereitetes ZIP-Dokumentarchiv. Sie erscheinen in derselben Bibliothek wie neue Scans. Lose Dokumente ohne Zuordnung erscheinen im Eingang, vorhandene Archivordner werden direkt übernommen. Ein zusätzlicher Ordner „Importierte Dokumente“ wird nicht angelegt. Vorhandene Originalaufnahmen und Aufnahmedaten werden übernommen, sofern das Archiv sie enthält und eindeutig zuordnet. Importierte PDFs bleiben zusätzlich als Original erhalten. Bearbeitbare Seiten sind Bildkopien: vorhandene PDF-Textschichten, Formulare und digitale Signaturen werden nicht in den neuen Export übertragen. Bewahre wichtige Originale und eine getrennte Sicherung auf.

Wähle „Fotos auswählen“, um Bilder aus der Fotomediathek zu übernehmen. Auf dem iPhone und bei unterstützter geordneter Fotoauswahl unter Android erscheinen die Auswahlzahlen direkt im nativen Fotopicker. Unterstützt dein Android-Gerät diese Reihenfolge nicht, zeigt PicScanner einen Hinweis: Nutze dann „Dateien auswählen“.

Über „Dateien auswählen“ gibst du zunächst einen Ordner frei. Anschließend öffnet sich die Dateiliste von PicScanner. Tippe Bilder und PDFs in der gewünschten Importreihenfolge an; die Nummer erscheint sofort neben jeder ausgewählten Datei. Erneutes Antippen entfernt eine Datei und nummeriert die Auswahl neu. Unterordner lassen sich öffnen, ohne die bisherige Auswahl zu verlieren. Die Seiten jeder PDF bleiben in ihrer ursprünglichen Reihenfolge zusammen. Bestätige die Auswahl mit „Dateien importieren“. Pro Auswahl sind bis zu 100 Dateien mit jeweils höchstens 150 MB möglich; insgesamt werden höchstens 100 Seiten übernommen. Einzelne Bilder dürfen höchstens 40 Megapixel haben.

Vor der Vorschau werden alle importierten Bildseiten und gerenderten PDF-Seiten wie neue Kameraaufnahmen verarbeitet: Die App sucht Dokumentränder, entzerrt bei sicherer Erkennung die Perspektive und wendet den eingestellten Standardfilter sowie die aktivierte automatische Ausrichtung an. Unsichere Ränder werden nicht automatisch zugeschnitten. Du kannst das Ergebnis prüfen, manuell korrigieren und einzelne Seiten neu anordnen. Originaldateien bleiben erhalten; HEIC-Fotos erhalten bei Bedarf eine JPEG-Arbeitskopie. Derselbe Ablauf gilt beim Hinzufügen zu einem bestehenden Dokument.

Kann eine einzelne Datei nicht gelesen werden, werden die übrigen Dateien weiter vorbereitet. Vor dem Übernehmen zeigt die Vorschau die Anzahl ausgelassener Dateien. Unter „Details anzeigen“ findest du ihre Namen und den jeweiligen Grund. Eine unvollständig lesbare PDF wird als ganze Datei ausgelassen; ihre ersten Seiten werden nicht unbemerkt übernommen. Korrigiere die betroffene Datei oder wähle sie später erneut aus.

## Cloud und NAS

Ein optionaler HTTPS-WebDAV-Server erhält PDFs und die gewählte Ordnerstruktur. Automatische Uploads laufen nur bei geöffneter App nach dem Speichern neuer Dokumente; es gibt keine permanente Hintergrundsynchronisation. Hersteller-Portale für den Fernzugriff sind keine WebDAV-Endpunkte. Nutze eine erreichbare HTTPS-WebDAV-Adresse mit gültigem Zertifikat, gegebenenfalls über ein VPN. OneDrive wird über Teilen bzw. den Android-Dateidialog erreicht; eine direkte automatische OneDrive-Verbindung gibt es derzeit nicht.

## Sicherung, Löschung und Grenzen

Die Bibliothek liegt im privaten App-Speicher. Filter bearbeiten Arbeitskopien. Löschen in der App und Entfernen der App können lokale Daten entfernen; extern exportierte Dateien bleiben bestehen. Sichere wichtige Unterlagen separat und kontrolliere Export und Vollständigkeit, bevor du andere Backups entfernst. Zurzeit gibt es keine automatische vollständige Sicherung der gesamten Bibliothek. Texterkennung, Zuschnitt und Benennung können sich irren. Qualität und Geschwindigkeit hängen von Aufnahme, Gerät und Seitenumfang ab.


## Mehrere Dokumente bearbeiten

Halte ein Dokument gedrückt und tippe weitere Dokumente an. Die Auswahlleiste bleibt beim Scrollen oben sichtbar. Dort kannst du exportieren oder nach Bestätigung gemeinsam löschen. Das weitere Menü bietet Verschieben, automatische Ablage, Zusammenführen und alle angezeigten Dokumente auswählen. Bereits exportierte Dateien bleiben beim Löschen erhalten.

## Lange Kassenbelege

Fotografiere einen sehr langen Beleg lieber in mehreren gut lesbaren Abschnitten als aus großer Entfernung. Mit Serienaufnahme kannst du diese Abschnitte in einem Dokument sammeln und einzeln prüfen. Kontrolliere, dass alle Positionen und der Gesamtbetrag lesbar sind. Ein automatisches nahtloses Zusammenfügen von Abschnitten ist derzeit nicht verfügbar.

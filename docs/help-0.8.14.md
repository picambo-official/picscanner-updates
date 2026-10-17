# PicScanner – Anleitung

Stand: 17. Oktober 2026

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

Ordner öffnest du wie im Dateimanager. Die Pfadleiste und der Pfeil nach oben führen zu übergeordneten Ordnern. Über das Drei-Punkte-Menü am Ordner oder am aktuellen Pfad kannst du ihn umbenennen, mit allen Unterordnern verschieben oder löschen. Beim Löschen bleiben die Dokumente erhalten und landen im Eingang. Gleichnamige Zielordner werden nicht zusammengeführt; wähle dann einen anderen Namen oder ein anderes Ziel. Gelernte Ablagezuordnungen folgen umbenannten und verschobenen Ordnern. Die Ordneraktionen ändern zunächst nur deine lokale Bibliothek; vorhandene Serverkopien bleiben unverändert.

Über „Ordner teilen“ im Ordner-Menü erhältst du eine ZIP-Datei mit allen Dokumenten und Unterordnern, auch leeren Ordnern. Suchfilter und Favoriten begrenzen diesen Export nicht. Scans werden als PDF mit den aktuellen Bearbeitungen exportiert; unverändert abgelegte PDF-, Bild- und Word-Dateien bleiben im Originalformat. Gleichnamige Dateien erhalten eindeutige Namen. Die ZIP-Datei enthält die Dokumente, nicht die vollständige App samt Originalaufnahmen, Suchindex und Einstellungen. Die normale Teilen-Auswahl bestimmt, wohin du sie weitergibst.

Raster und Liste zeigen Vorschaubilder; die kompakte Liste spart Platz. Die gewählte Ansicht und Sortierung bleiben gespeichert. Filter zeigen mehrseitige Dokumente, Seiten mit Anmerkungen oder Dokumente ohne erkannten Text. Suche durchsucht Namen, OCR-Text, Notizen und Schlagwörter. Favoriten und Eingang erleichtern den Zugriff. Halte ein Dokument gedrückt, um mehrere auszuwählen und gemeinsam zu exportieren.

## Lange Kassenbelege lesen

In der Seitenansicht, beim Prüfen einer Aufnahme und in der Filtervorschau passt „Auf Bildschirmbreite“ auch sehr lange, schmale Belege an die verfügbare Breite an. Danach nach oben oder unten schieben und bei Bedarf weiter vergrößern. „Ganze Seite“ zeigt wieder die Übersicht; Doppeltippen wechselt zwischen Breite und Übersicht. In der Markierungsansicht findest du „Bildschirmbreite“ im Zoom-Werkzeug. Die Anzeige verändert weder Bildauflösung noch Exportqualität.

## Seiten und Inhalt bearbeiten

Öffne ein Dokument, um Seiten hinzuzufügen, zu drehen, zuzuschneiden, neu anzuordnen oder zu entfernen. Bearbeiten öffnet eine separate Maske für Textfelder, Zeichnen, Markierungen und handschriftliche Unterschriften. Diese Ergänzungen erscheinen auch im Bild-/PDF-Export. Das Ändern des Suchtextes ersetzt keine Buchstaben in einem fotografierten Dokument. Eine handschriftliche Unterschrift ist keine qualifizierte elektronische Signatur.

## Teilen und speichern

Teilen & exportieren bietet PDF, Seitenbilder und Word (DOCX). Word enthält erkannten Text und Seitenabbildungen; es ist keine originalgetreue Rekonstruktion komplexer Word-Layouts. Der WhatsApp-Button öffnet die installierte App; versendet wird erst nach deiner Auswahl dort. Beim Speichern einer PDF wählst du selbst Ziel und Namen im Android-Dateidialog. Mehrere markierte Dokumente werden als ZIP ausgegeben.

## Dateien und Archive übernehmen

Importiere Bilder und PDFs oder ein vorbereitetes ZIP-Dokumentarchiv. Sie erscheinen in derselben Bibliothek wie neue Scans. Lose Dokumente ohne Zuordnung erscheinen im Eingang, vorhandene Archivordner werden direkt übernommen. Ein zusätzlicher Ordner „Importierte Dokumente“ wird nicht angelegt. Vorhandene Originalaufnahmen und Aufnahmedaten werden übernommen, sofern das Archiv sie enthält und eindeutig zuordnet. Importierte PDFs bleiben zusätzlich als Original erhalten. Bearbeitbare Seiten sind Bildkopien: vorhandene PDF-Textschichten, Formulare und digitale Signaturen werden nicht in den neuen Export übertragen. Bewahre wichtige Originale und eine getrennte Sicherung auf.

Wähle „Fotos auswählen“, um Bilder aus der Fotomediathek zu übernehmen. Auf dem iPhone und bei unterstützter geordneter Fotoauswahl unter Android erscheinen die Auswahlzahlen direkt im nativen Fotopicker. Unterstützt dein Android-Gerät diese Reihenfolge nicht, zeigt PicScanner einen Hinweis: Nutze dann „Dateien auswählen“.

Über „Dateien auswählen“ gibst du zunächst einen Ordner frei. Anschließend öffnet sich die Dateiliste von PicScanner. Tippe Bilder und PDFs in der gewünschten Importreihenfolge an; die Nummer erscheint sofort neben jeder ausgewählten Datei. Erneutes Antippen entfernt eine Datei und nummeriert die Auswahl neu. Unterordner lassen sich öffnen, ohne die bisherige Auswahl zu verlieren. Die Seiten jeder PDF bleiben in ihrer ursprünglichen Reihenfolge zusammen. Bestätige die Auswahl mit „Dateien importieren“. Pro Auswahl sind bis zu 100 Dateien mit jeweils höchstens 150 MB möglich; insgesamt werden höchstens 100 Seiten übernommen. Einzelne Bilder dürfen höchstens 40 Megapixel haben.

Nach der Dateiauswahl kannst du bei PDFs „Original-PDFs ablegen“ oder „Als Seiten bearbeiten“ wählen. Die Originalablage übernimmt jede PDF unverändert in den gewählten Ordner; nur ein kleines Titelbild für die Bibliothek wird erzeugt. Es werden keine bearbeitbaren Seitenbilder oder Filter berechnet. Vorhandener PDF-Text wird für die lokale Suche übernommen; Seiten ohne Textschicht erhalten im Hintergrund lokale Texterkennung. Auf älteren Android-Versionen wird dafür generell Texterkennung verwendet. Die dafür vorübergehend erzeugten Seitenbilder werden anschließend gelöscht. Der Fortschritt wird gespeichert; nach erneutem Öffnen der App geht es weiter. Fehler lassen sich im Dokument mit „Text erkennen“ erneut versuchen. Suchtreffer zeigen die PDF-Seite. Die Originaldatei bleibt unverändert, der Suchtext wird nur in PicScanner gespeichert. Öffnen, Umbenennen, Verschieben und PDF-Teilen bleiben möglich. Seitenfilter und Markierungen erfordern später „In bearbeitbare Seiten umwandeln“ im Dokument. Dabei bleibt die Original-PDF separat erhalten; neue Bild-/PDF-Exporte der Arbeitskopie übernehmen ihre Textschichten, Formularfunktionen und digitalen Signaturen nicht. Mit ausgewählte Bilder werden weiterhin normal verarbeitet. Für Original-PDFs gilt die Dateigrößengrenze, die 100-Seiten-Grenze gilt für die Bildumwandlung beim Import.

Vor der Vorschau werden alle importierten Bildseiten und gerenderten PDF-Seiten wie neue Kameraaufnahmen verarbeitet: Die App sucht Dokumentränder, entzerrt bei sicherer Erkennung die Perspektive und wendet den eingestellten Standardfilter sowie die aktivierte automatische Ausrichtung an. Unsichere Ränder werden nicht automatisch zugeschnitten. Du kannst das Ergebnis prüfen, manuell korrigieren und einzelne Seiten neu anordnen. Originaldateien bleiben erhalten; HEIC-Fotos erhalten bei Bedarf eine JPEG-Arbeitskopie. Derselbe Ablauf gilt beim Hinzufügen zu einem bestehenden Dokument.

Kann eine einzelne Datei nicht gelesen werden, werden die übrigen Dateien weiter vorbereitet. Vor dem Übernehmen zeigt die Vorschau die Anzahl ausgelassener Dateien. Unter „Details anzeigen“ findest du ihre Namen und den jeweiligen Grund. Eine unvollständig lesbare PDF wird als ganze Datei ausgelassen; ihre ersten Seiten werden nicht unbemerkt übernommen. Korrigiere die betroffene Datei oder wähle sie später erneut aus.

## Cloud und NAS

**Einweg-Sicherung: PicScanner → Server.** Es gibt keinen Zweiwege-Abgleich und keine automatische Übernahme von Serverdateien. Gesichert wird die exportierte PDF bzw. unverändert abgelegte Originaldatei, nicht die vollständige App mit Originalaufnahmen, Bearbeitungshistorie und Einstellungen.

An jedem Dokument findest du ein kleines Sicherungssymbol. Antippen erklärt den Zustand und bietet „Aktuelle Fassung sichern“: nur lokal (kein Nachweis), vorgemerkt, wird gesichert, wartet nach einem fehlgeschlagenen Versuch, übertragen oder seit der Sicherung geändert. „Übertragen“ bestätigt die Serverantwort für diese Fassung; es ist keine laufende Prüfung, ob die Datei noch auf dem Server liegt. Bereits vor Einführung der Anzeige hochgeladene Dateien haben keinen nachträglichen Nachweis. Beim Verbindungswechsel bzw. Trennen wird eine alte Sicherung nicht als aktuelle Sicherung am neuen Ziel angezeigt.

Du kannst HTTPS-WebDAV oder ein lokales FTP-NAS verbinden. FTP ist unverschlüsselt und ausschließlich für private Netzwerkadressen im vertrauenswürdigen Heimnetz vorgesehen; für verschlüsselte Verbindungen nutze HTTPS-WebDAV mit gültigem Zertifikat. Auf dem NAS müssen der passende Dienst und Schreibrechte eingerichtet sein. Eine gewählte Basisablage muss bereits existieren; PicScanner legt darunter seine Dokumentordner an.

Nach dem Ablegen werden bei aktivierter Automatik unveränderte PDF-/Originaldateien in eine lokale Warteschlange kopiert. Ohne erreichbares NAS bleiben sie vorgemerkt. Bei geöffneter App wird alle 30 Sekunden und beim Zurückkehren erneut geprüft. Im Hintergrund übernimmt die Zeitplanung Android bzw. iOS; Energiesparmodus, fehlendes WLAN, deaktivierte Hintergrundaktualisierung oder erzwungenes Beenden können Übertragungen verzögern. Ein sofortiger Upload beim Betreten des Heimnetzes ist daher nicht garantiert. Unter Cloud & NAS stehen Anzahl, letzter Status und „Vorgemerkte Sicherungen übertragen“. Zugangs- oder Schreibfehler behalten die Datei für einen neuen Versuch.

Es handelt sich um eine Sicherung von PicScanner zum Server, nicht um einen gegenseitigen Abgleich. Vorhandene eigene Dateien am selben Ziel werden bei erneuter Sicherung ersetzt. Änderungen am Dokument müssen erneut abgelegt bzw. hochgeladen werden. Ordnerwechsel können ältere Serverkopien zurücklassen; lokale Löschungen löschen keine Serverdateien. Noch nicht gestartete Uploads gelöschter Dokumente werden verworfen. Beim Wechsel des Servers oder Benutzers gehen vorgemerkte Dateien nicht automatisch an das neue Ziel. Das Entfernen der Verbindung stoppt weitere Uploads; eine gerade laufende Übertragung kann noch abschließen. Bereits übertragene Dateien bleiben auf dem Server.

Bei FTP öffnet „Sicherungsordner auf Server wählen“ die Ordner auf deinem NAS. Tippe einen Ordner zum Öffnen an; der Pfeil führt eine Ebene zurück, das Haus-Symbol zur Serverwurzel. „Ordner verwenden“ übernimmt den Pfad in das Formular. Erst „Prüfen & speichern“ ändert das Sicherungsziel. Die PicScanner-Ordnerstruktur wird unterhalb dieses Ziels angelegt. Das Durchsuchen liest nur Ordnerlisten und legt keine Serverdateien an. Bei fehlenden Leserechten oder nicht unterstützten Ordnerlisten kannst du den vollständigen Zielpfad weiterhin direkt eingeben. Bestehende Serverkopien werden bei einem Zielwechsel nicht verschoben.

### Bereits vorhandene FTP-Sicherungen und ältere Dokumente

Nach „Prüfen & speichern“ einer FTP-Verbindung öffnet sich automatisch „Bestand & Nachsichern“. Du kannst die Prüfung später unter „Serverbestand prüfen & alte Dokumente sichern“ erneut starten. Es gilt das gespeicherte Sicherungsziel; Änderungen im Formular zuerst speichern.

Die App prüft die zu deiner Bibliothek gehörenden Sicherungspfade, nicht beliebige fremde Dateien auf dem Server. Dateiname allein genügt nicht: „Identisch auf Server“ setzt gleiche Größe und SHA-256-Prüfsumme voraus. Die Inhalte werden dazu gelesen, ohne sie als neue Dokumente zu importieren. Der Status gilt für den angezeigten Prüfzeitpunkt. Fehlende Leserechte, unterbrochene Downloads, unbekannte Listenformate und inzwischen geänderte Dokumente zählen als ungeprüft, nicht als gesichert.

„Dokumente nachsichern“ merkt fehlende ältere Dokumente gesammelt vor, unabhängig vom Schalter für neue Dokumente. Identische und bereits vorgemerkte Fassungen werden ausgelassen. Bei „Vorhanden · Fassung nicht bestätigt“ bleibt die Serverdatei unverändert. Optional kannst du „Unklare Fassungen zusätzlich sichern“ einschalten; dann wird eine zusätzliche Datei mit „Sicherung“ im Namen vorbereitet. Vor dem Upload prüft die Warteschlange den Zielpfad erneut. Liegt dort inzwischen anderer Inhalt, wartet dieser Auftrag, statt ihn zu ersetzen. Prüfsummen bereits übertragener Fassungen bleiben lokal beim Trennen und Wiederverbinden erhalten.

Ältere erzeugte PDFs können bei erneutem Export wegen Zeitstempeln andere Bytes haben. Wenn ein passender lokaler Übertragungsnachweis und die damalige Exportdatei vorhanden sind, verwendet die Prüfung diese. Ohne verlässlichen Nachweis meldet sie die Fassung als unklar. Verschobene oder fremd umbenannte Serverdateien werden nicht anhand unsicherer Namensähnlichkeiten zugeordnet. „Anhalten“ stoppt nach dem laufenden Dokument; bereits vorgemerkte Kopien bleiben erhalten. Die Übertragung bleibt eine Einweg-Dateisicherung.

Hersteller-Portale für Fernzugriff sind keine WebDAV-/FTP-Endpunkte. Ein VPN kann dein NAS erreichbar machen. OneDrive wird über Teilen bzw. den Android-Dateidialog erreicht; eine direkte automatische OneDrive-Verbindung gibt es derzeit nicht.

## Sicherung, Löschung und Grenzen

Die Bibliothek liegt im privaten App-Speicher. Filter bearbeiten Arbeitskopien. Löschen in der App und Entfernen der App können lokale Daten entfernen; extern exportierte Dateien bleiben bestehen. Sichere wichtige Unterlagen separat und kontrolliere Export und Vollständigkeit, bevor du andere Backups entfernst. Zurzeit gibt es keine automatische vollständige Sicherung der gesamten Bibliothek. Texterkennung, Zuschnitt und Benennung können sich irren. Qualität und Geschwindigkeit hängen von Aufnahme, Gerät und Seitenumfang ab.


## Mehrere Dokumente bearbeiten

Halte ein Dokument gedrückt und tippe weitere Dokumente an. Die Auswahlleiste bleibt beim Scrollen oben sichtbar. Dort kannst du exportieren oder nach Bestätigung gemeinsam löschen. Das weitere Menü bietet Verschieben, automatische Ablage, Zusammenführen und alle angezeigten Dokumente auswählen. Bereits exportierte Dateien bleiben beim Löschen erhalten.

## Lange Kassenbelege

Fotografiere einen sehr langen Beleg lieber in mehreren gut lesbaren Abschnitten als aus großer Entfernung. Mit Serienaufnahme kannst du diese Abschnitte in einem Dokument sammeln und einzeln prüfen. Kontrolliere, dass alle Positionen und der Gesamtbetrag lesbar sind. Ein automatisches nahtloses Zusammenfügen von Abschnitten ist derzeit nicht verfügbar.


## Bilder und PDFs aus anderen Apps empfangen

Wähle in einer anderen App Bilder oder PDFs aus und tippe auf Teilen → PicScanner. Unter Android öffnet sich PicScanner; unter iOS bestätigst du „Dateien übernehmen“, tippst auf „Fertig“ und öffnest danach PicScanner. In der Bibliothek erscheint der Teileingang mit „Prüfen und importieren“. Dort legst du Reihenfolge, Ränder, Filter, Namen und Ablage wie beim normalen Import fest. Das Abbrechen der Vorschau lässt die Übergabe erhalten. Erst nach gesicherter Übernahme werden die betreffenden Dateien aus dem Teileingang entfernt. Über „Verwerfen“ entfernst du die Übergabe ausdrücklich.

Pro Übergabe sind bis zu 100 Bilder oder PDFs mit jeweils höchstens 150 MB möglich; der lokale Teileingang ist auf 1 GB begrenzt. Fehlgeschlagene Dateien werden einzeln angezeigt. Textnachrichten, Links und Word-Dateien können nicht auf diesem Weg übernommen werden.

## Text direkt im Scan auswählen und Seiten bearbeiten

Öffne eine Seite und wähle „Text auswählen“. Die Texterkennung läuft lokal. Tippe Wörter an oder ziehe einen Auswahlbereich über mehrere Wörter. Kopiere die Auswahl oder hebe sie als Markierung hervor. „Alles“ wählt den erkannten Text der Seite; prüfe die Erkennung und Lesereihenfolge vor weiterer Verwendung. Die Texterkennung verändert das Bild nicht.

Die Markierungsansicht bietet Zoom, Stift, Textmarker, Rechtecke, Pfeile, Textfelder und Unterschriften. Stelle Farbe und Strichbreite beziehungsweise Textgröße und Schriftstil ein. Ergänzungen lassen sich auswählen, verschieben, duplizieren und entfernen. Eine gespeicherte Unterschrift kannst du erneut einsetzen. Rückgängig und Wiederholen gelten für die aktuelle Bearbeitung. Beim Verlassen mit Änderungen kannst du speichern, verwerfen oder weiterarbeiten. Gespeicherte Ergänzungen erscheinen im PDF- und Bildexport.

Vorhandene Buchstaben im fotografierten Dokument werden nicht ersetzt. Markierungen und überdeckende Formen sind keine sichere Schwärzung vertraulicher Inhalte. Originale bleiben erhalten.

## Dokumentstapel intelligent aufteilen

Ein Dokument mit mindestens zwei Seiten öffnen und unter **Dokumentaktionen → Intelligent aufteilen** die lokale Analyse starten. Vorhandener Text wird wiederverwendet; fehlender Text wird auf dem Gerät erkannt. Du kannst die Analyse anhalten und später fortsetzen.

Die Vorschau zeigt Dokumentabschnitte, vorgeschlagene Namen und die ursprünglichen Seitennummern. Antippen einer Seite öffnet das Bild und den erkannten Text. Über das Seitenmenü kannst du eine Seite einem anderen Dokument zuordnen, **hier trennen** oder die Reihenfolge ändern. Abschnitte lassen sich mit dem folgenden verbinden. Namen sind vor dem Speichern änderbar; Korrekturen werden als lokaler Entwurf gesichert.

Gleiche ausdrücklich bezeichnete Dokumentnummern und passende Seitenzähler helfen bei der Zuordnung. Kunden- oder Kontonummern allein reichen nicht. Eindeutige Seitenzähler können eine vertauschte Reihenfolge vorschlagen. Fehlende Seiten, unlesbarer Text, Deckblätter und unklare Zusammenhänge werden zur Prüfung markiert. Es handelt sich um Vorschläge: Fehlende Seiten lassen sich nicht rekonstruieren, und bei uneindeutigen Briefen ist deine Kontrolle nötig.

**Dokumente anlegen** erstellt normale Dokumente im Ordner des Ausgangsstapels. Der Stapel bleibt unverändert bestehen; jede Seite muss genau einem Abschnitt zugeordnet sein. Scanbilder werden nicht erneut komprimiert, vorhandene Bearbeitungen und Anmerkungen bleiben erhalten. Bei verknüpften Originaldateien bleibt der vollständige Originalstapel als Referenz erhalten. Ein geänderter Ausgangsstapel verlangt eine neue Analyse.

PDF-Dateien ohne Arbeitsbilder bleiben PDFs; Text und Seiteninhalte werden nicht in Bilder umgewandelt. Inhaltsverzeichnisse und interne Seitenverknüpfungen des ursprünglichen PDFs werden nicht in die Teildokumente übertragen. Geschützte PDFs, digitale Signaturen und interaktive Formulare eignen sich nicht für diesen direkten Weg. Erstelle bei Bedarf bewusst eine bearbeitbare Arbeitskopie; das signierte Original bleibt separat erhalten. Die Aufteilung ist für 2 bis 2.000 Seiten vorgesehen; eine Texterkennung vieler Bildseiten dauert länger als die Zuordnung vorhandener Texte.

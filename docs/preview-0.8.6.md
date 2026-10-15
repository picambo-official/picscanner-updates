# PicScanner 0.8.6 – Vorabversion

Diese Fassung gehört zum internen Google-Play-Test. Die öffentliche Produktion und eine künftige App-Store-Version sind davon getrennt.

- Gültige JPEGs mit besonderen Neustartmarkierungen werden beim Import nicht mehr fälschlich abgewiesen.
- Bei einzelnen nicht lesbaren Dateien werden die übrigen Seiten weiter vorbereitet. Die Vorschau nennt ausgelassene Dateien und ihre Gründe vor dem Übernehmen. Eine unvollständig lesbare PDF wird als ganze Datei ausgelassen.
- Die Kamera versucht nach unsicheren Rändern einen weiteren Erkennungsdurchlauf mit zusätzlichem Bildkontext. Manuelle Korrektur bleibt möglich; abgeschnittener Bildinhalt kann nicht wiederhergestellt werden.
- Originaldateien bleiben erhalten. Die Grenzen von 100 Gesamtseiten, 150 MB je Datei und 40 Megapixeln je Bild gelten weiterhin.
- Nummerierte Auswahl, Vorschau, Filter und spätere Seitenergänzung aus 0.8.5 bleiben enthalten.

[Vorabtest bei Google Play](https://play.google.com/apps/internaltest/4700249122595124514) · [Anleitung 0.8.6](help-0.8.6.md)

Der Test ist auf freigeschaltete Google-Konten begrenzt. Google steuert die Auslieferung. Ein verfügbarer Testrelease bestätigt keine Installation auf einem konkreten Handy. Fotos bei Bedarf über „Dateien auswählen“ in der nummerierten Ordnerliste auswählen. PDF-Arbeitskopien enthalten Seitenbilder; Textschichten und digitale Signaturen bleiben im zusätzlich erhaltenen PDF-Original.

Der iOS-Quellstand enthält dieselben Importkorrekturen und erweitert den Zuschnitteditor um die neuronale Erkennung. Aktuelle native iPhone-Abnahme und Store-Einreichung stehen aus; es gibt noch keinen öffentlichen Apple-Download oder TestFlight-Link.

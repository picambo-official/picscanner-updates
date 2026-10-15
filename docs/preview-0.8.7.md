# PicScanner 0.8.7 – Vorabversion

Diese Fassung gehört zum internen Google-Play-Test. Öffentliche Produktion und eine künftige App-Store-Version sind davon getrennt.

- Schnellere Bildverarbeitung und weniger wiederholte Datenkopien bei Stapelimporten.
- Mehrere Seiten werden abhängig von Prozessor und Bildgröße begrenzt parallel vorbereitet. Originale und Auswahlreihenfolge bleiben erhalten.
- Die Texterkennung wird wiederverwendet; automatische Ausrichtung, Randerkennung, Entzerrung und Filter bleiben aktiv.
- Das bisherige Ausgabebudget und die JPEG-Qualitätsvorgaben bleiben unverändert. Nicht unterstützte native Bildvarianten behalten ihren Kompatibilitätsweg.
- Die Importkorrekturen und nummerierte Auswahl aus 0.8.6 bleiben enthalten.

[Vorabtest bei Google Play](https://play.google.com/apps/internaltest/4700249122595124514) · [Anleitung 0.8.7](help-0.8.7.md)

Zwei Vergleichspaare mit 30 unterschiedlichen fiktiven JPEGs im Achtkern-Android-Emulator ergaben 82,48 → 7,15 und 81,15 → 7,15 Sekunden bis zur bearbeiteten Seitenvorschau (11,53× bzw. 11,35×). Die unabhängige Textprüfung fand in alten und neuen Ausgaben alle 360 erwarteten Textstellen. Auf vier virtuellen Kernen lag der Median der Vergleichspaare bei 9,66×. Diese Messungen sind keine Laufzeitgarantie für echte Geräte, andere Formate oder das anschließende dauerhafte Bibliotheksspeichern.

Der Test ist auf freigeschaltete Google-Konten begrenzt. Google steuert die Auslieferung. Ein verfügbarer Testrelease bestätigt keine Installation auf einem konkreten Handy. Es gibt weiterhin keinen öffentlichen Apple-Download oder TestFlight-Link; die aktuelle iPhone-Abnahme steht aus.

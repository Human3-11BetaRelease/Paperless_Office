**ATTENTION**
This is a project in ALPHA State, that cannot be compiled or used in any way. See the Wiki for project documentation information



# Projekt Dokumenten-Digitalisierung und -Organisation

**Gesamtziel** ist eine verbesserte Ordnung und vereinfachte Digitalisierung.

- Hashtag-basierte Ablage, um Dokumente vielen Projekten zuordnen zu können
    - Kommandozeilentool mit Hashtag-Zuordnung im Explorer
    - Suchtool, um Dateien mit bestimmte HashTag ausfindig zu machen
- Dokumente einfach mit dem Smartphone digitaliseren
    - SmartphoneApp zum:
        - Foto-Machen
        - Hastag-Zuordnen
        - Hochladen ins System
    - Digitalisierungsbox:
        - Smartphone-Auflage zum Scannen von DIN-A4-Dateien
        - Ausleuchtung der Box zur Qualitätssteigerung
        - Box sollte Reisefähig sein
        - Dokumente sollten "geglättet" werden können

## Teilprojekt HashTag-Basierte Dateiablage

Dateien und Dokumente sind häufig mehreren Punkten zuzuordnen (z.B. beiden Seiten einer Schnittstelle). Über die HashTag-Verwaltung soll die Zuordnung zu beliebig vielen Aspekten möglich werden und die Dokumente immer auffindbar sein. Das soll auf Ordner-Ebene oder bis auf DateiEbene funktionieren (Ordner mehreren Projekten zuordnen oder einzelne Dateien mehreren Projekten zuordnen)

### Anforderungen

- Dokumente im normalen Dateisystem abgelegt
- Bedienung über ContextMenu des Explorers
- Suchfunktion mit Auflistung von Dateien
- Beim Verschieben von Dateien darf keine Tagging-Information verloren gehen, bzw. sie sollte mitwandern




## Teilprojekt Smartphone-as-a-Scanner

### DigitalisierungsApp für Android

Ziel ist eine App mit "FotoStudioBox", um Dokumente maximal einfach einzuscannen und der Hashtagbasierten Dateiablage zuzuordnen.

### Fotostudiobox

Die Fotostudiobox soll die Dokumente ideal ausleuchten und das Smartphone so positionieren können, dass genau ein Foto des DIN A4 Blattes erstellt wird.

## Teilprojekt Automatische Inhaltserkennung

Ziel ist ein DockerContainer, der die Scans erhält (z.B. per EMail), Texterkennung darüber laufen lässt und den erkannten Text durchsuchbar zusammen mit dem Original weiterleitet, sodass sie in die Hashtagbasierte Ablage eingefügt werden. (z.B. über einen Ordner je Scan mit den durchsuchbaren Texten)

## Teilprojekt Smartphone-as-a-Diktiergerät

Ziel ist eine App, um unterwegs möglichst einfach Sprachmemos aufzunehmen, die hochgeladen, per Spracherkennung umgewandelt und dann Hashtagbasiert abgelegt werden.

## Teilprojekt Versionsverwaltung und Synchronisierung

Sämtliche Dokumente sollen in einer Versionsverwaltung hinterlegt werden.

Ein Script soll den Laptop automatisch mit dem Serverstatus abgleichen.

Hier wird wohl auf ein StandardTool zurückgegriffen

# Secure-Darts - Downloads

Hier liegen die veroeffentlichten Installer des **Secure-Darts Trackers**. Kein Quelltext - nur die fertigen Dateien unter [Releases](../../releases).

Die Anwendung selbst läuft unter **[secure-darts.com](https://secure-darts.com)**.

## Was ist der Tracker?

Ein kleines Programm für Windows, das über Kameras erkennt, wohin deine Darts treffen, und das Ergebnis an die Web-App weitergibt. Es läuft vollstaendig auf deinem eigenen Rechner: Die Kamerabilder verlassen ihn nicht, und die Verbindung zur Web-App geht über 127.0.0.1 - also gar nicht erst ins Netz.

## Installation

Unter [Releases](../../releases) die neueste Setup-Datei herunterladen und starten.

Windows meldet sich dabei mit "Der Computer wurde durch Windows geschützt", weil die Datei noch nicht signiert ist. Über *Weitere Informationen* und *Trotzdem ausführen* geht es weiter. Wer sichergehen will, vergleicht vorher die SHA-256-Prüfsumme, die bei jedem Release steht: `certutil -hashfile <datei> SHA256`

Beim ersten Start öffnet sich die Einrichtung - Kameras suchen, zuordnen, Board erkennen. Danach startet der Tracker von selbst. Dann secure-darts.com öffnen; die Verbindung stellt sich allein her.

## Voraussetzungen

Windows 10 oder 11 (64 Bit), zwei bis drei USB-Kameras um das Board, rund 400 MB Platz.

Wichtig: Unter *Einstellungen &rarr; Datenschutz &rarr; Kamera* muss "Desktop-Apps den Zugriff auf Ihre Kamera erlauben" eingeschaltet sein. Steht es aus, zeigt die Vorschau ein schwarzes Bild, **ohne dass eine Fehlermeldung erscheint**.

## Updates

Läuft der Tracker und du öffnest secure-darts.com, meldet die Seite eine neue Fassung, sobald es eine gibt. Der neue Installer wird einfach über den alten ausgeführt. **Kamerazuordnung und Kalibrierung bleiben erhalten** - neu einrichten musst du nicht.

## Fehler gefunden?

Der Tracker ist in einer frühen Alpha. Rückmeldungen gern über das Kontaktformular auf secure-darts.com.

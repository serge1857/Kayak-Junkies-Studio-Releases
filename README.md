# KAYAK JUNKIES Shorts Studio – Downloads

Hier gibt es den Windows-Installer des KAYAK JUNKIES Shorts Studios. Das Studio erstellt aus einem
Angelvideo bis zu zehn unterschiedliche Shorts mit Untertiteln, Effekten und eigener Musik – lokal auf
dem eigenen Rechner, ohne Upload.

## Voraussetzungen

- Windows 10 oder 11 (64 Bit)
- Prozessor mit AVX2 (alle AMD Ryzen, Intel ab etwa 2013)
- Aktueller Grafiktreiber von NVIDIA, AMD oder Intel. Sprach- und Bildanalyse nutzen die Grafikkarte, wenn
  möglich, sonst den Prozessor. Fehlt die Vulkan-Laufzeit des Treibers, weist das Setup darauf hin.
- Rund 4 GB freier Speicher (Programm und Modelle)

## Installieren

1. Unter **[Releases](../../releases/latest)** die Datei `KayakJunkiesStudioRust-Setup-<Version>.exe` laden.
2. Ausführen. Es sind keine Administratorrechte nötig; installiert wird nach
   `%LOCALAPPDATA%\Programs\KAYAK JUNKIES Studio Rust`.
3. Beim ersten Start die gewünschten Sprach- und Bildmodelle wählen. Sie werden einmalig geladen
   (je nach Auswahl etwa 0,1 bis 3 GB), danach läuft die Auswertung offline.

**Windows SmartScreen** kann beim ersten Start „Der Computer wurde durch Windows geschützt“ anzeigen, weil
der Installer nicht digital signiert ist. Dann auf **„Weitere Informationen“ → „Trotzdem ausführen“** klicken.

## Updates

Das Studio sucht beim Start nach einer neuen Version, lädt sie im Hintergrund und fragt dann, ob es
sofort neu starten oder das Update beim Beenden installieren soll. Abschalten lässt sich das unter
Einstellungen → Updates.

> **Wichtig für Versionen 0.7.6 bis 0.7.9:** Diese Versionen finden ohne GitHub-Anmeldung keine Updates.
> Bitte die neueste Version **einmal von Hand** installieren (wie oben). Danach funktionieren Updates wieder
> automatisch. Die Einstellungen und Ergebnisse bleiben dabei erhalten.

Wer noch die ältere Python-Fassung des Studios nutzt, bekommt diese Fassung automatisch als Update angeboten;
sie wird zusätzlich installiert.

## Musik

Nur eigene, lizenzierte Musik verwenden. Titel z. B. mit dem eigenen Epidemic-Sound-Abo herunterladen und im
Studio über „Importieren …“ oder per Ziehen ins Fenster übernehmen. Der Knopf „Epidemic Sound“ öffnet die
Seite im Browser; neue Downloads landen dann automatisch im Musikordner.

## Hinweise

- Es wird nichts hochgeladen oder veröffentlicht.
- Dieses Repository enthält nur die Installationsdateien; der Quellcode ist nicht öffentlich.

# /projectclean

Starte den ProjectClean-Skill für dieses Projekt.

## Verhalten

Nutze `SKILL.md` aus diesem Repository als Arbeitsgrundlage und führe den Ablauf in dieser Reihenfolge durch:

1. Projektkontext laden (Regeln, Stack, Versionsdateien, Testbefehle)
2. Versionsnummer erhöhen (alle zuständigen Dateien synchron)
3. Tests ausführen – bei Fehlern stoppen und fragen
4. Committen (nur relevante Dateien, kein `--no-verify`)
5. Pushen (kein Force-Push ohne Freigabe)
6. Dokumentation aktualisieren (CHANGELOG, Versionen, Deployment – detailliert)
7. Lokales Backup erstellen (mit Hashmanifest)
8. Ältere Backups löschen (mindestens 3 behalten)
9. Ordner aufräumen und Speicherplatz sparen

Wenn nicht alle Schritte gewünscht sind, frage kurz welche ausgeführt werden sollen.

## Sicherheitsregeln

- Keine Secrets, `.env`-Dateien oder personenbezogenen Daten in Git, Backups oder Doku.
- Dateien nur löschen, wenn sie eindeutig als temporär oder reproduzierbar identifiziert sind.
- Mindestens die letzten 3 vollständigen Backups erhalten.
- Kein Force-Push und keine Live-Aktionen ohne ausdrückliche Freigabe.

## Ergebnis

Am Ende kurz berichten:

- Neuer Versionsstand
- Test-Ergebnis
- Commit-Hash und Push-Status
- Aktualisierte Dokumentation
- Backup-Pfad und Retention
- Freigegebener Speicherplatz
- Offene Punkte

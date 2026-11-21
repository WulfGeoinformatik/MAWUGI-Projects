# MAWUGI Projects - Administration

Dieses Handbuch richtet sich an die IT-Administration. Es beschreibt Installation, Lizenzierung, Konfiguration und Betrieb von MAWUGI Projects, dem CMIS-Projektexplorer für d.velop documents.

## Überblick

| | |
|---|---|
| Plattform | Windows 10/11, 64 Bit |
| Installationsart | pro Rechner (alle Benutzer), Administratorrechte erforderlich |
| Unterstützte DMS | d.velop documents (über die CMIS-Schnittstelle) |
| Verbindung | HTTPS zum DMS, keine weiteren Server oder Dienste |
| Lizenzprüfung | offline über eine signierte Lizenzdatei, kein Lizenzserver |

## Pfade auf einen Blick

| Zweck | Pfad | Bemerkung |
|---|---|---|
| Programm | `C:\Program Files\MAWUGI Projects\` | Standard, bei der Installation änderbar |
| Lizenzdatei (empfohlen) | `C:\ProgramData\MAWUGI Projects\lizenz.lic` | bleibt bei Updates und Deinstallation erhalten |
| Lizenzdatei (alternativ) | `<Programmverzeichnis>\lizenz.lic` | geht bei einer Deinstallation verloren |
| Benutzereinstellungen | `%APPDATA%\MAWUGI Projects\settings.json` | pro Windows-Benutzer |
| Arbeitsordner (Zeichentisch) | `%USERPROFILE%\mawugi\mawugi-projects\` | Standard, in der App änderbar |
| Metadatei je Akte | `<Arbeitsordner>\<Akte>\.mawugi.json` | versteckt, darf nicht gelöscht oder geändert werden |

# Gruppenrichtlinien (GPO)

## Ziel

Verwaltung und Konfiguration von Computern und Benutzern über Gruppenrichtlinien.

## Testumgebung

- Windows Server 2022
- Windows 11
- VirtualBox

## Verwendete Werkzeuge

- Gruppenrichtlinienverwaltung (GPMC)
- Server-Manager
- gpupdate
- gpresult

## Aufgabe

Erstellung und Konfiguration einer Gruppenrichtlinie für die Active-Directory-Domäne.

## Durchführung

- Neue Gruppenrichtlinie erstellt
- Richtlinie mit einer Organisationseinheit (OU) verknüpft
- Gruppenrichtlinieneinstellungen konfiguriert
- Anwendung der Richtlinie mit gpupdate überprüft
- Ergebnis mit gpresult kontrolliert

## Ergebnis

Die Gruppenrichtlinie wurde erfolgreich angewendet. Die konfigurierten Einstellungen wurden auf dem Client erfolgreich übernommen.

## Erkenntnisse

Gruppenrichtlinien ermöglichen die zentrale Verwaltung von Benutzern und Computern sowie die einheitliche Umsetzung von Sicherheits- und Systemeinstellungen.

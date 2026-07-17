# Windows-Client

## Ziel

Einbindung eines Windows-Clients in eine Active-Directory-Domäne sowie Überprüfung der Kommunikation mit dem Domänencontroller.

## Testumgebung

- Windows Server 2022
- Windows 11
- VirtualBox

## Verwendete Werkzeuge

- Windows-Einstellungen
- Server-Manager
- Eingabeaufforderung (CMD)

## Aufgabe

Domänenbeitritt eines Windows-Clients sowie Überprüfung der Anmeldung und Netzwerkkommunikation.

## Durchführung

- Windows-Client der Domäne hinzugefügt
- Anmeldung mit einem Domänenbenutzer durchgeführt
- Netzwerkverbindung überprüft
- Namensauflösung mit nslookup getestet
- Erreichbarkeit des Domänencontrollers mit ping überprüft
- Gruppenrichtlinien mit gpupdate aktualisiert

## Ergebnis

Der Windows-Client wurde erfolgreich in die Domäne aufgenommen. Die Anmeldung mit einem Domänenkonto sowie die Kommunikation mit dem Domänencontroller funktionieren fehlerfrei.

## Erkenntnisse

Der erfolgreiche Domänenbeitritt setzt eine funktionierende DNS-Konfiguration und eine stabile Netzwerkverbindung voraus.

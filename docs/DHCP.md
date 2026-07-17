# DHCP

## Ziel

Konfiguration eines DHCP-Servers zur automatischen Vergabe von IP-Adressen innerhalb einer Windows-Domäne.

## Testumgebung

- Windows Server 2022
- Windows 11
- VirtualBox

## Aufgabe

Installation und Konfiguration des DHCP-Servers sowie Erstellung eines IPv4-Bereichs für Clients.

## Durchführung

- Installation der DHCP-Serverrolle
- Autorisierung des DHCP-Servers in Active Directory
- Erstellung eines IPv4-Adressbereichs
- Konfiguration von Standardgateway und DNS-Server
- Überprüfung der automatischen IP-Adressvergabe

## Ergebnis

Clients erhalten ihre Netzwerkkonfiguration automatisch über den DHCP-Server. Die Kommunikation innerhalb der Domäne funktioniert erfolgreich.

## Erkenntnisse

DHCP vereinfacht die zentrale Netzwerkverwaltung, reduziert Konfigurationsfehler und ermöglicht eine automatische IP-Adressvergabe für Clients.

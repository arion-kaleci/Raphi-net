# Raphi-net

Arion, Kaveen, Raphael, Kevin, Leandro

---
## Arbeitspackete

Router, Switch + Dokumentation = Arion + Leandro

Clients, Server + Webserver = Kevin + Kaveen

---
IP-Adressen Zusammengefasst

| **Bezeichnung**           | **IP-Adresse**    | **Erläuterung**                                                |
|---------------------------|-------------------|----------------------------------------------------------------|
| Router (DHCP)             | 192.168.1.1       | Gerät, das DHCP-Dienste anbietet, DNS: 8.8.8.8, Gateway: 192.168.0.1, range: 192.168.1.50 - 192.168.1.254|
| Server (Webserver), Raphi-Server, Nutzername = raphi        | 192.168.1.2       | Server, der Webdienste bereitstellt                            |
| Win11-Client                  | 192.168.1.3       | Vom DHCP zugewiesene IP-Adresse                                |
| Ubuntu-Client                  | 192.168.1.4       | Vom DHCP zugewiesene IP-Adresse                                |
| Switch                    | 192.168.1.239     | Management-IP der Switch                                       |
| Generelle Netzadresse     | 192.168.1.0       | Netzadresse des Subnetzes                                      |
| Subnetzmaske              | 255.255.255.0     | Ermöglicht 254 Hosts pro Subnetz (2 Adressen reserviert)       |
| Broadcast-Adresse         | 192.168.1.255     | Broadcast-Adresse dieses Subnetzes (für Kommunikation an alle) |
| Lease-Zeitraum            | 2 Stunden         | Zeitspanne, für die DHCP-Adressen vergeben werden              |



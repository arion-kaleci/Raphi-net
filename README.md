# Raphi-net

Arion, Kaveen, Raphael, Kevin, Leandro

---
## Arbeitspackete

Router, Switch + Dokumentation = Arion + Leandro

Clients = Kevin 
Server + Webserver = Kaveen

---
IP-Adressen Zusammengefasst

| **Bezeichnung**           | **IP-Adresse**    | **Erläuterung**                                                |
|---------------------------|-------------------|----------------------------------------------------------------|
| Router (DHCP)             | 192.168.1.1       | Gerät, das DHCP-Dienste anbietet, DNS: 8.8.8.8, Gateway: 192.168.0.1, range: 192.168.1.50 - 192.168.1.254|
| Server (Webserver), Raphi-Server, Nutzername = raphi        | 192.168.1.2       | Server, der Webdienste bereitstellt                            |
| Win11-Client                  | 192.168.1.52       | Vom DHCP zugewiesene IP-Adresse                                |
| Ubuntu-Client                  | 192.168.1.51       | Vom DHCP zugewiesene IP-Adresse                                |
| Switch                    | 192.168.0.239     | Management-IP der Switch                                       |
| Generelle Netzadresse     | 192.168.1.0       | Netzadresse des Subnetzes                                      |
| Subnetzmaske              | 255.255.255.0     | Ermöglicht 254 Hosts pro Subnetz (2 Adressen reserviert)       |
| Broadcast-Adresse         | 192.168.1.255     | Broadcast-Adresse dieses Subnetzes (für Kommunikation an alle) |
| Lease-Zeitraum            | 2 Stunden         | Zeitspanne, für die DHCP-Adressen vergeben werden              |


# Clients
Die Clients haben wir standartweise installiert. sie haben am Schluss vom DHCP-Server die IP-Adressen der Tabelle erhalten und wurden nicht statisch gesetzt, weshalb sich die Adressen eventuell ändern könnten. Sie können sich auch mit den anderen Geräten sauber pingen.

---

# Router
Wir haben beim Router folgende Dinge konfiguriert:

![NAT-aktiviert](images/Bild1-router)


Zuerst haben wir beim Router "NAT" aktiviert.

![DHCP-Funktion aktivieren](images/Bild2-router)

Danach haben wir noch den DHCP-Sevrer aktiviert und folgendes eingestellt, dass die range von 192.168.1.50 bis 192.168.1.254 geht, damit beispielsweise Server, die mit statischen Adressen hinzugefügt werden, nicht ein Grund sind, die range zu ändern. Dies gilt nur für 47 weitere Server, was genug sein sollte, aber im Falle das man 48 Server oder Geräte hat, ist man gezwungen die range zu ändern.

Wie schon bei der IP-Adress Tabelle erwähnt, hat der Router die IP-Adresse 192.168.1.1.

# Switch 
Wir mussten bei der Switch nur das "Port mirroring" erlauben, was man im nächsten Bild sehen kann. Die Adresse ist wie bei der Tabelle 192.168.0.239

![Port-Einstellungen](images/Bild1-switch)



# Server mit Webserver
Diese Aufgabe konnte noch nicht erledigt werden



# Fazit Arion


---

# Fazit Kaveen

---

# Fazit Kevin


---

# Fazit Leandro


---

# Fazit Raphael
Raphael war leider bei der Umsetzung der Aufgaben nicht anwesend, weshalb er keinen Fazit schreiben kann.


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
Die Clients sind standardmässig installiert, sie haben die IP-Adressen aus der Tabelle vom DHCP-Server erhalten und sind nicht statisch eingestellt, d.h. die Adressen können sich ändern. Sie können auch mit den anderen Geräten sauber pingen.

---

# Router
Wir haben den Router wie folgt konfiguriert:

![NAT-aktiviert](images/Bild1-router.png)

Zuerst haben wir "NAT" auf dem Router aktiviert.

![DHCP-Funktion aktivieren](images/Bild2-router.png)

Dann haben wir noch den DHCP-Server aktiviert und so eingestellt, dass die range von 192.168.1.50 bis 192.168.1.254 geht, damit z.B. Server, die mit statischen Adressen hinzugefügt werden, kein Grund sind, die range zu ändern. Dies gilt nur für 47 zusätzliche Server, was ausreichend sein sollte, aber wenn man 48 Server oder Geräte hat, ist man gezwungen, die range zu ändern.

Wie bereits in der IP-Adressentabelle erwähnt, hat der Router die IP-Adresse 192.168.1.1.

# Switch 
Wir mussten nur das "Port Mirroring" auf dem Switch aktivieren, wie im folgenden Bild zu sehen ist. Die Adresse ist 192.168.0.239.

![Port-Einstellungen](images/Bild1-switch.png)



# Server mit Webserver
Für das Installieren des Linux Servers brauchte ich einen USB Stick, der richtig formatiert ist. Mit Rufus ging das. Das Einrichten ist an sich nicht schwer, jedoch darf man nicht den Namenserver vergessen. Ein guter Wert wäre 9.9.9.9. Die Einrichtung ist nicht schwer. Da es ein Server ist, sollte man eine statische IP-Adresse reintun. Der Befehl für die Installation lautet wie folgt: "sudo apt install apache2".

---

# Fazit Arion
Die Aufgaben waren spannend, ich konnte mein Wissen unter Beweis stellen und noch mehr lernen. Durch die Aufgaben konnte ich auch etwas von dem Wissen, das ich durch meine Krankheit verpasst habe, lernen und so mein Wissen erweitern. Leider hatten wir Probleme mit dem Server, da er kein Internet wollte, aber mit der Hilfe von Frank konnten wir das lösen.

---

# Fazit Kaveen
Der Auftrag hat mir sehr viel Spass gemacht. Aber ich hatte Probleme mit dem Verbinden des Servers mit unserem Netzwerk, aber danach hatten wir das hingekriegt. Ich freue mich auf weitere Gruppenaufträge.

---

# Fazit Kevin
Die Aufgaben waren nicht nur interessant, sondern gaben mir die Gelegenheit, mein Wissen anzuwenden und zusätzlich neue Erkenntnisse zu gewinnen. Besonders hilfreich war, dass ich durch die Übungen auch Themen nachholen konnte und so meine Kenntnisse weiter vertiefen konnte. Zwar gab es technische Schwierigkeiten mit dem Sever, was später behoben werden konnte.

---

# Fazit Leandro
Die Durchführung des Projekts hat mir sehr viel Spass gemacht und ich fande meine Gruppe sehr lustig und motiviert, da wir es gut und schnell lösen konnten, wir hatten nur ein paar Probleme, aber sonst war es kein Problem. Ich war verantwortlich für den Router und den Switch. Mir hat der Tag sehr viel Spass gemacht und ich konnte sehr viel lernen.

---

# Fazit Raphael
Raphael war bei der Durchführung der Aufgaben leider nicht anwesend, so dass er keine Schlussbemerkungen machen kann.


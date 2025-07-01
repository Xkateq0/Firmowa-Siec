# Projekt sieci firmowej (Cisco Packet Tracer)

## 🧩 Opis
Kompletny projekt sieci LAN odwzorowujący strukturę małej firmy. W sieci zastosowano:

- VLAN-y (HR, IT, Zarząd)
- Routing między VLAN-ami (subinterfejsy)
- RIP v2 jako protokół dynamicznego routingu
- NAT – umożliwienie dostępu do internetu
- DHCP – automatyczne przydzielanie adresów
- DNS – rozwiązywanie nazw
- HTTP – lokalny serwer firmowy z własną stroną
- ACL – ograniczenie komunikacji między działami

## 🖼️ Topologia
![Topologia](topologia.PNG)

## 🧪 Testy
- ping między VLAN-ami
![ping](testy/ping.PNG)
- przydzielone adresy przez DHCP
![dhcp](testy/dhcp.PNG)
- dostęp do serwera DNS
![dns](testy/dns.PNG)
- dostęp do strony internetowej
![http/https](testy/http)

## 📂 Pliki
- `siec.pkt` – plik Cisco Packet Tracer
- `README.md` – ten plik


## ✍️ Autor
Katarzyna Trzaska

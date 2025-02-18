# IPv4 und IPv6 Informationen

## IPv4 (Internet Protocol Version 4)

### Adressformat
- **32-Bit-Adresse**: IPv4-Adressen sind 32 Bit lang.
- **Dotted-Decimal-Notation**: Adressen werden in der Form `xxx.xxx.xxx.xxx` dargestellt, wobei `xxx` eine Zahl zwischen 0 und 255 ist.
- **Beispiel**: `192.168.1.1`

### Adressklassen
- **Klasse A**: 1.0.0.0 bis 126.0.0.0
- **Klasse B**: 128.0.0.0 bis 191.255.0.0
- **Klasse C**: 192.0.0.0 bis 223.255.255.0
- **Klasse D**: 224.0.0.0 bis 239.255.255.255 (Multicast)
- **Klasse E**: 240.0.0.0 bis 255.255.255.255 (Experimentell)

### Subnetting
- **Subnetzmaske**: Bestimmt, welcher Teil der IP-Adresse das Netzwerk und welcher Teil den Host identifiziert.
- **CIDR (Classless Inter-Domain Routing)**: Erweiterung des IPv4-Adressraums durch variable Subnetzmasken.

### Private Adressbereiche
- **10.0.0.0 bis 10.255.255.255**
- **172.16.0.0 bis 172.31.255.255**
- **192.168.0.0 bis 192.168.255.255**

## IPv6 (Internet Protocol Version 6)

### Adressformat
- **128-Bit-Adresse**: IPv6-Adressen sind 128 Bit lang (8 4er Blöcke).
- **Hexadezimal-Notation**: Adressen werden in der Form `xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx` dargestellt, wobei `xxxx` ein hexadezimaler Wert ist.
- **Beispiel**: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`

### Adresstypen
- **Unicast**: Eindeutige Adresse für ein einzelnes Interface.
- **Multicast**: Adresse für eine Gruppe von Interfaces.
- **Anycast**: Adresse für eine Gruppe von Interfaces, wobei das Paket an das nächste Interface gesendet wird.

### Adressbereiche
- **Global Unicast**: `2000::/3`
- **Unique Local Unicast**: `fc00::/7`
- **Link-Local Unicast**: `fe80::/10`
- **Multicast**: `ff00::/8`

### Vorteile von IPv6
- **Größerer Adressraum**: 128-Bit-Adressen bieten eine viel größere Anzahl von Adressen im Vergleich zu IPv4.
- **Einfachere Adressverwaltung**: Keine Notwendigkeit für NAT (Network Address Translation).
- **Integrierte Sicherheit**: IPsec ist in IPv6 integriert.
- **Verbesserte Mobilität**: Bessere Unterstützung für mobile Geräte.

### Übergangstechnologien
- **Dual Stack**: Unterstützung sowohl von IPv4 als auch IPv6.
- **Tunneling**: IPv6-Pakete werden in IPv4-Pakete eingekapselt.
- **NAT64**: Übersetzung zwischen IPv6 und IPv4.


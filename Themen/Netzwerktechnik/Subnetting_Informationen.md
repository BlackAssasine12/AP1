# Subnetting Informationen

## Einführung in Subnetting

Subnetting ist der Prozess der Aufteilung eines IP-Netzwerks in kleinere, logische Subnetze. Dies ermöglicht eine effizientere Nutzung der IP-Adressen und eine bessere Netzwerkverwaltung.

## IPv4 Subnetting

### Grundlagen
- **Subnetzmaske**: Bestimmt, welcher Teil der IP-Adresse das Netzwerk und welcher Teil den Host identifiziert.
- **CIDR (Classless Inter-Domain Routing)**: Erweiterung des IPv4-Adressraums durch variable Subnetzmasken.

### Beispiel
- **IP-Adresse**: `192.168.1.1`
- **Subnetzmaske**: `255.255.255.0` (oder `/24`)
- **Netzwerkadresse**: `192.168.1.0`
- **Broadcast-Adresse**: `192.168.1.255`
- **Host-Bereich**: `192.168.1.1` bis `192.168.1.254`

### Subnetzmaske berechnen
- **/24**: `255.255.255.0`
- **/25**: `255.255.255.128`
- **/26**: `255.255.255.192`
- **/27**: `255.255.255.224`

### Schritte zum Subnetting
1. **Bestimmen der Anzahl der benötigten Subnetze und Hosts**.
2. **Berechnen der Subnetzmaske** basierend auf der Anzahl der benötigten Subnetze.
3. **Berechnen der Anzahl der verfügbaren Hosts** pro Subnetz.
4. **Zuweisen der Subnetze** und Host-Adressen.

## IPv6 Subnetting

### Grundlagen
- **Präfixlänge**: Bestimmt, welcher Teil der IPv6-Adresse das Netzwerk und welcher Teil den Host identifiziert.
- **Standard-Präfixlänge**: `/64` für die meisten Netzwerke.
- Eine IPv6-Adresse besteht aus **128 Bit**, aufgeteilt in Präfix (Netzwerkteil) und Interface-ID (Host-Teil).

### Beispiel
- **IPv6-Adresse**: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`
- **Präfixlänge**: `/64`
- **Netzwerkadresse**: `2001:0db8:85a3:0000::/64`

### Gekürzte vs. ungekürzte Darstellung
- Gekürzt: `2001:db8:85a3::/64`  
- Ungekürzt: `2001:0db8:85a3:0000:0000:0000:0000:0000/64`  
Die ungekürzte Form zeigt alle Blöcke mit führenden Nullen, die gekürzte Form nutzt IPv6-Kurzschreibweisen.

### Standardpräfix und Teilnetz-ID
- **Standardpräfix (/48)**: umfasst die ersten 48 Bit einer Adresse.  
  - Beispiel: `2001:db8:abcd::/48`  
  - Ungekürzt: `2001:0db8:abcd:0000:0000:0000:0000:0000/48`  

- **Teilnetz-ID (16 Bit)**: erweitert das Präfix auf 64 Bit.  
  - Beispiel: `2001:db8:abcd:1234::/64`  
  - Ungekürzt: `2001:0db8:abcd:1234:0000:0000:0000:0000/64`

Damit gilt: **/48 (Präfix) + 16 Bit Teilnetz-ID = /64 Subnetz**.

### Anzahl der möglichen Subnetze
- Mit einem /48-Präfix stehen **16 zusätzliche Bits** für Subnetz-IDs zur Verfügung.  
- Das ergibt **2¹⁶ = 65.536 mögliche /64-Subnetze**.  
- Jedes /64-Subnetz enthält **2⁶⁴ mögliche Hostadressen**.

### Schritte zum Subnetting
1. **Bestimmen der benötigten Anzahl von Subnetzen**.  
2. **Präfixlänge wählen** (z. B. /48 vom Provider).  
3. **Teilnetz-ID berechnen** (z. B. 16 Bit → ergibt /64-Netze).  
4. **Subnetze zuweisen**.  

## Vorteile von Subnetting
- **Effiziente Nutzung der IP-Adressen**: Reduziert die Verschwendung von IP-Adressen.
- **Verbesserte Netzwerksicherheit**: Isoliert verschiedene Netzwerksegmente.
- **Bessere Netzwerkverwaltung**: Erleichtert die Verwaltung und Überwachung des Netzwerks.

## Zusammenfassung
Subnetting ist ein wesentlicher Bestandteil der Netzwerkverwaltung und ermöglicht eine effiziente Nutzung der IP-Adressen sowohl in IPv4 als auch in IPv6.  

Bei IPv6 ist besonders wichtig:  
- **/48 Präfix** → vom Provider vergeben.  
- **16-Bit Teilnetz-ID** → ergibt **65.536 mögliche /64-Subnetze**.  
- **/64 Subnetze** sind der Standard in IPv6 und bieten unvorstellbar viele Adressen pro Netz.  

# WIP

# Bit und Byte: Dateigrößen und Umrechnung

In der digitalen Welt spielen Bit und Byte eine zentrale Rolle, wenn es um die Größe von Dateien geht. Diese Markdown-Datei erklärt die grundlegenden Einheiten und bietet eine praktische Übersichtstabelle sowie einen allgemeinen Rechenweg.

---

## Einheiten und Definitionen

- **Bit (b)**: Die kleinste Informationseinheit in der digitalen Welt. Ein Bit kann entweder den Wert `0` oder `1` haben.
- **Byte (B)**: Ein Byte besteht aus 8 Bit. Es ist die Standardgröße, um Datenmengen darzustellen.

Zusätzliche Einheiten werden durch Potenzen von 1024 dargestellt:

| Einheit  | Symbol | Größe in Byte         |
| -------- | ------ | --------------------- |
| Bit      | b      | 1 Bit                 |
| Byte     | B      | 8 Bit                 |
| Kilobyte | KB     | 1024 Byte (2^10 Byte) |
| Megabyte | MB     | 1024 KB (2^20 Byte)   |
| Gigabyte | GB     | 1024 MB (2^30 Byte)   |
| Terabyte | TB     | 1024 GB (2^40 Byte)   |
| Petabyte | PB     | 1024 TB (2^50 Byte)   |
| Exabyte  | EB     | 1024 PB (2^60 Byte)   |

---

## Umrechnungstabelle

Die folgende Tabelle zeigt die Werte für Umrechnungen zwischen den Einheiten:

## IEC-Binärpräfixe und SI-Dezimalpräfixe

| Anzahl Bytes | Name     | Symbol | Unterschied gerundet | Anzahl Bytes | Name      | Symbol |
| ------------ | -------- | ------ | -------------------- | ------------ | --------- | ------ |
| 2^10         | Kibibyte | KiB    | 2,4 %                | 10^3         | Kilobyte  | kB     |
| 2^20         | Mebibyte | MiB    | 4,4 %                | 10^6         | Megabyte  | MB     |
| 2^30         | Gibibyte | GiB    | 7,4 %                | 10^9         | Gigabyte  | GB     |
| 2^40         | Tebibyte | TiB    | 9,1 %                | 10^12        | Terabyte  | TB     |
| 2^50         | Pebibyte | PiB    | 12,6 %               | 10^15        | Petabyte  | PB     |
| 2^60         | Exbibyte | EiB    | 15,3 %               | 10^18        | Exabyte   | EB     |
| 2^70         | Zebibyte | ZiB    | 18,1 %               | 10^21        | Zettabyte | ZB     |
| 2^80         | Yobibyte | YiB    | 20,9 %               | 10^24        | Yottabyte | YB     |
    
---

## Umrechnung
Beispielaufgabe 2.4 Tebibyte in Gigabyte

$Zahlenwert \cdot \frac{Einheit}{Zieleinheit} \cdot Zieleinheit$

$2.4 \cdot \frac{Tebibyte}{Gigabyte} \cdot Gigabyte$

$2.4 \cdot \frac{2^40}{10^9} \cdot Gigabyte$

(gemeint ist 2^40)

$2638.83 \cdot Gigabyte$

2.638,83 Gigabyte
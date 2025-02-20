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

<div style="display: flex; justify-content: space-between;">
  <h2>IEC-Binärpräfixe</h2>
  <h2>SI-Dezimalpräfixe</h2>
</div>

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

## Allgemeiner Rechenweg

### Von einer größeren Einheit zu einer kleineren Einheit (z. B. MB → Byte):
Multipliziere den Wert mit dem entsprechenden Multiplikator:

\[
Wert_{kleinere Einheit} = Wert_{größere Einheit} \times Multiplikator
\]

**Beispiel:**

1 Megabyte (MB) = 1 × 1024 × 1024 = 1.048.576 Byte

### Von einer kleineren Einheit zu einer größeren Einheit (z. B. Byte → MB):
Teile den Wert durch den entsprechenden Multiplikator:

\[
Wert_{größere Einheit} = \frac{Wert_{kleinere Einheit}}{Multiplikator}
\]

**Beispiel:**

1.048.576 Byte = 1.048.576 ÷ (1024 × 1024) = 1 Megabyte (MB)

---

## Fazit

Diese Umrechnungstabelle und der allgemeine Rechenweg können helfen, Dateigrößen präzise und schnell umzurechnen. Mit der Tabelle als Referenz und den Rechenmethoden bist du bestens für Berechnungen im Bereich Bit und Byte ausgestattet.

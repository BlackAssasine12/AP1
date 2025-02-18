# WIP

# Bit und Byte: Dateigrößen und Umrechnung

In der digitalen Welt spielen Bit und Byte eine zentrale Rolle, wenn es um die Größe von Dateien geht. Diese Markdown-Datei erklärt die grundlegenden Einheiten und bietet eine praktische Übersichtstabelle sowie einen allgemeinen Rechenweg.

---

## Einheiten und Definitionen

- **Bit (b)**: Die kleinste Informationseinheit in der digitalen Welt. Ein Bit kann entweder den Wert `0` oder `1` haben.
- **Byte (B)**: Ein Byte besteht aus 8 Bit. Es ist die Standardgröße, um Datenmengen darzustellen.

Zusätzliche Einheiten werden durch Potenzen von 1024 dargestellt:

| Einheit   | Symbol  | Größe in Byte                 |
|-----------|---------|-------------------------------|
| Bit       | b       | 1 Bit                         |
| Byte      | B       | 8 Bit                         |
| Kilobyte  | KB      | 1024 Byte (2^10 Byte)         |
| Megabyte  | MB      | 1024 KB (2^20 Byte)           |
| Gigabyte  | GB      | 1024 MB (2^30 Byte)           |
| Terabyte  | TB      | 1024 GB (2^40 Byte)           |
| Petabyte  | PB      | 1024 TB (2^50 Byte)           |
| Exabyte   | EB      | 1024 PB (2^60 Byte)           |

---

## Umrechnungstabelle

Die folgende Tabelle zeigt die Werte für Umrechnungen zwischen den Einheiten:

| Ursprungseinheit | Zielgröße (Byte)         | Multiplikator          |
|------------------|--------------------------|------------------------|
| Bit              | Byte                    | `1 ÷ 8`                |
| Byte             | Bit                     | `8`                    |
| Kilobyte         | Byte                    | `1024`                 |
| Byte             | Kilobyte                | `1 ÷ 1024`             |
| Megabyte         | Byte                    | `1024 × 1024`          |
| Byte             | Megabyte                | `1 ÷ (1024 × 1024)`    |
| Gigabyte         | Byte                    | `1024 × 1024 × 1024`   |
| Byte             | Gigabyte                | `1 ÷ (1024 × 1024 × 1024)` |

| Einheit    | Symbol  | Größe in Byte                 |
|------------|---------|-------------------------------|
| Bit        | b       | 1 Bit                         |
| Byte       | B       | 8 Bit                         |
| Kibibyte   | KiB     | 1024 Byte (2^10 Byte)         |
| Mebibyte   | MiB     | 1024 KiB (2^20 Byte)          |
| Gibibyte   | GiB     | 1024 MiB (2^30 Byte)          |
| Tebibyte   | TiB     | 1024 GiB (2^40 Byte)          |
| Pebibyte   | PiB     | 1024 TiB (2^50 Byte)          |
| Exbibyte   | EiB     | 1024 PiB (2^60 Byte)          |
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

# Farben für meinen Tiny Engineer

Vorschauen sind aus einem Foto des Originals umgefärbt, keine echten Drucke. Die Mengen stammen aus Bambu Studio (P2S, 0,16 mm, 20 % Füllung) und gelten pro Roboter.

| Bild | Inhalt |
| --- | --- |
| [farbideen.jpg](farbideen.jpg) | Neun Farbkombinationen zur Auswahl |
| [variante1-bambu.jpg](variante1-bambu.jpg) | Variante 1: Weiß, Schwarz, Silbergrau, Anthrazit, blaugraues „Glas“ |
| [variante2-fusion.png](variante2-fusion.png) | Variante 2 im CAD-Modell (Fusion) |
| [variante2-tasse.png](variante2-tasse.png) | Tasse „I ♥ IT“ im CAD-Modell |
| [variante2-bildschirm.png](variante2-bildschirm.png) | Laptop-Bildschirm mit Konsole |
| [variante2-realistisch.jpg](variante2-realistisch.jpg) | Aktueller Stand von Variante 2 als Foto-Vorschau (Tisch RAL 7016) |
| [variante2-dasfilament.jpg](variante2-dasfilament.jpg) | Variante 2: Farben von dasfilament.de, Tasse „I ♥ IT“ |

## Variante 2 (dasfilament.de)

| Teile | Farbe | Filament | pro Roboter |
| --- | --- | --- | --- |
| Head, Chest, Hat, Belly, Neck, Mug (mit Henkel), AiEmblem (Logo), Konsolenschrift | Weiß | PLA Weiß | 60 g |
| UpperArm (2×), ForearmLeft/Right, Coffee (Tasseninhalt), LaptopScreen (Bildschirm), Chair, SeatLeft, SeatRight, Schrift auf der Tasse | Schwarz | PLA Schwarz | 79 g |
| Desk (Tischkorpus), DeskPad (Unterplatte mit Ecken), LampBase | Anthrazitgrau | PETG RAL 7016 | 90 g |
| LaptopCase, LampCap | Alu-Silber | PETG Alu-Silber | 13 g |
| Bell (Klingel) | Silber | PLA Silber | < 1 g |
| DeskTop (Tischplatte ohne unterste 0,36 mm), LampDiffuser (Lampenschirm) | Glas | PETG Natur (glasklar) | 34 g |
| DeskTop, unterste 0,36 mm (2 Schichten) | Blauschimmer | PETG Transparent Blau | 5 g |
| Herz auf der Tasse, LampButton | Feuerrot | PLA Feuerrot | < 1 g |

Bestellung bei dasfilament.de (1,75 mm, Preise vom 30.09.2026):

| Filament | Link | Bedarf für 3 Roboter | Kauf | Preis |
| --- | --- | --- | --- | --- |
| PLA Weiß | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-weiss-1-kg/) | 196 g (inkl. Testteile) | 1 kg | 15,99 € |
| PLA Schwarz | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-schwarz-1-kg/) | 237 g | 1 kg | 15,99 € |
| PETG RAL 7016 Anthrazitgrau | [1 kg](https://dasfilament.de/produkt/petg-filament-175-mm-7016-1-kg/) | 269 g | 1 kg | 21,00 € |
| PETG Natur | [1 kg](https://dasfilament.de/produkt/petg-filament-175-mm-natur-1-kg/) | 102 g | 1 kg | 21,00 € |
| PETG Alu-Silber | [Probe](https://dasfilament.de/produkt/petg-filament-50-g-sample-175-mm-alu-silber/) | 39 g | 2 × 50 g | 5,90 € |
| PLA Feuerrot | [Probe](https://dasfilament.de/produkt/pla-filament-175-mm-feuerrot-50-g-sample/) | < 3 g plus Spülmenge | 50 g | 2,95 € |
| PLA Silber | [Probe](https://dasfilament.de/produkt/pla-filament-175-mm-silber-50-g-sample/) | 1 g | 50 g | 2,95 € |
| PETG Transparent Blau | [Probe](https://dasfilament.de/produkt/petg-filament-50-g-sample-175-mm-transparent-blau/) | 15 g | 50 g | 2,95 € |
| **Filament gesamt** | | | | **88,73 €** |
| Farbmuster-Set, optional (68 Plättchen) | [Set](https://dasfilament.de/produkt/farbplaettchen-farbmuster-set-swatches/) | – | 1 | 19,94 € |

Versandkosten stehen erst im Warenkorb. Das Farbmuster-Set zeigt jede Farbe in Stufen von 0,2 bis 2 mm Dicke; damit lässt sich prüfen, wie klar PETG Natur in Plattenstärke wirkt.

## Slicer-Profile

DAS FILAMENT bietet Profile für Bambu Studio (PLA, PETG, TPU; alle Bambu-Drucker, auch P2S 0,4 mm): [dasfilament.de/slicer-profile](https://dasfilament.de/slicer-profile/). Import: Datei → Importieren → „Konfigurationen importieren …“ mit der ZIP-Datei. Die Rollen haben keinen RFID-Chip, das Profil im AMS einmal pro Fach wählen.

## Druckhinweise

- **Material je Druckteil:** In keinem Teil treffen PLA und PETG aufeinander; PLA und PETG haften schlecht aneinander.
- **PETG** haftet auf glatten Druckplatten sehr stark: strukturierte Platte oder Trennmittel verwenden.
- **Glasplatte:** mit 100 % Füllung drucken, sonst sieht man das Füllmuster durch das klare PETG. Die untersten 0,36 mm (erste Schicht 0,2 mm plus eine 0,16-mm-Schicht) sind PETG Transparent Blau und geben einen leichten Blauschimmer; die Gesamtdicke ist unverändert. Druckdatei [../tischplatte/Tischplatte_Blauschicht_Teile.3mf](../tischplatte/Tischplatte_Blauschicht_Teile.3mf) (ein Objekt, zwei Teile); ein einziger Farbwechsel. Darunter liegen Unterplatte und geschlossener Tischkorpus in Anthrazitgrau, Elektronik sieht man nicht.
- **Bildschirm:** Konsole „$ ./hello / Hello human! / What are we / building today?“ in Consolas Fett, 2,6 mm hoch, weiß auf schwarz, 0,36 mm tief eingelegt. Die Bildschirmseite liegt beim Druck auf dem Bett; Farbwechsel nur in den ersten zwei Schichten. Druckdatei [../bildschirm/Bildschirm_Konsole_Teile.3mf](../bildschirm/Bildschirm_Konsole_Teile.3mf). Die Striche sind nur ~0,35 mm breit; in der Slicer-Vorschau prüfen, ob alle Zeichen gedruckt werden.
- **Tasse „I ♥ IT“:** Dateien in [../tasse/](../tasse/). Schrift und Herz sind 0,4 mm erhaben, gegenüber dem Henkel; der Henkel zeigt beim Einsetzen nach hinten. `Tasse_ILoveIT_Teile.3mf` öffnet Bambu Studio als ein Objekt mit fünf Teilen (Tasse, Herz, drei Buchstaben). Alle drei Tassen zusammen auf einer Platte drucken, dann fallen die Farbwechsel im Schriftbereich nur einmal an.
- **Tisch:** Original-Druckdatei `Desk.3mf`, einfarbig in RAL 7016.
- **Klingel:** Den Knopf oben bildet der Kopf der M2×16-Schraube, mit der die Klingel am Tisch befestigt wird.
- **Lampensockel** bleibt deckend (Anthrazitgrau): Er sitzt über dem ESP32, durchsichtig sähe man die Platine.
